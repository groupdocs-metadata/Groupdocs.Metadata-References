---
title: NikonMakerNotePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents NIKON MakerNote metadata.
type: docs
weight: 135
url: /java/com.groupdocs.metadata.core/nikonmakernotepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ExifDictionaryBasePackage](../../com.groupdocs.metadata.core/exifdictionarybasepackage), [com.groupdocs.metadata.core.MakerNotePackage](../../com.groupdocs.metadata.core/makernotepackage)
```
public final class NikonMakerNotePackage extends MakerNotePackage
```

Represents NIKON MakerNote metadata.
## Constructors

| Constructor | Description |
| --- | --- |
| [NikonMakerNotePackage(TiffTag[] tags)](#NikonMakerNotePackage-com.groupdocs.metadata.core.TiffTag---) | Initializes a new instance of the  NikonMakerNotePackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getMakerNoteVersion()](#getMakerNoteVersion--) | Gets the MakerNote version. |
| [getIso()](#getIso--) | Gets the iso. |
| [getColorMode()](#getColorMode--) | Gets the color mode. |
| [getQuality()](#getQuality--) | Gets the quality string. |
| [getWhiteBalance()](#getWhiteBalance--) | Gets the white balance. |
| [getSharpness()](#getSharpness--) | Gets the sharpness. |
| [getFocusMode()](#getFocusMode--) | Gets the focus mode. |
| [getFlashSetting()](#getFlashSetting--) | Gets the flash setting. |
| [getFlashType()](#getFlashType--) | Gets the type of the flash. |
### NikonMakerNotePackage(TiffTag[] tags) {#NikonMakerNotePackage-com.groupdocs.metadata.core.TiffTag---}
```
public NikonMakerNotePackage(TiffTag[] tags)
```


Initializes a new instance of the  NikonMakerNotePackage  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | [TiffTag\[\]](../../com.groupdocs.metadata.core/tifftag) | Array of TIFF tags. |

### getMakerNoteVersion() {#getMakerNoteVersion--}
```
public final byte[] getMakerNoteVersion()
```


Gets the MakerNote version.

**Returns:**
byte[] - The MakerNote version.
### getIso() {#getIso--}
```
public final int[] getIso()
```


Gets the iso.

**Returns:**
int[] - The iso.
### getColorMode() {#getColorMode--}
```
public final String getColorMode()
```


Gets the color mode.

**Returns:**
java.lang.String - The color mode.
### getQuality() {#getQuality--}
```
public final String getQuality()
```


Gets the quality string.

**Returns:**
java.lang.String - The quality.
### getWhiteBalance() {#getWhiteBalance--}
```
public final String getWhiteBalance()
```


Gets the white balance.

**Returns:**
java.lang.String - The white balance.
### getSharpness() {#getSharpness--}
```
public final String getSharpness()
```


Gets the sharpness.

**Returns:**
java.lang.String - The sharpness.
### getFocusMode() {#getFocusMode--}
```
public final String getFocusMode()
```


Gets the focus mode.

**Returns:**
java.lang.String - The focus mode.
### getFlashSetting() {#getFlashSetting--}
```
public final String getFlashSetting()
```


Gets the flash setting.

**Returns:**
java.lang.String - The flash setting.
### getFlashType() {#getFlashType--}
```
public final String getFlashType()
```


Gets the type of the flash.

**Returns:**
java.lang.String - The type of the flash.
