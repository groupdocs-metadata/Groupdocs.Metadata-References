---
title: AviHeader
second_title: GroupDocs.Signature for Java API Reference
description: Represents the AVIMAINHEADER structure in an AVI video.
type: docs
weight: 24
url: /java/com.groupdocs.metadata.core/aviheader/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class AviHeader extends CustomPackage
```

Represents the AVIMAINHEADER structure in an AVI video.

**Learn more**

 *  [Working with metadata in AVI files][]


[Working with metadata in AVI files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+AVI+files
## Constructors

| Constructor | Description |
| --- | --- |
| [AviHeader()](#AviHeader--) | Initializes a new instance of the  AviHeader  class. |
## Methods

| Method | Description |
| --- | --- |
| [getMicroSecPerFrame()](#getMicroSecPerFrame--) | Gets the the number of microseconds between frames. |
| [getMaxBytesPerSec()](#getMaxBytesPerSec--) |  |
| [getPaddingGranularity()](#getPaddingGranularity--) | Gets the alignment for data, in bytes. |
| [getAviHeaderFlags()](#getAviHeaderFlags--) | Gets a bitwise combination of zero or more of the AVI flags. |
| [getTotalFrames()](#getTotalFrames--) | Gets the the total number of frames of data in the file. |
| [getInitialFrames()](#getInitialFrames--) |  |
| [getStreams()](#getStreams--) | Gets the number of streams in the file. |
| [getSuggestedBufferSize()](#getSuggestedBufferSize--) |  |
| [getWidth()](#getWidth--) | Gets the width of the AVI file in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the AVI file in pixels. |
### AviHeader() {#AviHeader--}
```
public AviHeader()
```


Initializes a new instance of the  AviHeader  class.

### getMicroSecPerFrame() {#getMicroSecPerFrame--}
```
public final int getMicroSecPerFrame()
```


Gets the the number of microseconds between frames. This value indicates the overall timing for the file.

**Returns:**
int - The number of microseconds between frames.
### getMaxBytesPerSec() {#getMaxBytesPerSec--}
```
public final int getMaxBytesPerSec()
```


Gets the approximate maximum data rate of the file. 

 This value indicates the number of bytes per second the system must handle to present an AVI sequence as specified by the other parameters contained in the main header and stream header chunks.

**Returns:**
int - The the approximate maximum data rate of the file.
### getPaddingGranularity() {#getPaddingGranularity--}
```
public final int getPaddingGranularity()
```


Gets the alignment for data, in bytes. Pad the data to multiples of this value.

**Returns:**
int - The the alignment for data.
### getAviHeaderFlags() {#getAviHeaderFlags--}
```
public final AviHeaderFlags getAviHeaderFlags()
```


Gets a bitwise combination of zero or more of the AVI flags.

**Returns:**
[AviHeaderFlags](../../com.groupdocs.metadata.core/aviheaderflags) - The AVI flags.
### getTotalFrames() {#getTotalFrames--}
```
public final int getTotalFrames()
```


Gets the the total number of frames of data in the file.

**Returns:**
int - The total number of frames.
### getInitialFrames() {#getInitialFrames--}
```
public final int getInitialFrames()
```


Gets the initial frame for interleaved files. 

 Noninterleaved files should specify zero. If you are creating interleaved files, specify the number of frames in the file prior to the initial frame of the AVI sequence in this member.

**Returns:**
int - The initial frames.
### getStreams() {#getStreams--}
```
public final int getStreams()
```


Gets the number of streams in the file. For example, a file with audio and video has two streams.

**Returns:**
int - The number of streams.
### getSuggestedBufferSize() {#getSuggestedBufferSize--}
```
public final int getSuggestedBufferSize()
```


Gets the suggested buffer size for reading the file. 

 Generally, this size should be large enough to contain the largest chunk in the file. If set to zero, or if it is too small, the playback software will have to reallocate memory during playback, which will reduce performance. For an interleaved file, the buffer size should be large enough to read an entire record, and not just a chunk.

**Returns:**
int - The suggested buffer size for reading the file.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the AVI file in pixels.

**Returns:**
int - The width in pixels.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the AVI file in pixels.

**Returns:**
int - The height in pixels.
