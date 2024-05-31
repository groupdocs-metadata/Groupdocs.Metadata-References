---
title: MatroskaVideoFieldOrder
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the field ordering of the Matroska video.
type: docs
weight: 375
url: /java/com.groupdocs.metadata.core/matroskavideofieldorder/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum MatroskaVideoFieldOrder extends Enum<MatroskaVideoFieldOrder> implements IEnumValue
```

Represents the field ordering of the Matroska video. If FlagInterlaced is not set to 1, this Element MUST be ignored.
## Fields

| Field | Description |
| --- | --- |
| [Progressive](#Progressive) | Progressive ordering. |
| [Tff](#Tff) | Tiff ordering. |
| [Undetermined](#Undetermined) | Undetermined ordering. |
| [Bff](#Bff) | Biff ordering. |
| [BffSwapped](#BffSwapped) | Bff (swapped) ordering. |
| [TffSwapped](#TffSwapped) | Tff (swapped) ordering. |
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
### Progressive {#Progressive}
```
public static final MatroskaVideoFieldOrder Progressive
```


Progressive ordering.

### Tff {#Tff}
```
public static final MatroskaVideoFieldOrder Tff
```


Tiff ordering.

### Undetermined {#Undetermined}
```
public static final MatroskaVideoFieldOrder Undetermined
```


Undetermined ordering.

### Bff {#Bff}
```
public static final MatroskaVideoFieldOrder Bff
```


Biff ordering.

### BffSwapped {#BffSwapped}
```
public static final MatroskaVideoFieldOrder BffSwapped
```


Bff (swapped) ordering.

### TffSwapped {#TffSwapped}
```
public static final MatroskaVideoFieldOrder TffSwapped
```


Tff (swapped) ordering.

### values() {#values--}
```
public static MatroskaVideoFieldOrder[] values()
```




**Returns:**
com.groupdocs.metadata.core.MatroskaVideoFieldOrder[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MatroskaVideoFieldOrder valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MatroskaVideoFieldOrder](../../com.groupdocs.metadata.core/matroskavideofieldorder)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static MatroskaVideoFieldOrder getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[MatroskaVideoFieldOrder](../../com.groupdocs.metadata.core/matroskavideofieldorder)
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
