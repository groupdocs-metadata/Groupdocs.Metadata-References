---
title: XmpCropUnit
second_title: GroupDocs.Metadata for Java API Reference
description: Represent a unit for CropWidth and CropHeight in XmpCameraRawPackage.
type: docs
weight: 409
url: /java/com.groupdocs.metadata.core/xmpcropunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum XmpCropUnit extends Enum<XmpCropUnit> implements IEnumValue
```

Represent a unit for CropWidth and CropHeight in  XmpCameraRawPackage .
## Fields

| Field | Description |
| --- | --- |
| [Pixels](#Pixels) | Pixels units. |
| [Inches](#Inches) | Inches units. |
| [Cm](#Cm) | Centimeters units. |
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
### Pixels {#Pixels}
```
public static final XmpCropUnit Pixels
```


Pixels units.

### Inches {#Inches}
```
public static final XmpCropUnit Inches
```


Inches units.

### Cm {#Cm}
```
public static final XmpCropUnit Cm
```


Centimeters units.

### values() {#values--}
```
public static XmpCropUnit[] values()
```




**Returns:**
com.groupdocs.metadata.core.XmpCropUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static XmpCropUnit valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[XmpCropUnit](../../com.groupdocs.metadata.core/xmpcropunit)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static XmpCropUnit getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[XmpCropUnit](../../com.groupdocs.metadata.core/xmpcropunit)
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
