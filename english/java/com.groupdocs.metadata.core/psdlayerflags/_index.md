---
title: PsdLayerFlags
second_title: GroupDocs.Metadata for Java API Reference
description: The Photoshop layer flags.
type: docs
weight: 209
url: /java/com.groupdocs.metadata.core/psdlayerflags/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class PsdLayerFlags implements IEnumValue
```

The Photoshop layer flags.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | No flags are set. |
| [TransparencyProtected](#TransparencyProtected) | The transparency protected flag. |
| [Visible](#Visible) | The visibility flag. |
| [Obsolete](#Obsolete) | The obsolete flag. |
| [HasUsefulInformation](#HasUsefulInformation) | Defines if bit 4 has useful information. |
| [PixelDataIrrelevantToAppearanceInDocument](#PixelDataIrrelevantToAppearanceInDocument) | The pixel data is irrelevant to appearance in a document. |
| [Undocumented](#Undocumented) | An undocumented flag. |
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
public static final PsdLayerFlags None
```


No flags are set.

### TransparencyProtected {#TransparencyProtected}
```
public static final PsdLayerFlags TransparencyProtected
```


The transparency protected flag.

### Visible {#Visible}
```
public static final PsdLayerFlags Visible
```


The visibility flag.

### Obsolete {#Obsolete}
```
public static final PsdLayerFlags Obsolete
```


The obsolete flag.

### HasUsefulInformation {#HasUsefulInformation}
```
public static final PsdLayerFlags HasUsefulInformation
```


Defines if bit 4 has useful information. 1 for Photoshop 5.0 and later,

### PixelDataIrrelevantToAppearanceInDocument {#PixelDataIrrelevantToAppearanceInDocument}
```
public static final PsdLayerFlags PixelDataIrrelevantToAppearanceInDocument
```


The pixel data is irrelevant to appearance in a document.

### Undocumented {#Undocumented}
```
public static final PsdLayerFlags Undocumented
```


An undocumented flag.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static PsdLayerFlags getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[PsdLayerFlags](../../com.groupdocs.metadata.core/psdlayerflags)
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
