---
title: ToDataSetList
second_title: GroupDocs.Metadata for .NET API 参考
description: 从包中创建数据集列表
type: docs
weight: 90
url: /zh/net/groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist/
---
## IptcRecordSet.ToDataSetList method

从包中创建数据集列表。

```csharp
public IReadOnlyList<IptcDataSet> ToDataSetList()
```

### 返回值

包含包中所有 IPTC 数据集的列表。

### 例子

此示例演示如何从 IPTC 元数据包中读取所有 IPTC IIM 数据集。

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithIptc))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null && root.IptcPackage != null)
    {
        foreach (var dataSet in root.IptcPackage.ToDataSetList())
        {
            Console.WriteLine(dataSet.RecordNumber);
            Console.WriteLine(dataSet.DataSetNumber);
            Console.WriteLine(dataSet.AlternativeName);
            Console.WriteLine(dataSet.Value);
        }
    }
}
```

### 也可以看看

* interface [IReadOnlyList&lt;T&gt;](../../../groupdocs.metadata.common/ireadonlylist-1)
* class [IptcDataSet](../../iptcdataset)
* class [IptcRecordSet](../../iptcrecordset)
* 命名空间 [GroupDocs.Metadata.Standards.Iptc](../../iptcrecordset)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
