---
title: TiffRational
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a rational number.
type: docs
weight: 248
url: /nodejs-java/com.groupdocs.metadata.core/tiffrational/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class TiffRational implements System.IEquatable<TiffRational>
```

Represents a rational number.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffRational(long numerator, long denominator)](#TiffRational-long-long-) | Initializes a new instance of the  TiffRational  class. |
## Methods

| Method | Description |
| --- | --- |
| [getNumerator()](#getNumerator--) | Gets the numerator. |
| [getDenominator()](#getDenominator--) | Gets the denominator. |
| [getValue()](#getValue--) | Gets the rational value. |
| [equals(TiffRational rational, TiffRational other)](#equals-com.groupdocs.metadata.core.TiffRational-com.groupdocs.metadata.core.TiffRational-) | Compares a pair of  TiffRational  numbers. |
| [equals(TiffRational other)](#equals-com.groupdocs.metadata.core.TiffRational-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether the current object is equal to another object of the same type. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [op_Equality(TiffRational left, TiffRational right)](#op-Equality-com.groupdocs.metadata.core.TiffRational-com.groupdocs.metadata.core.TiffRational-) | Indicates whether two objects of the same type are equal. |
| [op_Inequality(TiffRational left, TiffRational right)](#op-Inequality-com.groupdocs.metadata.core.TiffRational-com.groupdocs.metadata.core.TiffRational-) | Indicates whether two objects of the same type are not equal. |
| [toString()](#toString--) | Returns a  string  that represents this instance. |
### TiffRational(long numerator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long numerator, long denominator)
```


Initializes a new instance of the  TiffRational  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | long | The numerator. |
| denominator | long | The denominator. |

### getNumerator() {#getNumerator--}
```
public final long getNumerator()
```


Gets the numerator.

**Returns:**
long - The numerator.
### getDenominator() {#getDenominator--}
```
public final long getDenominator()
```


Gets the denominator.

**Returns:**
long - The denominator.
### getValue() {#getValue--}
```
public final double getValue()
```


Gets the rational value.

**Returns:**
double - The rational value.
### equals(TiffRational rational, TiffRational other) {#equals-com.groupdocs.metadata.core.TiffRational-com.groupdocs.metadata.core.TiffRational-}
```
public static boolean equals(TiffRational rational, TiffRational other)
```


Compares a pair of  TiffRational  numbers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rational | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | A rational number. |
| other | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | Another rational number. |

**Returns:**
boolean -  true  if the objects are equal; otherwise,  false .
### equals(TiffRational other) {#equals-com.groupdocs.metadata.core.TiffRational-}
```
public final boolean equals(TiffRational other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | An object to compare with this object. |

**Returns:**
boolean -  true  if the current object is equal to the  other  parameter; otherwise,  false .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An object to compare with this object. |

**Returns:**
boolean -  true  if the current object is equal to the  obj  parameter; otherwise,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### op_Equality(TiffRational left, TiffRational right) {#op-Equality-com.groupdocs.metadata.core.TiffRational-com.groupdocs.metadata.core.TiffRational-}
```
public static boolean op_Equality(TiffRational left, TiffRational right)
```


Indicates whether two objects of the same type are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The left object. |
| right | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The rigt object. |

**Returns:**
boolean - True if the objects are equal; otherwise, false.
### op_Inequality(TiffRational left, TiffRational right) {#op-Inequality-com.groupdocs.metadata.core.TiffRational-com.groupdocs.metadata.core.TiffRational-}
```
public static boolean op_Inequality(TiffRational left, TiffRational right)
```


Indicates whether two objects of the same type are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The left object. |
| right | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The right object. |

**Returns:**
boolean - True if the objects are not equal; otherwise, false.
### toString() {#toString--}
```
public String toString()
```


Returns a  string  that represents this instance.

**Returns:**
java.lang.String - A  string  that represents this instance.
