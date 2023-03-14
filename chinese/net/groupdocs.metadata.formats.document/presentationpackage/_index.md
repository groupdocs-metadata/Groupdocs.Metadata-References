---
title: PresentationPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示演示文稿中的本机元数据包
type: docs
weight: 1090
url: /zh/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

表示演示文稿中的本机元数据包。

```csharp
public class PresentationPackage : DocumentPackage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | 获取或设置应用程序模板。 |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | 获取或设置文档的作者。 |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | 获取或设置类别。 |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | 获取或设置注释。 |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | 获取或设置公司。 |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | 获取或设置内容状态。只能在 PPTX 文档中更新。 |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | 获取或设置内容类型。只能在 PPTX 文档中更新。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | 获取或设置文档创建日期。 |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | 获取或设置超链接基础。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | 获取或设置关键字。 |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | 获取或设置最后打印日期。 |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | 获取或设置最后一位作者的姓名。 |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | 获取上次修改演示文稿的日期和时间。 |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | 获取或设置管理器。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | 获取创建文档的应用程序的名称。 |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | 获取表示格式。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | 获取或设置修订号。 |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | 获取或设置一个值，该值指示演示文稿是否在多人之间共享。只能在 PPTX 文档中更新。 |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | 获取或设置主题。 |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | 获取或设置文档的标题。 |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | 获取或设置文档的总编辑时间。 |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | 获取应用程序版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | 从包中删除所有可写元数据属性。 |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | 删除所有内置元数据属性。 |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | 删除所有自定义元数据属性。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | 删除指定名称的可写元数据属性。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | 添加或替换具有指定名称的元数据属性。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [在演示文稿中使用元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### 例子

此示例演示如何更新演示文稿中的内置元数据属性。

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### 也可以看看

* class [DocumentPackage](../documentpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
