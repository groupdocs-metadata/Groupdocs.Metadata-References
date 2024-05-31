---
title: MatroskaPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a metadata container in a Matroska video.
type: docs
weight: 149
url: /nodejs-java/com.groupdocs.metadata.core/matroskapackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage)
```
public class MatroskaPackage extends MatroskaBasePackage
```

Represents a metadata container in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getEbmlHeader()](#getEbmlHeader--) | Gets the EBML header metadata. |
| [getSegments()](#getSegments--) | Gets the segment information metadata. |
| [getTracks()](#getTracks--) | Gets the track metadata entries. |
| [getTags()](#getTags--) | Gets the tagging metadata. |
| [getContentType()](#getContentType--) | Gets the Matroska content type. |
| [getSubtitleTracks()](#getSubtitleTracks--) | Gets the subtitle metadata entries. |
### getEbmlHeader() {#getEbmlHeader--}
```
public final MatroskaEbmlHeader getEbmlHeader()
```


Gets the EBML header metadata.

**Returns:**
[MatroskaEbmlHeader](../../com.groupdocs.metadata.core/matroskaebmlheader) - The EBML header metadata.
### getSegments() {#getSegments--}
```
public final MatroskaSegment[] getSegments()
```


Gets the segment information metadata.

**Returns:**
com.groupdocs.metadata.core.MatroskaSegment[] - The segment information metadata.
### getTracks() {#getTracks--}
```
public final MatroskaTrack[] getTracks()
```


Gets the track metadata entries.

**Returns:**
com.groupdocs.metadata.core.MatroskaTrack[] - The track metadata entries.
### getTags() {#getTags--}
```
public final MatroskaTag[] getTags()
```


Gets the tagging metadata.

**Returns:**
com.groupdocs.metadata.core.MatroskaTag[] - The tagging metadata.
### getContentType() {#getContentType--}
```
public final MatroskaContentType getContentType()
```


Gets the Matroska content type.

**Returns:**
[MatroskaContentType](../../com.groupdocs.metadata.core/matroskacontenttype) - The Matroska content type.
### getSubtitleTracks() {#getSubtitleTracks--}
```
public final MatroskaSubtitleTrack[] getSubtitleTracks()
```


Gets the subtitle metadata entries.

**Returns:**
com.groupdocs.metadata.core.MatroskaSubtitleTrack[] - The subtitle metadata entries.
