---
title: TiffSRational
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents signed rational number.
type: docs
weight: 253
url: /nodejs-java/com.groupdocs.metadata.core/tiffsrational/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class TiffSRational implements System.IEquatable<TiffSRational>
```

Represents signed rational number.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffSRational(int numerator, int denominator)](#TiffSRational-int-int-) | Initializes a new instance of the  TiffSRational  class. |
## Methods

| Method | Description |
| --- | --- |
| [getNumerator()](#getNumerator--) | Gets numerator. |
| [getDenominator()](#getDenominator--) | Gets denominator. |
| [getValue()](#getValue--) | Gets actual value represented as double. |
| [equals(TiffSRational rational, TiffSRational other)](#equals-com.groupdocs.metadata.core.TiffSRational-com.groupdocs.metadata.core.TiffSRational-) | Compares pair of  TiffSRational . |
| [equals(TiffSRational other)](#equals-com.groupdocs.metadata.core.TiffSRational-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Indicates whether the current object is equal to another object of the same type. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [op_Equality(TiffSRational left, TiffSRational right)](#op-Equality-com.groupdocs.metadata.core.TiffSRational-com.groupdocs.metadata.core.TiffSRational-) | Indicates whether two objects of the same type are equal. |
| [op_Inequality(TiffSRational left, TiffSRational right)](#op-Inequality-com.groupdocs.metadata.core.TiffSRational-com.groupdocs.metadata.core.TiffSRational-) | Indicates whether two objects of the same type are not equal. |
| [toString()](#toString--) | Returns a  System.String  that represents this instance. |
### TiffSRational(int numerator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int numerator, int denominator)
```


Initializes a new instance of the  TiffSRational  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | int | The numerator. |
| denominator | int | The denominator. |

### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Gets numerator.

**Returns:**
int - The numerator.
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Gets denominator.

**Returns:**
int - The denominator.
### getValue() {#getValue--}
```
public final double getValue()
```


Gets actual value represented as double.

**Returns:**
double - Double value.
### equals(TiffSRational rational, TiffSRational other) {#equals-com.groupdocs.metadata.core.TiffSRational-com.groupdocs.metadata.core.TiffSRational-}
```
public static boolean equals(TiffSRational rational, TiffSRational other)
```


Compares pair of  TiffSRational .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rational | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | Comparing item. |
| other | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | Other item. |

**Returns:**
boolean -  true  if objects are equal; otherwise  false .
### equals(TiffSRational other) {#equals-com.groupdocs.metadata.core.TiffSRational-}
```
public final boolean equals(TiffSRational other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | An object to compare with this object. |

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
### op_Equality(TiffSRational left, TiffSRational right) {#op-Equality-com.groupdocs.metadata.core.TiffSRational-com.groupdocs.metadata.core.TiffSRational-}
```
public static boolean op_Equality(TiffSRational left, TiffSRational right)
```


Indicates whether two objects of the same type are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | The left object. |
| right | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | The rigt object. |

**Returns:**
boolean - True if the objects are equal; otherwise, false.
### op_Inequality(TiffSRational left, TiffSRational right) {#op-Inequality-com.groupdocs.metadata.core.TiffSRational-com.groupdocs.metadata.core.TiffSRational-}
```
public static boolean op_Inequality(TiffSRational left, TiffSRational right)
```


Indicates whether two objects of the same type are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | The left object. |
| right | [TiffSRational](../../com.groupdocs.metadata.core/tiffsrational) | The rigt object. |

**Returns:**
boolean - True if the objects are not equal; otherwise, false.
### toString() {#toString--}
```
public String toString()
```


Returns a  System.String  that represents this instance.

**Returns:**
java.lang.String - A  System.String  that represents this instance.
