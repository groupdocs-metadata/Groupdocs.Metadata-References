---
title: ImageResourceBlock
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: 
type: docs
weight: 125
url: /nodejs-java/com.groupdocs.metadata.core/imageresourceblock/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class ImageResourceBlock extends CustomPackage
```

Represents a Photoshop Image Resource block. 

 Image resource blocks are the basic building unit of several file formats, including Photoshop's native file format, JPEG, and TIFF. Image resources are used to store non-pixel data associated with images, such as pen tool paths.

**Learn more**

 *  [Working with metadata in PSD images][]


[Working with metadata in PSD images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PSD+images
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Gets the image resource block signature. |
| [getID()](#getID--) | Gets the unique identifier for the resource. |
| [getName()](#getName--) | Gets the image resource block name. |
| [getData()](#getData--) | Gets the resource data. |
### getSignature() {#getSignature--}
```
public final String getSignature()
```


Gets the image resource block signature.

**Returns:**
java.lang.String - The image resource block signature
### getID() {#getID--}
```
public final ImageResourceID getID()
```


Gets the unique identifier for the resource.

**Returns:**
[ImageResourceID](../../com.groupdocs.metadata.core/imageresourceid) - The identifier.
### getName() {#getName--}
```
public final String getName()
```


Gets the image resource block name.

**Returns:**
java.lang.String - The image resource block name.
### getData() {#getData--}
```
public final byte[] getData()
```


Gets the resource data.

**Returns:**
byte[] - The resource data.
