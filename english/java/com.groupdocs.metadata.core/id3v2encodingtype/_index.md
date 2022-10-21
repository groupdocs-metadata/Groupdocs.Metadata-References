---
title: ID3V2EncodingType
second_title: GroupDocs.Metadata for Java API Reference
description: Defines different types of text encoding used in ID3v2.
type: docs
weight: 321
url: /java/com.groupdocs.metadata.core/id3v2encodingtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum ID3V2EncodingType extends Enum<ID3V2EncodingType> implements IEnumValue
```

Defines different types of text encoding used in ID3v2.
## Fields

| Field | Description |
| --- | --- |
| [Iso88591](#Iso88591) | The ISO-8859-1 encoding. |
| [Utf16](#Utf16) | The UTF-16 encoding with BOM. |
| [Utf16Be](#Utf16Be) | The UTF-16 encoding without BOM. |
| [Utf8](#Utf8) | The UTF-8 encoding. |
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
### Iso88591 {#Iso88591}
```
public static final ID3V2EncodingType Iso88591
```


The ISO-8859-1 encoding.

### Utf16 {#Utf16}
```
public static final ID3V2EncodingType Utf16
```


The UTF-16 encoding with BOM.

### Utf16Be {#Utf16Be}
```
public static final ID3V2EncodingType Utf16Be
```


The UTF-16 encoding without BOM.

### Utf8 {#Utf8}
```
public static final ID3V2EncodingType Utf8
```


The UTF-8 encoding.

### values() {#values--}
```
public static ID3V2EncodingType[] values()
```




**Returns:**
com.groupdocs.metadata.core.ID3V2EncodingType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ID3V2EncodingType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static ID3V2EncodingType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype)
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
