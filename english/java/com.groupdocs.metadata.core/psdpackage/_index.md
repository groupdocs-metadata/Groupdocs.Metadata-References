---
title: PsdPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents native Photoshop metadata.
type: docs
weight: 210
url: /java/com.groupdocs.metadata.core/psdpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class PsdPackage extends CustomPackage
```

Represents native Photoshop metadata.

**Learn more**

 *  [Working with metadata in PSD images][]


[Working with metadata in PSD images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PSD+images
## Methods

| Method | Description |
| --- | --- |
| [getChannelCount()](#getChannelCount--) | Gets the number of channels. |
| [getColorMode()](#getColorMode--) | Gets the psd color mode. |
| [getCompression()](#getCompression--) | Gets the compression method used for image data. |
| [getPhotoshopVersion()](#getPhotoshopVersion--) | Gets the Photoshop version. |
| [getHeight()](#getHeight--) | Gets the height of the image. |
| [getWidth()](#getWidth--) | Gets PSD width of the image. |
| [getLayers()](#getLayers--) | Gets the Photoshop layers. |
### getChannelCount() {#getChannelCount--}
```
public final int getChannelCount()
```


Gets the number of channels.

**Returns:**
int - The number of channels.
### getColorMode() {#getColorMode--}
```
public final PsdColorMode getColorMode()
```


Gets the psd color mode.

**Returns:**
[PsdColorMode](../../com.groupdocs.metadata.core/psdcolormode) - The color mode.
### getCompression() {#getCompression--}
```
public final PsdCompressionMethod getCompression()
```


Gets the compression method used for image data.

**Returns:**
[PsdCompressionMethod](../../com.groupdocs.metadata.core/psdcompressionmethod) - The compression method.
### getPhotoshopVersion() {#getPhotoshopVersion--}
```
public final int getPhotoshopVersion()
```


Gets the Photoshop version.

**Returns:**
int - The photoshop version.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the image.

**Returns:**
int - The height of the image.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets PSD width of the image.

**Returns:**
int - The width of the image.
### getLayers() {#getLayers--}
```
public final PsdLayer[] getLayers()
```


Gets the Photoshop layers.

**Returns:**
com.groupdocs.metadata.core.PsdLayer[] - The Photoshop layers.
