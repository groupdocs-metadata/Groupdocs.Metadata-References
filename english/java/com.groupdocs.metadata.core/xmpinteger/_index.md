---
title: XmpInteger
second_title: GroupDocs.Metadata for Java API Reference
description: Represents XMP Integer basic type.
type: docs
weight: 310
url: /java/com.groupdocs.metadata.core/xmpinteger/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase)
```
public final class XmpInteger extends XmpValueBase
```

Represents XMP Integer basic type.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpInteger(long value)](#XmpInteger-long-) | Initializes a new instance of the  XmpInteger  class. |
| [XmpInteger(int value)](#XmpInteger-int-) | Initializes a new instance of the  XmpInteger  class. |
| [XmpInteger(String value)](#XmpInteger-java.lang.String-) | Initializes a new instance of the  XmpInteger  class. |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets the value. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### XmpInteger(long value) {#XmpInteger-long-}
```
public XmpInteger(long value)
```


Initializes a new instance of the  XmpInteger  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The value. |

### XmpInteger(int value) {#XmpInteger-int-}
```
public XmpInteger(int value)
```


Initializes a new instance of the  XmpInteger  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value. |

### XmpInteger(String value) {#XmpInteger-java.lang.String-}
```
public XmpInteger(String value)
```


Initializes a new instance of the  XmpInteger  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value contained integer. |

### getValue() {#getValue--}
```
public final long getValue()
```


Gets the value.

**Returns:**
long - Integer value.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
