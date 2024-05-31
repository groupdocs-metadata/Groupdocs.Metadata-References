---
title: OpenTypeUnicodeEncoding
second_title: GroupDocs.Metadata for Java API Reference
description: Represents encoding for OpenTypePlatform.Unicode platform.
type: docs
weight: 390
url: /java/com.groupdocs.metadata.core/opentypeunicodeencoding/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum OpenTypeUnicodeEncoding extends Enum<OpenTypeUnicodeEncoding> implements IEnumValue
```

Represents encoding for  OpenTypePlatform.Unicode  platform.
## Fields

| Field | Description |
| --- | --- |
| [Unicode10](#Unicode10) | Unicode 1.0 semantics. |
| [Unicode11](#Unicode11) | Unicode 1.1 semantics. |
| [Iso](#Iso) | ISO/IEC 10646 semantics. |
| [Unicode20Bmp](#Unicode20Bmp) | Unicode 2.0 and onwards semantics, Unicode BMP only ('cmap' subtable formats 0, 4, 6). |
| [Unicode20Full](#Unicode20Full) | Unicode 2.0 and onwards semantics, Unicode full repertoire ('cmap' subtable formats 0, 4, 6, 10, 12). |
| [UnicodeVariation](#UnicodeVariation) | Unicode Variation Sequences ('cmap' subtable format 14). |
| [UnicodeFull](#UnicodeFull) | Unicode full repertoire ('cmap' subtable formats 0, 4, 6, 10, 12, 13). |
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
### Unicode10 {#Unicode10}
```
public static final OpenTypeUnicodeEncoding Unicode10
```


Unicode 1.0 semantics.

### Unicode11 {#Unicode11}
```
public static final OpenTypeUnicodeEncoding Unicode11
```


Unicode 1.1 semantics.

### Iso {#Iso}
```
public static final OpenTypeUnicodeEncoding Iso
```


ISO/IEC 10646 semantics.

### Unicode20Bmp {#Unicode20Bmp}
```
public static final OpenTypeUnicodeEncoding Unicode20Bmp
```


Unicode 2.0 and onwards semantics, Unicode BMP only ('cmap' subtable formats 0, 4, 6).

### Unicode20Full {#Unicode20Full}
```
public static final OpenTypeUnicodeEncoding Unicode20Full
```


Unicode 2.0 and onwards semantics, Unicode full repertoire ('cmap' subtable formats 0, 4, 6, 10, 12).

### UnicodeVariation {#UnicodeVariation}
```
public static final OpenTypeUnicodeEncoding UnicodeVariation
```


Unicode Variation Sequences ('cmap' subtable format 14).

### UnicodeFull {#UnicodeFull}
```
public static final OpenTypeUnicodeEncoding UnicodeFull
```


Unicode full repertoire ('cmap' subtable formats 0, 4, 6, 10, 12, 13).

### values() {#values--}
```
public static OpenTypeUnicodeEncoding[] values()
```




**Returns:**
com.groupdocs.metadata.core.OpenTypeUnicodeEncoding[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static OpenTypeUnicodeEncoding valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[OpenTypeUnicodeEncoding](../../com.groupdocs.metadata.core/opentypeunicodeencoding)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static OpenTypeUnicodeEncoding getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[OpenTypeUnicodeEncoding](../../com.groupdocs.metadata.core/opentypeunicodeencoding)
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
