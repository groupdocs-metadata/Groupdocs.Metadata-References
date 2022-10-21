---
title: ID3V2CommentFrame
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a COMM frame in an ID3V2Tag.
type: docs
weight: 83
url: /java/com.groupdocs.metadata.core/id3v2commentframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public final class ID3V2CommentFrame extends ID3V2TagFrame
```

Represents a COMM frame in an  ID3V2Tag .

--------------------

This frame is intended for any kind of full text information that does not fit in any other frame.

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2CommentFrame(ID3V2EncodingType encoding, String language, String description, String text)](#ID3V2CommentFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the  ID3V2CommentFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCommentEncoding()](#getCommentEncoding--) | Gets the encoding of the comment. |
| [getLanguage()](#getLanguage--) | Gets the language of the comment (3 characters). |
| [getShortContentDescription()](#getShortContentDescription--) | Gets the short content description. |
| [getText()](#getText--) | Gets the text of the comment. |
### ID3V2CommentFrame(ID3V2EncodingType encoding, String language, String description, String text) {#ID3V2CommentFrame-com.groupdocs.metadata.core.ID3V2EncodingType-java.lang.String-java.lang.String-java.lang.String-}
```
public ID3V2CommentFrame(ID3V2EncodingType encoding, String language, String description, String text)
```


Initializes a new instance of the  ID3V2CommentFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encoding | [ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) | The encoding of the comment. |
| language | java.lang.String | The language of the comment. |
| description | java.lang.String | A short content description. |
| text | java.lang.String | The text of the comment. |

### getCommentEncoding() {#getCommentEncoding--}
```
public final ID3V2EncodingType getCommentEncoding()
```


Gets the encoding of the comment.

**Returns:**
[ID3V2EncodingType](../../com.groupdocs.metadata.core/id3v2encodingtype) - The encoding of the comment.
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the language of the comment (3 characters).

**Returns:**
java.lang.String - The language of the comment.
### getShortContentDescription() {#getShortContentDescription--}
```
public final String getShortContentDescription()
```


Gets the short content description.

**Returns:**
java.lang.String - The short content description.
### getText() {#getText--}
```
public final String getText()
```


Gets the text of the comment.

**Returns:**
java.lang.String - The text of the comment.
