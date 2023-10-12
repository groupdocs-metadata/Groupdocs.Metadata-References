---
title: ID3V2PrivateFrame
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a PRIV frame in an ID3V2Tag.
type: docs
weight: 118
url: /java/com.groupdocs.metadata.core/id3v2privateframe/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe)
```
public final class ID3V2PrivateFrame extends ID3V2TagFrame
```

Represents a PRIV frame in an  ID3V2Tag . The frame is used to contain information from a software producer that its program uses and does not fit into the other frames.

**Learn more**

 *  [Handling the ID3v2 tag][]


[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2PrivateFrame(String ownerIdentifier, byte[] data)](#ID3V2PrivateFrame-java.lang.String-byte---) | Initializes a new instance of the  ID3V2PrivateFrame  class. |
## Methods

| Method | Description |
| --- | --- |
| [getOwnerIdentifier()](#getOwnerIdentifier--) | Gets the owner identifier. |
| [getBinaryData()](#getBinaryData--) | Gets the binary data. |
### ID3V2PrivateFrame(String ownerIdentifier, byte[] data) {#ID3V2PrivateFrame-java.lang.String-byte---}
```
public ID3V2PrivateFrame(String ownerIdentifier, byte[] data)
```


Initializes a new instance of the  ID3V2PrivateFrame  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerIdentifier | java.lang.String | The owner identifier. |
| data | byte[] | Frame binary data. |

### getOwnerIdentifier() {#getOwnerIdentifier--}
```
public final String getOwnerIdentifier()
```


Gets the owner identifier.

**Returns:**
java.lang.String - The owner identifier.
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Gets the binary data.

**Returns:**
byte[] - The binary data.
