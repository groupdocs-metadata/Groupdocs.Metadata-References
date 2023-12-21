---
title: TorrentRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package intended to work with metadata of a TORRENT file.
type: docs
weight: 252
url: /java/com.groupdocs.metadata.core/torrentrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class TorrentRootPackage extends RootMetadataPackage
```

Represents the root package intended to work with metadata of a TORRENT file.

**Learn more**

 *  [Working with TORRENT files][]

This code sample shows how to read metadata of a TORRENT file.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputTorrent)) {
>      TorrentRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getTorrentPackage().getAnnounce());
>      System.out.println(root.getTorrentPackage().getComment());
>      System.out.println(root.getTorrentPackage().getCreatedBy());
>      System.out.println(root.getTorrentPackage().getCreationDate());
>      for (TorrentSharedFilePackage file : root.getTorrentPackage().getSharedFiles()) {
>          System.out.println(file.getName());
>          System.out.println(file.getLength());
>      }
>      // ...
>  }
>  
> ```
> ```


[Working with TORRENT files]: https://docs.groupdocs.com/display/metadatajava/Working+with+TORRENT+files
## Methods

| Method | Description |
| --- | --- |
| [getTorrentPackage()](#getTorrentPackage--) | Gets the TORRENT file metadata package. |
### getTorrentPackage() {#getTorrentPackage--}
```
public final TorrentPackage getTorrentPackage()
```


Gets the TORRENT file metadata package.

**Returns:**
[TorrentPackage](../../com.groupdocs.metadata.core/torrentpackage) - The TORRENT file metadata package.
