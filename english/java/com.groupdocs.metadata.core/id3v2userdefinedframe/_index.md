---
title: ID3V2UserDefinedFrame
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a TXXX frame in an ID3V2Tag.
type: docs
weight: 123
url: /java/com.groupdocs.metadata.core/id3v2userdefinedframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public final class ID3V2UserDefinedFrame extends ID3V2TagFrame
```

Represents a TXXX frame in an  ID3V2Tag .

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2UserDefinedFrame(String description, String value)](#ID3V2UserDefinedFrame-java.lang.String-java.lang.String-) | Initializes a new instance of the  ID3V2UserDefinedFrame  class. |
| [ID3V2UserDefinedFrame(ID3V2EncodingType encoding, String description, String value)](#ID3V2UserDefinedFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-java.lang.String-) | Initializes a new instance of the  ID3V2UserDefinedFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getEncoding()](#getEncoding--) | Gets the encoding of the frame. |
| [getDescription()](#getDescription--) | Gets the description. |
| [getValue()](#getValue--) | Gets the value. |
### ID3V2UserDefinedFrame(String description, String value) {#ID3V2UserDefinedFrame-java.lang.String-java.lang.String-}
```
public ID3V2UserDefinedFrame(String description, String value)
```


Initializes a new instance of the  ID3V2UserDefinedFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| description | java.lang.String | The description. |
| value | java.lang.String | The value. |

### ID3V2UserDefinedFrame(ID3V2EncodingType encoding, String description, String value) {#ID3V2UserDefinedFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-java.lang.String-}
```
public ID3V2UserDefinedFrame(ID3V2EncodingType encoding, String description, String value)
```


Initializes a new instance of the  ID3V2UserDefinedFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | [ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) | The encoding of the frame. |
| description | java.lang.String | The description. |
| value | java.lang.String | The text value. |

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
### getValue() {#getValue--}
```
public final String getValue()
```


Gets the value.

**Returns:**
java.lang.String - The value.
