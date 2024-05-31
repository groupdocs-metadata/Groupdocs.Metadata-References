---
title: ID3V1Tag
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents an ID3v1 tag.
type: docs
weight: 111
url: /nodejs-java/com.groupdocs.metadata.core/id3v1tag/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ID3Tag](../../com.groupdocs.metadata.core/id3tag)
```
public final class ID3V1Tag extends ID3Tag
```

Represents an ID3v1 tag. Please find more information at  [https://en.wikipedia.org/wiki/ID3\#ID3v1][https_en.wikipedia.org_wiki_ID3_ID3v1] .

--------------------

ID3(v1) tag is a small chunk of extra data at the end of MP3. Please find more information at  http://id3.org/ID3v1 .

**Learn more**

 *  [Handling the ID3v1 tag][]

This code sample shows how to read the ID3v1 tag in an MP3 file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.MP3WithID3V1)) {
>      MP3RootPackage root = metadata.getRootPackageGeneric();
>      if (root.getID3V1() != null) {
>          System.out.println(root.getID3V1().getAlbum());
>          System.out.println(root.getID3V1().getArtist());
>          System.out.println(root.getID3V1().getTitle());
>          System.out.println(root.getID3V1().getVersion());
>          System.out.println(root.getID3V1().getComment());
>          // ...
>      }
>  }
>  
> ```
> ```


[https_en.wikipedia.org_wiki_ID3_ID3v1]: https://en.wikipedia.org/wiki/ID3#ID3v1
[Handling the ID3v1 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+ID3v1+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [ID3V1Tag()](#ID3V1Tag--) | Initializes a new instance of the  ID3V1Tag  class. |
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets the ID3 version. |
| [getArtist()](#getArtist--) | Gets the artist. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sets the artist. |
| [getAlbum()](#getAlbum--) | Gets the album. |
| [setAlbum(String value)](#setAlbum-java.lang.String-) | Sets the album. |
| [getGenreValue()](#getGenreValue--) | Gets the genre identifier. |
| [getComment()](#getComment--) | Gets the comment. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the comment. |
| [getTitle()](#getTitle--) | Gets the title. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title. |
| [getYear()](#getYear--) | Gets the year. |
| [setYear(String value)](#setYear-java.lang.String-) | Sets the year. |
| [getTrackNumber()](#getTrackNumber--) | Gets the track number. |
| [setTrackNumber(Integer value)](#setTrackNumber-java.lang.Integer-) | Sets the track number. |
### ID3V1Tag() {#ID3V1Tag--}
```
public ID3V1Tag()
```


Initializes a new instance of the  ID3V1Tag  class.

### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets the ID3 version. It can be ID3 or ID3v1.1

**Returns:**
java.lang.String - The ID3 version.
### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the artist. Maximum length is 30 characters.

**Returns:**
java.lang.String - The artist.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public final void setArtist(String value)
```


Sets the artist. Maximum length is 30 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The artist. |

### getAlbum() {#getAlbum--}
```
public final String getAlbum()
```


Gets the album. Maximum length is 30 characters.

**Returns:**
java.lang.String - The album.
### setAlbum(String value) {#setAlbum-java.lang.String-}
```
public final void setAlbum(String value)
```


Sets the album. Maximum length is 30 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The album. |

### getGenreValue() {#getGenreValue--}
```
public final ID3V1Genre getGenreValue()
```


Gets the genre identifier.

**Returns:**
[ID3V1Genre](../../com.groupdocs.metadata.core/id3v1genre) - The genre identifier.
### getComment() {#getComment--}
```
public final String getComment()
```


Gets the comment. Maximum length is 30 characters.

**Returns:**
java.lang.String - The comment.
### setComment(String value) {#setComment-java.lang.String-}
```
public final void setComment(String value)
```


Sets the comment. Maximum length is 30 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The comment. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the title.

**Returns:**
java.lang.String - The title.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets the title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The title. |

### getYear() {#getYear--}
```
public final String getYear()
```


Gets the year. Maximum length is 4 characters.

**Returns:**
java.lang.String - The year.
### setYear(String value) {#setYear-java.lang.String-}
```
public final void setYear(String value)
```


Sets the year. Maximum length is 4 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The year. |

### getTrackNumber() {#getTrackNumber--}
```
public final Integer getTrackNumber()
```


Gets the track number. Presented in a ID3v1.1 tag only.

**Returns:**
java.lang.Integer - The track number.

--------------------

If the value of  TrackNumber  is a positive integer then ID3 changes version to 'ID3v1.1' automatically.
### setTrackNumber(Integer value) {#setTrackNumber-java.lang.Integer-}
```
public final void setTrackNumber(Integer value)
```


Sets the track number. Presented in a ID3v1.1 tag only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The track number.

--------------------

If the value of  TrackNumber  is a positive integer then ID3 changes version to 'ID3v1.1' automatically. |

