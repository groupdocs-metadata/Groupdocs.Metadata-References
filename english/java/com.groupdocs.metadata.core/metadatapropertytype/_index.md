---
title: MetadataPropertyType
second_title: GroupDocs.Metadata for Java API Reference
description: Defines metadata property types.
type: docs
weight: 371
url: /java/com.groupdocs.metadata.core/metadatapropertytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum MetadataPropertyType extends Enum<MetadataPropertyType> implements IEnumValue
```

Defines metadata property types.
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Represents an empty (null) property. |
| [String](#String) | Represents a string property. |
| [Boolean](#Boolean) | Represents a boolean property. |
| [DateTime](#DateTime) | Represents a date property. |
| [TimeSpan](#TimeSpan) | Represents a time property. |
| [Integer](#Integer) | Represents an integer property. |
| [Long](#Long) | Represents a long integer property. |
| [Double](#Double) | Represents a property with a double or float value. |
| [StringArray](#StringArray) | Represents a string array property. |
| [ByteArray](#ByteArray) | Represents a byte array property. |
| [DoubleArray](#DoubleArray) | Represents an array of double values. |
| [IntegerArray](#IntegerArray) | Represents an array of integer values. |
| [LongArray](#LongArray) | Represents an array of long values. |
| [Metadata](#Metadata) | Represents a nested metadata block. |
| [MetadataArray](#MetadataArray) | Represents an array of nested metadata blocks. |
| [Guid](#Guid) | Represents a global unique identifier value. |
| [PropertyValueArray](#PropertyValueArray) | Represents a metadata property value array. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
### Empty {#Empty}
```
public static final MetadataPropertyType Empty
```


Represents an empty (null) property.

### String {#String}
```
public static final MetadataPropertyType String
```


Represents a string property.

### Boolean {#Boolean}
```
public static final MetadataPropertyType Boolean
```


Represents a boolean property.

### DateTime {#DateTime}
```
public static final MetadataPropertyType DateTime
```


Represents a date property.

### TimeSpan {#TimeSpan}
```
public static final MetadataPropertyType TimeSpan
```


Represents a time property.

### Integer {#Integer}
```
public static final MetadataPropertyType Integer
```


Represents an integer property.

### Long {#Long}
```
public static final MetadataPropertyType Long
```


Represents a long integer property.

### Double {#Double}
```
public static final MetadataPropertyType Double
```


Represents a property with a double or float value.

### StringArray {#StringArray}
```
public static final MetadataPropertyType StringArray
```


Represents a string array property.

### ByteArray {#ByteArray}
```
public static final MetadataPropertyType ByteArray
```


Represents a byte array property.

### DoubleArray {#DoubleArray}
```
public static final MetadataPropertyType DoubleArray
```


Represents an array of double values.

### IntegerArray {#IntegerArray}
```
public static final MetadataPropertyType IntegerArray
```


Represents an array of integer values.

### LongArray {#LongArray}
```
public static final MetadataPropertyType LongArray
```


Represents an array of long values.

### Metadata {#Metadata}
```
public static final MetadataPropertyType Metadata
```


Represents a nested metadata block.

### MetadataArray {#MetadataArray}
```
public static final MetadataPropertyType MetadataArray
```


Represents an array of nested metadata blocks.

### Guid {#Guid}
```
public static final MetadataPropertyType Guid
```


Represents a global unique identifier value.

### PropertyValueArray {#PropertyValueArray}
```
public static final MetadataPropertyType PropertyValueArray
```


Represents a metadata property value array.

### values() {#values--}
```
public static MetadataPropertyType[] values()
```




**Returns:**
com.groupdocs.metadata.core.MetadataPropertyType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MetadataPropertyType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static MetadataPropertyType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype)
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
