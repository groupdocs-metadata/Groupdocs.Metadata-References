---
title: XmpPacketWrapper
second_title: GroupDocs.Metadata for Java API Reference
description: Contains serialized XMP package including header and trailer.
type: docs
weight: 282
url: /java/com.groupdocs.metadata.core/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmpType](../../com.groupdocs.metadata.core/ixmptype)
```
public class XmpPacketWrapper extends MetadataPackage implements IXmpType
```

Contains serialized XMP package including header and trailer. A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPI header, XmpTrailerPI trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.groupdocs.metadata.core.XmpHeaderPI-com.groupdocs.metadata.core.XmpTrailerPI-com.groupdocs.metadata.core.XmpMeta-) | Initializes a new instance of the  XmpPacketWrapper  class. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initializes a new instance of the  XmpPacketWrapper  class. |
## Methods

| Method | Description |
| --- | --- |
| [getHeaderPI()](#getHeaderPI--) | Gets the header processing instruction. |
| [setHeaderPI(XmpHeaderPI value)](#setHeaderPI-com.groupdocs.metadata.core.XmpHeaderPI-) | Sets the header processing instruction. |
| [getMeta()](#getMeta--) | Gets the XMP meta. |
| [setMeta(XmpMeta value)](#setMeta-com.groupdocs.metadata.core.XmpMeta-) | Sets the XMP meta. |
| [getTrailerPI()](#getTrailerPI--) | Gets the trailer processing instruction. |
| [setTrailerPI(XmpTrailerPI value)](#setTrailerPI-com.groupdocs.metadata.core.XmpTrailerPI-) | Sets the trailer processing instruction. |
| [getPackages()](#getPackages--) | Gets array of  XmpPackage  inside XMP. |
| [getPackageCount()](#getPackageCount--) | Gets the number of packages inside the XMP structure. |
| [getSchemes()](#getSchemes--) | Provides access to known XMP schemas. |
| [addPackage(XmpPackage package_)](#addPackage-com.groupdocs.metadata.core.XmpPackage-) | Adds the package. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Gets package by namespace uri. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determines whether package is exist in XMP wrapper. |
| [removePackage(XmpPackage package_)](#removePackage-com.groupdocs.metadata.core.XmpPackage-) | Removes the specified package. |
| [clearPackages()](#clearPackages--) | Removes all  XmpPackage  inside XMP. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
### XmpPacketWrapper(XmpHeaderPI header, XmpTrailerPI trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.groupdocs.metadata.core.XmpHeaderPI-com.groupdocs.metadata.core.XmpTrailerPI-com.groupdocs.metadata.core.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPI header, XmpTrailerPI trailer, XmpMeta xmpMeta)
```


Initializes a new instance of the  XmpPacketWrapper  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | [XmpHeaderPI](../../com.groupdocs.metadata.core/xmpheaderpi) | XMP header processing instruction. |
| trailer | [XmpTrailerPI](../../com.groupdocs.metadata.core/xmptrailerpi) | XMP trailer processing instruction. |
| xmpMeta | [XmpMeta](../../com.groupdocs.metadata.core/xmpmeta) | Instance of  XmpMeta . |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initializes a new instance of the  XmpPacketWrapper  class.

### getHeaderPI() {#getHeaderPI--}
```
public final XmpHeaderPI getHeaderPI()
```


Gets the header processing instruction.

**Returns:**
[XmpHeaderPI](../../com.groupdocs.metadata.core/xmpheaderpi) - The header processing instruction.
### setHeaderPI(XmpHeaderPI value) {#setHeaderPI-com.groupdocs.metadata.core.XmpHeaderPI-}
```
public final void setHeaderPI(XmpHeaderPI value)
```


Sets the header processing instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpHeaderPI](../../com.groupdocs.metadata.core/xmpheaderpi) | The header processing instruction. |

### getMeta() {#getMeta--}
```
public final XmpMeta getMeta()
```


Gets the XMP meta.

**Returns:**
[XmpMeta](../../com.groupdocs.metadata.core/xmpmeta) - The XMP meta.
### setMeta(XmpMeta value) {#setMeta-com.groupdocs.metadata.core.XmpMeta-}
```
public final void setMeta(XmpMeta value)
```


Sets the XMP meta.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpMeta](../../com.groupdocs.metadata.core/xmpmeta) | The XMP meta. |

### getTrailerPI() {#getTrailerPI--}
```
public final XmpTrailerPI getTrailerPI()
```


Gets the trailer processing instruction.

**Returns:**
[XmpTrailerPI](../../com.groupdocs.metadata.core/xmptrailerpi) - The trailer processing instruction.
### setTrailerPI(XmpTrailerPI value) {#setTrailerPI-com.groupdocs.metadata.core.XmpTrailerPI-}
```
public final void setTrailerPI(XmpTrailerPI value)
```


Sets the trailer processing instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTrailerPI](../../com.groupdocs.metadata.core/xmptrailerpi) | The trailer processing instruction. |

### getPackages() {#getPackages--}
```
public final XmpPackage[] getPackages()
```


Gets array of  XmpPackage  inside XMP.

**Returns:**
com.groupdocs.metadata.core.XmpPackage[] - XMP packages.
### getPackageCount() {#getPackageCount--}
```
public final int getPackageCount()
```


Gets the number of packages inside the XMP structure.

**Returns:**
int - The package count.
### getSchemes() {#getSchemes--}
```
public final XmpSchemes getSchemes()
```


Provides access to known XMP schemas.

**Returns:**
[XmpSchemes](../../com.groupdocs.metadata.core/xmpschemes) - XMP schemes.
### addPackage(XmpPackage package_) {#addPackage-com.groupdocs.metadata.core.XmpPackage-}
```
public final void addPackage(XmpPackage package_)
```


Adds the package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.groupdocs.metadata.core/xmppackage) |  |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public final XmpPackage getPackage(String namespaceUri)
```


Gets package by namespace uri.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | Package schema uri. |

**Returns:**
[XmpPackage](../../com.groupdocs.metadata.core/xmppackage) - Appropriate  XmpPackage  if package found by  namespaceUri ; otherwise null.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public final boolean containsPackage(String namespaceUri)
```


Determines whether package is exist in XMP wrapper.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | Package namespace URI. |

**Returns:**
boolean -  true  if package found by  namespaceUri ; otherwise  false .
### removePackage(XmpPackage package_) {#removePackage-com.groupdocs.metadata.core.XmpPackage-}
```
public final void removePackage(XmpPackage package_)
```


Removes the specified package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.groupdocs.metadata.core/xmppackage) |  |

### clearPackages() {#clearPackages--}
```
public final void clearPackages()
```


Removes all  XmpPackage  inside XMP.

### getXmpRepresentation() {#getXmpRepresentation--}
```
public final String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String -  string  contained XMP representation.
