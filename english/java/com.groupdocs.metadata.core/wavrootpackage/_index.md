---
title: WavRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a WAV audio.
type: docs
weight: 238
url: /java/com.groupdocs.metadata.core/wavrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class WavRootPackage extends RootMetadataPackage implements IXmp
```

Represents the root package allowing working with metadata in a WAV audio.

This code sample shows how to extract technical audio information from a WAV file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputWav)) {
>      WavRootPackage root = metadata.getRootPackageGeneric();
>      if (root.getWavPackage() != null) {
>          System.out.println(root.getWavPackage().getAudioFormat());
>          System.out.println(root.getWavPackage().getBitsPerSample());
>          System.out.println(root.getWavPackage().getBlockAlign());
>          System.out.println(root.getWavPackage().getByteRate());
>          System.out.println(root.getWavPackage().getNumberOfChannels());
>          System.out.println(root.getWavPackage().getSampleRate());
>      }
>  }
>  
> ```
> ```
## Methods

| Method | Description |
| --- | --- |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [getWavPackage()](#getWavPackage--) | Gets the WAV native metadata package. |
| [getRiffInfoPackage()](#getRiffInfoPackage--) | Gets the package containing RIFF Info tags. |
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

### getWavPackage() {#getWavPackage--}
```
public final WavPackage getWavPackage()
```


Gets the WAV native metadata package.

**Returns:**
[WavPackage](../../com.groupdocs.metadata.core/wavpackage) - The WAV native metadata package.
### getRiffInfoPackage() {#getRiffInfoPackage--}
```
public final RiffInfoPackage getRiffInfoPackage()
```


Gets the package containing RIFF Info tags.

**Returns:**
[RiffInfoPackage](../../com.groupdocs.metadata.core/riffinfopackage) - The package containing RIFF Info tags.
