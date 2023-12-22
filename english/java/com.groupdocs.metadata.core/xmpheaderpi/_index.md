---
title: XmpHeaderPI
second_title: GroupDocs.Metadata for Java API Reference
description: Represents XMP header processing instruction.
type: docs
weight: 309
url: /java/com.groupdocs.metadata.core/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmpType](../../com.groupdocs.metadata.core/ixmptype)
```
public final class XmpHeaderPI implements IXmpType
```

Represents XMP header processing instruction.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpHeaderPI()](#XmpHeaderPI--) | Initializes a new instance of the  XmpHeaderPI  class. |
## Methods

| Method | Description |
| --- | --- |
| [getGuid()](#getGuid--) | Represents Header GUID. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Converts XMP value to the xml representation. |
### XmpHeaderPI() {#XmpHeaderPI--}
```
public XmpHeaderPI()
```


Initializes a new instance of the  XmpHeaderPI  class.

### getGuid() {#getGuid--}
```
public final String getGuid()
```


Represents Header GUID.

**Returns:**
java.lang.String - The unique identifier.

--------------------

The text of the header PI contains a GUID, making it unlikely to appear by accident in the data stream.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Converts XMP value to the xml representation.

**Returns:**
java.lang.String - Returns  string  representation of XMP value.
