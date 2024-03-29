---
title: MatroskaPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 Matroska 视频中的元数据容器
type: docs
weight: 2470
url: /zh/net/groupdocs.metadata.formats.video/matroskapackage/
---
## MatroskaPackage class

表示 Matroska 视频中的元数据容器。

```csharp
public class MatroskaPackage : MatroskaBasePackage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ContentType](../../groupdocs.metadata.formats.video/matroskapackage/contenttype) { get; } | 获取 Matroska 内容类型。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [EbmlHeader](../../groupdocs.metadata.formats.video/matroskapackage/ebmlheader) { get; } | 获取 EBML 标头元数据。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Segments](../../groupdocs.metadata.formats.video/matroskapackage/segments) { get; } | 获取段信息元数据。 |
| [SubtitleTracks](../../groupdocs.metadata.formats.video/matroskapackage/subtitletracks) { get; } | 获取字幕元数据条目。 |
| [Tags](../../groupdocs.metadata.formats.video/matroskapackage/tags) { get; } | 获取标记元数据。 |
| [Tracks](../../groupdocs.metadata.formats.video/matroskapackage/tracks) { get; } | 获取曲目元数据条目。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [使用 Matroska (MKV) 文件中的元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### 也可以看看

* class [MatroskaBasePackage](../matroskabasepackage)
* 命名空间 [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
