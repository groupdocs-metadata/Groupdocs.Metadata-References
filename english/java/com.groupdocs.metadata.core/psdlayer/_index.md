---
title: PsdLayer
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a layer in a PSD file.
type: docs
weight: 208
url: /java/com.groupdocs.metadata.core/psdlayer/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class PsdLayer extends CustomPackage
```

Represents a layer in a PSD file.

**Learn more**

 *  [Working with metadata in PSD images][]


[Working with metadata in PSD images]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PSD+images
## Methods

| Method | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Gets the bits per pixel value. |
| [getChannelCount()](#getChannelCount--) | Gets the number of channels. |
| [getFlags()](#getFlags--) | Gets the layer flags. |
| [getLength()](#getLength--) | Gets the overall layer length in bytes. |
| [getOpacity()](#getOpacity--) | Gets the layer opacity. |
| [getTop()](#getTop--) | Gets the top layer position. |
| [getLeft()](#getLeft--) | Gets the left layer position. |
| [getBottom()](#getBottom--) | Gets the bottom layer position. |
| [getRight()](#getRight--) | Gets the right layer position. |
| [getHeight()](#getHeight--) | Gets the height. |
| [getWidth()](#getWidth--) | Gets the width. |
| [getName()](#getName--) | Gets the layer name. |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


Gets the bits per pixel value.

**Returns:**
int - The bits per pixel value.
### getChannelCount() {#getChannelCount--}
```
public final int getChannelCount()
```


Gets the number of channels.

**Returns:**
int - The number of channels.
### getFlags() {#getFlags--}
```
public final PsdLayerFlags getFlags()
```


Gets the layer flags.

**Returns:**
[PsdLayerFlags](../../com.groupdocs.metadata.core/psdlayerflags) - The flags.
### getLength() {#getLength--}
```
public final int getLength()
```


Gets the overall layer length in bytes.

**Returns:**
int - The overall layer length in bytes.
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Gets the layer opacity. 0 = transparent, 255 = opaque.

**Returns:**
byte - The opacity.
### getTop() {#getTop--}
```
public final int getTop()
```


Gets the top layer position.

**Returns:**
int - The top layer position.
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Gets the left layer position.

**Returns:**
int - The left layer position.
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Gets the bottom layer position.

**Returns:**
int - The bottom layer position.
### getRight() {#getRight--}
```
public final int getRight()
```


Gets the right layer position.

**Returns:**
int - The right layer position.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height.

**Returns:**
int - The height.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width.

**Returns:**
int - The width.
### getName() {#getName--}
```
public final String getName()
```


Gets the layer name.

**Returns:**
java.lang.String - The layer name.
