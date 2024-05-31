---
title: ApePackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents an APE v2 metadata package.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.metadata.core/apepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class ApePackage extends CustomPackage
```

Represents an APE v2 metadata package. Please find more information at  [http://wiki.hydrogenaud.io/index.php?title=APE\_key][http_wiki.hydrogenaud.io_index.php_title_APE_key] .

**Learn more**

 *  [Handling the APEv2 tag][]

This example demonstrates how to read the APEv2 tag in an MP3 file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.MP3WithApe)) {
>      MP3RootPackage root = metadata.getRootPackageGeneric();
>      if (root.getApeV2() != null) {
>          System.out.println(root.getApeV2().getAlbum());
>          System.out.println(root.getApeV2().getTitle());
>          System.out.println(root.getApeV2().getArtist());
>          System.out.println(root.getApeV2().getComposer());
>          System.out.println(root.getApeV2().getCopyright());
>          System.out.println(root.getApeV2().getGenre());
>          System.out.println(root.getApeV2().getLanguage());
>          // ...
>      }
>  }
>  
> ```
> ```


[http_wiki.hydrogenaud.io_index.php_title_APE_key]: http://wiki.hydrogenaud.io/index.php?title=APE_key
[Handling the APEv2 tag]: https://docs.groupdocs.com/display/metadatajava/Handling+the+APEv2+tag
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets the title. |
| [getSubtitle()](#getSubtitle--) | Gets the subtitle. |
| [getArtist()](#getArtist--) | Gets the artist. |
| [getAlbum()](#getAlbum--) | Gets the album. |
| [getDebutAlbum()](#getDebutAlbum--) | Gets the debut album. |
| [getPublisher()](#getPublisher--) | Gets the publisher. |
| [getConductor()](#getConductor--) | Gets the conductor. |
| [getTrack()](#getTrack--) | Gets the track number. |
| [getComposer()](#getComposer--) | Gets the composer. |
| [getComment()](#getComment--) | Gets the comment. |
| [getCopyright()](#getCopyright--) | Gets the copyright. |
| [getPublicationRight()](#getPublicationRight--) | Gets the publication right. |
| [getFile()](#getFile--) | Gets the file. |
| [getIsbn()](#getIsbn--) | Gets the ISBN number with check digit. |
| [getRecordLocation()](#getRecordLocation--) | Gets the record location. |
| [getGenre()](#getGenre--) | Gets the genre. |
| [getIsrc()](#getIsrc--) | Gets the International Standard Recording Number. |
| [getAbstract()](#getAbstract--) | Gets the abstract link. |
| [getLanguage()](#getLanguage--) | Gets the language. |
| [getBibliography()](#getBibliography--) | Gets the bibliography. |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the title.

**Returns:**
java.lang.String - The title.
### getSubtitle() {#getSubtitle--}
```
public final String getSubtitle()
```


Gets the subtitle.

**Returns:**
java.lang.String - The subtitle.
### getArtist() {#getArtist--}
```
public final String getArtist()
```


Gets the artist.

**Returns:**
java.lang.String - The artist.
### getAlbum() {#getAlbum--}
```
public final String getAlbum()
```


Gets the album.

**Returns:**
java.lang.String - The album.
### getDebutAlbum() {#getDebutAlbum--}
```
public final String getDebutAlbum()
```


Gets the debut album.

**Returns:**
java.lang.String - The debut album.
### getPublisher() {#getPublisher--}
```
public final String getPublisher()
```


Gets the publisher.

**Returns:**
java.lang.String - The publisher.
### getConductor() {#getConductor--}
```
public final String getConductor()
```


Gets the conductor.

**Returns:**
java.lang.String - The conductor.
### getTrack() {#getTrack--}
```
public final Integer getTrack()
```


Gets the track number.

**Returns:**
java.lang.Integer - The track number.
### getComposer() {#getComposer--}
```
public final String getComposer()
```


Gets the composer.

**Returns:**
java.lang.String - The composer.
### getComment() {#getComment--}
```
public final String getComment()
```


Gets the comment.

**Returns:**
java.lang.String - The comment.
### getCopyright() {#getCopyright--}
```
public final String getCopyright()
```


Gets the copyright.

**Returns:**
java.lang.String - The copyright.
### getPublicationRight() {#getPublicationRight--}
```
public final String getPublicationRight()
```


Gets the publication right.

**Returns:**
java.lang.String - The publication right.
### getFile() {#getFile--}
```
public final String getFile()
```


Gets the file.

**Returns:**
java.lang.String - The file.
### getIsbn() {#getIsbn--}
```
public final String getIsbn()
```


Gets the ISBN number with check digit. See more: https://en.wikipedia.org/wiki/International\_Standard\_Book\_Number.

**Returns:**
java.lang.String - The ISBN number.
### getRecordLocation() {#getRecordLocation--}
```
public final String getRecordLocation()
```


Gets the record location.

**Returns:**
java.lang.String - The record location.
### getGenre() {#getGenre--}
```
public final String getGenre()
```


Gets the genre.

**Returns:**
java.lang.String - The genre.
### getIsrc() {#getIsrc--}
```
public final String getIsrc()
```


Gets the International Standard Recording Number.

**Returns:**
java.lang.String - The International Standard Recording Number.
### getAbstract() {#getAbstract--}
```
public final String getAbstract()
```


Gets the abstract link.

**Returns:**
java.lang.String - The abstract link.
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the language.

**Returns:**
java.lang.String - The language.
### getBibliography() {#getBibliography--}
```
public final String getBibliography()
```


Gets the bibliography.

**Returns:**
java.lang.String - The bibliography.
