---
title: ID3V2AttachedPictureFrame
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents an APIC frame in an ID3V2Tag.
type: docs
weight: 112
url: /nodejs-java/com.groupdocs.metadata.core/id3v2attachedpictureframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public final class ID3V2AttachedPictureFrame extends ID3V2TagFrame
```

Represents an APIC frame in an  ID3V2Tag .

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2AttachedPictureFrame(ID3V2EncodingType encoding, String mimeType, ID3V2AttachedPictureType pictureType, String description, byte[] pictureData)](#ID3V2AttachedPictureFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-com.groupdocs.metadata.core.ID3V2AttachedPictureType-java.lang.String-byte---) | Initializes a new instance of the  ID3V2AttachedPictureFrame  class. |
| [ID3V2AttachedPictureFrame(ID3V2AttachedPictureType pictureType, String description, byte[] pictureData)](#ID3V2AttachedPictureFrame-com.groupdocs.metadata.core.ID3V2AttachedPictureType-java.lang.String-byte---) | Initializes a new instance of the  ID3V2AttachedPictureFrame  class. |
| [ID3V2AttachedPictureFrame(byte[] pictureData)](#ID3V2AttachedPictureFrame-byte---) | Initializes a new instance of the  ID3V2AttachedPictureFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getDescriptionEncoding()](#getDescriptionEncoding--) | Gets the encoding used to encode the picture description. |
| [getMimeType()](#getMimeType--) | Gets the MIME type of the picture. |
| [getAttachedPictureType()](#getAttachedPictureType--) | Gets the type of the picture. |
| [getDescription()](#getDescription--) | Gets the picture description. |
| [getPictureData()](#getPictureData--) | Gets the picture data. |
### ID3V2AttachedPictureFrame(ID3V2EncodingType encoding, String mimeType, ID3V2AttachedPictureType pictureType, String description, byte[] pictureData) {#ID3V2AttachedPictureFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-com.groupdocs.metadata.core.ID3V2AttachedPictureType-java.lang.String-byte---}
```
public ID3V2AttachedPictureFrame(ID3V2EncodingType encoding, String mimeType, ID3V2AttachedPictureType pictureType, String description, byte[] pictureData)
```


Initializes a new instance of the  ID3V2AttachedPictureFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | [ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) | The frame encoding. |
| mimeType | java.lang.String | The MIME-type of the image. |
| pictureType | [ID3V2AttachedPictureType](../../com.groupdocs.metadata.core/id3v2attachedpicturetype) | The type of the picture. |
| description | java.lang.String | The description of the picture. |
| pictureData | byte[] | The picture data. |

### ID3V2AttachedPictureFrame(ID3V2AttachedPictureType pictureType, String description, byte[] pictureData) {#ID3V2AttachedPictureFrame-com.groupdocs.metadata.core.ID3V2AttachedPictureType-java.lang.String-byte---}
```
public ID3V2AttachedPictureFrame(ID3V2AttachedPictureType pictureType, String description, byte[] pictureData)
```


Initializes a new instance of the  ID3V2AttachedPictureFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pictureType | [ID3V2AttachedPictureType](../../com.groupdocs.metadata.core/id3v2attachedpicturetype) | The type of the picture. |
| description | java.lang.String | The description of the picture. |
| pictureData | byte[] | The picture data. |

### ID3V2AttachedPictureFrame(byte[] pictureData) {#ID3V2AttachedPictureFrame-byte---}
```
public ID3V2AttachedPictureFrame(byte[] pictureData)
```


Initializes a new instance of the  ID3V2AttachedPictureFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pictureData | byte[] | The picture data. |

### getDescriptionEncoding() {#getDescriptionEncoding--}
```
public final ID3V2EncodingType getDescriptionEncoding()
```


Gets the encoding used to encode the picture description.

**Returns:**
[ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) - The encoding used to encode the picture description.
### getMimeType() {#getMimeType--}
```
public final String getMimeType()
```


Gets the MIME type of the picture.

**Returns:**
java.lang.String - The MIME type of the picture.
### getAttachedPictureType() {#getAttachedPictureType--}
```
public final ID3V2AttachedPictureType getAttachedPictureType()
```


Gets the type of the picture.

**Returns:**
[ID3V2AttachedPictureType](../../com.groupdocs.metadata.core/id3v2attachedpicturetype) - The type of the picture.
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the picture description. The description has a maximum length of 64 characters, but may be empty.

**Returns:**
java.lang.String - The picture description.
### getPictureData() {#getPictureData--}
```
public final byte[] getPictureData()
```


Gets the picture data.

**Returns:**
byte[] - The picture data.
