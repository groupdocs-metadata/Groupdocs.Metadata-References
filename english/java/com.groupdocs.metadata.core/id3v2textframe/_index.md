---
title: ID3V2TextFrame
second_title: GroupDocs.Signature for Java API Reference
description: Represents a text frame in an ID3V2Tag.
type: docs
weight: 121
url: /java/com.groupdocs.metadata.core/id3v2textframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public class ID3V2TextFrame extends ID3V2TagFrame
```

Represents a text frame in an  ID3V2Tag . Almost all frames starting with the T character fall into this category. There is only one exception, which is the TXXX frame represented by the  ID3V2UserDefinedFrame  class.

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2TextFrame(String id, ID3V2EncodingType encoding, String value)](#ID3V2TextFrame-java.lang.String-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-) | Initializes a new instance of the  ID3V2TextFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getTextEncoding()](#getTextEncoding--) | Gets the text encoding. |
| [getText()](#getText--) | Gets the text value. |
### ID3V2TextFrame(String id, ID3V2EncodingType encoding, String value) {#ID3V2TextFrame-java.lang.String-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-}
```
public ID3V2TextFrame(String id, ID3V2EncodingType encoding, String value)
```


Initializes a new instance of the  ID3V2TextFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The frame id. |
| encoding | [ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) | The encoding of the frame. |
| value | java.lang.String | The frame value. |

### getTextEncoding() {#getTextEncoding--}
```
public final ID3V2EncodingType getTextEncoding()
```


Gets the text encoding.

**Returns:**
[ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) - The text encoding.
### getText() {#getText--}
```
public final String getText()
```


Gets the text value.

**Returns:**
java.lang.String - The text value.
