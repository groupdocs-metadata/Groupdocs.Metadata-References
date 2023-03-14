---
title: XmpMediaManagementPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 XMP 媒体管理命名空间
type: docs
weight: 3170
url: /zh/net/groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/
---
## XmpMediaManagementPackage class

表示 XMP 媒体管理命名空间。

```csharp
public sealed class XmpMediaManagementPackage : XmpPackage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmpMediaManagementPackage](xmpmediamanagementpackage)() | 初始化一个新的实例[`XmpMediaManagementPackage`](../xmpmediamanagementpackage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DerivedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/derivedfrom) { get; set; } | 获取或设置对派生此资源的资源的引用。 |
| [DocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/documentid) { get; set; } | 获取或设置资源的所有版本和再现的通用标识符。 |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/history) { get; set; } | 获取或设置导致此资源的高级操作数组。 |
| [Ingredients](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/ingredients) { get; set; } | 获取或设置对通过包含或引用合并到此资源中的资源的引用。 |
| [InstanceID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/instanceid) { get; set; } | 获取或设置资源特定化身的标识符，每次保存文件时更新。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [ManagedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managedfrom) { get; set; } | 获取或设置对文档的引用，因为它在成为托管之前。 |
| [Manager](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manager) { get; set; } | 获取或设置管理此资源的资产管理系统的名称。 |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managervariant) { get; set; } | 获取或设置资产管理系统的特定变体。 |
| [ManageTo](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageto) { get; set; } | 获取或设置资产管理系统标识托管资源的URI |
| [ManageUI](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageui) { get; set; } | 获取或设置可用于通过 Web 浏览器访问有关托管资源的信息的 URI。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 获取命名空间 URI。 |
| [OriginalDocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/originaldocumentid) { get; set; } | 获取或设置当前资源派生自的原始资源的公共标识符。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | 获取 xmlns 前缀。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [RenditionClass](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionclass) { get; set; } | 获取或设置此资源的再现类名称。 |
| [RenditionParams](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionparams) { get; set; } | 获取或设置用于提供额外再现参数 的值，这些参数太复杂或冗长而无法在 xmpMM:RenditionClass. 中编码 |
| [VersionID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versionid) { get; set; } | 获取或设置此资源的文档版本标识符。 |
| [Versions](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versions) { get; set; } | 获取或设置与此资源关联的版本历史记录。 |
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
