---
title: AsfExtendedStreamPropertyFlags
second_title: GroupDocs.Signature for Java API Reference
description: Defines ASF extended stream property flags.
type: docs
weight: 17
url: /java/com.groupdocs.metadata.core/asfextendedstreampropertyflags/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class AsfExtendedStreamPropertyFlags implements IEnumValue
```

Defines ASF extended stream property flags.
## Fields

| Field | Description |
| --- | --- |
| [Reliable](#Reliable) | This digital media stream, if sent over a network, must be carried over a reliable data communications transport mechanism. |
| [Seekable](#Seekable) | This flag should be set only if the stream is seekable. |
| [NoCleanpoints](#NoCleanpoints) | The stream does not contain any cleanpoints. |
| [ResendLiveCleanpoints](#ResendLiveCleanpoints) | A stream is joined in mid-transmission, all information from the most recent cleanpoint up to the current time should be sent before normal streaming begins at the current time. |
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
### Reliable {#Reliable}
```
public static final AsfExtendedStreamPropertyFlags Reliable
```


This digital media stream, if sent over a network, must be carried over a reliable data communications transport mechanism.

### Seekable {#Seekable}
```
public static final AsfExtendedStreamPropertyFlags Seekable
```


This flag should be set only if the stream is seekable.

### NoCleanpoints {#NoCleanpoints}
```
public static final AsfExtendedStreamPropertyFlags NoCleanpoints
```


The stream does not contain any cleanpoints.

### ResendLiveCleanpoints {#ResendLiveCleanpoints}
```
public static final AsfExtendedStreamPropertyFlags ResendLiveCleanpoints
```


A stream is joined in mid-transmission, all information from the most recent cleanpoint up to the current time should be sent before normal streaming begins at the current time.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static AsfExtendedStreamPropertyFlags getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[AsfExtendedStreamPropertyFlags](../../com.groupdocs.metadata.core/asfextendedstreampropertyflags)
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
