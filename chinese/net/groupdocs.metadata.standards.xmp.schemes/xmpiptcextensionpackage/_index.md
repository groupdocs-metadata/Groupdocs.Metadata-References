---
title: XmpIptcExtensionPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 代表IPTC扩展XMP包
type: docs
weight: 3150
url: /zh/net/groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/
---
## XmpIptcExtensionPackage class

代表IPTC扩展XMP包。

```csharp
public sealed class XmpIptcExtensionPackage : XmpPackage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmpIptcExtensionPackage](xmpiptcextensionpackage)() | 初始化一个新的实例[`XmpIptcExtensionPackage`](../xmpiptcextensionpackage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AdditionalModelInformation](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/additionalmodelinformation) { get; set; } | 获取或设置模型发布图像中有关模型的种族和其他方面的信息。 |
| [AgesOfModels](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/agesofmodels) { get; set; } | 获取或设置在模型发布图像中拍摄此图像时人体模型的年龄。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DigitalImageGuid](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalimageguid) { get; set; } | 获取或设置此数字图像的全局唯一标识符。 |
| [DigitalSourceType](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalsourcetype) { get; set; } | 获取或设置此数字图像源的类型。 |
| [Event](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/event) { get; set; } | 获取或设置拍摄照片的特定事件的描述。 |
| [IptcLastEdited](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/iptclastedited) { get; set; } | 获取或设置上次编辑任何 IPTC 照片元数据字段的日期和可选时间。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [MaxAvailableHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailableheight) { get; set; } | 获取或设置原始照片的最大可用高度（以像素为单位），通过缩小尺寸从中导出此照片。 |
| [MaxAvailableWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailablewidth) { get; set; } | 获取或设置原始照片的最大可用宽度（以像素为单位），通过缩小尺寸从中导出此照片。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 获取命名空间 URI。 |
| [OrganisationInImageCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagecodes) { get; set; } | 从受控词汇表中获取或设置代码，用于识别图像中的组织或公司。 |
| [OrganisationInImageNames](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagenames) { get; set; } | 获取或设置图像中出现的组织或公司的名称。 |
| [PersonsInImage](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/personsinimage) { get; set; } | 获取或设置项目内容相关人员的姓名。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | 获取 xmlns 前缀。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_7)(string, string) | 设置字符串属性。 |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_2)(string, XmpArray) | 设置继承自的值[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | 设置继承自的值[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | 设置继承自的值[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase). |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 也可以看看

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 命名空间 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
