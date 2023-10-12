---
title: XmpValueBase
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base XMP value.
type: docs
weight: 340
url: /java/com.groupdocs.metadata.core/xmpvaluebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmpType](../../com.groupdocs.metadata.core/ixmptype)
```
public abstract class XmpValueBase extends PropertyValue implements IXmpType
```

Represents base XMP value.
## Methods

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Returns a string that represents the property value. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the property value.

**Returns:**
java.lang.String - A string that represents the property value.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public abstract String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
