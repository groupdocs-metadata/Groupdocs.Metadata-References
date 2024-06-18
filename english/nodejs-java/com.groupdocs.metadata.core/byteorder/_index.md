---
title: ByteOrder
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines various byte orders.
type: docs
weight: 364
url: /nodejs-java/com.groupdocs.metadata.core/byteorder/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum ByteOrder extends Enum<ByteOrder> implements IEnumValue
```

Defines various byte orders.
## Fields

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | The byte order is unknown. |
| [BigEndian](#BigEndian) | Big endian. |
| [LittleEndian](#LittleEndian) | Little endian. |
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
### Unknown {#Unknown}
```
public static final ByteOrder Unknown
```


The byte order is unknown.

### BigEndian {#BigEndian}
```
public static final ByteOrder BigEndian
```


Big endian.

### LittleEndian {#LittleEndian}
```
public static final ByteOrder LittleEndian
```


Little endian.

### values() {#values--}
```
public static ByteOrder[] values()
```




**Returns:**
com.groupdocs.metadata.core.ByteOrder[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ByteOrder valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ByteOrder](../../com.groupdocs.metadata.core/byteorder)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static ByteOrder getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[ByteOrder](../../com.groupdocs.metadata.core/byteorder)
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
