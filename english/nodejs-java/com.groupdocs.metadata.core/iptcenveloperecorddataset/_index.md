---
title: IptcEnvelopeRecordDataSet
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines IPTC Envelope Record dataSet numbers.
type: docs
weight: 135
url: /nodejs-java/com.groupdocs.metadata.core/iptcenveloperecorddataset/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class IptcEnvelopeRecordDataSet implements IEnumValue
```

Defines IPTC Envelope Record dataSet numbers.
## Fields

| Field | Description |
| --- | --- |
| [ModelVersion](#ModelVersion) |  |
| [Destination](#Destination) |  |
| [FileFormat](#FileFormat) | File format. |
| [FileFormatVersion](#FileFormatVersion) |  |
| [ServiceIdentifier](#ServiceIdentifier) |  |
| [EnvelopeNumber](#EnvelopeNumber) |  |
| [ProductID](#ProductID) |  |
| [EnvelopePriority](#EnvelopePriority) |  |
| [DateSent](#DateSent) |  |
| [TimeSent](#TimeSent) |  |
| [CodedCharacterSet](#CodedCharacterSet) |  |
| [Uno](#Uno) | Invalid (eternal identifier). |
| [ArmIdentifier](#ArmIdentifier) | The DataSet identifies the Abstract Relationship Method (ARM) which is described in a document registered by the originator of the ARM with the IPTC and NAA. |
| [ArmVersion](#ArmVersion) | Binary number representing the particular version of the ARM specified in DataSet 1:120. |
## Methods

| Method | Description |
| --- | --- |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
| [name()](#name--) |  |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### ModelVersion {#ModelVersion}
```
public static final IptcEnvelopeRecordDataSet ModelVersion
```


A binary number identifying the version of the Information 

 Interchange Model, Part I, utilised by the provider. Version numbers are assigned by IPTC and NAA. 

 The version number of this record is four (4).

### Destination {#Destination}
```
public static final IptcEnvelopeRecordDataSet Destination
```


Optional, repeatable, maximum 1024 octets, consisting of sequentially contiguous graphic characters. 

 This DataSet is to accommodate some providers who require routing information above the appropriate OSI layers.

### FileFormat {#FileFormat}
```
public static final IptcEnvelopeRecordDataSet FileFormat
```


File format.

### FileFormatVersion {#FileFormatVersion}
```
public static final IptcEnvelopeRecordDataSet FileFormatVersion
```


Mandatory, not repeatable, two octets. 

 A binary number representing the particular version of the File Format specified in 1:20. 

 A list of File Formats, including version cross references, is included as Appendix A.

### ServiceIdentifier {#ServiceIdentifier}
```
public static final IptcEnvelopeRecordDataSet ServiceIdentifier
```


Mandatory, not repeatable. Up to 10 octets, consisting of graphic characters. 

 Identifies the provider and product.

### EnvelopeNumber {#EnvelopeNumber}
```
public static final IptcEnvelopeRecordDataSet EnvelopeNumber
```


Mandatory, not repeatable, eight octets, consisting of numeric characters. 

 The characters form a number that will be unique for the date specified in 1:70 and for the Service Identifier specified in 1:30. 

 If identical envelope numbers appear with the same date and with the same Service Identifier, records 2-9 must be unchanged from the original. 

 This is not intended to be a sequential serial number reception check.

### ProductID {#ProductID}
```
public static final IptcEnvelopeRecordDataSet ProductID
```


Optional, repeatable. Up to 32 octets, consisting of graphic characters. 

 Allows a provider to identify subsets of its overall service. 

 Used to provide receiving organization data on which to select, route, or otherwise handle data.

### EnvelopePriority {#EnvelopePriority}
```
public static final IptcEnvelopeRecordDataSet EnvelopePriority
```


Optional, not repeatable. A single octet, consisting of a numeric character. 

 Specifies the envelope handling priority and not the editorial urgency (see 2:10, Urgency). '1' indicates the most urgent, '5' the normal urgency, and '8' the least urgent copy. The numeral '9' indicates a User Defined Priority. The numeral '0' is reserved for future use.

### DateSent {#DateSent}
```
public static final IptcEnvelopeRecordDataSet DateSent
```


Mandatory, not repeatable. Eight octets, consisting of numeric characters. 

 Uses the format CCYYMMDD (century, year, month, day) as defined in ISO 8601 to indicate year, month and day the service sent the material.

### TimeSent {#TimeSent}
```
public static final IptcEnvelopeRecordDataSet TimeSent
```


Uses the format HHMMSS±HHMM where HHMMSS refers to local hour, minute and seconds and HHMM refers to hours and minutes ahead (+) or behind (-) Universal Coordinated Time as described in ISO 8601. This is the time the service sent the material.

### CodedCharacterSet {#CodedCharacterSet}
```
public static final IptcEnvelopeRecordDataSet CodedCharacterSet
```


Optional, not repeatable, up to 32 octets, consisting of one or more control functions used for the announcement, invocation or designation of coded character sets. The control functions follow the ISO 2022 standard and may consist of the escape control character and one or more graphic characters. For more details see Appendix C, the IPTC-NAA Code Library.

### Uno {#Uno}
```
public static final IptcEnvelopeRecordDataSet Uno
```


Invalid (eternal identifier).

### ArmIdentifier {#ArmIdentifier}
```
public static final IptcEnvelopeRecordDataSet ArmIdentifier
```


The DataSet identifies the Abstract Relationship Method (ARM) which is described in a document registered by the originator of the ARM with the IPTC and NAA.

### ArmVersion {#ArmVersion}
```
public static final IptcEnvelopeRecordDataSet ArmVersion
```


Binary number representing the particular version of the ARM specified in DataSet 1:120.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static IptcEnvelopeRecordDataSet getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IptcEnvelopeRecordDataSet](../../com.groupdocs.metadata.core/iptcenveloperecorddataset)
### getFirst() {#getFirst--}
```
public static IEnumValue getFirst()
```




**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getAllValues() {#getAllValues--}
```
public Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[]
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getRawValueType() {#getRawValueType--}
```
public RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype)
### getRawValue() {#getRawValue--}
```
public int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int
### name() {#name--}
```
public String name()
```


Returns the name of this enumeration value.

**Returns:**
java.lang.String
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
