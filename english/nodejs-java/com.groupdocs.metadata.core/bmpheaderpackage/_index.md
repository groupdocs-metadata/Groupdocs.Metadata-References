---
title: BmpHeaderPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents BMP header info.
type: docs
weight: 27
url: /nodejs-java/com.groupdocs.metadata.core/bmpheaderpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class BmpHeaderPackage extends CustomPackage
```

Represents BMP header info.

**Learn more**

 *  [Working with BMP metadata][]


[Working with BMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+BMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Gets the size of the header in bytes. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel value. |
| [getImageSize()](#getImageSize--) | Gets the bitmap raw data size in bytes. |
| [getPlanes()](#getPlanes--) | Gets the number of planes. |
| [getColorsImportant()](#getColorsImportant--) | Gets the number of important palette colors. |
### getHeaderSize() {#getHeaderSize--}
```
public final long getHeaderSize()
```


Gets the size of the header in bytes.

**Returns:**
long - The size of the header in bytes.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


Gets the bits per pixel value.

**Returns:**
int - The bits per pixel value.
### getImageSize() {#getImageSize--}
```
public final long getImageSize()
```


Gets the bitmap raw data size in bytes.

**Returns:**
long - The bitmap raw data size in bytes.
### getPlanes() {#getPlanes--}
```
public final int getPlanes()
```


Gets the number of planes.

**Returns:**
int - The number of planes.
### getColorsImportant() {#getColorsImportant--}
```
public final long getColorsImportant()
```


Gets the number of important palette colors.

**Returns:**
long - The number of important palette colors.
