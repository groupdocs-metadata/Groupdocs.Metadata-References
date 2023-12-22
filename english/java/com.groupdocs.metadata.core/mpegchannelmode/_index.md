---
title: MpegChannelMode
second_title: GroupDocs.Metadata for Java API Reference
description: Defines MPEG audio channel modes.
type: docs
weight: 372
url: /java/com.groupdocs.metadata.core/mpegchannelmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum MpegChannelMode extends Enum<MpegChannelMode> implements IEnumValue
```

Defines MPEG audio channel modes.
## Fields

| Field | Description |
| --- | --- |
| [Stereo](#Stereo) | Stereo mode. |
| [JointStereo](#JointStereo) | Joint stereo mode. |
| [DualChannel](#DualChannel) | Dual channel mode. |
| [Mono](#Mono) | Mono mode. |
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
### Stereo {#Stereo}
```
public static final MpegChannelMode Stereo
```


Stereo mode.

### JointStereo {#JointStereo}
```
public static final MpegChannelMode JointStereo
```


Joint stereo mode.

### DualChannel {#DualChannel}
```
public static final MpegChannelMode DualChannel
```


Dual channel mode.

### Mono {#Mono}
```
public static final MpegChannelMode Mono
```


Mono mode.

### values() {#values--}
```
public static MpegChannelMode[] values()
```




**Returns:**
com.groupdocs.metadata.core.MpegChannelMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MpegChannelMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MpegChannelMode](../../com.groupdocs.metadata.core/mpegchannelmode)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static MpegChannelMode getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[MpegChannelMode](../../com.groupdocs.metadata.core/mpegchannelmode)
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
