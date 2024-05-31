---
title: PsdColorMode
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the psd file format color mode.
type: docs
weight: 398
url: /java/com.groupdocs.metadata.core/psdcolormode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum PsdColorMode extends Enum<PsdColorMode> implements IEnumValue
```

Represents the psd file format color mode.
## Fields

| Field | Description |
| --- | --- |
| [Bitmap](#Bitmap) | The bitmap color mode. |
| [Grayscale](#Grayscale) | The grayscale mode. |
| [Indexed](#Indexed) | The indexed color mode. |
| [Rgb](#Rgb) | The RGB color mode. |
| [Cmyk](#Cmyk) | The CMYK color mode. |
| [Multichannel](#Multichannel) | The multichannel color mode. |
| [Duotone](#Duotone) | The duotone color mode. |
| [Lab](#Lab) | The LAB color mode. |
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
### Bitmap {#Bitmap}
```
public static final PsdColorMode Bitmap
```


The bitmap color mode.

### Grayscale {#Grayscale}
```
public static final PsdColorMode Grayscale
```


The grayscale mode.

### Indexed {#Indexed}
```
public static final PsdColorMode Indexed
```


The indexed color mode.

### Rgb {#Rgb}
```
public static final PsdColorMode Rgb
```


The RGB color mode.

### Cmyk {#Cmyk}
```
public static final PsdColorMode Cmyk
```


The CMYK color mode.

### Multichannel {#Multichannel}
```
public static final PsdColorMode Multichannel
```


The multichannel color mode.

### Duotone {#Duotone}
```
public static final PsdColorMode Duotone
```


The duotone color mode.

### Lab {#Lab}
```
public static final PsdColorMode Lab
```


The LAB color mode.

### values() {#values--}
```
public static PsdColorMode[] values()
```




**Returns:**
com.groupdocs.metadata.core.PsdColorMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PsdColorMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PsdColorMode](../../com.groupdocs.metadata.core/psdcolormode)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static PsdColorMode getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[PsdColorMode](../../com.groupdocs.metadata.core/psdcolormode)
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
