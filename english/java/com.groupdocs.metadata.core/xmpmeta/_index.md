---
title: XmpMeta
second_title: GroupDocs.Metadata for Java API Reference
description: Represents xmpmeta.
type: docs
weight: 278
url: /java/com.groupdocs.metadata.core/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpElementBase](../../com.groupdocs.metadata.core/xmpelementbase)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmpType](../../com.groupdocs.metadata.core/ixmptype)
```
public final class XmpMeta extends XmpElementBase implements IXmpType
```

Represents xmpmeta. Optional. The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpMeta()](#XmpMeta--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Gets Adobe XMP toolkit version. |
| [setAttribute(String attribute, String value)](#setAttribute-java.lang.String-java.lang.String-) | Adds an attribute. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Converts XMP value to the xml representation. |
### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public final String getAdobeXmpToolkit()
```


Gets Adobe XMP toolkit version.

**Returns:**
java.lang.String - The toolkit version.
### setAttribute(String attribute, String value) {#setAttribute-java.lang.String-java.lang.String-}
```
public void setAttribute(String attribute, String value)
```


Adds an attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | The attribute. |
| value | java.lang.String | The value. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Converts XMP value to the xml representation.

**Returns:**
java.lang.String - Returns  string  representation of XMP value.
