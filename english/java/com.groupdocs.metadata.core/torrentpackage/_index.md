---
title: TorrentPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents torrent descriptor file metadata.
type: docs
weight: 212
url: /java/com.groupdocs.metadata.core/torrentpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class TorrentPackage extends CustomPackage
```

Represents torrent descriptor file metadata. Please find more information at  [https://en.wikipedia.org/wiki/Torrent\_file][https_en.wikipedia.org_wiki_Torrent_file] .

**Learn more**

 *  [Working with TORRENT files][]


[https_en.wikipedia.org_wiki_Torrent_file]: https://en.wikipedia.org/wiki/Torrent_file
[Working with TORRENT files]: https://docs.groupdocs.com/display/metadatajava/Working+with+TORRENT+files
## Methods

| Method | Description |
| --- | --- |
| [getAnnounce()](#getAnnounce--) | Gets the URL of the tracker. |
| [setAnnounce(String value)](#setAnnounce-java.lang.String-) | Sets the URL of the tracker. |
| [getComment()](#getComment--) | Gets the author's comment. |
| [setComment(String value)](#setComment-java.lang.String-) | Sets the author's comment. |
| [getCreationDate()](#getCreationDate--) | Gets the creation date of the torrent. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Sets the creation date of the torrent. |
| [getCreatedBy()](#getCreatedBy--) | Gets the name and version of the program used to create the torrent. |
| [setCreatedBy(String value)](#setCreatedBy-java.lang.String-) | Sets the name and version of the program used to create the torrent. |
| [getSharedFiles()](#getSharedFiles--) | Gets an array containing shared file information entries. |
| [getPieceLength()](#getPieceLength--) | Gets the number of bytes in each piece. |
| [getPieces()](#getPieces--) | Gets a byte array consisting of the concatenation of all 20-byte SHA1 hash values, one per piece. |
### getAnnounce() {#getAnnounce--}
```
public final String getAnnounce()
```


Gets the URL of the tracker.

**Returns:**
java.lang.String - The URL of the tracker.
### setAnnounce(String value) {#setAnnounce-java.lang.String-}
```
public final void setAnnounce(String value)
```


Sets the URL of the tracker.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The URL of the tracker. |

### getComment() {#getComment--}
```
public final String getComment()
```


Gets the author's comment.

**Returns:**
java.lang.String - The author's comment.
### setComment(String value) {#setComment-java.lang.String-}
```
public final void setComment(String value)
```


Sets the author's comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The author's comment. |

### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Gets the creation date of the torrent.

**Returns:**
java.util.Date - The creation date of the torrent.
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


Sets the creation date of the torrent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The creation date of the torrent. |

### getCreatedBy() {#getCreatedBy--}
```
public final String getCreatedBy()
```


Gets the name and version of the program used to create the torrent.

**Returns:**
java.lang.String - The name and version of the program used to create the torrent.
### setCreatedBy(String value) {#setCreatedBy-java.lang.String-}
```
public final void setCreatedBy(String value)
```


Sets the name and version of the program used to create the torrent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name and version of the program used to create the torrent. |

### getSharedFiles() {#getSharedFiles--}
```
public final TorrentSharedFilePackage[] getSharedFiles()
```


Gets an array containing shared file information entries.

**Returns:**
com.groupdocs.metadata.core.TorrentSharedFilePackage[] - An array containing shared file information entries.
### getPieceLength() {#getPieceLength--}
```
public final long getPieceLength()
```


Gets the number of bytes in each piece. For more information please see .

**Returns:**
long - The number of bytes in each piece.
### getPieces() {#getPieces--}
```
public final byte[] getPieces()
```


Gets a byte array consisting of the concatenation of all 20-byte SHA1 hash values, one per piece.

**Returns:**
byte[] - A byte array consisting of the concatenation of all 20-byte SHA1 hash values, one per piece.
