---
title: SpreadsheetPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示电子表格中的本机元数据包
type: docs
weight: 1200
url: /zh/net/groupdocs.metadata.formats.document/spreadsheetpackage/
---
## SpreadsheetPackage class

表示电子表格中的本机元数据包。

```csharp
public class SpreadsheetPackage : DocumentPackage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/spreadsheetpackage/author) { get; set; } | 获取或设置文档作者。 |
| [Category](../../groupdocs.metadata.formats.document/spreadsheetpackage/category) { get; set; } | 获取或设置类别。 |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetpackage/comments) { get; set; } | 获取或设置注释。 |
| [Company](../../groupdocs.metadata.formats.document/spreadsheetpackage/company) { get; set; } | 获取或设置公司。 |
| [ContentStatus](../../groupdocs.metadata.formats.document/spreadsheetpackage/contentstatus) { get; set; } | 获取或设置内容状态。 |
| [ContentType](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttype) { get; set; } | 获取或设置内容类型。 |
| [ContentTypeProperties](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttypeproperties) { get; } | 获取包含内容类型属性的元数据包。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [CreatedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/createdtime) { get; set; } | 获取或设置文档创建日期。 |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/spreadsheetpackage/hyperlinkbase) { get; set; } | 获取或设置超链接基础。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Keywords](../../groupdocs.metadata.formats.document/spreadsheetpackage/keywords) { get; set; } | 获取或设置关键字。 |
| [Language](../../groupdocs.metadata.formats.document/spreadsheetpackage/language) { get; set; } | 获取或设置文档语言。 |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastprinteddate) { get; set; } | 获取或设置 UTC 格式的最后打印日期。 |
| [LastSavedBy](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedby) { get; set; } | 获取或设置最后一位作者的姓名。 |
| [LastSavedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedtime) { get; set; } | 获取或设置上次保存的UTC时间。 |
| [Manager](../../groupdocs.metadata.formats.document/spreadsheetpackage/manager) { get; set; } | 获取或设置管理器。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [NameOfApplication](../../groupdocs.metadata.formats.document/spreadsheetpackage/nameofapplication) { get; set; } | 获取或设置应用程序的名称。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Revision](../../groupdocs.metadata.formats.document/spreadsheetpackage/revision) { get; set; } | 获取或设置文档修订号。 |
| [Subject](../../groupdocs.metadata.formats.document/spreadsheetpackage/subject) { get; set; } | 获取或设置主题。 |
| [Template](../../groupdocs.metadata.formats.document/spreadsheetpackage/template) { get; set; } | 获取或设置文档模板名称。 |
| [Title](../../groupdocs.metadata.formats.document/spreadsheetpackage/title) { get; set; } | 获取或设置文档的标题。 |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/totaleditingtime) { get; set; } | 获取或设置以分钟为单位的总编辑时间。 |
| [Version](../../groupdocs.metadata.formats.document/spreadsheetpackage/version) { get; set; } | 获取或设置创建文档的应用程序的版本号。 |

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
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set)(string, bool) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_3)(string, DateTime) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_1)(string, double) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_2)(string, int) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_4)(string, string) | 添加或替换具有指定名称的元数据属性。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [在电子表格中使用元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### 例子

此示例说明如何更新电子表格中的内置元数据属性。

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputXlsx);
}
```

### 也可以看看

* class [DocumentPackage](../documentpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
