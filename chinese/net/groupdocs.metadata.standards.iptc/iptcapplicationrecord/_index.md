---
title: IptcApplicationRecord
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 IPTC 应用程序记录
type: docs
weight: 2880
url: /zh/net/groupdocs.metadata.standards.iptc/iptcapplicationrecord/
---
## IptcApplicationRecord class

表示 IPTC 应用程序记录。

```csharp
public sealed class IptcApplicationRecord : IptcRecord
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [IptcApplicationRecord](iptcapplicationrecord)() | 初始化一个新的实例[`IptcApplicationRecord`](../iptcapplicationrecord)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllKeywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/allkeywords) { get; set; } | 获取或设置关键字。 |
| [ByLine](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/byline) { get; set; } | 获取或设置对象创建者的姓名，例如作家、摄影师或图形艺术家。 |
| [ByLines](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylines) { get; set; } | 获取或设置对象创建者的姓名，例如作家、摄影师或图形艺术家。 |
| [ByLineTitle](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitle) { get; set; } | 获取或设置对象的创建者或创建者的头衔。 |
| [ByLineTitles](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitles) { get; set; } | 获取或设置对象的创建者或创建者的头衔。 |
| [CaptionAbstract](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/captionabstract) { get; set; } | 获取或设置对象的文本描述，特别是在对象不是文本的情况下使用。 |
| [City](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/city) { get; set; } | 获取或设置城市。 |
| [Contact](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contact) { get; set; } | 获取或设置有关个人或组织的信息，这些信息可以提供有关对象的更多背景信息。 |
| [Contacts](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contacts) { get; set; } | 获取或设置有关个人或组织的信息，这些信息可以提供有关对象的更多背景信息。 |
| [ContentLocationCode](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcode) { get; set; } | 获取或设置内容位置代码。 |
| [ContentLocationCodes](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcodes) { get; set; } | 获取或设置内容位置代码。 |
| [ContentLocationName](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationname) { get; set; } | 获取或设置内容位置名称。 |
| [ContentLocationNames](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationnames) { get; set; } | 获取或设置内容位置名称。 |
| [CopyrightNotice](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/copyrightnotice) { get; set; } | 获取或设置版权声明。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [Credit](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/credit) { get; set; } | 获取或设置有关对象提供者的信息，不一定是所有者/创建者。 |
| [DateCreated](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/datecreated) { get; set; } | 获取或设置对象的知识内容的创建日期。 |
| [Headline](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/headline) { get; set; } | 获取或设置提供对象内容概要的可发布条目。 |
| [Item](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/item) { get; } | 获取[`IptcDataSet`](../iptcdataset)用指定的数字. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Keywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/keywords) { get; set; } | 获取或设置关键字。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [ProgramVersion](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/programversion) { get; set; } | 获取或设置程序版本。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | 获取记录号。 |
| [ReferenceDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedate) { get; set; } | 获取或设置当前对象引用的先前信封的日期。 |
| [ReferenceDates](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedates) { get; } | 获取当前对象引用的先前信封的日期。 |
| [ReleaseDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/releasedate) { get; set; } | 获取或设置发布日期。 |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | 从包中创建一个列表。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [使用 IPTC IIM 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### 也可以看看

* class [IptcRecord](../iptcrecord)
* 命名空间 [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
