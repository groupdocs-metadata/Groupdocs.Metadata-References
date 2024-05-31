---
title: XmpComplexType
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base abstraction for XMP Complex value type.
type: docs
weight: 308
url: /java/com.groupdocs.metadata.core/xmpcomplextype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer)
```
public class XmpComplexType extends XmpMetadataContainer
```

Represents base abstraction for XMP Complex value type.

--------------------

See more: XMP Specification Part 2, Chapter 1.2.2
## Methods

| Method | Description |
| --- | --- |
| [getPrefixes()](#getPrefixes--) | Gets the namespace prefixes that are used in the  XmpComplexType  instance. |
| [getNamespaceUris()](#getNamespaceUris--) | Gets the namespace URIs that are used in the  XmpComplexType  instance. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
| [toString()](#toString--) | Returns a  String  that represents this instance. |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Gets the namespace URI associated with the specified prefix. |
### getPrefixes() {#getPrefixes--}
```
public final String[] getPrefixes()
```


Gets the namespace prefixes that are used in the  XmpComplexType  instance.

**Returns:**
java.lang.String[] - The namespace prefixes.
### getNamespaceUris() {#getNamespaceUris--}
```
public final String[] getNamespaceUris()
```


Gets the namespace URIs that are used in the  XmpComplexType  instance.

**Returns:**
java.lang.String[] - The namespace URIs.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
### toString() {#toString--}
```
public String toString()
```


Returns a  String  that represents this instance.

**Returns:**
java.lang.String - A  String  that represents this instance.
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public final String getNamespaceUri(String prefix)
```


Gets the namespace URI associated with the specified prefix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix of the namespace to get. |

**Returns:**
java.lang.String - The associated namespace URI if the prefix is registered; otherwise, null.
