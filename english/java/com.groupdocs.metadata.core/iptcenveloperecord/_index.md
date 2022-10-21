---
title: IptcEnvelopeRecord
second_title: GroupDocs.Metadata for Java API Reference
description: Represents an IPTC Envelope Record.
type: docs
weight: 102
url: /java/com.groupdocs.metadata.core/iptcenveloperecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.IptcRecord](../../com.groupdocs.metadata.core/iptcrecord)
```
public final class IptcEnvelopeRecord extends IptcRecord
```

Represents an IPTC Envelope Record.

**Learn more**

 *  [Working with IPTC IIM metadata][]


[Working with IPTC IIM metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+IPTC+IIM+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [IptcEnvelopeRecord()](#IptcEnvelopeRecord--) | Initializes a new instance of the  IptcEnvelopeRecord  class. |
## Methods

| Method | Description |
| --- | --- |
| [getModelVersion()](#getModelVersion--) | Gets a number identifying the version of the information. |
| [setModelVersion(Integer value)](#setModelVersion-java.lang.Integer-) | Sets a number identifying the version of the information. |
| [getDestination()](#getDestination--) | Gets the destination. |
| [setDestination(String value)](#setDestination-java.lang.String-) | Sets the destination. |
| [getDestinations()](#getDestinations--) | Gets an array of destinations. |
| [setDestinations(String[] value)](#setDestinations-java.lang.String---) | Sets an array of destinations. |
| [getFileFormat()](#getFileFormat--) | Gets the file format. |
| [setFileFormat(Integer value)](#setFileFormat-java.lang.Integer-) | Sets the file format. |
| [getFileFormatVersion()](#getFileFormatVersion--) | Gets the file format version. |
| [setFileFormatVersion(Integer value)](#setFileFormatVersion-java.lang.Integer-) | Sets the file format version. |
| [getServiceIdentifier()](#getServiceIdentifier--) | Gets the service identifier. |
| [setServiceIdentifier(String value)](#setServiceIdentifier-java.lang.String-) | Sets the service identifier. |
| [getProductID()](#getProductID--) | Gets the product identifier. |
| [setProductID(String value)](#setProductID-java.lang.String-) | Sets the product identifier. |
| [getProductIds()](#getProductIds--) | Gets the product identifiers. |
| [setProductIds(String[] value)](#setProductIds-java.lang.String---) | Sets the product identifiers. |
| [getDateSent()](#getDateSent--) | Gets the date the service sent the material. |
| [setDateSent(Date value)](#setDateSent-java.util.Date-) | Sets the date the service sent the material. |
| [getByIptcEnvelopeRecordDataSet(IptcEnvelopeRecordDataSet dataSetNumber)](#getByIptcEnvelopeRecordDataSet-com.groupdocs.metadata.core.IptcEnvelopeRecordDataSet-) | Gets the  IptcDataSet  with the specified number. |
### IptcEnvelopeRecord() {#IptcEnvelopeRecord--}
```
public IptcEnvelopeRecord()
```


Initializes a new instance of the  IptcEnvelopeRecord  class.

### getModelVersion() {#getModelVersion--}
```
public final Integer getModelVersion()
```


Gets a number identifying the version of the information.

**Returns:**
java.lang.Integer - The model version.
### setModelVersion(Integer value) {#setModelVersion-java.lang.Integer-}
```
public final void setModelVersion(Integer value)
```


Sets a number identifying the version of the information.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The model version. |

### getDestination() {#getDestination--}
```
public final String getDestination()
```


Gets the destination.

**Returns:**
java.lang.String - The destination.
### setDestination(String value) {#setDestination-java.lang.String-}
```
public final void setDestination(String value)
```


Sets the destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The destination. |

### getDestinations() {#getDestinations--}
```
public final String[] getDestinations()
```


Gets an array of destinations.

**Returns:**
java.lang.String[] - The destinations.
### setDestinations(String[] value) {#setDestinations-java.lang.String---}
```
public final void setDestinations(String[] value)
```


Sets an array of destinations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The destinations. |

### getFileFormat() {#getFileFormat--}
```
public final Integer getFileFormat()
```


Gets the file format.

**Returns:**
java.lang.Integer - The file format.
### setFileFormat(Integer value) {#setFileFormat-java.lang.Integer-}
```
public final void setFileFormat(Integer value)
```


Sets the file format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The file format. |

### getFileFormatVersion() {#getFileFormatVersion--}
```
public final Integer getFileFormatVersion()
```


Gets the file format version. A number representing the particular version of the File Format specified in  FileFormat .

**Returns:**
java.lang.Integer - The file format version.
### setFileFormatVersion(Integer value) {#setFileFormatVersion-java.lang.Integer-}
```
public final void setFileFormatVersion(Integer value)
```


Sets the file format version. A number representing the particular version of the File Format specified in  FileFormat .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The file format version. |

### getServiceIdentifier() {#getServiceIdentifier--}
```
public final String getServiceIdentifier()
```


Gets the service identifier.

**Returns:**
java.lang.String - The service identifier.
### setServiceIdentifier(String value) {#setServiceIdentifier-java.lang.String-}
```
public final void setServiceIdentifier(String value)
```


Sets the service identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The service identifier. |

### getProductID() {#getProductID--}
```
public final String getProductID()
```


Gets the product identifier.

**Returns:**
java.lang.String - The product identifier.
### setProductID(String value) {#setProductID-java.lang.String-}
```
public final void setProductID(String value)
```


Sets the product identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The product identifier. |

### getProductIds() {#getProductIds--}
```
public final String[] getProductIds()
```


Gets the product identifiers.

**Returns:**
java.lang.String[] - The product identifiers.
### setProductIds(String[] value) {#setProductIds-java.lang.String---}
```
public final void setProductIds(String[] value)
```


Sets the product identifiers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The product identifiers. |

### getDateSent() {#getDateSent--}
```
public final Date getDateSent()
```


Gets the date the service sent the material.

**Returns:**
java.util.Date - The date the service sent the material.
### setDateSent(Date value) {#setDateSent-java.util.Date-}
```
public final void setDateSent(Date value)
```


Sets the date the service sent the material.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date the service sent the material. |

### getByIptcEnvelopeRecordDataSet(IptcEnvelopeRecordDataSet dataSetNumber) {#getByIptcEnvelopeRecordDataSet-com.groupdocs.metadata.core.IptcEnvelopeRecordDataSet-}
```
public final IptcDataSet getByIptcEnvelopeRecordDataSet(IptcEnvelopeRecordDataSet dataSetNumber)
```


Gets the  IptcDataSet  with the specified number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataSetNumber | [IptcEnvelopeRecordDataSet](../../com.groupdocs.metadata.core/iptcenveloperecorddataset) | The dataSet number. |

**Returns:**
[IptcDataSet](../../com.groupdocs.metadata.core/iptcdataset) - The  IptcDataSet  with the specified number.
