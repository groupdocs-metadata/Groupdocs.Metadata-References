---
title: IptcRecordSet
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 IPTC 记录的集合
type: docs
weight: 2940
url: /zh/net/groupdocs.metadata.standards.iptc/iptcrecordset/
---
## IptcRecordSet class

表示 IPTC 记录的集合。

```csharp
public sealed class IptcRecordSet : CustomPackage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [IptcRecordSet](iptcrecordset#constructor)() | 初始化[`IptcRecordSet`](../iptcrecordset)类. |
| [IptcRecordSet](iptcrecordset#constructor_1)(IptcDataSet[]) | 初始化[`IptcRecordSet`](../iptcrecordset)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ApplicationRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/applicationrecord) { get; set; } | 获取或设置应用程序记录。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [EnvelopeRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/enveloperecord) { get; set; } | 获取或设置信封记录。 |
| [Item](../../groupdocs.metadata.standards.iptc/iptcrecordset/item) { get; } | 获取[`IptcRecord`](../iptcrecord)具有指定的编号。 (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../groupdocs.metadata.standards.iptc/iptcrecordset/add)(IptcDataSet) | 将指定的数据集添加到相应的记录中。 如果指定编号的数据集已经存在，则认为该数据集是可重复的。 |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.standards.iptc/iptcrecordset/clear)() | 从集合中删除所有记录。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove)(byte) | 删除指定记录号的记录。 |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove_1)(byte, byte) | 删除具有指定记录和数据集编号的数据集。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.standards.iptc/iptcrecordset/set)(IptcDataSet) | 在相应的记录中添加或更新指定的数据集。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [ToDataSetList](../../groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist)() | 从包中创建一个数据集列表。 |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecordset/tolist)() | 从包中创建一个列表。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**学到更多**

* [使用 IPTC IIM 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### 例子

此代码示例显示了更新基本 IPTC 元数据属性的热点。

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // 如果缺少 IPTC 包，请设置它
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        if (root.IptcPackage.EnvelopeRecord == null)
        {
            root.IptcPackage.EnvelopeRecord = new IptcEnvelopeRecord();
        }

        root.IptcPackage.EnvelopeRecord.DateSent = DateTime.Now;
        root.IptcPackage.EnvelopeRecord.ProductID = Guid.NewGuid().ToString();

        // ...

        if (root.IptcPackage.ApplicationRecord == null)
        {
            root.IptcPackage.ApplicationRecord = new IptcApplicationRecord();
        }

        root.IptcPackage.ApplicationRecord.ByLine = "GroupDocs";
        root.IptcPackage.ApplicationRecord.Headline = "test";
        root.IptcPackage.ApplicationRecord.ByLineTitle = "code sample";
        root.IptcPackage.ApplicationRecord.ReleaseDate = DateTime.Today;

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### 也可以看看

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 命名空间 [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
