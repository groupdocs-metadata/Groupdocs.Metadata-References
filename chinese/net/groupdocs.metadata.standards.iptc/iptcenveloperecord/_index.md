---
title: IptcEnvelopeRecord
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 IPTC 信封记录
type: docs
weight: 2910
url: /zh/net/groupdocs.metadata.standards.iptc/iptcenveloperecord/
---
## IptcEnvelopeRecord class

表示 IPTC 信封记录。

```csharp
public sealed class IptcEnvelopeRecord : IptcRecord
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [IptcEnvelopeRecord](iptcenveloperecord)() | 初始化一个新的实例[`IptcEnvelopeRecord`](../iptcenveloperecord)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DateSent](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/datesent) { get; set; } | 获取或设置服务发送材料的日期。 |
| [Destination](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destination) { get; set; } | 获取或设置目标。 |
| [Destinations](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/destinations) { get; set; } | 获取或设置目的地数组。 |
| [FileFormat](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformat) { get; set; } | 获取或设置文件格式。 |
| [FileFormatVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/fileformatversion) { get; set; } | 获取或设置文件格式版本。 代表指定的文件格式的特定版本的数字[`FileFormat`](./fileformat). |
| [Item](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/item) { get; } | 获取[`IptcDataSet`](../iptcdataset)用指定的数字. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [ModelVersion](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/modelversion) { get; set; } | 获取或设置标识信息版本的数字。 |
| [ProductID](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productid) { get; set; } | 获取或设置产品标识符。 |
| [ProductIds](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/productids) { get; set; } | 获取或设置产品标识符。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | 获取记录号。 |
| [ServiceIdentifier](../../groupdocs.metadata.standards.iptc/iptcenveloperecord/serviceidentifier) { get; set; } | 获取或设置服务标识符。 |

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
