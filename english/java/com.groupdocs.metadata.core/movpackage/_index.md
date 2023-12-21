---
title: MovPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents QuickTime metadata.
type: docs
weight: 162
url: /java/com.groupdocs.metadata.core/movpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class MovPackage extends CustomPackage
```

Represents QuickTime metadata.

**Learn more**

 *  [Working with metadata in MOV Files][]


[Working with metadata in MOV Files]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+MOV+Files
## Methods

| Method | Description |
| --- | --- |
| [getDirector()](#getDirector--) | Name of the director of the movie content. |
| [getDescription()](#getDescription--) | Description of the movie file content. |
| [getLocationMotion()](#getLocationMotion--) | An indication of the direction the camera is moving during the shot. |
| [getLocationFacing()](#getLocationFacing--) | An indication of the direction the camera is facing during the shot. |
| [getLocationDate()](#getLocationDate--) | A date and time, stored using the extended format defined in ISO 8601:2004- Data elements and interchange format. |
| [getLocationRole()](#getLocationRole--) | A single byte, binary value containing a value from the set: 0 indicates \\u201cshooting location\\u201d, 1 indicates \\u201creal location\\u201d, 2 indicates \\u201cfictional location\\u201d. |
| [getLocationNote()](#getLocationNote--) | Descriptive comment. |
| [getLocationBody()](#getLocationBody--) | The astronomical body, for compatibility with the 3GPP format |
| [getLocationName()](#getLocationName--) | Name of the location. |
| [getUserRatings()](#getUserRatings--) | A number, assigned by the user, that indicates the rating or relative value of the movie. |
| [getUsers()](#getUsers--) | A name indicating a user-defined collection that includes this movie. |
| [getYear()](#getYear--) | Year when the movie file or the original content was created or recorded. |
| [getSoftware()](#getSoftware--) | Name of software used to create the movie file content. |
| [getProducer()](#getProducer--) | Name of producer of movie file content. |
| [getAlbum()](#getAlbum--) | Album or collection name of which the movie content forms a part |
| [getKeywords()](#getKeywords--) | Keywords associated with the movie file content. |
| [getInformation()](#getInformation--) | Information about the movie file content. |
| [getGenre()](#getGenre--) | Text describing the genre or genres to which the movie content conforms. |
| [getTitle()](#getTitle--) | The title of the movie file content. |
| [getCreationDate()](#getCreationDate--) | The date the movie file content was created. |
| [getCopyright()](#getCopyright--) | Copyright statement for the movie file content. |
| [getComment()](#getComment--) | User entered comment regarding the movie file content. |
| [getAuthor()](#getAuthor--) | Name of the author of the movie file content. |
| [getArtwork()](#getArtwork--) | A single image that can represent the movie file content. |
| [getArtist()](#getArtist--) | Name of the artist who created the movie file content. |
| [getPublisher()](#getPublisher--) | Name of publisher of movie file content. |
| [getMovieCreationTime()](#getMovieCreationTime--) | A 32-bit integer that specifies the creation calendar date and time for the movie atom. |
| [setMovieCreationTime(System.DateTime value)](#setMovieCreationTime-com.aspose.ms.System.DateTime-) | A 32-bit integer that specifies the creation calendar date and time for the movie atom. |
| [getMovieModificationTime()](#getMovieModificationTime--) | A 32-bit integer that specifies the calendar date and time of the last change to the movie atom. |
| [setMovieModificationTime(System.DateTime value)](#setMovieModificationTime-com.aspose.ms.System.DateTime-) | A 32-bit integer that specifies the calendar date and time of the last change to the movie atom. |
| [getMovieDuration()](#getMovieDuration--) | A time value that indicates the duration of the movie in seconds. |
| [getAtoms()](#getAtoms--) | Gets an array of [MovAtom](../../com.groupdocs.metadata.core/movatom) atoms. |
### getDirector() {#getDirector--}
```
public final String getDirector()
```


Name of the director of the movie content.

Value: The Director.

**Returns:**
java.lang.String
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Description of the movie file content.

Value: The Description.

**Returns:**
java.lang.String
### getLocationMotion() {#getLocationMotion--}
```
public final String getLocationMotion()
```


An indication of the direction the camera is moving during the shot.

Value: The LocationMotion.

**Returns:**
java.lang.String
### getLocationFacing() {#getLocationFacing--}
```
public final String getLocationFacing()
```


An indication of the direction the camera is facing during the shot.

Value: The LocationFacing.

**Returns:**
java.lang.String
### getLocationDate() {#getLocationDate--}
```
public final String getLocationDate()
```


A date and time, stored using the extended format defined in ISO 8601:2004- Data elements and interchange format.

Value: The LocationDate.

**Returns:**
java.lang.String
### getLocationRole() {#getLocationRole--}
```
public final String getLocationRole()
```


A single byte, binary value containing a value from the set: 0 indicates \\u201cshooting location\\u201d, 1 indicates \\u201creal location\\u201d, 2 indicates \\u201cfictional location\\u201d. Other values are reserved.

Value: The LocationRole.

**Returns:**
java.lang.String
### getLocationNote() {#getLocationNote--}
```
public final String getLocationNote()
```


Descriptive comment.

Value: The LocationNote.

**Returns:**
java.lang.String
### getLocationBody() {#getLocationBody--}
```
public final String getLocationBody()
```


The astronomical body, for compatibility with the 3GPP format

Value: The LocationBody.

**Returns:**
java.lang.String
### getLocationName() {#getLocationName--}
```
public final String getLocationName()
```


Name of the location.

Value: The LocationName.

**Returns:**
java.lang.String
### getUserRatings() {#getUserRatings--}
```
public final String getUserRatings()
```


A number, assigned by the user, that indicates the rating or relative value of the movie. This number can range from 0.0 to 5.0. A value of 0.0 indicates that the user has not rated the movie.

Value: The UserRatings.

**Returns:**
java.lang.String
### getUsers() {#getUsers--}
```
public final String getUsers()
```


A name indicating a user-defined collection that includes this movie.

Value: The Users.

**Returns:**
java.lang.String
### getYear() {#getYear--}
```
public final String getYear()
```


Year when the movie file or the original content was created or recorded.

Value: The Year.

**Returns:**
java.lang.String
### getSoftware() {#getSoftware--}
```
public final String getSoftware()
```


Name of software used to create the movie file content.

Value: The Software.

**Returns:**
java.lang.String
### getProducer() {#getProducer--}
```
public final String getProducer()
```


Name of producer of movie file content.

Value: The Producer.

**Returns:**
java.lang.String
### getAlbum() {#getAlbum--}
```
public final String getAlbum()
```


Album or collection name of which the movie content forms a part

Value: The Album.

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Keywords associated with the movie file content.

Value: The Keywords.

**Returns:**
java.lang.String
### getInformation() {#getInformation--}
```
public final String getInformation()
```


Information about the movie file content.

Value: The Information.

**Returns:**
java.lang.String
### getGenre() {#getGenre--}
```
public final String getGenre()
```


Text describing the genre or genres to which the movie content conforms.

Value: The Genre.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public final String getTitle()
```


The title of the movie file content.

Value: The Title.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public final String getCreationDate()
```


The date the movie file content was created.

Value: The CreationDate.

**Returns:**
java.lang.String
### getCopyright() {#getCopyright--}
```
public final String getCopyright()
```


Copyright statement for the movie file content.

Value: The Copyright.

**Returns:**
java.lang.String
### getComment() {#getComment--}
```
public final String getComment()
```


User entered comment regarding the movie file content.

Value: The Comment.

**Returns:**
java.lang.String
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Name of the author of the movie file content.

Value: The Author.

**Returns:**
java.lang.String
### getArtwork() {#getArtwork--}
```
public final String getArtwork()
```


A single image that can represent the movie file content.

Value: The Artwork.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public final String getArtist()
```


Name of the artist who created the movie file content.

Value: The Artist.

**Returns:**
java.lang.String
### getPublisher() {#getPublisher--}
```
public final String getPublisher()
```


Name of publisher of movie file content.

Value: The Publisher.

**Returns:**
java.lang.String
### getMovieCreationTime() {#getMovieCreationTime--}
```
public final System.DateTime getMovieCreationTime()
```


A 32-bit integer that specifies the creation calendar date and time for the movie atom.

Value: A 32-bit integer that specifies the creation calendar date and time for the movie atom.

**Returns:**
com.aspose.ms.System.DateTime
### setMovieCreationTime(System.DateTime value) {#setMovieCreationTime-com.aspose.ms.System.DateTime-}
```
public final void setMovieCreationTime(System.DateTime value)
```


A 32-bit integer that specifies the creation calendar date and time for the movie atom.

Value: A 32-bit integer that specifies the creation calendar date and time for the movie atom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

### getMovieModificationTime() {#getMovieModificationTime--}
```
public final System.DateTime getMovieModificationTime()
```


A 32-bit integer that specifies the calendar date and time of the last change to the movie atom.

Value: A 32-bit integer that specifies the calendar date and time of the last change to the movie atom.

**Returns:**
com.aspose.ms.System.DateTime
### setMovieModificationTime(System.DateTime value) {#setMovieModificationTime-com.aspose.ms.System.DateTime-}
```
public final void setMovieModificationTime(System.DateTime value)
```


A 32-bit integer that specifies the calendar date and time of the last change to the movie atom.

Value: A 32-bit integer that specifies the calendar date and time of the last change to the movie atom.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

### getMovieDuration() {#getMovieDuration--}
```
public final long getMovieDuration()
```


A time value that indicates the duration of the movie in seconds.

Value: A time value that indicates the duration of the movie in seconds.

**Returns:**
long
### getAtoms() {#getAtoms--}
```
public final MovAtom[] getAtoms()
```


Gets an array of [MovAtom](../../com.groupdocs.metadata.core/movatom) atoms.

Value: The QuickTime atoms.

**Returns:**
com.groupdocs.metadata.core.MovAtom[]
