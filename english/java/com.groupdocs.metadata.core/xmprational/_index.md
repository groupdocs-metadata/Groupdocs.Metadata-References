---
title: XmpRational
second_title: GroupDocs.Signature for Java API Reference
description: Represents XMP XmpRational.
type: docs
weight: 325
url: /java/com.groupdocs.metadata.core/xmprational/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase)
```
public final class XmpRational extends XmpValueBase
```

Represents XMP XmpRational.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpRational(long numerator, long denominator)](#XmpRational-long-long-) | Initializes a new instance of the  XmpRational  class. |
| [XmpRational(String value)](#XmpRational-java.lang.String-) | Initializes a new instance of the  XmpBoolean  class. |
## Methods

| Method | Description |
| --- | --- |
| [getNumerator()](#getNumerator--) | Gets numerator. |
| [getDenominator()](#getDenominator--) | Gets denominator |
| [getDoubleValue()](#getDoubleValue--) | Gets value of rational type presented in double format. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### XmpRational(long numerator, long denominator) {#XmpRational-long-long-}
```
public XmpRational(long numerator, long denominator)
```


Initializes a new instance of the  XmpRational  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | long | The numerator. |
| denominator | long | The denominator. |

### XmpRational(String value) {#XmpRational-java.lang.String-}
```
public XmpRational(String value)
```


Initializes a new instance of the  XmpBoolean  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

### getNumerator() {#getNumerator--}
```
public final long getNumerator()
```


Gets numerator.

**Returns:**
long - The numerator.
### getDenominator() {#getDenominator--}
```
public final long getDenominator()
```


Gets denominator

**Returns:**
long - The denominator.
### getDoubleValue() {#getDoubleValue--}
```
public final double getDoubleValue()
```


Gets value of rational type presented in double format.

**Returns:**
double - Double value.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
