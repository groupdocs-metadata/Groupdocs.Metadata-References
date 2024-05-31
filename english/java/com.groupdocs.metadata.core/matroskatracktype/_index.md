---
title: MatroskaTrackType
second_title: GroupDocs.Metadata for Java API Reference
description: Represents Matroska track types coded in 8 bits.
type: docs
weight: 373
url: /java/com.groupdocs.metadata.core/matroskatracktype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum MatroskaTrackType extends Enum<MatroskaTrackType> implements IEnumValue
```

Represents Matroska track types coded in 8 bits.
## Fields

| Field | Description |
| --- | --- |
| [Undefined](#Undefined) | The undefined track type. |
| [Video](#Video) | Track is a video track. |
| [Audio](#Audio) | Track is an audio track. |
| [Complex](#Complex) | Track is a complex track, i.e. |
| [Logo](#Logo) | Track is a logo track. |
| [Subtitle](#Subtitle) | Track is a subtitle track. |
| [Button](#Button) | Track is a button track. |
| [Control](#Control) | Track is a control track. |
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
### Undefined {#Undefined}
```
public static final MatroskaTrackType Undefined
```


The undefined track type.

### Video {#Video}
```
public static final MatroskaTrackType Video
```


Track is a video track.

### Audio {#Audio}
```
public static final MatroskaTrackType Audio
```


Track is an audio track.

### Complex {#Complex}
```
public static final MatroskaTrackType Complex
```


Track is a complex track, i.e. a combined video and audio track.

### Logo {#Logo}
```
public static final MatroskaTrackType Logo
```


Track is a logo track.

### Subtitle {#Subtitle}
```
public static final MatroskaTrackType Subtitle
```


Track is a subtitle track.

### Button {#Button}
```
public static final MatroskaTrackType Button
```


Track is a button track.

### Control {#Control}
```
public static final MatroskaTrackType Control
```


Track is a control track.

### values() {#values--}
```
public static MatroskaTrackType[] values()
```




**Returns:**
com.groupdocs.metadata.core.MatroskaTrackType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MatroskaTrackType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MatroskaTrackType](../../com.groupdocs.metadata.core/matroskatracktype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static MatroskaTrackType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[MatroskaTrackType](../../com.groupdocs.metadata.core/matroskatracktype)
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
