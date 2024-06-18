---
title: AsfDescriptorType
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines ASF descriptor types.
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.metadata.core/asfdescriptortype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class AsfDescriptorType implements IEnumValue
```

Defines ASF descriptor types.
## Fields

| Field | Description |
| --- | --- |
| [Unicode](#Unicode) | The unicode string type. |
| [ByteArray](#ByteArray) | The byte array type. |
| [Bool](#Bool) | The 32-bit bool type. |
| [DWord](#DWord) | The 32-bit unsigned integer type. |
| [QWord](#QWord) | The 64-bit unsigned integer type. |
| [Word](#Word) | The 16-bit unsigned integer type. |
| [Guid](#Guid) | The 128-bit (16 byte) GUID type. |
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
### Unicode {#Unicode}
```
public static final AsfDescriptorType Unicode
```


The unicode string type.

### ByteArray {#ByteArray}
```
public static final AsfDescriptorType ByteArray
```


The byte array type.

### Bool {#Bool}
```
public static final AsfDescriptorType Bool
```


The 32-bit bool type.

### DWord {#DWord}
```
public static final AsfDescriptorType DWord
```


The 32-bit unsigned integer type.

### QWord {#QWord}
```
public static final AsfDescriptorType QWord
```


The 64-bit unsigned integer type.

### Word {#Word}
```
public static final AsfDescriptorType Word
```


The 16-bit unsigned integer type.

### Guid {#Guid}
```
public static final AsfDescriptorType Guid
```


The 128-bit (16 byte) GUID type.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static AsfDescriptorType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[AsfDescriptorType](../../com.groupdocs.metadata.core/asfdescriptortype)
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
