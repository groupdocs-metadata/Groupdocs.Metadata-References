---
title: AsfBaseStreamProperty
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base stream property metadata in the ASF media container.
type: docs
weight: 13
url: /java/com.groupdocs.metadata.core/asfbasestreamproperty/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class AsfBaseStreamProperty extends CustomPackage
```

Represents base stream property metadata in the ASF media container.

**Learn more**

 *  [Working with Metadata in ASF Files][]


[Working with Metadata in ASF Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+Metadata+in+ASF+Files
## Methods

| Method | Description |
| --- | --- |
| [getStreamType()](#getStreamType--) | Gets the type of this stream. |
| [getStreamNumber()](#getStreamNumber--) | Gets the number of this stream. |
| [getStartTime()](#getStartTime--) | Gets the presentation time of the first object, indicating where this digital media stream starts within the context of the timeline of the ASF file as a whole. |
| [getEndTime()](#getEndTime--) | Gets the presentation time of the last object plus the duration of play, indicating where this digital media stream ends within the context of the timeline of the ASF file as a whole. |
| [getBitrate()](#getBitrate--) | Gets the leak rate R, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead. |
| [getAlternateBitrate()](#getAlternateBitrate--) | Gets the leak rate RAlt, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead. |
| [getFlags()](#getFlags--) | Gets the flags. |
| [getLanguage()](#getLanguage--) | Gets the stream language. |
| [getAverageTimePerFrame()](#getAverageTimePerFrame--) | Gets the average time duration, measured in 100-nanosecond units, of each frame. |
| [getAverageBitrate()](#getAverageBitrate--) | Gets the average bitrate. |
### getStreamType() {#getStreamType--}
```
public final AsfStreamType getStreamType()
```


Gets the type of this stream.

**Returns:**
[AsfStreamType](../../com.groupdocs.metadata.core/asfstreamtype) - The type of this stream.
### getStreamNumber() {#getStreamNumber--}
```
public final byte getStreamNumber()
```


Gets the number of this stream.

**Returns:**
byte - The number of this stream.
### getStartTime() {#getStartTime--}
```
public final Long getStartTime()
```


Gets the presentation time of the first object, indicating where this digital media stream starts within the context of the timeline of the ASF file as a whole.

**Returns:**
java.lang.Long - The presentation time of the first object.
### getEndTime() {#getEndTime--}
```
public final Long getEndTime()
```


Gets the presentation time of the last object plus the duration of play, indicating where this digital media stream ends within the context of the timeline of the ASF file as a whole.

**Returns:**
java.lang.Long - The presentation time of the last object plus the duration of play.
### getBitrate() {#getBitrate--}
```
public final Long getBitrate()
```


Gets the leak rate R, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead.

**Returns:**
java.lang.Long - The bleak rate R, in bits per second.
### getAlternateBitrate() {#getAlternateBitrate--}
```
public final Long getAlternateBitrate()
```


Gets the leak rate RAlt, in bits per second, of a leaky bucket that contains the data portion of the stream without overflowing, excluding all ASF Data Packet overhead.

**Returns:**
java.lang.Long - The leak rate RAlt, in bits per second.
### getFlags() {#getFlags--}
```
public final AsfExtendedStreamPropertyFlags getFlags()
```


Gets the flags.

**Returns:**
[AsfExtendedStreamPropertyFlags](../../com.groupdocs.metadata.core/asfextendedstreampropertyflags) - The flags.
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the stream language.

**Returns:**
java.lang.String - The stream language.
### getAverageTimePerFrame() {#getAverageTimePerFrame--}
```
public final Long getAverageTimePerFrame()
```


Gets the average time duration, measured in 100-nanosecond units, of each frame.

**Returns:**
java.lang.Long - The average time duration, measured in 100-nanosecond units, of each frame.
### getAverageBitrate() {#getAverageBitrate--}
```
public final Long getAverageBitrate()
```


Gets the average bitrate.

**Returns:**
java.lang.Long - The average bitrate.
