---
title: LyricsTag
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents Lyrics3 v2.00 metadata.
type: docs
weight: 143
url: /nodejs-java/com.groupdocs.metadata.core/lyricstag/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class LyricsTag extends CustomPackage
```

Represents Lyrics3 v2.00 metadata. Please find more information at  http://id3.org/Lyrics3v2 .

--------------------

Lyrics3 v2.00 uses fields to represent information. The data in a field can consist of ASCII characters in the range 01 to 254 according to the standard. As the ASCII character map is only defined from 00 to 128 ISO-8859-1 might be assumed. Numerical fields are 5 or 6 characters long, depending on location, and are padded with zeroes.

**Learn more**

 *  [Handling the Lyrics tag][]

This code sample shows how to read the Lyrics tag from an MP3 file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.MP3WithLyrics)) {
>      MP3RootPackage root = metadata.getRootPackageGeneric();
>      if (root.getLyrics3V2() != null) {
>          System.out.println(root.getLyrics3V2().getLyrics());
>          System.out.println(root.getLyrics3V2().getAlbum());
>          System.out.println(root.getLyrics3V2().getArtist());
>          System.out.println(root.getLyrics3V2().getTrack());
>          // ...
>          // Alternatively, you can loop through a full list of tag fields
>          for (LyricsField field : root.getLyrics3V2().toList()) {
>              System.out.println(String.format("%s = %s", field.getID(), field.getData()));
>          }
>      }
>  }
>  
> ```
> ```


[Handling the Lyrics tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+Lyrics+tag
## Constructors

| Constructor | Description |
| --- | --- |
| [LyricsTag()](#LyricsTag--) | Initializes a new instance of the  LyricsTag  class. |
## Methods

| Method | Description |
| --- | --- |
| [getLyrics()](#getLyrics--) | Gets the lyrics. |
| [setLyrics(String value)](#setLyrics-java.lang.String-) | Sets the lyrics. |
| [getAdditionalInfo()](#getAdditionalInfo--) | Gets the additional information. |
| [setAdditionalInfo(String value)](#setAdditionalInfo-java.lang.String-) | Sets the additional information. |
| [getAuthor()](#getAuthor--) | Gets the author. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the author. |
| [getAlbum()](#getAlbum--) | Gets the album name. |
| [setAlbum(String value)](#setAlbum-java.lang.String-) | Sets the album name. |
| [getArtist()](#getArtist--) | Gets the artist name. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sets the artist name. |
| [getTrack()](#getTrack--) | Gets the track title. |
| [setTrack(String value)](#setTrack-java.lang.String-) | Sets the track title. |
| [set(LyricsField field)](#set-com.groupdocs.metadata.core.LyricsField-) | Adds or replaces the specified Lyrics3 field. |
| [remove(String id)](#remove-java.lang.String-) | Removes the field with the specified id. |
| [get(String id)](#get-java.lang.String-) | Gets the value of the field with the specified id. |
| [toList()](#toList--) | Creates a list from the package. |
### LyricsTag() {#LyricsTag--}
```
public LyricsTag()
```


Initializes a new instance of the  LyricsTag  class.

### getLyrics() {#getLyrics--}
```
public final String getLyrics()
```


Gets the lyrics. This value is represented by the LYR field.

**Returns:**
java.lang.String - The lyrics.
### setLyrics(String value) {#setLyrics-java.lang.String-}
```
public final void setLyrics(String value)
```


Sets the lyrics. This value is represented by the LYR field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The lyrics. |

### getAdditionalInfo() {#getAdditionalInfo--}
```
public final String getAdditionalInfo()
```


Gets the additional information. This value is represented by the INF field.

**Returns:**
java.lang.String - The additional information.

--------------------

This is always three (3) characters long in v2.00, but might be longer in a future standard. The first byte indicates weather or not a lyrics field is present. "1" for present and "0" for otherwise. The second character indicates if there is a timestamp in the lyrics. Again "1" for yes and "0" for no. The third character inhibits tracks for random selection - "1" if inhibited and "0" if not.
### setAdditionalInfo(String value) {#setAdditionalInfo-java.lang.String-}
```
public final void setAdditionalInfo(String value)
```


Sets the additional information. This value is represented by the INF field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The additional information.

--------------------

This is always three (3) characters long in v2.00, but might be longer in a future standard. The first byte indicates weather or not a lyrics field is present. "1" for present and "0" for otherwise. The second character indicates if there is a timestamp in the lyrics. Again "1" for yes and "0" for no. The third character inhibits tracks for random selection - "1" if inhibited and "0" if not. |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the author. This value is represented by the AUT field.

**Returns:**
java.lang.String - The author.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sets the author. This value is represented by the AUT field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The author. |

### getAlbum() {#getAlbum--}
```
public final String getAlbum()
```


Gets the album name. This value is represented by the EAL field.

**Returns:**
java.lang.String - The album.
### setAlbum(String value) {#setAlbum-java.lang.String-}
```
public final void setAlbum(String value)
```


Sets the album name. This value is represented by the EAL field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The album. |

### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the artist name. This value is represented by the EAR field.

**Returns:**
java.lang.String - The artist.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public final void setArtist(String value)
```


Sets the artist name. This value is represented by the EAR field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The artist. |

### getTrack() {#getTrack--}
```
public final String getTrack()
```


Gets the track title. This value is represented by the ETT field.

**Returns:**
java.lang.String - The track.
### setTrack(String value) {#setTrack-java.lang.String-}
```
public final void setTrack(String value)
```


Sets the track title. This value is represented by the ETT field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The track. |

### set(LyricsField field) {#set-com.groupdocs.metadata.core.LyricsField-}
```
public final void set(LyricsField field)
```


Adds or replaces the specified Lyrics3 field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [LyricsField](../../com.groupdocs.metadata.core/lyricsfield) | The field to be set. |

### remove(String id) {#remove-java.lang.String-}
```
public final void remove(String id)
```


Removes the field with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The field identifier. |

### get(String id) {#get-java.lang.String-}
```
public final String get(String id)
```


Gets the value of the field with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The id of the field. |

**Returns:**
java.lang.String - The value if the tag contains a field with the specified id; otherwise, null.
### toList() {#toList--}
```
public final IReadOnlyList<LyricsField> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list of all fields contained in the Lyrics3 tag.
