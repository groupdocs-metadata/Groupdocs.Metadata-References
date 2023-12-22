---
title: MatroskaTrack
second_title: GroupDocs.Metadata for Java API Reference
description: Represents track metadata in a Matroska video.
type: docs
weight: 156
url: /java/com.groupdocs.metadata.core/matroskatrack/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.MatroskaBasePackage](../../com.groupdocs.metadata.core/matroskabasepackage)
```
public class MatroskaTrack extends MatroskaBasePackage
```

Represents track metadata in a Matroska video.

**Learn more**

 *  [Working with metadata in Matroska (MKV) files][Working with metadata in Matroska _MKV_ files]


[Working with metadata in Matroska _MKV_ files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Matroska+%28MKV%29+files
## Methods

| Method | Description |
| --- | --- |
| [getTrackNumber()](#getTrackNumber--) | Gets the track number as used in the Block Header. |
| [getTrackUid()](#getTrackUid--) | Gets the unique ID to identify the Track. |
| [getTrackType()](#getTrackType--) | Gets the type of the track. |
| [getFlagEnabled()](#getFlagEnabled--) | Gets the enabled flag, true if the track is usable. |
| [getDefaultDuration()](#getDefaultDuration--) | Gets the number of nanoseconds (not scaled via  MatroskaSegment.TimecodeScale ) per frame. |
| [getName()](#getName--) | Gets the human-readable track name. |
| [getLanguage()](#getLanguage--) | Gets the language of the track in the Matroska languages form. |
| [getLanguageIetf()](#getLanguageIetf--) | Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. |
| [getCodecID()](#getCodecID--) | Gets an ID corresponding to the codec. |
| [getCodecName()](#getCodecName--) | Gets a human-readable string specifying the codec. |
### getTrackNumber() {#getTrackNumber--}
```
public final long getTrackNumber()
```


Gets the track number as used in the Block Header. Using more than 127 tracks is not encouraged, though the design allows an unlimited number.

**Returns:**
long - The track number as used in the Block Header.
### getTrackUid() {#getTrackUid--}
```
public final long getTrackUid()
```


Gets the unique ID to identify the Track. This SHOULD be kept the same when making a direct stream copy of the Track to another file.

**Returns:**
long - The unique ID to identify the Track.
### getTrackType() {#getTrackType--}
```
public final MatroskaTrackType getTrackType()
```


Gets the type of the track.

**Returns:**
[MatroskaTrackType](../../com.groupdocs.metadata.core/matroskatracktype) - The type of the track.
### getFlagEnabled() {#getFlagEnabled--}
```
public final boolean getFlagEnabled()
```


Gets the enabled flag, true if the track is usable.

**Returns:**
boolean - The enabled flag.
### getDefaultDuration() {#getDefaultDuration--}
```
public final Long getDefaultDuration()
```


Gets the number of nanoseconds (not scaled via  MatroskaSegment.TimecodeScale ) per frame.

**Returns:**
java.lang.Long - The number of nanoseconds (not scaled via  MatroskaSegment.TimecodeScale ) per frame.

--------------------

Note: 'frame' in the Matroska sense -- one Element put into a (Simple)Block.
### getName() {#getName--}
```
public final String getName()
```


Gets the human-readable track name.

**Returns:**
java.lang.String - The human-readable track name.
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the language of the track in the Matroska languages form. This Element MUST be ignored if the  LanguageIetf  Element is used in the same TrackEntry.

**Returns:**
java.lang.String - The language of the track in the Matroska languages form.

--------------------

Language codes can be either the 3 letters bibliographic ISO-639-2 form (like "fre" for french), or such a language code followed by a dash and a country code for specialities in languages(like "fre-ca" for Canadian French). Country codes are the same as used for internet domains.
### getLanguageIetf() {#getLanguageIetf--}
```
public final String getLanguageIetf()
```


Gets the language of the track according to BCP 47 and using the IANA Language Subtag Registry. If this Element is used, then any  Language  Elements used in the same TrackEntry MUST be ignored.

**Returns:**
java.lang.String - The language of the track according to BCP 47 and using the IANA Language Subtag Registry.
### getCodecID() {#getCodecID--}
```
public final String getCodecID()
```


Gets an ID corresponding to the codec.

**Returns:**
java.lang.String - An ID corresponding to the codec.

--------------------

See the http://www.matroska.org/technical/specs/codecid/index.html codec page for more info.
### getCodecName() {#getCodecName--}
```
public final String getCodecName()
```


Gets a human-readable string specifying the codec.

**Returns:**
java.lang.String - A human-readable string specifying the codec.
