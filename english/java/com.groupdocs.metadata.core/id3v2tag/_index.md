---
title: ID3V2Tag
second_title: GroupDocs.Metadata for Java API Reference
description: Represents an ID3v2 tag.
type: docs
weight: 87
url: /java/com.groupdocs.metadata.core/id3v2tag/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3Tag](../../com.groupdocs.metadata.core/id3tag)
```
public final class ID3V2Tag extends ID3Tag
```

Represents an ID3v2 tag. Please find more information at  [https://en.wikipedia.org/wiki/ID3\#ID3v2][https_en.wikipedia.org_wiki_ID3_ID3v2] .

**Learn more**

 *  [Handling the ID3v2 tag][]

This example shows how to read the ID3v2 tag in an MP3 file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.MP3WithID3V2)) {
>      MP3RootPackage root = metadata.getRootPackageGeneric();
>      if (root.getID3V2() != null) {
>          System.out.println(root.getID3V2().getAlbum());
>          System.out.println(root.getID3V2().getArtist());
>          System.out.println(root.getID3V2().getBand());
>          System.out.println(root.getID3V2().getTitle());
>          System.out.println(root.getID3V2().getComposers());
>          System.out.println(root.getID3V2().getCopyright());
>          System.out.println(root.getID3V2().getPublisher());
>          System.out.println(root.getID3V2().getOriginalAlbum());
>          System.out.println(root.getID3V2().getMusicalKey());
>          if (root.getID3V2().getAttachedPictures() != null) {
>              for (ID3V2AttachedPictureFrame attachedPicture : root.getID3V2().getAttachedPictures()) {
>                  System.out.println(attachedPicture.getAttachedPictureType());
>                  System.out.println(attachedPicture.getMimeType());
>                  System.out.println(attachedPicture.getDescription());
>                  // ...
>              }
>          }
>          // ...
>      }
>  }
>  
> ```
> ```


[https_en.wikipedia.org_wiki_ID3_ID3v2]: https://en.wikipedia.org/wiki/ID3#ID3v2
[Handling the ID3v2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v2+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V2Tag()](#ID3V2Tag--) | Initializes a new instance of the  ID3V2Tag  class. |
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets the ID3 version. |
| [getTagSize()](#getTagSize--) | Gets the size of the tag. |
| [getAlbum()](#getAlbum--) | Gets the Album/Movie/Show title. |
| [setAlbum(String value)](#setAlbum-java.lang.String-) | Sets the Album/Movie/Show title. |
| [getArtist()](#getArtist--) | Gets the Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sets the Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. |
| [getBand()](#getBand--) | Gets the Band/Orchestra/Accompaniment. |
| [setBand(String value)](#setBand-java.lang.String-) | Sets the Band/Orchestra/Accompaniment. |
| [getBitsPerMinute()](#getBitsPerMinute--) | Gets the number of beats per minute in the main part of the audio. |
| [setBitsPerMinute(String value)](#setBitsPerMinute-java.lang.String-) | Sets the number of beats per minute in the main part of the audio. |
| [getComposers()](#getComposers--) | Gets the composers. |
| [setComposers(String value)](#setComposers-java.lang.String-) | Sets the composers. |
| [getContentType()](#getContentType--) | Gets the content type. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Sets the content type. |
| [getCopyright()](#getCopyright--) | Gets the copyright message. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Sets the copyright message. |
| [getDate()](#getDate--) | Gets a numeric string in the DDMM format containing the date for the recording. |
| [setDate(String value)](#setDate-java.lang.String-) | Sets a numeric string in the DDMM format containing the date for the recording. |
| [getEncodedBy()](#getEncodedBy--) | Gets the name of the person or organization that encoded the audio file. |
| [setEncodedBy(String value)](#setEncodedBy-java.lang.String-) | Sets the name of the person or organization that encoded the audio file. |
| [getPublisher()](#getPublisher--) | Gets the name of the label or publisher. |
| [setPublisher(String value)](#setPublisher-java.lang.String-) | Sets the name of the label or publisher. |
| [getTime()](#getTime--) | Gets a numeric string in the HHMM format containing the time for the recording. |
| [setTime(String value)](#setTime-java.lang.String-) | Sets a numeric string in the HHMM format containing the time for the recording. |
| [getTitle()](#getTitle--) | Gets the Title/Song name/Content description. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the Title/Song name/Content description. |
| [getSubtitle()](#getSubtitle--) | Gets the Subtitle/Description refinement. |
| [setSubtitle(String value)](#setSubtitle-java.lang.String-) | Sets the Subtitle/Description refinement. |
| [getMusicalKey()](#getMusicalKey--) | Gets the musical key in which the sound starts. |
| [setMusicalKey(String value)](#setMusicalKey-java.lang.String-) | Sets the musical key in which the sound starts. |
| [getLengthInMilliseconds()](#getLengthInMilliseconds--) | Gets the length of the audio file in milliseconds, represented as a numeric string. |
| [setLengthInMilliseconds(String value)](#setLengthInMilliseconds-java.lang.String-) | Sets the length of the audio file in milliseconds, represented as a numeric string. |
| [getOriginalAlbum()](#getOriginalAlbum--) | Gets the original album/movie/show title. |
| [setOriginalAlbum(String value)](#setOriginalAlbum-java.lang.String-) | Sets the original album/movie/show title. |
| [getTrackNumber()](#getTrackNumber--) | Gets a numeric string containing the order number of the audio-file on its original recording. |
| [setTrackNumber(String value)](#setTrackNumber-java.lang.String-) | Sets a numeric string containing the order number of the audio-file on its original recording. |
| [getSizeInBytes()](#getSizeInBytes--) | Gets the size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. |
| [setSizeInBytes(String value)](#setSizeInBytes-java.lang.String-) | Sets the size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. |
| [getIsrc()](#getIsrc--) | Gets the International Standard Recording Code (ISRC) (12 characters). |
| [setIsrc(String value)](#setIsrc-java.lang.String-) | Sets the International Standard Recording Code (ISRC) (12 characters). |
| [getSoftwareHardware()](#getSoftwareHardware--) | Gets the used audio encoder and its settings when the file was encoded. |
| [setSoftwareHardware(String value)](#setSoftwareHardware-java.lang.String-) | Sets the used audio encoder and its settings when the file was encoded. |
| [getYear()](#getYear--) | Gets a numeric string with a year of the recording. |
| [setYear(String value)](#setYear-java.lang.String-) | Sets a numeric string with a year of the recording. |
| [getComments()](#getComments--) | Gets the user comments. |
| [setComments(ID3V2CommentFrame[] value)](#setComments-com.groupdocs.metadata.core.ID3V2CommentFrame---) | Sets the user comments. |
| [getAttachedPictures()](#getAttachedPictures--) | Gets the attached pictures directly related to the audio file. |
| [setAttachedPictures(ID3V2AttachedPictureFrame[] value)](#setAttachedPictures-com.groupdocs.metadata.core.ID3V2AttachedPictureFrame---) | Sets the attached pictures directly related to the audio file. |
| [getTrackPlayCounter()](#getTrackPlayCounter--) | Gets the number of times the file has been played. |
| [toList()](#toList--) | Creates a list from the package. |
| [removeAttachedPictures()](#removeAttachedPictures--) | Removes all attached pictures stored in APIC frames. |
| [get(String frameId)](#get-java.lang.String-) | Gets an array of frames with the specified id. |
| [set(ID3V2TagFrame frame)](#set-com.groupdocs.metadata.core.ID3V2TagFrame-) | Removes all frames having the same id as the specified one and adds the new frame to the tag. |
| [clear(String frameId)](#clear-java.lang.String-) | Removes all frames with the specified id. |
| [add(ID3V2TagFrame frame)](#add-com.groupdocs.metadata.core.ID3V2TagFrame-) | Adds a frame to the tag. |
| [remove(ID3V2TagFrame frame)](#remove-com.groupdocs.metadata.core.ID3V2TagFrame-) | Removes the specified frame from the tag. |
### ID3V2Tag() {#ID3V2Tag--}
```
public ID3V2Tag()
```


Initializes a new instance of the  ID3V2Tag  class.

### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets the ID3 version.

**Returns:**
java.lang.String - The ID3 version.
### getTagSize() {#getTagSize--}
```
public final int getTagSize()
```


Gets the size of the tag.

**Returns:**
int - The size of the tag.
### getAlbum() {#getAlbum--}
```
public final String getAlbum()
```


Gets the Album/Movie/Show title. This value is represented by the TALB frame.

**Returns:**
java.lang.String - The Album/Movie/Show title.
### setAlbum(String value) {#setAlbum-java.lang.String-}
```
public final void setAlbum(String value)
```


Sets the Album/Movie/Show title. This value is represented by the TALB frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Album/Movie/Show title. |

### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. This value is represented by the TPE1 frame.

**Returns:**
java.lang.String - The Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public final void setArtist(String value)
```


Sets the Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. This value is represented by the TPE1 frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. |

### getBand() {#getBand--}
```
public final String getBand()
```


Gets the Band/Orchestra/Accompaniment. This value is represented by the TPE2 frame.

**Returns:**
java.lang.String - The Band/Orchestra/Accompaniment.
### setBand(String value) {#setBand-java.lang.String-}
```
public final void setBand(String value)
```


Sets the Band/Orchestra/Accompaniment. This value is represented by the TPE2 frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Band/Orchestra/Accompaniment. |

### getBitsPerMinute() {#getBitsPerMinute--}
```
public final String getBitsPerMinute()
```


Gets the number of beats per minute in the main part of the audio. This value is represented by the TBPM frame.

**Returns:**
java.lang.String - The number of beats per minute in the main part of the audio.
### setBitsPerMinute(String value) {#setBitsPerMinute-java.lang.String-}
```
public final void setBitsPerMinute(String value)
```


Sets the number of beats per minute in the main part of the audio. This value is represented by the TBPM frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The number of beats per minute in the main part of the audio. |

### getComposers() {#getComposers--}
```
public final String getComposers()
```


Gets the composers. The names are separated with the "/" character. This value is represented by the TCOM frame.

**Returns:**
java.lang.String - The composers. The names are separated with the "/" character.
### setComposers(String value) {#setComposers-java.lang.String-}
```
public final void setComposers(String value)
```


Sets the composers. The names are separated with the "/" character. This value is represented by the TCOM frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The composers. The names are separated with the "/" character. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Gets the content type. This value is represented by the TCON frame.

**Returns:**
java.lang.String - The content type.
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Sets the content type. This value is represented by the TCON frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The content type. |

### getCopyright() {#getCopyright--}
```
public final String getCopyright()
```


Gets the copyright message. This value is represented by the TCOP frame.

**Returns:**
java.lang.String - The copyright message.

--------------------

Every time this field is displayed the field must be preceded with "Copyright ?? ".
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public final void setCopyright(String value)
```


Sets the copyright message. This value is represented by the TCOP frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The copyright message.

--------------------

Every time this field is displayed the field must be preceded with "Copyright ?? ". |

### getDate() {#getDate--}
```
public final String getDate()
```


Gets a numeric string in the DDMM format containing the date for the recording. This field is always four characters long. This value is represented by the TDAT frame.

**Returns:**
java.lang.String - A numeric string in the DDMM format containing the date for the recording.
### setDate(String value) {#setDate-java.lang.String-}
```
public final void setDate(String value)
```


Sets a numeric string in the DDMM format containing the date for the recording. This field is always four characters long. This value is represented by the TDAT frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A numeric string in the DDMM format containing the date for the recording. |

### getEncodedBy() {#getEncodedBy--}
```
public final String getEncodedBy()
```


Gets the name of the person or organization that encoded the audio file. This value is represented by the TENC frame.

**Returns:**
java.lang.String - The name of the person or organization that encoded the audio file.
### setEncodedBy(String value) {#setEncodedBy-java.lang.String-}
```
public final void setEncodedBy(String value)
```


Sets the name of the person or organization that encoded the audio file. This value is represented by the TENC frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the person or organization that encoded the audio file. |

### getPublisher() {#getPublisher--}
```
public final String getPublisher()
```


Gets the name of the label or publisher. This value is represented by the TPUB frame.

**Returns:**
java.lang.String - The name of the label or publisher.
### setPublisher(String value) {#setPublisher-java.lang.String-}
```
public final void setPublisher(String value)
```


Sets the name of the label or publisher. This value is represented by the TPUB frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the label or publisher. |

### getTime() {#getTime--}
```
public final String getTime()
```


Gets a numeric string in the HHMM format containing the time for the recording. This field is always four characters long. This value is represented by the TIME frame.

**Returns:**
java.lang.String - A numeric string in the HHMM format containing the time for the recording.
### setTime(String value) {#setTime-java.lang.String-}
```
public final void setTime(String value)
```


Sets a numeric string in the HHMM format containing the time for the recording. This field is always four characters long. This value is represented by the TIME frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A numeric string in the HHMM format containing the time for the recording. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the Title/Song name/Content description. This value is represented by the TIT2 frame.

**Returns:**
java.lang.String - The Title/Song name/Content description.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets the Title/Song name/Content description. This value is represented by the TIT2 frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Title/Song name/Content description. |

### getSubtitle() {#getSubtitle--}
```
public final String getSubtitle()
```


Gets the Subtitle/Description refinement. This value is represented by the TIT3 frame.

**Returns:**
java.lang.String - The Subtitle/Description refinement.
### setSubtitle(String value) {#setSubtitle-java.lang.String-}
```
public final void setSubtitle(String value)
```


Sets the Subtitle/Description refinement. This value is represented by the TIT3 frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Subtitle/Description refinement. |

### getMusicalKey() {#getMusicalKey--}
```
public final String getMusicalKey()
```


Gets the musical key in which the sound starts. This value is represented by the TKEY frame.

**Returns:**
java.lang.String - The musical key in which the sound starts.
### setMusicalKey(String value) {#setMusicalKey-java.lang.String-}
```
public final void setMusicalKey(String value)
```


Sets the musical key in which the sound starts. This value is represented by the TKEY frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The musical key in which the sound starts. |

### getLengthInMilliseconds() {#getLengthInMilliseconds--}
```
public final String getLengthInMilliseconds()
```


Gets the length of the audio file in milliseconds, represented as a numeric string. This value is represented by the TLEN frame.

**Returns:**
java.lang.String - The length of the audio file in milliseconds, represented as a numeric string.
### setLengthInMilliseconds(String value) {#setLengthInMilliseconds-java.lang.String-}
```
public final void setLengthInMilliseconds(String value)
```


Sets the length of the audio file in milliseconds, represented as a numeric string. This value is represented by the TLEN frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The length of the audio file in milliseconds, represented as a numeric string. |

### getOriginalAlbum() {#getOriginalAlbum--}
```
public final String getOriginalAlbum()
```


Gets the original album/movie/show title. This value is represented by the TOAL frame.

**Returns:**
java.lang.String - The original album/movie/show title.
### setOriginalAlbum(String value) {#setOriginalAlbum-java.lang.String-}
```
public final void setOriginalAlbum(String value)
```


Sets the original album/movie/show title. This value is represented by the TOAL frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The original album/movie/show title. |

### getTrackNumber() {#getTrackNumber--}
```
public final String getTrackNumber()
```


Gets a numeric string containing the order number of the audio-file on its original recording. This value is represented by the TRCK frame.

**Returns:**
java.lang.String - A numeric string containing the order number of the audio-file on its original recording
### setTrackNumber(String value) {#setTrackNumber-java.lang.String-}
```
public final void setTrackNumber(String value)
```


Sets a numeric string containing the order number of the audio-file on its original recording. This value is represented by the TRCK frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A numeric string containing the order number of the audio-file on its original recording |

### getSizeInBytes() {#getSizeInBytes--}
```
public final String getSizeInBytes()
```


Gets the size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. This value is represented by the TSIZ frame.

**Returns:**
java.lang.String - The size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string.
### setSizeInBytes(String value) {#setSizeInBytes-java.lang.String-}
```
public final void setSizeInBytes(String value)
```


Sets the size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. This value is represented by the TSIZ frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. |

### getIsrc() {#getIsrc--}
```
public final String getIsrc()
```


Gets the International Standard Recording Code (ISRC) (12 characters). This value is represented by the TSRC frame.

**Returns:**
java.lang.String - The International Standard Recording Code (ISRC) (12 characters).
### setIsrc(String value) {#setIsrc-java.lang.String-}
```
public final void setIsrc(String value)
```


Sets the International Standard Recording Code (ISRC) (12 characters). This value is represented by the TSRC frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The International Standard Recording Code (ISRC) (12 characters). |

### getSoftwareHardware() {#getSoftwareHardware--}
```
public final String getSoftwareHardware()
```


Gets the used audio encoder and its settings when the file was encoded. This value is represented by the TSSE frame.

**Returns:**
java.lang.String - The used audio encoder and its settings when the file was encoded.
### setSoftwareHardware(String value) {#setSoftwareHardware-java.lang.String-}
```
public final void setSoftwareHardware(String value)
```


Sets the used audio encoder and its settings when the file was encoded. This value is represented by the TSSE frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The used audio encoder and its settings when the file was encoded. |

### getYear() {#getYear--}
```
public final String getYear()
```


Gets a numeric string with a year of the recording. This frames is always four characters long (until the year 10000). This value is represented by the TYER frame.

**Returns:**
java.lang.String - A numeric string with a year of the recording. This frames is always four characters long (until the year 10000).
### setYear(String value) {#setYear-java.lang.String-}
```
public final void setYear(String value)
```


Sets a numeric string with a year of the recording. This frames is always four characters long (until the year 10000). This value is represented by the TYER frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A numeric string with a year of the recording. This frames is always four characters long (until the year 10000). |

### getComments() {#getComments--}
```
public final ID3V2CommentFrame[] getComments()
```


Gets the user comments. This value is represented by the COMM frame. The frame is intended for any kind of full text information that does not fit in any other frame.

**Returns:**
com.groupdocs.metadata.core.ID3V2CommentFrame[] - The user comments.
### setComments(ID3V2CommentFrame[] value) {#setComments-com.groupdocs.metadata.core.ID3V2CommentFrame---}
```
public final void setComments(ID3V2CommentFrame[] value)
```


Sets the user comments. This value is represented by the COMM frame. The frame is intended for any kind of full text information that does not fit in any other frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ID3V2CommentFrame\[\]](../../com.groupdocs.metadata.core/id3v2commentframe) | The user comments. |

### getAttachedPictures() {#getAttachedPictures--}
```
public final ID3V2AttachedPictureFrame[] getAttachedPictures()
```


Gets the attached pictures directly related to the audio file. This value is represented by the APIC frame.

**Returns:**
com.groupdocs.metadata.core.ID3V2AttachedPictureFrame[] - The attached pictures directly related to the audio file.
### setAttachedPictures(ID3V2AttachedPictureFrame[] value) {#setAttachedPictures-com.groupdocs.metadata.core.ID3V2AttachedPictureFrame---}
```
public final void setAttachedPictures(ID3V2AttachedPictureFrame[] value)
```


Sets the attached pictures directly related to the audio file. This value is represented by the APIC frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ID3V2AttachedPictureFrame\[\]](../../com.groupdocs.metadata.core/id3v2attachedpictureframe) | The attached pictures directly related to the audio file. |

### getTrackPlayCounter() {#getTrackPlayCounter--}
```
public final Long getTrackPlayCounter()
```


Gets the number of times the file has been played. This value is represented by the PCNT frame.

**Returns:**
java.lang.Long - The number of times a file has been played.
### toList() {#toList--}
```
public final IReadOnlyList<ID3V2TagFrame> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list of all frames contained in the ID3v2 tag.
### removeAttachedPictures() {#removeAttachedPictures--}
```
public final void removeAttachedPictures()
```


Removes all attached pictures stored in APIC frames.

### get(String frameId) {#get-java.lang.String-}
```
public final ID3V2TagFrame[] get(String frameId)
```


Gets an array of frames with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameId | java.lang.String | The id of the frames to get. |

**Returns:**
com.groupdocs.metadata.core.ID3V2TagFrame[] - An array of frames with the specified id.
### set(ID3V2TagFrame frame) {#set-com.groupdocs.metadata.core.ID3V2TagFrame-}
```
public final void set(ID3V2TagFrame frame)
```


Removes all frames having the same id as the specified one and adds the new frame to the tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frame | [ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe) | The frame to replace all frames of its kind with. |

### clear(String frameId) {#clear-java.lang.String-}
```
public final void clear(String frameId)
```


Removes all frames with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameId | java.lang.String | The id of the frames to remove. |

### add(ID3V2TagFrame frame) {#add-com.groupdocs.metadata.core.ID3V2TagFrame-}
```
public final void add(ID3V2TagFrame frame)
```


Adds a frame to the tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frame | [ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe) | The frame to be added to the tag. |

### remove(ID3V2TagFrame frame) {#remove-com.groupdocs.metadata.core.ID3V2TagFrame-}
```
public final void remove(ID3V2TagFrame frame)
```


Removes the specified frame from the tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frame | [ID3V2TagFrame](../../com.groupdocs.metadata.core/id3v2tagframe) | The frame to be removed from the tag. |

