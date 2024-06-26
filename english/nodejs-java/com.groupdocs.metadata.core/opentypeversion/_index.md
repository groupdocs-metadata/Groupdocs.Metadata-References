---
title: OpenTypeVersion
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the OpenType version.
type: docs
weight: 391
url: /nodejs-java/com.groupdocs.metadata.core/opentypeversion/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum OpenTypeVersion extends Enum<OpenTypeVersion> implements IEnumValue
```

Represents the OpenType version.
## Fields

| Field | Description |
| --- | --- |
| [TrueType](#TrueType) | The TrueType font. |
| [Cff](#Cff) | The OpenType font with PostScript outlines. |
| [TrueTypeOsX](#TrueTypeOsX) | The OS X and iOS TrueType font. |
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
### TrueType {#TrueType}
```
public static final OpenTypeVersion TrueType
```


The TrueType font.

### Cff {#Cff}
```
public static final OpenTypeVersion Cff
```


The OpenType font with PostScript outlines.

### TrueTypeOsX {#TrueTypeOsX}
```
public static final OpenTypeVersion TrueTypeOsX
```


The OS X and iOS TrueType font.

### values() {#values--}
```
public static OpenTypeVersion[] values()
```




**Returns:**
com.groupdocs.metadata.core.OpenTypeVersion[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static OpenTypeVersion valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[OpenTypeVersion](../../com.groupdocs.metadata.core/opentypeversion)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static OpenTypeVersion getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[OpenTypeVersion](../../com.groupdocs.metadata.core/opentypeversion)
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
