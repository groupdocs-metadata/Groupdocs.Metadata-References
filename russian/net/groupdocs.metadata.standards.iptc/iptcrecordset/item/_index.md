---
title: Item
second_title: Справочник по API GroupDocs.Metadata для .NET
description: ПолучаетIptcRecordgroupdocs.metadata.standards.iptc/iptcrecord с указанным номером.
type: docs
weight: 40
url: /ru/net/groupdocs.metadata.standards.iptc/iptcrecordset/item/
---
## IptcRecordSet indexer (1 of 2)

Получает[`IptcRecord`](../../iptcrecord) с указанным номером.

```csharp
public IptcRecord this[byte recordNumber] { get; }
```

| Параметр | Описание |
| --- | --- |
| recordNumber | Номер записи. |

### Возвращаемое значение

[`IptcRecord`](../../iptcrecord)с указанным номером, если он найден; в противном случае ноль.

### Смотрите также

* class [IptcRecord](../../iptcrecord)
* class [IptcRecordSet](../../iptcrecordset)
* пространство имен [GroupDocs.Metadata.Standards.Iptc](../../iptcrecordset)
* сборка [GroupDocs.Metadata](../../../)

---

## IptcRecordSet indexer (2 of 2)

Получает[`IptcDataSet`](../../iptcdataset) с указанной записью и номером набора данных.

```csharp
public IptcDataSet this[byte recordNumber, byte dataSetNumber] { get; }
```

| Параметр | Описание |
| --- | --- |
| recordNumber | Номер записи. |
| dataSetNumber | Номер набора данных. |

### Возвращаемое значение

[`IptcDataSet`](../../iptcdataset) с указанной записью и номером набора данных.

### Смотрите также

* class [IptcDataSet](../../iptcdataset)
* class [IptcRecordSet](../../iptcrecordset)
* пространство имен [GroupDocs.Metadata.Standards.Iptc](../../iptcrecordset)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->