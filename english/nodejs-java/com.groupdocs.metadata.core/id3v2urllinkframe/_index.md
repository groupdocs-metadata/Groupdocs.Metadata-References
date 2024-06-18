---
title: ID3V2UrlLinkFrame
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a URL link frame in an ID3V2Tag.
type: docs
weight: 122
url: /nodejs-java/com.groupdocs.metadata.core/id3v2urllinkframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public final class ID3V2UrlLinkFrame extends ID3V2TagFrame
```

Represents a URL link frame in an  ID3V2Tag . Name of the frame always starts with the W character.

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2UrlLinkFrame(String id, String url)](#ID3V2UrlLinkFrame-java.lang.String-java.lang.String-) | Initializes a new instance of the  ID3V2UrlLinkFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getUrl()](#getUrl--) | Gets the URL value. |
### ID3V2UrlLinkFrame(String id, String url) {#ID3V2UrlLinkFrame-java.lang.String-java.lang.String-}
```
public ID3V2UrlLinkFrame(String id, String url)
```


Initializes a new instance of the  ID3V2UrlLinkFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The frame id. |
| url | java.lang.String | The URL which is the value of the frame. |

### getUrl() {#getUrl--}
```
public final String getUrl()
```


Gets the URL value.

**Returns:**
java.lang.String - The URL value.
