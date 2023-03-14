---
title: XmpIptcCorePackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 代表IPTC Core XMP包
type: docs
weight: 3140
url: /zh/net/groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/
---
## XmpIptcCorePackage class

代表IPTC Core XMP包。

```csharp
public sealed class XmpIptcCorePackage : XmpPackage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmpIptcCorePackage](xmpiptccorepackage)() | 初始化一个新的实例[`XmpIptcCorePackage`](../xmpiptccorepackage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [CountryCode](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/countrycode) { get; set; } | 获取或设置内容关注的国家代码。该代码应取自 ISO 3166 两个或三个字母代码。 |
| [IntellectualGenre](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/intellectualgenre) { get; set; } | 获取或设置智力流派。描述新闻对象的性质、知识、艺术或新闻特征，而不是具体描述其内容。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Location](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/location) { get; set; } | 获取或设置内容所关注的位置。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 获取命名空间 URI。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | 获取 xmlns 前缀。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Scenes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/scenes) { get; set; } | 获取或设置照片内容的场景。 |
| [SubjectCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptccorepackage/subjectcodes) { get; set; } | 从 IPTC“Subject-NewsCodes”分类法中获取或设置一个或多个主题以对内容进行分类。每个主题都表示为无序列表中的 8 位字符串。 |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | 获取 XML 命名空间。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | 删除所有 XMP 属性。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | 将 XMP 值转换为 XML 表示。 |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | 删除具有指定名称的属性。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | 设置布尔属性。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | 集DateTime财产. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | 设置双重属性。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | 设置整数属性。 |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | 设置字符串属性。 |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | 设置继承自的值[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | 设置继承自的值[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | 设置继承自的值[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase). |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 也可以看看

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 命名空间 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
