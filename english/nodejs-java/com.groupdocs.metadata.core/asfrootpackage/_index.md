---
title: AsfRootPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents the root package allowing working with metadata in an ASF video.
type: docs
weight: 22
url: /nodejs-java/com.groupdocs.metadata.core/asfrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class AsfRootPackage extends RootMetadataPackage implements IXmp
```

Represents the root package allowing working with metadata in an ASF video.

**Learn more**

 *  [Working with Metadata in ASF Files][]
 *  [Working with XMP metadata][]

This code sample demonstrates how to read native ASF metadata.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputAsf)) {
>      AsfRootPackage root = metadata.getRootPackageGeneric();
>      AsfPackage asfPackage = root.getAsfPackage();
>      // Display basic properties
>      System.out.println(String.format("Creation date: %s", asfPackage.getCreationDate()));
>      System.out.println(String.format("File id: %s", asfPackage.getFileID()));
>      System.out.println(String.format("Flags: %s", asfPackage.getFlags()));
>      // Display Asf Codec Information
>      for (AsfCodec codecInfo : asfPackage.getCodecInformation()) {
>          System.out.println(String.format("Codec type: %s", codecInfo.getCodecType()));
>          System.out.println(String.format("Description: %s", codecInfo.getDescription()));
>          System.out.println(String.format("Codec information: %s", codecInfo.getInformation()));
>          System.out.println(codecInfo.getName());
>      }
>      // Display metadata descriptors
>      for (AsfBaseDescriptor descriptor : asfPackage.getMetadataDescriptors()) {
>          System.out.println(String.format("Name: %s", descriptor.getName()));
>          System.out.println(String.format("Value: %s", descriptor.getValue()));
>          System.out.println(String.format("Content type: %s", descriptor.getAsfContentType()));
>          if (descriptor instanceof AsfMetadataDescriptor) {
>              AsfMetadataDescriptor metadataDescriptor = (AsfMetadataDescriptor) descriptor;
>              System.out.println(String.format("Language: %s", metadataDescriptor.getLanguage()));
>              System.out.println(String.format("Stream number: %s", metadataDescriptor.getStreamNumber()));
>              System.out.println(String.format("Original name: %s", metadataDescriptor.getOriginalName()));
>          }
>      }
>      //Display the base stream properties
>      for (AsfBaseStreamProperty property : asfPackage.getStreamProperties()) {
>          System.out.println(String.format("Alternate bitrate: %s", property.getAlternateBitrate()));
>          System.out.println(String.format("Average bitrate: %s", property.getAverageBitrate()));
>          System.out.println(String.format("Average time per frame: %s", property.getAverageTimePerFrame()));
>          System.out.println(String.format("Bitrate: %s", property.getBitrate()));
>          System.out.println(String.format("Stream end time: %s", property.getEndTime()));
>          System.out.println(String.format("Stream flags: %s", property.getFlags()));
>          System.out.println(String.format("Stream language: %s", property.getLanguage()));
>          System.out.println(String.format("Stream start time: %s", property.getStartTime()));
>          System.out.println(String.format("Stream number: %s", property.getStreamNumber()));
>          System.out.println(String.format("Stream type: %s", property.getStreamType()));
>          //Display the audio stream properties
>          if (property instanceof AsfAudioStreamProperty) {
>              AsfAudioStreamProperty audioStreamProperty = (AsfAudioStreamProperty) property;
>              System.out.println(String.format("Audio bits per sample: %s", audioStreamProperty.getBitsPerSample()));
>              System.out.println(String.format("Audio channels: %s", audioStreamProperty.getChannels()));
>              System.out.println(String.format("Audio format tag: %s", audioStreamProperty.getFormatTag()));
>              System.out.println(String.format("Audio samples per second: %s", audioStreamProperty.getSamplesPerSecond()));
>          }
>          //Display the video stream properties
>          if (property instanceof AsfVideoStreamProperty) {
>              AsfVideoStreamProperty videoStreamProperty = (AsfVideoStreamProperty) property;
>              System.out.println(String.format("Video bits per pixels: %s", videoStreamProperty.getBitsPerPixels()));
>              System.out.println(String.format("Compression: %s", videoStreamProperty.getCompression()));
>              System.out.println(String.format("Image height: %s", videoStreamProperty.getImageHeight()));
>              System.out.println(String.format("Image width: %s", videoStreamProperty.getImageWidth()));
>          }
>      }
>  }
>  
> ```
> ```


[Working with Metadata in ASF Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+Metadata+in+ASF+Files
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getAsfPackage()](#getAsfPackage--) | Gets the ASF metadata package. |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
| [copyTo(MetadataPackage metadata)](#copyTo-com.groupdocs.metadata.core.MetadataPackage-) |  |
### getAsfPackage() {#getAsfPackage--}
```
public final AsfPackage getAsfPackage()
```


Gets the ASF metadata package.

**Returns:**
[AsfPackage](../../com.groupdocs.metadata.core/asfpackage) - The ASF metadata package.
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

### copyTo(MetadataPackage metadata) {#copyTo-com.groupdocs.metadata.core.MetadataPackage-}
```
public void copyTo(MetadataPackage metadata)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| metadata | [MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage) |  |

