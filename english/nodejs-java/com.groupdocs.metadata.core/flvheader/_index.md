---
title: FlvHeader
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a FLV video header.
type: docs
weight: 102
url: /nodejs-java/com.groupdocs.metadata.core/flvheader/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class FlvHeader extends CustomPackage
```

Represents a FLV video header.

**Learn more**

 *  [Working with metadata in FLV files][]


[Working with metadata in FLV files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+FLV+files
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets the file version. |
| [getTypeFlags()](#getTypeFlags--) | Gets the FLV type flags. |
| [hasAudioTags()](#hasAudioTags--) | Gets a value indicating whether audio tags are present in the file. |
| [hasVideoTags()](#hasVideoTags--) | Gets a value indicating whether video tags are present in the file. |
### getVersion() {#getVersion--}
```
public final byte getVersion()
```


Gets the file version.

**Returns:**
byte - The file version.
### getTypeFlags() {#getTypeFlags--}
```
public final byte getTypeFlags()
```


Gets the FLV type flags.

**Returns:**
byte - The FLV type flags.
### hasAudioTags() {#hasAudioTags--}
```
public final boolean hasAudioTags()
```


Gets a value indicating whether audio tags are present in the file.

**Returns:**
boolean - True if the FLV file contains audio tags; otherwise, false.
### hasVideoTags() {#hasVideoTags--}
```
public final boolean hasVideoTags()
```


Gets a value indicating whether video tags are present in the file.

**Returns:**
boolean - True if the FLV file contains video tags; otherwise, false.
