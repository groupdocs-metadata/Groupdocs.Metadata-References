---
title: IEnumValue
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines a value of an enumeration.
type: docs
weight: 355
url: /nodejs-java/com.groupdocs.metadata.core/ienumvalue/
---```
public interface IEnumValue
```

Defines a value of an enumeration.
## Methods

| Method | Description |
| --- | --- |
| [getAllValues()](#getAllValues--) | Returns the array of all values defined in the class. |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) | Returns the enumeration value by the raw value associated with it. |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) | Returns the enumeration value by its name. |
| [getRawValueType()](#getRawValueType--) | Returns the underlying type of the raw value of this enumeration value. |
| [getRawValue()](#getRawValue--) | Returns the raw value of this enumeration value. |
| [name()](#name--) | Returns the name of this enumeration value. |
### getAllValues() {#getAllValues--}
```
public abstract Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[] - The array of all values defined in the class.
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public abstract IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int | The raw value. |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue) - The enumeration value.
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public abstract IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the enumeration value. |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue) - The enumeration value.
### getRawValueType() {#getRawValueType--}
```
public abstract RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype) - The underlying type of the raw value.
### getRawValue() {#getRawValue--}
```
public abstract int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int - The raw value.
### name() {#name--}
```
public abstract String name()
```


Returns the name of this enumeration value.

**Returns:**
java.lang.String - The name.
