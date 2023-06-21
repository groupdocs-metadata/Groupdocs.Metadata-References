---
title: PsdCompressionMethod
second_title: GroupDocs.Metadata for Java API Reference
description: Defines the compression method used for image data.
type: docs
weight: 392
url: /java/com.groupdocs.metadata.core/psdcompressionmethod/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum PsdCompressionMethod extends Enum<PsdCompressionMethod> implements IEnumValue
```

Defines the compression method used for image data.
## Fields

| Field | Description |
| --- | --- |
| [Raw](#Raw) | No compression. |
| [Rle](#Rle) | RLE compressed. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP without prediction. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP with prediction. |
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
### Raw {#Raw}
```
public static final PsdCompressionMethod Raw
```


No compression. The image data stored as raw bytes in RGBA planar order. That means that first all R data is written, then all G is written, then all B and finally all A data is written.

### Rle {#Rle}
```
public static final PsdCompressionMethod Rle
```


RLE compressed. The image data starts with the byte counts for all the scan lines (rows \* channels), with each count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately. The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final PsdCompressionMethod ZipWithoutPrediction
```


ZIP without prediction.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final PsdCompressionMethod ZipWithPrediction
```


ZIP with prediction.

### values() {#values--}
```
public static PsdCompressionMethod[] values()
```




**Returns:**
com.groupdocs.metadata.core.PsdCompressionMethod[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PsdCompressionMethod valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PsdCompressionMethod](../../com.groupdocs.metadata.core/psdcompressionmethod)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static PsdCompressionMethod getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[PsdCompressionMethod](../../com.groupdocs.metadata.core/psdcompressionmethod)
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
