---
title: ID3V2TagFrame
second_title: GroupDocs.Signature for Java API Reference
description: Represents a generic frame in an ID3V2Tag.
type: docs
weight: 119
url: /java/com.groupdocs.metadata.core/id3v2tagframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class ID3V2TagFrame extends CustomPackage
```

Represents a generic frame in an  ID3V2Tag .

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2TagFrame(String frameId, byte[] data)](#ID3V2TagFrame-java.lang.String-byte---) | Initializes a new instance of the  ID3V2TagFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [getFlags()](#getFlags--) | Gets the frame flags. |
| [getData()](#getData--) | Gets the frame data. |
### ID3V2TagFrame(String frameId, byte[] data) {#ID3V2TagFrame-java.lang.String-byte---}
```
public ID3V2TagFrame(String frameId, byte[] data)
```


Initializes a new instance of the  ID3V2TagFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameId | java.lang.String | The id of the frame (four characters matching the pattern [A-Z0-9]). |
| data | byte[] | The content of the frame. |

### getId() {#getId--}
```
public final String getId()
```


Gets the id of the frame (four characters matching the pattern [A-Z0-9]).

**Returns:**
java.lang.String - The id of the frame (four characters matching the pattern [A-Z0-9]).
### getFlags() {#getFlags--}
```
public final ID3V2TagFrameFlags getFlags()
```


Gets the frame flags.

**Returns:**
[ID3V2TagFrameFlags](../../com.groupdocs.metadata.core/id3v2tagframeflags) - The frame flags.
### getData() {#getData--}
```
public final byte[] getData()
```


Gets the frame data.

**Returns:**
byte[] - The frame data.
