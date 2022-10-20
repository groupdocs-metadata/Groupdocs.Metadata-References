---
title: ApePackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 APE v2 元数据包 请在以下位置找到更多信息http//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key.
type: docs
weight: 380
url: /zh/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

表示 APE v2 元数据包。 请在以下位置找到更多信息[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key).

```csharp
public sealed class ApePackage : CustomPackage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | 获取抽象链接。 |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | 获取相册。 |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | 获取艺术家。 |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | 获取参考书目。 |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | 获取评论。 |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | 获取作曲家。 |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | 获取导体。 |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | 获得版权。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | 获得首张专辑。 |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | 获取文件。 |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | 获取流派。 |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | 获取带有校验位的 ISBN 号。查看更多：https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | 获取国际标准记录编号。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定的名称。 |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | 获取语言。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | 获取发布权。 |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | 获取发布者。 |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | 获取记录位置。 |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | 获取字幕。 |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | 获取标题。 |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | 获取曲目编号。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**学到更多**

* [处理 APEv2 标签](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### 例子

本示例演示如何读取 MP3 文件中的 APEv2 标签。

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### 也可以看看

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 命名空间 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
