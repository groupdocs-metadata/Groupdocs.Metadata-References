---
title: MpegAudioPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents MPEG audio metadata.
type: docs
weight: 165
url: /java/com.groupdocs.metadata.core/mpegaudiopackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class MpegAudioPackage extends CustomPackage
```

Represents MPEG audio metadata.

This example demonstrates how to read MPEG audio metadata from an MP3 file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.MP3WithID3V2)) {
>      MP3RootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getMpegAudioPackage().getBitrate());
>      System.out.println(root.getMpegAudioPackage().getChannelMode());
>      System.out.println(root.getMpegAudioPackage().getEmphasis());
>      System.out.println(root.getMpegAudioPackage().getFrequency());
>      System.out.println(root.getMpegAudioPackage().getHeaderPosition());
>      System.out.println(root.getMpegAudioPackage().getLayer());
>      // ...
>  }
>  
> ```
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MpegAudioPackage()](#MpegAudioPackage--) | Initializes a new instance of the  MpegAudioPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getMpegAudioVersion()](#getMpegAudioVersion--) | Gets the MPEG audio version. |
| [getLayer()](#getLayer--) | Gets the layer description. |
| [isProtected()](#isProtected--) | Gets  true  if protected. |
| [getHeaderPosition()](#getHeaderPosition--) | Gets the header offset. |
| [getBitrate()](#getBitrate--) | Gets the bitrate. |
| [getFrequency()](#getFrequency--) | Gets the frequency. |
| [getPaddingBit()](#getPaddingBit--) | Gets the padding bit. |
| [getPrivateBit()](#getPrivateBit--) | Gets a value indicating whether [private bit]. |
| [getChannelMode()](#getChannelMode--) | Gets the channel mode. |
| [getCopyright()](#getCopyright--) | Gets the copyright bit. |
| [isOriginal()](#isOriginal--) | Gets the original bit. |
| [getEmphasis()](#getEmphasis--) | Gets the emphasis. |
| [getModeExtensionBits()](#getModeExtensionBits--) | Gets the mode extension bits. |
### MpegAudioPackage() {#MpegAudioPackage--}
```
public MpegAudioPackage()
```


Initializes a new instance of the  MpegAudioPackage  class.

### getMpegAudioVersion() {#getMpegAudioVersion--}
```
public final MpegAudioVersion getMpegAudioVersion()
```


Gets the MPEG audio version. Can be MPEG-1, MPEG-2 etc.

**Returns:**
[MpegAudioVersion](../../com.groupdocs.metadata.core/mpegaudioversion) - The MPEG audio version.
### getLayer() {#getLayer--}
```
public final int getLayer()
```


Gets the layer description. For an MP3 audio it is '3'.

**Returns:**
int - The layer description.
### isProtected() {#isProtected--}
```
public final boolean isProtected()
```


Gets  true  if protected.

**Returns:**
boolean -  true  if is protected; otherwise,  false .
### getHeaderPosition() {#getHeaderPosition--}
```
public final long getHeaderPosition()
```


Gets the header offset.

**Returns:**
long - The header offset.
### getBitrate() {#getBitrate--}
```
public final int getBitrate()
```


Gets the bitrate.

**Returns:**
int - The bitrate.
### getFrequency() {#getFrequency--}
```
public final int getFrequency()
```


Gets the frequency.

**Returns:**
int - The frequency.
### getPaddingBit() {#getPaddingBit--}
```
public final int getPaddingBit()
```


Gets the padding bit.

**Returns:**
int - The padding bit.
### getPrivateBit() {#getPrivateBit--}
```
public final boolean getPrivateBit()
```


Gets a value indicating whether [private bit].

**Returns:**
boolean -  true  if [private bit]; otherwise,  false .
### getChannelMode() {#getChannelMode--}
```
public final MpegChannelMode getChannelMode()
```


Gets the channel mode.

**Returns:**
[MpegChannelMode](../../com.groupdocs.metadata.core/mpegchannelmode) - The channel mode.
### getCopyright() {#getCopyright--}
```
public final boolean getCopyright()
```


Gets the copyright bit.

**Returns:**
boolean -  true  if copyright; otherwise,  false .
### isOriginal() {#isOriginal--}
```
public final boolean isOriginal()
```


Gets the original bit.

**Returns:**
boolean -  true  if audio is original; otherwise,  false .
### getEmphasis() {#getEmphasis--}
```
public final MpegEmphasis getEmphasis()
```


Gets the emphasis.

**Returns:**
[MpegEmphasis](../../com.groupdocs.metadata.core/mpegemphasis) - The emphasis.
### getModeExtensionBits() {#getModeExtensionBits--}
```
public final int getModeExtensionBits()
```


Gets the mode extension bits.

**Returns:**
int - The mode extension bits.
