---
title: ID3V2Tag
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 ID3v2 标记 请在以下位置找到更多信息https//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2.
type: docs
weight: 490
url: /zh/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

表示 ID3v2 标记。 请在以下位置找到更多信息[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2).

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | 初始化一个新的实例[`ID3V2Tag`](../id3v2tag)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | 获取或设置专辑/电影/节目标题。 此值由 TALB 帧表示。 |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | 获取或设置首席艺术家/首席表演者/独奏者/表演组。 此值由 TPE1 帧表示。 |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | 获取或设置与音频文件直接相关的附加图片。 该值由 APIC 帧表示。 |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | 获取或设置 Band/Orchestra/Accompaniment。 此值由 TPE2 帧表示。 |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | 获取或设置音频主要部分每分钟的节拍数。 该值由 TBPM 帧表示。 |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | 获取或设置用户评论。 此值由 COMM 框架表示。 该框架适用于不适合任何其他框架的任何类型的全文信息。 |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | 获取或设置作曲家。名称以“/”字符分隔。 此值由 TCOM 帧表示。 |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | 获取或设置内容类型。 此值由 TCON 帧表示。 |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | 获取或设置版权消息。 此值由 TCOP 帧表示。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | 获取或设置包含记录日期的 DDMM 格式的数字字符串。此字段始终为四个字符长。 此值由 TDAT 帧表示。 |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | 获取或设置对音频文件进行编码的个人或组织的名称。 此值由 TENC 帧表示。 |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | 获取或设置国际标准记录代码 (ISRC)（12 个字符）。 此值由 TSRC 帧表示。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | 获取或设置音频文件的长度（以毫秒为单位），以数字字符串表示。 该值由 TLEN 帧表示。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | 获取或设置声音开始的音乐键。 此值由 TKEY 帧表示。 |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | 获取或设置原始专辑/电影/节目标题。 此值由 TOAL 帧表示。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | 获取或设置标签或发布者的名称。 此值由 TPUB 框架表示。 |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | 获取或设置音频文件的大小（以字节为单位，不包括 ID3v2 标记），以数字字符串表示。 此值由 TSIZ 帧表示。 |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | 获取或设置文件编码时使用的音频编码器及其设置。 此值由 TSSE 帧表示。 |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | 获取或设置字幕/描述细化。 此值由 TIT3 帧表示。 |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | 获取标签的大小。 |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | 获取或设置包含录制时间的 HHMM 格式的数字字符串。此字段始终为四个字符长。 此值由 TIME 帧表示。 |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | 获取或设置 Title/Song name/Content description. 该值由 TIT2 帧表示。 |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | 获取或设置一个数字字符串，其中包含原始录音中音频文件的顺序号。 此值由 TRCK 帧表示。 |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | 获取文件已播放的次数。 该值由PCNT帧表示。 |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | 获取 ID3 版本。 |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | 获取或设置带有记录年份的数字字符串。此框架始终为四个字符长（直到 10000 年）。 此值由 TYER 框架表示。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | 向标签添加帧。 |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | 删除所有具有指定 id 的帧。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | 获取具有指定 id 的帧数组。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | 从标签中删除指定的帧。 |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | 删除存储在 APIC 框架中的所有附加图片。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | 删除所有与指定帧具有相同 ID 的帧，并将新帧添加到标签中。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | 从包中创建一个列表。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [处理 ID3v2 标签](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### 例子

这个例子展示了如何读取 MP3 文件中的 ID3v2 标签。

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### 也可以看看

* class [ID3Tag](../id3tag)
* 命名空间 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
