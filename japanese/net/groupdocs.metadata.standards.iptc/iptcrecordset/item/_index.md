---
title: Item
second_title: GroupDocs.Metadata for .NET API リファレンス
description: を取得しますIptcRecordgroupdocs.metadata.standards.iptc/iptcrecord指定された番号で.
type: docs
weight: 40
url: /ja/net/groupdocs.metadata.standards.iptc/iptcrecordset/item/
---
## IptcRecordSet indexer (1 of 2)

を取得します[`IptcRecord`](../../iptcrecord)指定された番号で.

```csharp
public IptcRecord this[byte recordNumber] { get; }
```

| パラメータ | 説明 |
| --- | --- |
| recordNumber | レコード番号。 |

### 戻り値

の[`IptcRecord`](../../iptcrecord)見つかった場合は、指定された番号で。それ以外の場合は null。

### 関連項目

* class [IptcRecord](../../iptcrecord)
* class [IptcRecordSet](../../iptcrecordset)
* 名前空間 [GroupDocs.Metadata.Standards.Iptc](../../iptcrecordset)
* 組み立て [GroupDocs.Metadata](../../../)

---

## IptcRecordSet indexer (2 of 2)

を取得します[`IptcDataSet`](../../iptcdataset)指定されたレコードとデータセット番号.

```csharp
public IptcDataSet this[byte recordNumber, byte dataSetNumber] { get; }
```

| パラメータ | 説明 |
| --- | --- |
| recordNumber | レコード番号。 |
| dataSetNumber | データセット番号。 |

### 戻り値

の[`IptcDataSet`](../../iptcdataset)指定されたレコードとデータセット番号で。

### 関連項目

* class [IptcDataSet](../../iptcdataset)
* class [IptcRecordSet](../../iptcrecordset)
* 名前空間 [GroupDocs.Metadata.Standards.Iptc](../../iptcrecordset)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
