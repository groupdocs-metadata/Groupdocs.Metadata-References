---
title: MatroskaTag
second_title: GroupDocs.Metadata for Java API Reference
description: Represents metadata describing Tracks Editions Chapters Attachments or the Segment as a whole in a Matroska video.
type: docs
weight: 155
url: /java/com.groupdocs.metadata.core/matroskatag/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage)
```
public class MatroskaTag extends MatroskaBasePackage
```

Represents metadata describing Tracks, Editions, Chapters, Attachments, or the Segment as a whole in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getTargetTypeValue()](#getTargetTypeValue--) | Gets the number to indicate the logical level of the target. |
| [getTargetType()](#getTargetType--) | Gets an informational string that can be used to display the logical level of the target. |
| [getTagTrackUid()](#getTagTrackUid--) | Gets a unique ID to identify the Track(s) the tags belong to. |
| [getSimpleTags()](#getSimpleTags--) | Gets the general information about the target. |
### getTargetTypeValue() {#getTargetTypeValue--}
```
public final MatroskaTargetTypeValue getTargetTypeValue()
```


Gets the number to indicate the logical level of the target.

**Returns:**
[MatroskaTargetTypeValue](../../com.groupdocs.metadata.core/matroskatargettypevalue) - The number to indicate the logical level of the target.
### getTargetType() {#getTargetType--}
```
public final String getTargetType()
```


Gets an informational string that can be used to display the logical level of the target. Like "ALBUM", "TRACK", "MOVIE", "CHAPTER", etc.

**Returns:**
java.lang.String - An informational string that can be used to display the logical level of the target.
### getTagTrackUid() {#getTagTrackUid--}
```
public final long getTagTrackUid()
```


Gets a unique ID to identify the Track(s) the tags belong to. If the value is 0 at this level, the tags apply to all tracks in the Segment.

**Returns:**
long - A unique ID to identify the Track(s) the tags belong to.
### getSimpleTags() {#getSimpleTags--}
```
public final MatroskaSimpleTag getSimpleTags()
```


Gets the general information about the target.

**Returns:**
[MatroskaSimpleTag](../../com.groupdocs.metadata.core/matroskasimpletag) - The general information about the target.
