---
title: XmpGuid
second_title: GroupDocs.Metadata for Java API Reference
description: Represents XMP global unique identifier.
type: docs
weight: 269
url: /java/com.groupdocs.metadata.core/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase)
```
public final class XmpGuid extends XmpValueBase
```

Represents XMP global unique identifier.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | Initializes a new instance of the  XmpGuid  class. |
| [XmpGuid(UUID value)](#XmpGuid-java.util.UUID-) | Initializes a new instance of the  XmpGuid  class. |
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Gets the value. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


Initializes a new instance of the  XmpGuid  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

### XmpGuid(UUID value) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID value)
```


Initializes a new instance of the  XmpGuid  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID | The unique identifier. |

### getValue() {#getValue--}
```
public final UUID getValue()
```


Gets the value.

**Returns:**
java.util.UUID - The value.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
