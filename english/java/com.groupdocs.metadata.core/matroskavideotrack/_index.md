---
title: MatroskaVideoTrack
second_title: GroupDocs.Signature for Java API Reference
description: Represents video metadata in a Matroska video.
type: docs
weight: 157
url: /java/com.groupdocs.metadata.core/matroskavideotrack/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage), [com.groupdocs.metadata.core.MatroskaTrack](../../com.groupdocs.metadata.core/matroskatrack)
```
public class MatroskaVideoTrack extends MatroskaTrack
```

Represents video metadata in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getFlagInterlaced()](#getFlagInterlaced--) | Gets a flag to declare if the video is known to be progressive or interlaced and if applicable to declare details about the interlacement. |
| [getFieldOrder()](#getFieldOrder--) | Gets declare the field ordering of the video. |
| [getStereoMode()](#getStereoMode--) | Gets the stereo-3D video mode. |
| [getAlphaMode()](#getAlphaMode--) | Gets the alpha Video Mode. |
| [getPixelWidth()](#getPixelWidth--) | Gets the width of the encoded video frames in pixels. |
| [getPixelHeight()](#getPixelHeight--) | Gets the height of the encoded video frames in pixels. |
| [getPixelCropBottom()](#getPixelCropBottom--) | Gets the number of video pixels to remove at the bottom of the image. |
| [getPixelCropTop()](#getPixelCropTop--) | Gets the number of video pixels to remove at the top of the image. |
| [getPixelCropLeft()](#getPixelCropLeft--) | Gets the number of video pixels to remove on the left of the image. |
| [getPixelCropRight()](#getPixelCropRight--) | Gets the number of video pixels to remove on the right of the image. |
| [getDisplayWidth()](#getDisplayWidth--) | Gets the width of the video frames to display. |
| [getDisplayHeight()](#getDisplayHeight--) | Gets the height of the video frames to display. |
| [getDisplayUnit()](#getDisplayUnit--) | Gets the how  DisplayWidth and  DisplayHeight  are interpreted. |
### getFlagInterlaced() {#getFlagInterlaced--}
```
public final MatroskaVideoFlagInterlaced getFlagInterlaced()
```


Gets a flag to declare if the video is known to be progressive or interlaced and if applicable to declare details about the interlacement.

**Returns:**
[MatroskaVideoFlagInterlaced](../../com.groupdocs.metadata.core/matroskavideoflaginterlaced) - A flag to declare if the video is known to be progressive or interlaced and if applicable to declare details about the interlacement.
### getFieldOrder() {#getFieldOrder--}
```
public final MatroskaVideoFieldOrder getFieldOrder()
```


Gets declare the field ordering of the video. If FlagInterlaced is not set to 1, this Element MUST be ignored.

**Returns:**
[MatroskaVideoFieldOrder](../../com.groupdocs.metadata.core/matroskavideofieldorder) - Declare the field ordering of the video.
### getStereoMode() {#getStereoMode--}
```
public final MatroskaVideoStereoMode getStereoMode()
```


Gets the stereo-3D video mode.

**Returns:**
[MatroskaVideoStereoMode](../../com.groupdocs.metadata.core/matroskavideostereomode) - The stereo-3D video mode.
### getAlphaMode() {#getAlphaMode--}
```
public final Long getAlphaMode()
```


Gets the alpha Video Mode. Presence of this Element indicates that the BlockAdditional Element could contain Alpha data.

Value: The alpha Video Mode.

**Returns:**
java.lang.Long
### getPixelWidth() {#getPixelWidth--}
```
public final long getPixelWidth()
```


Gets the width of the encoded video frames in pixels.

**Returns:**
long - The width of the encoded video frames in pixels.
### getPixelHeight() {#getPixelHeight--}
```
public final long getPixelHeight()
```


Gets the height of the encoded video frames in pixels.

**Returns:**
long - The height of the encoded video frames in pixels.
### getPixelCropBottom() {#getPixelCropBottom--}
```
public final long getPixelCropBottom()
```


Gets the number of video pixels to remove at the bottom of the image.

**Returns:**
long - The number of video pixels to remove at the bottom of the image.
### getPixelCropTop() {#getPixelCropTop--}
```
public final long getPixelCropTop()
```


Gets the number of video pixels to remove at the top of the image.

**Returns:**
long - The number of video pixels to remove at the top of the image.
### getPixelCropLeft() {#getPixelCropLeft--}
```
public final long getPixelCropLeft()
```


Gets the number of video pixels to remove on the left of the image.

**Returns:**
long - The number of video pixels to remove on the left of the image.
### getPixelCropRight() {#getPixelCropRight--}
```
public final long getPixelCropRight()
```


Gets the number of video pixels to remove on the right of the image.

**Returns:**
long - The number of video pixels to remove on the right of the image.
### getDisplayWidth() {#getDisplayWidth--}
```
public final Long getDisplayWidth()
```


Gets the width of the video frames to display. Applies to the video frame after cropping (PixelCrop\* Elements).

**Returns:**
java.lang.Long - The width of the video frames to display.
### getDisplayHeight() {#getDisplayHeight--}
```
public final Long getDisplayHeight()
```


Gets the height of the video frames to display. Applies to the video frame after cropping (PixelCrop\* Elements).

**Returns:**
java.lang.Long - The height of the video frames to display.
### getDisplayUnit() {#getDisplayUnit--}
```
public final MatroskaVideoDisplayUnit getDisplayUnit()
```


Gets the how  DisplayWidth and  DisplayHeight  are interpreted.

**Returns:**
[MatroskaVideoDisplayUnit](../../com.groupdocs.metadata.core/matroskavideodisplayunit) - The how  DisplayWidth and  DisplayHeight  are interpreted.
