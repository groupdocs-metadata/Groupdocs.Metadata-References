---
title: MP3RootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package allowing working with metadata in an MP3 audio.
type: docs
weight: 144
url: /java/com.groupdocs.metadata.core/mp3rootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class MP3RootPackage extends RootMetadataPackage implements IXmp
```

Represents the root package allowing working with metadata in an MP3 audio.

**Learn more**

 *  [Working with MP3 metadata][]
 *  [Working with XMP metadata][]


[Working with MP3 metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+MP3+metadata
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getMpegAudioPackage()](#getMpegAudioPackage--) | Gets the MPEG audio metadata package. |
| [getID3V1()](#getID3V1--) | Gets the ID3v1 metadata tag. |
| [setID3V1(ID3V1Tag value)](#setID3V1-com.groupdocs.metadata.core.ID3V1Tag-) | Sets the ID3v1 metadata tag. |
| [getID3V2()](#getID3V2--) | Gets the ID3v2 metadata tag. |
| [setID3V2(ID3V2Tag value)](#setID3V2-com.groupdocs.metadata.core.ID3V2Tag-) | Sets the ID3v2 metadata tag. |
| [getLyrics3V2()](#getLyrics3V2--) | Gets the Lyrics3v2 metadata tag. |
| [setLyrics3V2(LyricsTag value)](#setLyrics3V2-com.groupdocs.metadata.core.LyricsTag-) | Sets the Lyrics3v2 metadata tag. |
| [getApeV2()](#getApeV2--) | Gets the APE v2 metadata. |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [removeApeV2()](#removeApeV2--) | Removes the APEv2 audio tag. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
### getMpegAudioPackage() {#getMpegAudioPackage--}
```
public final MpegAudioPackage getMpegAudioPackage()
```


Gets the MPEG audio metadata package.

**Returns:**
[MpegAudioPackage](../../com.groupdocs.metadata.core/mpegaudiopackage) - The MPEG audio metadata package.
### getID3V1() {#getID3V1--}
```
public final ID3V1Tag getID3V1()
```


Gets the ID3v1 metadata tag. Please find more information at  http://id3.org/ID3v1 .

**Returns:**
[ID3V1Tag](../../com.groupdocs.metadata.core/id3v1tag) - The ID3v1 metadata tag attached to the audio file.

--------------------

The ID3(v1) tag is a small chunk of extra data at the end of an MP3 file.
### setID3V1(ID3V1Tag value) {#setID3V1-com.groupdocs.metadata.core.ID3V1Tag-}
```
public final void setID3V1(ID3V1Tag value)
```


Sets the ID3v1 metadata tag. Please find more information at  http://id3.org/ID3v1 .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ID3V1Tag](../../com.groupdocs.metadata.core/id3v1tag) | The ID3v1 metadata tag attached to the audio file.

--------------------

The ID3(v1) tag is a small chunk of extra data at the end of an MP3 file. |

### getID3V2() {#getID3V2--}
```
public final ID3V2Tag getID3V2()
```


Gets the ID3v2 metadata tag.

**Returns:**
[ID3V2Tag](../../com.groupdocs.metadata.core/id3v2tag) - The ID3v2 metadata tag attached to the audio file.
### setID3V2(ID3V2Tag value) {#setID3V2-com.groupdocs.metadata.core.ID3V2Tag-}
```
public final void setID3V2(ID3V2Tag value)
```


Sets the ID3v2 metadata tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ID3V2Tag](../../com.groupdocs.metadata.core/id3v2tag) | The ID3v2 metadata tag attached to the audio file. |

### getLyrics3V2() {#getLyrics3V2--}
```
public final LyricsTag getLyrics3V2()
```


Gets the Lyrics3v2 metadata tag.

**Returns:**
[LyricsTag](../../com.groupdocs.metadata.core/lyricstag) - The Lyrics3v2 metadata tag.
### setLyrics3V2(LyricsTag value) {#setLyrics3V2-com.groupdocs.metadata.core.LyricsTag-}
```
public final void setLyrics3V2(LyricsTag value)
```


Sets the Lyrics3v2 metadata tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [LyricsTag](../../com.groupdocs.metadata.core/lyricstag) | The Lyrics3v2 metadata tag. |

### getApeV2() {#getApeV2--}
```
public final ApePackage getApeV2()
```


Gets the APE v2 metadata.

**Returns:**
[ApePackage](../../com.groupdocs.metadata.core/apepackage) - The APE v2 metadata.
### getXmpPackage() {#getXmpPackage--}
```
public final XmpPacketWrapper getXmpPackage()
```


Gets the XMP metadata package.

**Returns:**
[XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) - The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
### setXmpPackage(XmpPacketWrapper value) {#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-}
```
public final void setXmpPackage(XmpPacketWrapper value)
```


Sets the XMP metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) | The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata |

### removeApeV2() {#removeApeV2--}
```
public final void removeApeV2()
```


Removes the APEv2 audio tag.

--------------------

This feature is not available in trial mode.

### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.
