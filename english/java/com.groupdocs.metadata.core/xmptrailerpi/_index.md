---
title: XmpTrailerPI
second_title: GroupDocs.Signature for Java API Reference
description: Represents XMP trailer processing instruction.
type: docs
weight: 337
url: /java/com.groupdocs.metadata.core/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmpType](../../com.groupdocs.metadata.core/ixmptype)
```
public final class XmpTrailerPI implements IXmpType
```

Represents XMP trailer processing instruction.

--------------------

The end="w" or end="r" portion shall be used by packet scanning processors to determine whether the XMP may be modified in-place.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpTrailerPI(boolean isWritable)](#XmpTrailerPI-boolean-) | Initializes a new instance of the  XmpTrailerPI  class. |
| [XmpTrailerPI()](#XmpTrailerPI--) | Initializes a new instance of the  XmpTrailerPI  class. |
## Methods

| Method | Description |
| --- | --- |
| [isWritable()](#isWritable--) | Indicates whether form may be modified in-place. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Converts XMP value to the xml representation. |
### XmpTrailerPI(boolean isWritable) {#XmpTrailerPI-boolean-}
```
public XmpTrailerPI(boolean isWritable)
```


Initializes a new instance of the  XmpTrailerPI  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isWritable | boolean | Indicates whether trailer is writable. |

### XmpTrailerPI() {#XmpTrailerPI--}
```
public XmpTrailerPI()
```


Initializes a new instance of the  XmpTrailerPI  class.

### isWritable() {#isWritable--}
```
public final boolean isWritable()
```


Indicates whether form may be modified in-place.

**Returns:**
boolean -  true  if XMP packet is writable; otherwise,  false .
### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Converts XMP value to the xml representation.

**Returns:**
java.lang.String - Returns  string  representation of XMP value.
