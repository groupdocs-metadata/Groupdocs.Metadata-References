---
title: OpenTypeFlags
second_title: GroupDocs.Metadata for Java API Reference
description: Represents OpenType font header flags.
type: docs
weight: 174
url: /java/com.groupdocs.metadata.core/opentypeflags/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class OpenTypeFlags implements IEnumValue
```

Represents OpenType font header flags.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Undefined, no flags. |
| [BaselineAtY0](#BaselineAtY0) | Baseline for font at y=0. |
| [LeftSidebearingAtX0](#LeftSidebearingAtX0) | Left sidebearing point at x=0 (relevant only for TrueType rasterizers). |
| [DependOnPointSize](#DependOnPointSize) | Instructions may depend on point size. |
| [ForceToInteger](#ForceToInteger) | Force ppem to integer values for all internal scaler math; may use fractional ppem sizes if this bit is clear. |
| [AlterAdvanceWidth](#AlterAdvanceWidth) | Instructions may alter advance width (the advance widths might not scale linearly). |
| [Lossless](#Lossless) | Font data is \\u201clossless\\u201d as a result of having been subjected to optimizing transformation and/or compression. |
| [Converted](#Converted) | Font converted (produce compatible metrics). |
| [Optimized](#Optimized) | Font optimized for ClearType\\u2122. |
| [Resort](#Resort) | Last Resort font. |
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
### None {#None}
```
public static final OpenTypeFlags None
```


Undefined, no flags.

### BaselineAtY0 {#BaselineAtY0}
```
public static final OpenTypeFlags BaselineAtY0
```


Baseline for font at y=0.

### LeftSidebearingAtX0 {#LeftSidebearingAtX0}
```
public static final OpenTypeFlags LeftSidebearingAtX0
```


Left sidebearing point at x=0 (relevant only for TrueType rasterizers).

### DependOnPointSize {#DependOnPointSize}
```
public static final OpenTypeFlags DependOnPointSize
```


Instructions may depend on point size.

### ForceToInteger {#ForceToInteger}
```
public static final OpenTypeFlags ForceToInteger
```


Force ppem to integer values for all internal scaler math; may use fractional ppem sizes if this bit is clear.

### AlterAdvanceWidth {#AlterAdvanceWidth}
```
public static final OpenTypeFlags AlterAdvanceWidth
```


Instructions may alter advance width (the advance widths might not scale linearly).

### Lossless {#Lossless}
```
public static final OpenTypeFlags Lossless
```


Font data is \\u201clossless\\u201d as a result of having been subjected to optimizing transformation and/or compression.

### Converted {#Converted}
```
public static final OpenTypeFlags Converted
```


Font converted (produce compatible metrics).

### Optimized {#Optimized}
```
public static final OpenTypeFlags Optimized
```


Font optimized for ClearType\\u2122.

### Resort {#Resort}
```
public static final OpenTypeFlags Resort
```


Last Resort font.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static OpenTypeFlags getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[OpenTypeFlags](../../com.groupdocs.metadata.core/opentypeflags)
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
