---
title: XmpArrayType
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents array type in XmpArray.
type: docs
weight: 406
url: /nodejs-java/com.groupdocs.metadata.core/xmparraytype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum XmpArrayType extends Enum<XmpArrayType> implements IEnumValue
```

Represents array type in  XmpArray .
## Fields

| Field | Description |
| --- | --- |
| [Unordered](#Unordered) | An unordered array. |
| [Ordered](#Ordered) | An ordered array. |
| [Alternative](#Alternative) | An alternative array. |
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
### Unordered {#Unordered}
```
public static final XmpArrayType Unordered
```


An unordered array.

### Ordered {#Ordered}
```
public static final XmpArrayType Ordered
```


An ordered array.

### Alternative {#Alternative}
```
public static final XmpArrayType Alternative
```


An alternative array.

### values() {#values--}
```
public static XmpArrayType[] values()
```




**Returns:**
com.groupdocs.metadata.core.XmpArrayType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static XmpArrayType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static XmpArrayType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype)
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
