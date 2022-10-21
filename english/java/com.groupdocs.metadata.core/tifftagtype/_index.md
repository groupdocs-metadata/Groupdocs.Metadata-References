---
title: TiffTagType
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the IFD data type.
type: docs
weight: 354
url: /java/com.groupdocs.metadata.core/tifftagtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum TiffTagType extends Enum<TiffTagType> implements IEnumValue
```

Represents the IFD data type.
## Fields

| Field | Description |
| --- | --- |
| [Byte](#Byte) | An 8-bit unsigned integer. |
| [Ascii](#Ascii) | An 8-bit byte with a 7-bit ASCII character. |
| [Short](#Short) | A 16-bit unsigned integer. |
| [Long](#Long) | A 32-bit unsigned integer. |
| [Rational](#Rational) | A pair of LONGs, numerator then denominator. |
| [SByte](#SByte) | An 8-bit signed integer. |
| [Undefined](#Undefined) | An undefined 8-bit byte. |
| [SShort](#SShort) | A 16-bit signed integer. |
| [SLong](#SLong) | A 32-bit signed integer. |
| [SRational](#SRational) | A pair of SLONGs, numerator then denominator. |
| [Float](#Float) | A 4-byte IEEE floating point value. |
| [Double](#Double) | An 8-byte IEEE floating point value. |
| [SubIfd](#SubIfd) | A 4-byte long offset value |
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
### Byte {#Byte}
```
public static final TiffTagType Byte
```


An 8-bit unsigned integer.

### Ascii {#Ascii}
```
public static final TiffTagType Ascii
```


An 8-bit byte with a 7-bit ASCII character.

### Short {#Short}
```
public static final TiffTagType Short
```


A 16-bit unsigned integer.

### Long {#Long}
```
public static final TiffTagType Long
```


A 32-bit unsigned integer.

### Rational {#Rational}
```
public static final TiffTagType Rational
```


A pair of LONGs, numerator then denominator.

### SByte {#SByte}
```
public static final TiffTagType SByte
```


An 8-bit signed integer.

### Undefined {#Undefined}
```
public static final TiffTagType Undefined
```


An undefined 8-bit byte.

### SShort {#SShort}
```
public static final TiffTagType SShort
```


A 16-bit signed integer.

### SLong {#SLong}
```
public static final TiffTagType SLong
```


A 32-bit signed integer.

### SRational {#SRational}
```
public static final TiffTagType SRational
```


A pair of SLONGs, numerator then denominator.

### Float {#Float}
```
public static final TiffTagType Float
```


A 4-byte IEEE floating point value.

### Double {#Double}
```
public static final TiffTagType Double
```


An 8-byte IEEE floating point value.

### SubIfd {#SubIfd}
```
public static final TiffTagType SubIfd
```


A 4-byte long offset value

### values() {#values--}
```
public static TiffTagType[] values()
```




**Returns:**
com.groupdocs.metadata.core.TiffTagType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TiffTagType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[TiffTagType](../../com.groupdocs.metadata.core/tifftagtype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static TiffTagType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[TiffTagType](../../com.groupdocs.metadata.core/tifftagtype)
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
