---
title: XmpDynamicMediaPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents XMP Dynamic Media namespace.
type: docs
weight: 313
url: /java/com.groupdocs.metadata.core/xmpdynamicmediapackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpDynamicMediaPackage extends XmpPackage
```

Represents XMP Dynamic Media namespace.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpDynamicMediaPackage()](#XmpDynamicMediaPackage--) | Initializes a new instance of the  XmpDynamicMediaPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getAbsPeakAudioFilePath()](#getAbsPeakAudioFilePath--) | Gets the absolute path to the file\\u2019s peak audio file. |
| [setAbsPeakAudioFilePath(String value)](#setAbsPeakAudioFilePath-java.lang.String-) | Sets the absolute path to the file\\u2019s peak audio file. |
| [getAlbum()](#getAlbum--) | Gets the name of the album. |
| [setAlbum(String value)](#setAlbum-java.lang.String-) | Sets the name of the album. |
| [getAltTapeName()](#getAltTapeName--) | Gets the alternative tape name, set via the project window or timecode dialog in Premiere. |
| [setAltTapeName(String value)](#setAltTapeName-java.lang.String-) | Sets the alternative tape name, set via the project window or timecode dialog in Premiere. |
| [getAltTimecode()](#getAltTimecode--) | Gets the timecode set by the user. |
| [setAltTimecode(XmpTimecode value)](#setAltTimecode-com.groupdocs.metadata.core.XmpTimecode-) | Sets the timecode set by the user. |
| [getArtist()](#getArtist--) | Gets the name of the artist or artists. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sets the name of the artist or artists. |
| [getAudioChannelType()](#getAudioChannelType--) | Gets the audio channel type. |
| [setAudioChannelType(String value)](#setAudioChannelType-java.lang.String-) | Sets the audio channel type. |
| [getAudioCompressor()](#getAudioCompressor--) | Gets the audio compression used. |
| [setAudioCompressor(String value)](#setAudioCompressor-java.lang.String-) | Sets the audio compression used. |
| [getAudioSampleRate()](#getAudioSampleRate--) | Gets the audio sample rate. |
| [setAudioSampleRate(Integer value)](#setAudioSampleRate-java.lang.Integer-) | Sets the audio sample rate. |
| [getAudioSampleType()](#getAudioSampleType--) | Gets the audio sample type. |
| [setAudioSampleType(String value)](#setAudioSampleType-java.lang.String-) | Sets the audio sample type. |
| [getCameraAngle()](#getCameraAngle--) | Gets the orientation of the camera to the subject in a static shot, from a fixed set of industry standard terminology. |
| [setCameraAngle(String value)](#setCameraAngle-java.lang.String-) | Sets the orientation of the camera to the subject in a static shot, from a fixed set of industry standard terminology. |
| [getCameraLabel()](#getCameraLabel--) | Gets the description of the camera used for a shoot. |
| [setCameraLabel(String value)](#setCameraLabel-java.lang.String-) | Sets the description of the camera used for a shoot. |
| [getCameraModel()](#getCameraModel--) | Gets the make and model of the camera used for a shoot. |
| [setCameraModel(String value)](#setCameraModel-java.lang.String-) | Sets the make and model of the camera used for a shoot. |
| [getCameraMove()](#getCameraMove--) | Gets the movement of the camera during the shot, from a fixed set of industry standard terminology. |
| [setCameraMove(String value)](#setCameraMove-java.lang.String-) | Sets the movement of the camera during the shot, from a fixed set of industry standard terminology. |
| [getClient()](#getClient--) | Gets the client for the job of which this shot or take is a part. |
| [setClient(String value)](#setClient-java.lang.String-) | Sets the client for the job of which this shot or take is a part. |
| [getComment()](#getComment--) | Gets the user\\u2019s comments. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the user\\u2019s comments. |
| [getComposer()](#getComposer--) | Gets the composer\\u2019s names. |
| [setComposer(String value)](#setComposer-java.lang.String-) | Sets the composer\\u2019s names. |
| [getDirector()](#getDirector--) | Gets the director of the scene. |
| [setDirector(String value)](#setDirector-java.lang.String-) | Sets the director of the scene. |
| [getDirectorPhotography()](#getDirectorPhotography--) | Gets the director of photography for the scene. |
| [setDirectorPhotography(String value)](#setDirectorPhotography-java.lang.String-) | Sets the director of photography for the scene. |
| [getDuration()](#getDuration--) | Gets the duration of the media file. |
| [setDuration(XmpTime value)](#setDuration-com.groupdocs.metadata.core.XmpTime-) | Sets the duration of the media file. |
| [getEngineer()](#getEngineer--) | Gets the engineer's names. |
| [setEngineer(String value)](#setEngineer-java.lang.String-) | Sets the engineer's names. |
| [getFileDataRate()](#getFileDataRate--) | Gets the file data rate in megabytes per second. |
| [setFileDataRate(XmpRational value)](#setFileDataRate-com.groupdocs.metadata.core.XmpRational-) | Sets the file data rate in megabytes per second. |
| [getGenre()](#getGenre--) | Gets the name of the genres. |
| [setGenre(String value)](#setGenre-java.lang.String-) | Sets the name of the genres. |
| [getGood()](#getGood--) | Gets a value indicating whether the shot is a keeper. |
| [setGood(Boolean value)](#setGood-java.lang.Boolean-) | Sets a value indicating whether the shot is a keeper. |
| [getInstrument()](#getInstrument--) | Gets the musical instruments. |
| [setInstrument(String value)](#setInstrument-java.lang.String-) | Sets the musical instruments. |
| [getIntroTime()](#getIntroTime--) | Gets the duration of lead time for queuing music. |
| [setIntroTime(XmpTime value)](#setIntroTime-com.groupdocs.metadata.core.XmpTime-) | Sets the duration of lead time for queuing music. |
| [getKey()](#getKey--) | Gets the audio\\u2019s musical key. |
| [setKey(String value)](#setKey-java.lang.String-) | Sets the audio\\u2019s musical key. |
| [getLogComment()](#getLogComment--) | Gets the user\\u2019s log comments. |
| [setLogComment(String value)](#setLogComment-java.lang.String-) | Sets the user\\u2019s log comments. |
| [getLoop()](#getLoop--) | Gets a value indicating whether the clip can be looped seamlessly. |
| [setLoop(Boolean value)](#setLoop-java.lang.Boolean-) | Sets a value indicating whether the clip can be looped seamlessly. |
| [getNumberOfBeats()](#getNumberOfBeats--) | Gets the total number of musical beats in a clip; for example, the beats-per-second times the duration in seconds. |
| [setNumberOfBeats(Double value)](#setNumberOfBeats-java.lang.Double-) | Sets the total number of musical beats in a clip; for example, the beats-per-second times the duration in seconds. |
| [getOutCue()](#getOutCue--) | Gets the time at which to fade out. |
| [setOutCue(XmpTime value)](#setOutCue-com.groupdocs.metadata.core.XmpTime-) | Sets the time at which to fade out. |
| [getProjectName()](#getProjectName--) | Gets the name of the project of which this file is a part. |
| [setProjectName(String value)](#setProjectName-java.lang.String-) | Sets the name of the project of which this file is a part. |
| [getRelativeTimestamp()](#getRelativeTimestamp--) | Gets the start time of the media inside the audio project. |
| [setRelativeTimestamp(XmpTime value)](#setRelativeTimestamp-com.groupdocs.metadata.core.XmpTime-) | Sets the start time of the media inside the audio project. |
| [getReleaseDate()](#getReleaseDate--) | Gets the date the title was released. |
| [setReleaseDate(Date value)](#setReleaseDate-java.util.Date-) | Sets the date the title was released. |
| [getShotDate()](#getShotDate--) | Gets the date and time when the video was shot. |
| [setShotDate(Date value)](#setShotDate-java.util.Date-) | Sets the date and time when the video was shot. |
| [getStartTimecode()](#getStartTimecode--) | Gets the timecode of the first frame of video in the file, as obtained from the device control. |
| [setStartTimecode(XmpTimecode value)](#setStartTimecode-com.groupdocs.metadata.core.XmpTimecode-) | Sets the timecode of the first frame of video in the file, as obtained from the device control. |
| [getTakeNumber()](#getTakeNumber--) | Gets a numeric value indicating the absolute number of a take. |
| [setTakeNumber(Integer value)](#setTakeNumber-java.lang.Integer-) | Sets a numeric value indicating the absolute number of a take. |
| [getTempo()](#getTempo--) | Gets the audio\\u2019s tempo. |
| [setTempo(Double value)](#setTempo-java.lang.Double-) | Sets the audio\\u2019s tempo. |
| [getTrackNumber()](#getTrackNumber--) | Gets a numeric value indicating the order of the audio file within its original recording. |
| [setTrackNumber(Integer value)](#setTrackNumber-java.lang.Integer-) | Sets a numeric value indicating the order of the audio file within its original recording. |
| [getVideoAlphaPremultipleColor()](#getVideoAlphaPremultipleColor--) | Gets the timecode of the first frame of video in the file, as obtained from the device control. |
| [setVideoAlphaPremultipleColor(XmpColorantBase value)](#setVideoAlphaPremultipleColor-com.groupdocs.metadata.core.XmpColorantBase-) | Sets the timecode of the first frame of video in the file, as obtained from the device control. |
| [getVideoAlphaUnityIsTransparent()](#getVideoAlphaUnityIsTransparent--) | Gets a value indicating whether the unity is clear. |
| [setVideoAlphaUnityIsTransparent(Boolean value)](#setVideoAlphaUnityIsTransparent-java.lang.Boolean-) | Sets a value indicating whether the unity is clear. |
| [getVideoFrameRate()](#getVideoFrameRate--) | Gets the video frame rate. |
| [setVideoFrameRate(Double value)](#setVideoFrameRate-java.lang.Double-) | Sets the video frame rate. |
| [getVideoFrameSize()](#getVideoFrameSize--) | Gets the frame size. |
| [setVideoFrameSize(XmpDimensions value)](#setVideoFrameSize-com.groupdocs.metadata.core.XmpDimensions-) | Sets the frame size. |
| [getVideoPixelAspectRatio()](#getVideoPixelAspectRatio--) | Gets the aspect ratio, expressed as wd/ht. |
| [setVideoPixelAspectRatio(XmpRational value)](#setVideoPixelAspectRatio-com.groupdocs.metadata.core.XmpRational-) | Sets the aspect ratio, expressed as wd/ht. |
| [getPartOfCompilation()](#getPartOfCompilation--) | Gets a value indicating whether the resource is a part of compilation. |
| [setPartOfCompilation(Boolean value)](#setPartOfCompilation-java.lang.Boolean-) | Sets a value indicating whether the resource is a part of compilation. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
| [set(String name, XmpComplexType value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpComplexType-) | Sets the value inherited from  XmpComplexType  . |
| [setAudioChannelType(XmpAudioChannelType audioChannelType)](#setAudioChannelType-com.groupdocs.metadata.core.XmpAudioChannelType-) | Sets the audio channel type. |
| [setAudioSampleType(XmpAudioSampleType audioSampleType)](#setAudioSampleType-com.groupdocs.metadata.core.XmpAudioSampleType-) | Sets the audio sample type. |
### XmpDynamicMediaPackage() {#XmpDynamicMediaPackage--}
```
public XmpDynamicMediaPackage()
```


Initializes a new instance of the  XmpDynamicMediaPackage  class.

### getAbsPeakAudioFilePath() {#getAbsPeakAudioFilePath--}
```
public final String getAbsPeakAudioFilePath()
```


Gets the absolute path to the file\\u2019s peak audio file.

**Returns:**
java.lang.String - The absolute path to the file\\u2019s peak audio file. If empty, no peak file exists.
### setAbsPeakAudioFilePath(String value) {#setAbsPeakAudioFilePath-java.lang.String-}
```
public final void setAbsPeakAudioFilePath(String value)
```


Sets the absolute path to the file\\u2019s peak audio file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The absolute path to the file\\u2019s peak audio file. If empty, no peak file exists. |

### getAlbum() {#getAlbum--}
```
public final String getAlbum()
```


Gets the name of the album.

**Returns:**
java.lang.String - The name of the album.
### setAlbum(String value) {#setAlbum-java.lang.String-}
```
public final void setAlbum(String value)
```


Sets the name of the album.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the album. |

### getAltTapeName() {#getAltTapeName--}
```
public final String getAltTapeName()
```


Gets the alternative tape name, set via the project window or timecode dialog in Premiere.

**Returns:**
java.lang.String - The alternative tape name, set via the project window or timecode dialog in Premiere.
### setAltTapeName(String value) {#setAltTapeName-java.lang.String-}
```
public final void setAltTapeName(String value)
```


Sets the alternative tape name, set via the project window or timecode dialog in Premiere.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The alternative tape name, set via the project window or timecode dialog in Premiere. |

### getAltTimecode() {#getAltTimecode--}
```
public final XmpTimecode getAltTimecode()
```


Gets the timecode set by the user.

**Returns:**
[XmpTimecode](../../com.groupdocs.metadata.core/xmptimecode) - The timecode set by the user. When specified, it is used instead of the startTimecode.
### setAltTimecode(XmpTimecode value) {#setAltTimecode-com.groupdocs.metadata.core.XmpTimecode-}
```
public final void setAltTimecode(XmpTimecode value)
```


Sets the timecode set by the user.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTimecode](../../com.groupdocs.metadata.core/xmptimecode) | The timecode set by the user. When specified, it is used instead of the startTimecode. |

### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the name of the artist or artists.

**Returns:**
java.lang.String - The name of the artist or artists.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public final void setArtist(String value)
```


Sets the name of the artist or artists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the artist or artists. |

### getAudioChannelType() {#getAudioChannelType--}
```
public final String getAudioChannelType()
```


Gets the audio channel type.

**Returns:**
java.lang.String - The audio channel type. One of: Mono, Stereo, 5.1, 7.1, 16 Channel, Other
### setAudioChannelType(String value) {#setAudioChannelType-java.lang.String-}
```
public final void setAudioChannelType(String value)
```


Sets the audio channel type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The audio channel type. One of: Mono, Stereo, 5.1, 7.1, 16 Channel, Other |

### getAudioCompressor() {#getAudioCompressor--}
```
public final String getAudioCompressor()
```


Gets the audio compression used.

**Returns:**
java.lang.String - The audio compression used. For example, MP3.
### setAudioCompressor(String value) {#setAudioCompressor-java.lang.String-}
```
public final void setAudioCompressor(String value)
```


Sets the audio compression used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The audio compression used. For example, MP3. |

### getAudioSampleRate() {#getAudioSampleRate--}
```
public final Integer getAudioSampleRate()
```


Gets the audio sample rate.

**Returns:**
java.lang.Integer - The audio sample rate. Can be any value, but commonly 32000, 44100, or 48000.
### setAudioSampleRate(Integer value) {#setAudioSampleRate-java.lang.Integer-}
```
public final void setAudioSampleRate(Integer value)
```


Sets the audio sample rate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The audio sample rate. Can be any value, but commonly 32000, 44100, or 48000. |

### getAudioSampleType() {#getAudioSampleType--}
```
public final String getAudioSampleType()
```


Gets the audio sample type.

**Returns:**
java.lang.String - The audio sample type. One of: 8Int, 16Int, 24Int, 32Int, 32Float, Compressed, Packed, Other.
### setAudioSampleType(String value) {#setAudioSampleType-java.lang.String-}
```
public final void setAudioSampleType(String value)
```


Sets the audio sample type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The audio sample type. One of: 8Int, 16Int, 24Int, 32Int, 32Float, Compressed, Packed, Other. |

### getCameraAngle() {#getCameraAngle--}
```
public final String getCameraAngle()
```


Gets the orientation of the camera to the subject in a static shot, from a fixed set of industry standard terminology.

**Returns:**
java.lang.String - The orientation of the camera to the subject in a static shot, from a fixed set of industry standard terminology. Predefined values include: Low Angle, Eye Level, High Angle, Overhead Shot, Birds Eye Shot, Dutch Angle, POV, Over the Shoulder, Reaction Shot.
### setCameraAngle(String value) {#setCameraAngle-java.lang.String-}
```
public final void setCameraAngle(String value)
```


Sets the orientation of the camera to the subject in a static shot, from a fixed set of industry standard terminology.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The orientation of the camera to the subject in a static shot, from a fixed set of industry standard terminology. Predefined values include: Low Angle, Eye Level, High Angle, Overhead Shot, Birds Eye Shot, Dutch Angle, POV, Over the Shoulder, Reaction Shot. |

### getCameraLabel() {#getCameraLabel--}
```
public final String getCameraLabel()
```


Gets the description of the camera used for a shoot.

**Returns:**
java.lang.String - The description of the camera used for a shoot. Can be any string, but is usually simply a number, for example "1", "2", or more explicitly "Camera 1".
### setCameraLabel(String value) {#setCameraLabel-java.lang.String-}
```
public final void setCameraLabel(String value)
```


Sets the description of the camera used for a shoot.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The description of the camera used for a shoot. Can be any string, but is usually simply a number, for example "1", "2", or more explicitly "Camera 1". |

### getCameraModel() {#getCameraModel--}
```
public final String getCameraModel()
```


Gets the make and model of the camera used for a shoot.

**Returns:**
java.lang.String - The make and model of the camera used for a shoot.
### setCameraModel(String value) {#setCameraModel-java.lang.String-}
```
public final void setCameraModel(String value)
```


Sets the make and model of the camera used for a shoot.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The make and model of the camera used for a shoot. |

### getCameraMove() {#getCameraMove--}
```
public final String getCameraMove()
```


Gets the movement of the camera during the shot, from a fixed set of industry standard terminology.

**Returns:**
java.lang.String - The movement of the camera during the shot, from a fixed set of industry standard terminology. Predefined values include: Aerial, Boom Up, Boom Down, Crane Up, Crane Down, Dolly In, Dolly Out, Pan Left, Pan Right, Pedestal Up, Pedestal Down, Tilt Up, Tilt Down, Tracking, Truck Left, Truck Right, Zoom In, Zoom Out.
### setCameraMove(String value) {#setCameraMove-java.lang.String-}
```
public final void setCameraMove(String value)
```


Sets the movement of the camera during the shot, from a fixed set of industry standard terminology.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The movement of the camera during the shot, from a fixed set of industry standard terminology. Predefined values include: Aerial, Boom Up, Boom Down, Crane Up, Crane Down, Dolly In, Dolly Out, Pan Left, Pan Right, Pedestal Up, Pedestal Down, Tilt Up, Tilt Down, Tracking, Truck Left, Truck Right, Zoom In, Zoom Out. |

### getClient() {#getClient--}
```
public final String getClient()
```


Gets the client for the job of which this shot or take is a part.

**Returns:**
java.lang.String - The client for the job of which this shot or take is a part.
### setClient(String value) {#setClient-java.lang.String-}
```
public final void setClient(String value)
```


Sets the client for the job of which this shot or take is a part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The client for the job of which this shot or take is a part. |

### getComment() {#getComment--}
```
public final String getComment()
```


Gets the user\\u2019s comments.

**Returns:**
java.lang.String - The user\\u2019s comments.
### setComment(String value) {#setComment-java.lang.String-}
```
public final void setComment(String value)
```


Sets the user\\u2019s comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The user\\u2019s comments. |

### getComposer() {#getComposer--}
```
public final String getComposer()
```


Gets the composer\\u2019s names.

**Returns:**
java.lang.String - The composer\\u2019s names.
### setComposer(String value) {#setComposer-java.lang.String-}
```
public final void setComposer(String value)
```


Sets the composer\\u2019s names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The composer\\u2019s names. |

### getDirector() {#getDirector--}
```
public final String getDirector()
```


Gets the director of the scene.

**Returns:**
java.lang.String - The director of the scene.
### setDirector(String value) {#setDirector-java.lang.String-}
```
public final void setDirector(String value)
```


Sets the director of the scene.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The director of the scene. |

### getDirectorPhotography() {#getDirectorPhotography--}
```
public final String getDirectorPhotography()
```


Gets the director of photography for the scene.

**Returns:**
java.lang.String - The director of photography for the scene.
### setDirectorPhotography(String value) {#setDirectorPhotography-java.lang.String-}
```
public final void setDirectorPhotography(String value)
```


Sets the director of photography for the scene.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The director of photography for the scene. |

### getDuration() {#getDuration--}
```
public final XmpTime getDuration()
```


Gets the duration of the media file.

**Returns:**
[XmpTime](../../com.groupdocs.metadata.core/xmptime) - The duration of the media file.
### setDuration(XmpTime value) {#setDuration-com.groupdocs.metadata.core.XmpTime-}
```
public final void setDuration(XmpTime value)
```


Sets the duration of the media file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTime](../../com.groupdocs.metadata.core/xmptime) | The duration of the media file. |

### getEngineer() {#getEngineer--}
```
public final String getEngineer()
```


Gets the engineer's names.

**Returns:**
java.lang.String - The engineer's names.
### setEngineer(String value) {#setEngineer-java.lang.String-}
```
public final void setEngineer(String value)
```


Sets the engineer's names.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The engineer's names. |

### getFileDataRate() {#getFileDataRate--}
```
public final XmpRational getFileDataRate()
```


Gets the file data rate in megabytes per second.

**Returns:**
[XmpRational](../../com.groupdocs.metadata.core/xmprational) - The file data rate in megabytes per second. For example: "36/10" = 3.6 MB/sec.
### setFileDataRate(XmpRational value) {#setFileDataRate-com.groupdocs.metadata.core.XmpRational-}
```
public final void setFileDataRate(XmpRational value)
```


Sets the file data rate in megabytes per second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpRational](../../com.groupdocs.metadata.core/xmprational) | The file data rate in megabytes per second. For example: "36/10" = 3.6 MB/sec. |

### getGenre() {#getGenre--}
```
public final String getGenre()
```


Gets the name of the genres.

**Returns:**
java.lang.String - The name of the genres.
### setGenre(String value) {#setGenre-java.lang.String-}
```
public final void setGenre(String value)
```


Sets the name of the genres.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the genres. |

### getGood() {#getGood--}
```
public final Boolean getGood()
```


Gets a value indicating whether the shot is a keeper.

**Returns:**
java.lang.Boolean - A value indicating whether the shot is a keeper.
### setGood(Boolean value) {#setGood-java.lang.Boolean-}
```
public final void setGood(Boolean value)
```


Sets a value indicating whether the shot is a keeper.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | A value indicating whether the shot is a keeper. |

### getInstrument() {#getInstrument--}
```
public final String getInstrument()
```


Gets the musical instruments.

**Returns:**
java.lang.String - The musical instruments.
### setInstrument(String value) {#setInstrument-java.lang.String-}
```
public final void setInstrument(String value)
```


Sets the musical instruments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The musical instruments. |

### getIntroTime() {#getIntroTime--}
```
public final XmpTime getIntroTime()
```


Gets the duration of lead time for queuing music.

**Returns:**
[XmpTime](../../com.groupdocs.metadata.core/xmptime) - The duration of lead time for queuing music.
### setIntroTime(XmpTime value) {#setIntroTime-com.groupdocs.metadata.core.XmpTime-}
```
public final void setIntroTime(XmpTime value)
```


Sets the duration of lead time for queuing music.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTime](../../com.groupdocs.metadata.core/xmptime) | The duration of lead time for queuing music. |

### getKey() {#getKey--}
```
public final String getKey()
```


Gets the audio\\u2019s musical key.

**Returns:**
java.lang.String - The audio\\u2019s musical key. One of: C, C\#, D, D\#, E, F, F\#, G, G\#, A, A\#, B.
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Sets the audio\\u2019s musical key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The audio\\u2019s musical key. One of: C, C\#, D, D\#, E, F, F\#, G, G\#, A, A\#, B. |

### getLogComment() {#getLogComment--}
```
public final String getLogComment()
```


Gets the user\\u2019s log comments.

**Returns:**
java.lang.String - The user\\u2019s log comments.
### setLogComment(String value) {#setLogComment-java.lang.String-}
```
public final void setLogComment(String value)
```


Sets the user\\u2019s log comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The user\\u2019s log comments. |

### getLoop() {#getLoop--}
```
public final Boolean getLoop()
```


Gets a value indicating whether the clip can be looped seamlessly.

**Returns:**
java.lang.Boolean - A value indicating whether the clip can be looped seamlessly.
### setLoop(Boolean value) {#setLoop-java.lang.Boolean-}
```
public final void setLoop(Boolean value)
```


Sets a value indicating whether the clip can be looped seamlessly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | A value indicating whether the clip can be looped seamlessly. |

### getNumberOfBeats() {#getNumberOfBeats--}
```
public final Double getNumberOfBeats()
```


Gets the total number of musical beats in a clip; for example, the beats-per-second times the duration in seconds.

**Returns:**
java.lang.Double - The total number of musical beats in a clip; for example, the beats-per-second times the duration in seconds.
### setNumberOfBeats(Double value) {#setNumberOfBeats-java.lang.Double-}
```
public final void setNumberOfBeats(Double value)
```


Sets the total number of musical beats in a clip; for example, the beats-per-second times the duration in seconds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double | The total number of musical beats in a clip; for example, the beats-per-second times the duration in seconds. |

### getOutCue() {#getOutCue--}
```
public final XmpTime getOutCue()
```


Gets the time at which to fade out.

**Returns:**
[XmpTime](../../com.groupdocs.metadata.core/xmptime) - The time at which to fade out.
### setOutCue(XmpTime value) {#setOutCue-com.groupdocs.metadata.core.XmpTime-}
```
public final void setOutCue(XmpTime value)
```


Sets the time at which to fade out.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTime](../../com.groupdocs.metadata.core/xmptime) | The time at which to fade out. |

### getProjectName() {#getProjectName--}
```
public final String getProjectName()
```


Gets the name of the project of which this file is a part.

**Returns:**
java.lang.String - The name of the project of which this file is a part.
### setProjectName(String value) {#setProjectName-java.lang.String-}
```
public final void setProjectName(String value)
```


Sets the name of the project of which this file is a part.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the project of which this file is a part. |

### getRelativeTimestamp() {#getRelativeTimestamp--}
```
public final XmpTime getRelativeTimestamp()
```


Gets the start time of the media inside the audio project.

**Returns:**
[XmpTime](../../com.groupdocs.metadata.core/xmptime) - The start time of the media inside the audio project.
### setRelativeTimestamp(XmpTime value) {#setRelativeTimestamp-com.groupdocs.metadata.core.XmpTime-}
```
public final void setRelativeTimestamp(XmpTime value)
```


Sets the start time of the media inside the audio project.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTime](../../com.groupdocs.metadata.core/xmptime) | The start time of the media inside the audio project. |

### getReleaseDate() {#getReleaseDate--}
```
public final Date getReleaseDate()
```


Gets the date the title was released.

**Returns:**
java.util.Date - The date the title was released.
### setReleaseDate(Date value) {#setReleaseDate-java.util.Date-}
```
public final void setReleaseDate(Date value)
```


Sets the date the title was released.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date the title was released. |

### getShotDate() {#getShotDate--}
```
public final Date getShotDate()
```


Gets the date and time when the video was shot.

**Returns:**
java.util.Date - The date and time when the video was shot.
### setShotDate(Date value) {#setShotDate-java.util.Date-}
```
public final void setShotDate(Date value)
```


Sets the date and time when the video was shot.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date and time when the video was shot. |

### getStartTimecode() {#getStartTimecode--}
```
public final XmpTimecode getStartTimecode()
```


Gets the timecode of the first frame of video in the file, as obtained from the device control.

**Returns:**
[XmpTimecode](../../com.groupdocs.metadata.core/xmptimecode) - The timecode of the first frame of video in the file, as obtained from the device control.
### setStartTimecode(XmpTimecode value) {#setStartTimecode-com.groupdocs.metadata.core.XmpTimecode-}
```
public final void setStartTimecode(XmpTimecode value)
```


Sets the timecode of the first frame of video in the file, as obtained from the device control.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTimecode](../../com.groupdocs.metadata.core/xmptimecode) | The timecode of the first frame of video in the file, as obtained from the device control. |

### getTakeNumber() {#getTakeNumber--}
```
public final Integer getTakeNumber()
```


Gets a numeric value indicating the absolute number of a take.

**Returns:**
java.lang.Integer - A numeric value indicating the absolute number of a take.
### setTakeNumber(Integer value) {#setTakeNumber-java.lang.Integer-}
```
public final void setTakeNumber(Integer value)
```


Sets a numeric value indicating the absolute number of a take.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | A numeric value indicating the absolute number of a take. |

### getTempo() {#getTempo--}
```
public final Double getTempo()
```


Gets the audio\\u2019s tempo.

**Returns:**
java.lang.Double - The audio\\u2019s tempo.
### setTempo(Double value) {#setTempo-java.lang.Double-}
```
public final void setTempo(Double value)
```


Sets the audio\\u2019s tempo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double | The audio\\u2019s tempo. |

### getTrackNumber() {#getTrackNumber--}
```
public final Integer getTrackNumber()
```


Gets a numeric value indicating the order of the audio file within its original recording.

**Returns:**
java.lang.Integer - A numeric value indicating the order of the audio file within its original recording.
### setTrackNumber(Integer value) {#setTrackNumber-java.lang.Integer-}
```
public final void setTrackNumber(Integer value)
```


Sets a numeric value indicating the order of the audio file within its original recording.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | A numeric value indicating the order of the audio file within its original recording. |

### getVideoAlphaPremultipleColor() {#getVideoAlphaPremultipleColor--}
```
public final XmpColorantBase getVideoAlphaPremultipleColor()
```


Gets the timecode of the first frame of video in the file, as obtained from the device control.

**Returns:**
[XmpColorantBase](../../com.groupdocs.metadata.core/xmpcolorantbase) - The timecode of the first frame of video in the file, as obtained from the device control.
### setVideoAlphaPremultipleColor(XmpColorantBase value) {#setVideoAlphaPremultipleColor-com.groupdocs.metadata.core.XmpColorantBase-}
```
public final void setVideoAlphaPremultipleColor(XmpColorantBase value)
```


Sets the timecode of the first frame of video in the file, as obtained from the device control.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpColorantBase](../../com.groupdocs.metadata.core/xmpcolorantbase) | The timecode of the first frame of video in the file, as obtained from the device control. |

### getVideoAlphaUnityIsTransparent() {#getVideoAlphaUnityIsTransparent--}
```
public final Boolean getVideoAlphaUnityIsTransparent()
```


Gets a value indicating whether the unity is clear.

**Returns:**
java.lang.Boolean -  true , if unity is clear; otherwise, it is opaque.
### setVideoAlphaUnityIsTransparent(Boolean value) {#setVideoAlphaUnityIsTransparent-java.lang.Boolean-}
```
public final void setVideoAlphaUnityIsTransparent(Boolean value)
```


Sets a value indicating whether the unity is clear.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean |  true , if unity is clear; otherwise, it is opaque. |

### getVideoFrameRate() {#getVideoFrameRate--}
```
public final Double getVideoFrameRate()
```


Gets the video frame rate.

**Returns:**
java.lang.Double - The video frame rate.
### setVideoFrameRate(Double value) {#setVideoFrameRate-java.lang.Double-}
```
public final void setVideoFrameRate(Double value)
```


Sets the video frame rate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double | The video frame rate. |

### getVideoFrameSize() {#getVideoFrameSize--}
```
public final XmpDimensions getVideoFrameSize()
```


Gets the frame size.

**Returns:**
[XmpDimensions](../../com.groupdocs.metadata.core/xmpdimensions) - The frame size.
### setVideoFrameSize(XmpDimensions value) {#setVideoFrameSize-com.groupdocs.metadata.core.XmpDimensions-}
```
public final void setVideoFrameSize(XmpDimensions value)
```


Sets the frame size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpDimensions](../../com.groupdocs.metadata.core/xmpdimensions) | The frame size. |

### getVideoPixelAspectRatio() {#getVideoPixelAspectRatio--}
```
public final XmpRational getVideoPixelAspectRatio()
```


Gets the aspect ratio, expressed as wd/ht.

**Returns:**
[XmpRational](../../com.groupdocs.metadata.core/xmprational) - The aspect ratio, expressed as wd/ht.
### setVideoPixelAspectRatio(XmpRational value) {#setVideoPixelAspectRatio-com.groupdocs.metadata.core.XmpRational-}
```
public final void setVideoPixelAspectRatio(XmpRational value)
```


Sets the aspect ratio, expressed as wd/ht.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpRational](../../com.groupdocs.metadata.core/xmprational) | The aspect ratio, expressed as wd/ht. |

### getPartOfCompilation() {#getPartOfCompilation--}
```
public final Boolean getPartOfCompilation()
```


Gets a value indicating whether the resource is a part of compilation.

**Returns:**
java.lang.Boolean - A value indicating whether the resource is a part of compilation.
### setPartOfCompilation(Boolean value) {#setPartOfCompilation-java.lang.Boolean-}
```
public final void setPartOfCompilation(Boolean value)
```


Sets a value indicating whether the resource is a part of compilation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | A value indicating whether the resource is a part of compilation. |

### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public void set(String name, String value)
```


Sets string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | java.lang.String | XMP metadata property value. |

### set(String name, XmpComplexType value) {#set-java.lang.String-com.groupdocs.metadata.core.XmpComplexType-}
```
public void set(String name, XmpComplexType value)
```


Sets the value inherited from  XmpComplexType  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | [XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype) | XMP metadata property value. |

### setAudioChannelType(XmpAudioChannelType audioChannelType) {#setAudioChannelType-com.groupdocs.metadata.core.XmpAudioChannelType-}
```
public final void setAudioChannelType(XmpAudioChannelType audioChannelType)
```


Sets the audio channel type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioChannelType | [XmpAudioChannelType](../../com.groupdocs.metadata.core/xmpaudiochanneltype) | The audio channel type. |

### setAudioSampleType(XmpAudioSampleType audioSampleType) {#setAudioSampleType-com.groupdocs.metadata.core.XmpAudioSampleType-}
```
public final void setAudioSampleType(XmpAudioSampleType audioSampleType)
```


Sets the audio sample type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioSampleType | [XmpAudioSampleType](../../com.groupdocs.metadata.core/xmpaudiosampletype) | The audio sample type. |

