---
title: TorrentSharedFilePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents shared file information.
type: docs
weight: 253
url: /java/com.groupdocs.metadata.core/torrentsharedfilepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class TorrentSharedFilePackage extends CustomPackage
```

Represents shared file information. Contains detailed info about each file in a torrent distribution.

**Learn more**

 *  [Working with TORRENT files][]


[Working with TORRENT files]: https://docs.groupdocs.com/display/metadatajava/Working+with+TORRENT+files
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the full name of the file (relative path to the file from the root torrent folder). |
| [getLength()](#getLength--) | Gets the length of the file in bytes. |
### getName() {#getName--}
```
public final String getName()
```


Gets the full name of the file (relative path to the file from the root torrent folder).

**Returns:**
java.lang.String - The full name of the file (relative path to the file from the root torrent folder).
### getLength() {#getLength--}
```
public final long getLength()
```


Gets the length of the file in bytes.

**Returns:**
long - The length of the file in bytes.
