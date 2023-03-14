---
title: DiagramPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示图表格式的本机元数据包
type: docs
weight: 890
url: /zh/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

表示图表格式的本机元数据包。

```csharp
public class DiagramPackage : DocumentPackage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | 获取或设置文档的备用名称。只能以 VDX 和 VSX 格式更新。 |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | 获取用于创建文档的实例的完整内部版本号。 |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | 获取上次用于编辑文档的实例的内部版本号。 |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | 获取或设置绘图类型的描述性文本，例如流程图或办公室布局。 此文本也可以在 Microsoft Visio 用户界面的“属性”对话框的“类别”框中输入。 |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | 获取或设置用户输入的信息，用于标识创建绘图的公司或为其创建绘图的公司。 最大长度为 63 个字符。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | 获取或设置创建或最后更新文件的人。 最大长度为 63 个字符.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | 获取或设置文档的描述性文本字符串。 使用此元素存储有关文档的重要信息，例如其用途、最近的更改或未决更改。 最多为 191 个字符。 |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | 获取或设置用于相对超链接的路径（超链接的链接文件位置是相对于 Microsoft Visio 图描述的）。 默认情况下，超链接路径是相对于当前文档的，除非指定了不同的路径在此元素中。 最大长度为 256 个字符。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | 获取或设置一个文本字符串，用于标识主题或有关文件的其他重要信息，例如项目名称、客户端名称或版本号。 最大字符串长度为 63 个字符。 |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | 获取或设置文档的语言。 只能以 VSD 和 VSDX 格式更新。 |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | 获取或设置用户输入的文本字符串，用于标识项目或部门的负责人。 最大长度为 63 个字符。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | 获取或设置预览图片。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | 获取或设置描述文档内容的用户定义文本字符串。 最大长度为 63 个字符。 |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | 获取或设置一个字符串值，指定从中创建文档的模板的文件名。 |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | 获取或设置指示文档创建时间的日期和时间值。 |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | 获取指示文档上次编辑时间的日期和时间值。 |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | 获取指示文档上次打印时间的日期和时间值。 |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | 获取指示文档上次保存时间的日期和时间值。 |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | 获取或设置用作文档描述性标题的用户定义文本字符串。 最大长度为 63 个字符。 |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | 添加或替换具有指定名称的元数据属性。 |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | 添加或替换具有指定名称的元数据属性。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [在图表中使用元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### 例子

此代码示例演示如何从图表中提取内置元数据属性。

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### 也可以看看

* class [DocumentPackage](../documentpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
