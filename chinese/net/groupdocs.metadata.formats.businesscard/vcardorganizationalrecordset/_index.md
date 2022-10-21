---
title: VCardOrganizationalRecordset
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示一组组织 vCard 记录 这些属性与 vCard 所代表对象的组织或组织单位的特征相关联的信息
type: docs
weight: 750
url: /zh/net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/
---
## VCardOrganizationalRecordset class

表示一组组织 vCard 记录。 这些属性与 vCard 所代表对象的组织或组织单位的特征相关联的信息。

```csharp
public class VCardOrganizationalRecordset : VCardRecordset
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AgentObjectRecord](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentobjectrecord) { get; } | 获取将代表 vCard 对象行事的另一个人的信息。 |
| [AgentRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentrecords) { get; } | 获取将代表 vCard 对象行事的另一个人的信息。 |
| [AgentUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agenturirecords) { get; } | 获取将代表 vCard 对象行事的另一个人的信息。 |
| [BinaryLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/binarylogos) { get; } | 获取与对象关联的徽标的图形图像。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定的名称。 |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [LogoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logobinaryrecords) { get; } | 获取与对象关联的徽标的图形图像。 |
| [LogoRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logorecords) { get; } | 获取与对象关联的徽标的图形图像。 |
| [LogoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logourirecords) { get; } | 获取与对象关联的徽标的图形图像的 URI。 |
| [MemberRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/memberrecords) { get; } | 获取此 vCard 所代表的组中的成员。 |
| [Members](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/members) { get; } | 获取此 vCard 所代表的组中的成员。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [ObjectAgent](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/objectagent) { get; } | 获取将代表 vCard 对象行事的另一个人的信息。 |
| [OrganizationNameRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnamerecords) { get; } | 获取与对象关联的组织名称和单位。 |
| [OrganizationNames](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnames) { get; } | 获取与对象关联的组织名称和单位。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [RelationshipRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationshiprecords) { get; } | 获取另一个实体与此 vCard 表示的实体之间的关系。 |
| [Relationships](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationships) { get; } | 获取另一个实体与此 vCard 表示的实体之间的关系。 |
| [RoleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/rolerecords) { get; } | 获取对象在特定情况下发挥的功能或部分。 |
| [Roles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/roles) { get; } | 获取对象在特定情况下发挥的功能或部分。 |
| [TitleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titlerecords) { get; } | 获取对象的职位或工作。 |
| [Titles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titles) { get; } | 获取对象的职位或工作。 |
| [UriAgents](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uriagents) { get; } | 获取将代表 vCard 对象行事的另一个人的信息。 |
| [UriLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/urilogos) { get; } | 获取与对象关联的徽标的图形图像的 URI。 |

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

* [使用 vCard 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### 也可以看看

* class [VCardRecordset](../vcardrecordset)
* 命名空间 [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
