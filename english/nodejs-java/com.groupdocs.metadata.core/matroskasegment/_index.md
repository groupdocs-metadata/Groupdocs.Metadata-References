---
title: MatroskaSegment
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a SEGMENTINFO element containing general information about the SEGMENT in a Matroska video.
type: docs
weight: 151
url: /nodejs-java/com.groupdocs.metadata.core/matroskasegment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage)
```
public class MatroskaSegment extends MatroskaBasePackage
```

Represents a SEGMENTINFO element containing general information about the SEGMENT in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getSegmentUid()](#getSegmentUid--) | Gets the unique 128 bit number identifying a SEGMENT. |
| [getSegmentFilename()](#getSegmentFilename--) | Gets the filename corresponding to this Segment. |
| [getTimecodeScale()](#getTimecodeScale--) | Gets the timecode scale value. |
| [getDuration()](#getDuration--) | Gets the duration of the SEGMENT. |
| [getDateUtc()](#getDateUtc--) | Gets the date and time that the Segment was created by the muxing application or library. |
| [getTitle()](#getTitle--) | Gets the general name of the Segment. |
| [getMuxingApp()](#getMuxingApp--) | Gets the full name of the application or library followed by the version number. |
| [getWritingApp()](#getWritingApp--) | Gets the full name of the application followed by the version number. |
| [getScaledDuration()](#getScaledDuration--) | Gets the scaled duration of the SEGMENT in milliseconds. |
### getSegmentUid() {#getSegmentUid--}
```
public final byte[] getSegmentUid()
```


Gets the unique 128 bit number identifying a SEGMENT. Obviously, a file can only be referred to by another file if a SEGMENTUID is present, however, playback is possible without that UID.

**Returns:**
byte[] - The unique 128 bit number identifying a SEGMENT.
### getSegmentFilename() {#getSegmentFilename--}
```
public final String getSegmentFilename()
```


Gets the filename corresponding to this Segment.

**Returns:**
java.lang.String - The filename corresponding to this Segment.
### getTimecodeScale() {#getTimecodeScale--}
```
public final long getTimecodeScale()
```


Gets the timecode scale value. Each scaled timecode in a MATROSKA file is multiplied by TIMECODESCALE to obtain the timecode in nanoseconds. Note that not all timecodes are scaled!

**Returns:**
long - The timecode scale value.
### getDuration() {#getDuration--}
```
public final Double getDuration()
```


Gets the duration of the SEGMENT. Please see  TimecodeScale  for more information.

**Returns:**
java.lang.Double - The duration of the SEGMENT.
### getDateUtc() {#getDateUtc--}
```
public final Date getDateUtc()
```


Gets the date and time that the Segment was created by the muxing application or library.

**Returns:**
java.util.Date - The date and time that the Segment was created by the muxing application or library.
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the general name of the Segment.

**Returns:**
java.lang.String - The general name of the Segment.
### getMuxingApp() {#getMuxingApp--}
```
public final String getMuxingApp()
```


Gets the full name of the application or library followed by the version number.

**Returns:**
java.lang.String - The full name of the application or library followed by the version number.
### getWritingApp() {#getWritingApp--}
```
public final String getWritingApp()
```


Gets the full name of the application followed by the version number.

**Returns:**
java.lang.String - The full name of the application followed by the version number.
### getScaledDuration() {#getScaledDuration--}
```
public final Double getScaledDuration()
```


Gets the scaled duration of the SEGMENT in milliseconds.

**Returns:**
java.lang.Double - The scaled duration of the SEGMENT in milliseconds.
