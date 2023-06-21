---
title: PropertyAccessLevels
second_title: GroupDocs.Metadata for Java API Reference
description: Defines access levels for metadata properties.
type: docs
weight: 207
url: /java/com.groupdocs.metadata.core/propertyaccesslevels/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class PropertyAccessLevels implements IEnumValue
```

Defines access levels for metadata properties.
## Fields

| Field | Description |
| --- | --- |
| [Read](#Read) | The property is read-only. |
| [Update](#Update) | It is possible to update the property using the  MetadataPackage.UpdateProperties  method. |
| [Remove](#Remove) | The property can be removed through the  MetadataPackage.RemoveProperties  method. |
| [Add](#Add) | It is possible to update the property using the  MetadataPackage.AddProperties  method. |
| [Full](#Full) | Grants full access to the property. |
| [AddOrUpdate](#AddOrUpdate) | It is allowed to add and update the property. |
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
### Read {#Read}
```
public static final PropertyAccessLevels Read
```


The property is read-only.

### Update {#Update}
```
public static final PropertyAccessLevels Update
```


It is possible to update the property using the  MetadataPackage.UpdateProperties  method.

### Remove {#Remove}
```
public static final PropertyAccessLevels Remove
```


The property can be removed through the  MetadataPackage.RemoveProperties  method.

### Add {#Add}
```
public static final PropertyAccessLevels Add
```


It is possible to update the property using the  MetadataPackage.AddProperties  method.

### Full {#Full}
```
public static final PropertyAccessLevels Full
```


Grants full access to the property.

### AddOrUpdate {#AddOrUpdate}
```
public static final PropertyAccessLevels AddOrUpdate
```


It is allowed to add and update the property. All other operations are restricted.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static PropertyAccessLevels getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[PropertyAccessLevels](../../com.groupdocs.metadata.core/propertyaccesslevels)
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
