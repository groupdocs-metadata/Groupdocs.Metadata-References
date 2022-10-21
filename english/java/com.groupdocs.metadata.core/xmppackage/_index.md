---
title: XmpPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base abstraction for XMP package.
type: docs
weight: 281
url: /java/com.groupdocs.metadata.core/xmppackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer)
```
public class XmpPackage extends XmpMetadataContainer
```

Represents base abstraction for XMP package.

**Learn more**

 *  [Working with XMP metadata][]

This example demonstrates how to add a custom XMP package to a file of any supported format.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputJpeg)) {
>      IXmp root = (IXmp) metadata.getRootPackage();
>      XmpPacketWrapper packet = new XmpPacketWrapper();
>      XmpPackage custom = new XmpPackage("gd", "https://groupdocs.com");
>      custom.set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
>      custom.set("gd:CreationDate", new Date());
>      custom.set("gd:Company", XmpArray.from(new String[]{"Aspose", "GroupDocs"}, XmpArrayType.Ordered));
>      packet.addPackage(custom);
>      root.setXmpPackage(packet);
>      metadata.save(Constants.OutputJpeg);
>  }
>  
> ```
> ```


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Initializes a new instance of the  XmpPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPrefix()](#getPrefix--) | Gets the xmlns prefix. |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the namespace URI. |
| [getXmlNamespace()](#getXmlNamespace--) | Gets the XML namespace. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
| [set(String name, int value)](#set-java.lang.String-int-) | Sets integer property. |
| [set(String name, boolean value)](#set-java.lang.String-boolean-) | Sets boolean property. |
| [set(String name, Date value)](#set-java.lang.String-java.util.Date-) | Sets  DateTime  property. |
| [set(String name, double value)](#set-java.lang.String-double-) | Sets double property. |
| [remove(String name)](#remove-java.lang.String-) | Removes the property with the specified name. |
| [clear()](#clear--) | Removes all XMP properties. |
| [set(String name, XmpValueBase value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpValueBase-) | Sets the value inherited from  XmpValueBase  . |
| [set(String name, XmpComplexType value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpComplexType-) | Sets the value inherited from  XmpComplexType  . |
| [set(String name, XmpArray value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-) | Sets the value inherited from  XmpArray  . |
| [getXmpRepresentation()](#getXmpRepresentation--) | Converts the XMP value to the XML representation. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Initializes a new instance of the  XmpPackage  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | XMP prefix, for example dc:title. |
| namespaceUri | java.lang.String | Namespace uri. |

### getPrefix() {#getPrefix--}
```
public final String getPrefix()
```


Gets the xmlns prefix.

**Returns:**
java.lang.String - The prefix.
### getNamespaceUri() {#getNamespaceUri--}
```
public final String getNamespaceUri()
```


Gets the namespace URI.

**Returns:**
java.lang.String - The namespace URI.
### getXmlNamespace() {#getXmlNamespace--}
```
public final String getXmlNamespace()
```


Gets the XML namespace.

**Returns:**
java.lang.String - The XML namespace.
### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public void set(String name, String value)
```


Sets string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | java.lang.String | XMP metadata property value. |

### set(String name, int value) {#set-java.lang.String-int-}
```
public final void set(String name, int value)
```


Sets integer property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | int | XMP metadata property value. |

### set(String name, boolean value) {#set-java.lang.String-boolean-}
```
public final void set(String name, boolean value)
```


Sets boolean property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | boolean | XMP metadata property value. |

### set(String name, Date value) {#set-java.lang.String-java.util.Date-}
```
public final void set(String name, Date value)
```


Sets  DateTime  property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | java.util.Date | XMP metadata property value. |

### set(String name, double value) {#set-java.lang.String-double-}
```
public final void set(String name, double value)
```


Sets double property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | double | XMP metadata property value. |

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Removes the property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |

**Returns:**
boolean - True if the specified metadata property is found and removed; otherwise, false.
### clear() {#clear--}
```
public final void clear()
```


Removes all XMP properties.

### set(String name, XmpValueBase value) {#set-java.lang.String-com.groupdocs.metadata.core.XmpValueBase-}
```
public final void set(String name, XmpValueBase value)
```


Sets the value inherited from  XmpValueBase  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | [XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase) | XMP metadata property value. |

### set(String name, XmpComplexType value) {#set-java.lang.String-com.groupdocs.metadata.core.XmpComplexType-}
```
public void set(String name, XmpComplexType value)
```


Sets the value inherited from  XmpComplexType  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | [XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype) | XMP metadata property value. |

### set(String name, XmpArray value) {#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-}
```
public void set(String name, XmpArray value)
```


Sets the value inherited from  XmpArray  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | [XmpArray](../../com.groupdocs.metadata.core/xmparray) | XMP metadata property value. |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Converts the XMP value to the XML representation.

**Returns:**
java.lang.String - A  string  representation of the XMP value.
