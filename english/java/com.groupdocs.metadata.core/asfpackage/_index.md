---
title: AsfPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents native metadata of the ASF media container.
type: docs
weight: 21
url: /java/com.groupdocs.metadata.core/asfpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class AsfPackage extends CustomPackage
```

Represents native metadata of the ASF media container.

**Learn more**

 *  [Working with Metadata in ASF Files][]


[Working with Metadata in ASF Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+Metadata+in+ASF+Files
## Methods

| Method | Description |
| --- | --- |
| [getFileID()](#getFileID--) | Gets the unique identifier for this file. |
| [getCreationDate()](#getCreationDate--) | Gets the date and time of the initial creation of the file. |
| [getFlags()](#getFlags--) | Gets the header flags. |
| [getStreamProperties()](#getStreamProperties--) | Gets the digital media stream properties. |
| [getMetadataDescriptors()](#getMetadataDescriptors--) | Gets the metadata descriptors. |
| [getCodecInformation()](#getCodecInformation--) | Gets the codec info entries. |
### getFileID() {#getFileID--}
```
public final UUID getFileID()
```


Gets the unique identifier for this file.

**Returns:**
java.util.UUID - The unique identifier for this file.
### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Gets the date and time of the initial creation of the file.

**Returns:**
java.util.Date - The date and time of the initial creation of the file.
### getFlags() {#getFlags--}
```
public final AsfFilePropertyFlags getFlags()
```


Gets the header flags.

**Returns:**
[AsfFilePropertyFlags](../../com.groupdocs.metadata.core/asffilepropertyflags) - The header flags.
### getStreamProperties() {#getStreamProperties--}
```
public final AsfBaseStreamProperty[] getStreamProperties()
```


Gets the digital media stream properties.

**Returns:**
com.groupdocs.metadata.core.AsfBaseStreamProperty[] - The digital media stream properties.
### getMetadataDescriptors() {#getMetadataDescriptors--}
```
public final AsfBaseDescriptor[] getMetadataDescriptors()
```


Gets the metadata descriptors.

**Returns:**
com.groupdocs.metadata.core.AsfBaseDescriptor[] - The metadata descriptors.
### getCodecInformation() {#getCodecInformation--}
```
public final AsfCodec[] getCodecInformation()
```


Gets the codec info entries.

**Returns:**
com.groupdocs.metadata.core.AsfCodec[] - The codec info entries.
