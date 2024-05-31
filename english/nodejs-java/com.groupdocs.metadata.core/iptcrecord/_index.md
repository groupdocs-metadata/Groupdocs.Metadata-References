---
title: IptcRecord
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents an IPTC record.
type: docs
weight: 136
url: /nodejs-java/com.groupdocs.metadata.core/iptcrecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class IptcRecord extends CustomPackage
```

Represents an IPTC record.

**Learn more**

 *  [Working with IPTC IIM metadata][]


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Methods

| Method | Description |
| --- | --- |
| [getRecordNumber()](#getRecordNumber--) | Gets the record number. |
| [toList()](#toList--) | Creates a list from the package. |
| [get_Item(byte dataSetNumber)](#get-Item-byte-) | Gets the  IptcDataSet  with the specified dataSet number. |
### getRecordNumber() {#getRecordNumber--}
```
public final byte getRecordNumber()
```


Gets the record number.

**Returns:**
byte - The record number.
### toList() {#toList--}
```
public final IReadOnlyList<IptcDataSet> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list that contains all IPTC dataSets from the package.
### get_Item(byte dataSetNumber) {#get-Item-byte-}
```
public final IptcDataSet get_Item(byte dataSetNumber)
```


Gets the  IptcDataSet  with the specified dataSet number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSetNumber | byte | The IPTC dataSet number. |

**Returns:**
[IptcDataSet](../../com.groupdocs.metadata.core/iptcdataset) - The  IptcDataSet  with the specified dataSet number, if found; otherwise null.
