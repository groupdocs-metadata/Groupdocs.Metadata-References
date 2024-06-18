---
title: LyricsField
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a LyricsTag field.
type: docs
weight: 142
url: /nodejs-java/com.groupdocs.metadata.core/lyricsfield/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataProperty](../../com.groupdocs.metadata.core/metadataproperty)
```
public final class LyricsField extends MetadataProperty
```

Represents a  LyricsTag  field.

**Learn more**

 *  [Handling the Lyrics tag][]


[Handling the Lyrics tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+Lyrics+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [LyricsField(String id, String data)](#LyricsField-java.lang.String-java.lang.String-) | Initializes a new instance of the  LyricsField  class. |
## Methods

| Method | Description |
| --- | --- |
| [getID()](#getID--) | Gets the id of the field (it's always three characters long). |
| [getSize()](#getSize--) | Gets the string representation of the field size. |
| [getData()](#getData--) | Gets the field data. |
### LyricsField(String id, String data) {#LyricsField-java.lang.String-java.lang.String-}
```
public LyricsField(String id, String data)
```


Initializes a new instance of the  LyricsField  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The three character field id. |
| data | java.lang.String | The field data. |

### getID() {#getID--}
```
public final String getID()
```


Gets the id of the field (it's always three characters long).

**Returns:**
java.lang.String - The id of the field (it's always three characters long).
### getSize() {#getSize--}
```
public final String getSize()
```


Gets the string representation of the field size.

**Returns:**
java.lang.String - The string representation of the field size.
### getData() {#getData--}
```
public final String getData()
```


Gets the field data.

**Returns:**
java.lang.String - The field data.
