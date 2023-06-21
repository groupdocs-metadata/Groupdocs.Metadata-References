---
title: ID3V2UserDefinedUrlLinkFrame
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a WXXX frame in an ID3V2Tag.
type: docs
weight: 125
url: /java/com.groupdocs.metadata.core/id3v2userdefinedurllinkframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public final class ID3V2UserDefinedUrlLinkFrame extends ID3V2TagFrame
```

Represents a WXXX frame in an  ID3V2Tag .

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2UserDefinedUrlLinkFrame(String description, String url)](#ID3V2UserDefinedUrlLinkFrame-java.lang.String-java.lang.String-) | Initializes a new instance of the  ID3V2UserDefinedUrlLinkFrame  class. |
| [ID3V2UserDefinedUrlLinkFrame(ID3V2EncodingType encoding, String description, String url)](#ID3V2UserDefinedUrlLinkFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-java.lang.String-) | Initializes a new instance of the  ID3V2UserDefinedUrlLinkFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getEncoding()](#getEncoding--) | Gets the encoding of the frame. |
| [getDescription()](#getDescription--) | Gets the description. |
| [getUrl()](#getUrl--) | Gets the URL. |
### ID3V2UserDefinedUrlLinkFrame(String description, String url) {#ID3V2UserDefinedUrlLinkFrame-java.lang.String-java.lang.String-}
```
public ID3V2UserDefinedUrlLinkFrame(String description, String url)
```


Initializes a new instance of the  ID3V2UserDefinedUrlLinkFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | The description. |
| url | java.lang.String | The actual value of the frame. |

### ID3V2UserDefinedUrlLinkFrame(ID3V2EncodingType encoding, String description, String url) {#ID3V2UserDefinedUrlLinkFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-java.lang.String-}
```
public ID3V2UserDefinedUrlLinkFrame(ID3V2EncodingType encoding, String description, String url)
```


Initializes a new instance of the  ID3V2UserDefinedUrlLinkFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | [ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) | The encoding of the frame. |
| description | java.lang.String | The description. |
| url | java.lang.String | The actual value of the frame. |

### getEncoding() {#getEncoding--}
```
public final ID3V2EncodingType getEncoding()
```


Gets the encoding of the frame.

**Returns:**
[ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) - The encoding of the frame.
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the description.

**Returns:**
java.lang.String - The description.
### getUrl() {#getUrl--}
```
public final String getUrl()
```


Gets the URL.

**Returns:**
java.lang.String - The URL.
