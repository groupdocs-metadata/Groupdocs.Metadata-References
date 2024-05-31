---
title: IptcDataSet
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents an IPTC DataSet metadata property.
type: docs
weight: 133
url: /nodejs-java/com.groupdocs.metadata.core/iptcdataset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataProperty](../../com.groupdocs.metadata.core/metadataproperty)
```
public final class IptcDataSet extends MetadataProperty
```

Represents an IPTC DataSet (metadata property).

**Learn more**

 *  [Working with IPTC IIM metadata][]


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [IptcDataSet(byte recordNumber, byte dataSetNumber, byte[] value)](#IptcDataSet-byte-byte-byte---) | Initializes a new instance of the  IptcDataSet  class. |
| [IptcDataSet(byte recordNumber, byte dataSetNumber, String value)](#IptcDataSet-byte-byte-java.lang.String-) | Initializes a new instance of the  IptcDataSet  class. |
| [IptcDataSet(byte recordNumber, byte dataSetNumber, int value)](#IptcDataSet-byte-byte-int-) | Initializes a new instance of the  IptcDataSet  class. |
| [IptcDataSet(byte recordNumber, byte dataSetNumber, Date value)](#IptcDataSet-byte-byte-java.util.Date-) | Initializes a new instance of the  IptcDataSet  class. |
## Methods

| Method | Description |
| --- | --- |
| [getRecordNumber()](#getRecordNumber--) | Gets the record number. |
| [getDataSetNumber()](#getDataSetNumber--) | Gets the dataSet number. |
| [getAlternativeName()](#getAlternativeName--) | Gets the alternative name of the dataSet. |
### IptcDataSet(byte recordNumber, byte dataSetNumber, byte[] value) {#IptcDataSet-byte-byte-byte---}
```
public IptcDataSet(byte recordNumber, byte dataSetNumber, byte[] value)
```


Initializes a new instance of the  IptcDataSet  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |
| dataSetNumber | byte | The dataSet number. |
| value | byte[] | A byte array value. |

### IptcDataSet(byte recordNumber, byte dataSetNumber, String value) {#IptcDataSet-byte-byte-java.lang.String-}
```
public IptcDataSet(byte recordNumber, byte dataSetNumber, String value)
```


Initializes a new instance of the  IptcDataSet  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |
| dataSetNumber | byte | The dataSet number. |
| value | java.lang.String | A string value. |

### IptcDataSet(byte recordNumber, byte dataSetNumber, int value) {#IptcDataSet-byte-byte-int-}
```
public IptcDataSet(byte recordNumber, byte dataSetNumber, int value)
```


Initializes a new instance of the  IptcDataSet  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |
| dataSetNumber | byte | The dataSet number. |
| value | int | An integer value. |

### IptcDataSet(byte recordNumber, byte dataSetNumber, Date value) {#IptcDataSet-byte-byte-java.util.Date-}
```
public IptcDataSet(byte recordNumber, byte dataSetNumber, Date value)
```


Initializes a new instance of the  IptcDataSet  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordNumber | byte | The record number. |
| dataSetNumber | byte | The dataSet number. |
| value | java.util.Date | A date value. |

### getRecordNumber() {#getRecordNumber--}
```
public final byte getRecordNumber()
```


Gets the record number.

**Returns:**
byte - The record number.
### getDataSetNumber() {#getDataSetNumber--}
```
public final byte getDataSetNumber()
```


Gets the dataSet number.

**Returns:**
byte - The dataSet number.
### getAlternativeName() {#getAlternativeName--}
```
public final String getAlternativeName()
```


Gets the alternative name of the dataSet.

**Returns:**
java.lang.String - The alternative name of the dataSet.
