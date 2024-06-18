---
title: PropertyTag
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a tag used to mark metadata properties.
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.metadata.tagging/propertytag/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class PropertyTag implements System.IEquatable<PropertyTag>
```

Represents a tag used to mark metadata properties.
## Methods

| Method | Description |
| --- | --- |
| [getCategory()](#getCategory--) | Gets the tag category. |
| [equals(PropertyTag other)](#equals-com.groupdocs.metadata.tagging.PropertyTag-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified object is equal to the current object. |
| [hashCode()](#hashCode--) | Serves as the default hash function. |
| [op_Equality(PropertyTag left, PropertyTag right)](#op-Equality-com.groupdocs.metadata.tagging.PropertyTag-com.groupdocs.metadata.tagging.PropertyTag-) | Indicates whether two objects of the same type are equal. |
| [op_Inequality(PropertyTag left, PropertyTag right)](#op-Inequality-com.groupdocs.metadata.tagging.PropertyTag-com.groupdocs.metadata.tagging.PropertyTag-) | Indicates whether two objects of the same type are not equal. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### getCategory() {#getCategory--}
```
public final TagCategory getCategory()
```


Gets the tag category.

**Returns:**
[TagCategory](../../com.groupdocs.metadata.tagging/tagcategory) - The tag category.
### equals(PropertyTag other) {#equals-com.groupdocs.metadata.tagging.PropertyTag-}
```
public final boolean equals(PropertyTag other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) | An object to compare with this object. |

**Returns:**
boolean - True if the current object is equal to the  other  parameter; otherwise, false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean - True if the specified object is equal to the current object; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as the default hash function.

**Returns:**
int - A hash code for the current object.
### op_Equality(PropertyTag left, PropertyTag right) {#op-Equality-com.groupdocs.metadata.tagging.PropertyTag-com.groupdocs.metadata.tagging.PropertyTag-}
```
public static boolean op_Equality(PropertyTag left, PropertyTag right)
```


Indicates whether two objects of the same type are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) | The left object. |
| right | [PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) | The rigt object. |

**Returns:**
boolean - True if the objects are equal; otherwise, false.
### op_Inequality(PropertyTag left, PropertyTag right) {#op-Inequality-com.groupdocs.metadata.tagging.PropertyTag-com.groupdocs.metadata.tagging.PropertyTag-}
```
public static boolean op_Inequality(PropertyTag left, PropertyTag right)
```


Indicates whether two objects of the same type are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) | The left object. |
| right | [PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) | The rigt object. |

**Returns:**
boolean - True if the objects are not equal; otherwise, false.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
