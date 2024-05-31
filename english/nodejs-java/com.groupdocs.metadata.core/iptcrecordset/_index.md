---
title: IptcRecordSet
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a collection of IPTC records.
type: docs
weight: 137
url: /nodejs-java/com.groupdocs.metadata.core/iptcrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class IptcRecordSet extends CustomPackage
```

Represents a collection of IPTC records.

**Learn more**

 *  [Working with IPTC IIM metadata][]

This code sample shows hot to update basic IPTC metadata properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputJpeg)) {
>      IIptc root = (IIptc) metadata.getRootPackage();
>      // Set the IPTC package if it's missing
>      if (root.getIptcPackage() == null) {
>          root.setIptcPackage(new IptcRecordSet());
>      }
>      if (root.getIptcPackage().getEnvelopeRecord() == null) {
>          root.getIptcPackage().setEnvelopeRecord(new IptcEnvelopeRecord());
>      }
>      root.getIptcPackage().getEnvelopeRecord().setDateSent(new Date());
>      root.getIptcPackage().getEnvelopeRecord().setProductID("test project id");
>      // ...
>      if (root.getIptcPackage().getApplicationRecord() == null) {
>          root.getIptcPackage().setApplicationRecord(new IptcApplicationRecord());
>      }
>      root.getIptcPackage().getApplicationRecord().setByLine("GroupDocs");
>      root.getIptcPackage().getApplicationRecord().setHeadline("test");
>      root.getIptcPackage().getApplicationRecord().setByLineTitle("code sample");
>      root.getIptcPackage().getApplicationRecord().setReleaseDate(new Date());
>      // ...
>      metadata.save(Constants.OutputJpeg);
>  }
>  
> ```
> ```


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [IptcRecordSet()](#IptcRecordSet--) | Initializes a new instance of the  IptcRecordSet  class. |
| [IptcRecordSet(IptcDataSet[] dataSets)](#IptcRecordSet-com.groupdocs.metadata.core.IptcDataSet---) | Initializes a new instance of the  IptcRecordSet  class. |
## Methods

| Method | Description |
| --- | --- |
| [getEnvelopeRecord()](#getEnvelopeRecord--) | Gets the Envelope Record. |
| [setEnvelopeRecord(IptcEnvelopeRecord value)](#setEnvelopeRecord-com.groupdocs.metadata.core.IptcEnvelopeRecord-) | Sets the Envelope Record. |
| [getApplicationRecord()](#getApplicationRecord--) | Gets the Application Record. |
| [setApplicationRecord(IptcApplicationRecord value)](#setApplicationRecord-com.groupdocs.metadata.core.IptcApplicationRecord-) | Sets the Application Record. |
| [get_Item(byte recordNumber)](#get-Item-byte-) | Gets the  IptcRecord  with the specified number. |
| [get_Item(byte recordNumber, byte dataSetNumber)](#get-Item-byte-byte-) | Gets the  IptcDataSet  with the specified record and dataSet number. |
| [set(IptcDataSet dataSet)](#set-com.groupdocs.metadata.core.IptcDataSet-) | Adds or updates the specified dataSet in the appropriate record. |
| [add(IptcDataSet dataSet)](#add-com.groupdocs.metadata.core.IptcDataSet-) | Adds the specified dataSet to the appropriate record. |
| [remove(byte recordNumber, byte dataSetNumber)](#remove-byte-byte-) | Removes the dataSet with the specified record and dataSet number. |
| [clear()](#clear--) | Removes all records from the collection. |
| [remove(byte recordNumber)](#remove-byte-) | Removes the record with the specified record number. |
| [toDataSetList()](#toDataSetList--) | Creates a list of dataSets from the package. |
| [toList()](#toList--) | Creates a list from the package. |
### IptcRecordSet() {#IptcRecordSet--}
```
public IptcRecordSet()
```


Initializes a new instance of the  IptcRecordSet  class.

### IptcRecordSet(IptcDataSet[] dataSets) {#IptcRecordSet-com.groupdocs.metadata.core.IptcDataSet---}
```
public IptcRecordSet(IptcDataSet[] dataSets)
```


Initializes a new instance of the  IptcRecordSet  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSets | [IptcDataSet\[\]](../../com.groupdocs.metadata.core/iptcdataset) | An array of IPTC dataSets. |

### getEnvelopeRecord() {#getEnvelopeRecord--}
```
public final IptcEnvelopeRecord getEnvelopeRecord()
```


Gets the Envelope Record.

**Returns:**
[IptcEnvelopeRecord](../../com.groupdocs.metadata.core/iptcenveloperecord) - The Envelope Record.
### setEnvelopeRecord(IptcEnvelopeRecord value) {#setEnvelopeRecord-com.groupdocs.metadata.core.IptcEnvelopeRecord-}
```
public final void setEnvelopeRecord(IptcEnvelopeRecord value)
```


Sets the Envelope Record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IptcEnvelopeRecord](../../com.groupdocs.metadata.core/iptcenveloperecord) | The Envelope Record. |

### getApplicationRecord() {#getApplicationRecord--}
```
public final IptcApplicationRecord getApplicationRecord()
```


Gets the Application Record.

**Returns:**
[IptcApplicationRecord](../../com.groupdocs.metadata.core/iptcapplicationrecord) - The Application Record.
### setApplicationRecord(IptcApplicationRecord value) {#setApplicationRecord-com.groupdocs.metadata.core.IptcApplicationRecord-}
```
public final void setApplicationRecord(IptcApplicationRecord value)
```


Sets the Application Record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IptcApplicationRecord](../../com.groupdocs.metadata.core/iptcapplicationrecord) | The Application Record. |

### get_Item(byte recordNumber) {#get-Item-byte-}
```
public final IptcRecord get_Item(byte recordNumber)
```


Gets the  IptcRecord  with the specified number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |

**Returns:**
[IptcRecord](../../com.groupdocs.metadata.core/iptcrecord) - The  IptcRecord  with the specified number, if found; otherwise null.
### get_Item(byte recordNumber, byte dataSetNumber) {#get-Item-byte-byte-}
```
public final IptcDataSet get_Item(byte recordNumber, byte dataSetNumber)
```


Gets the  IptcDataSet  with the specified record and dataSet number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |
| dataSetNumber | byte | The dataSet number. |

**Returns:**
[IptcDataSet](../../com.groupdocs.metadata.core/iptcdataset) - The  IptcDataSet  with the specified record and dataSet number.
### set(IptcDataSet dataSet) {#set-com.groupdocs.metadata.core.IptcDataSet-}
```
public final void set(IptcDataSet dataSet)
```


Adds or updates the specified dataSet in the appropriate record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSet | [IptcDataSet](../../com.groupdocs.metadata.core/iptcdataset) | The IPTC dataSet to add/update. |

### add(IptcDataSet dataSet) {#add-com.groupdocs.metadata.core.IptcDataSet-}
```
public final void add(IptcDataSet dataSet)
```


Adds the specified dataSet to the appropriate record. The dataSet is considered as repeatable if a dataSet with the specified number already exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSet | [IptcDataSet](../../com.groupdocs.metadata.core/iptcdataset) | The IPTC dataSet to add. |

### remove(byte recordNumber, byte dataSetNumber) {#remove-byte-byte-}
```
public final boolean remove(byte recordNumber, byte dataSetNumber)
```


Removes the dataSet with the specified record and dataSet number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |
| dataSetNumber | byte | The dataSet number. |

**Returns:**
boolean - True if the specified IPTC dataSet is found and removed; otherwise, false.
### clear() {#clear--}
```
public final void clear()
```


Removes all records from the collection.

### remove(byte recordNumber) {#remove-byte-}
```
public final boolean remove(byte recordNumber)
```


Removes the record with the specified record number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |

**Returns:**
boolean - True if the specified IPTC record is found and removed; otherwise, false.
### toDataSetList() {#toDataSetList--}
```
public final IReadOnlyList<IptcDataSet> toDataSetList()
```


Creates a list of dataSets from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list that contains all IPTC dataSets from the package.
### toList() {#toList--}
```
public final IReadOnlyList<IptcRecord> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list that contains all IPTC records from the package.
