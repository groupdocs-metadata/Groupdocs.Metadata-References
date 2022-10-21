---
title: EpubRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in an EPUB e-book.
type: docs
weight: 64
url: /java/com.groupdocs.metadata.core/epubrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IDublinCore](../../com.groupdocs.metadata.core/idublincore)
```
public class EpubRootPackage extends RootMetadataPackage implements IDublinCore
```

Represents the root package allowing working with metadata in an EPUB e-book.

**Learn more**

 *  [Working with metadata in EPUB E-Books][]

This code sample shows how to read EPUB format-specific metadata properties.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputEpub)) {
>      EpubRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getEpubPackage().getVersion());
>      System.out.println(root.getEpubPackage().getUniqueIdentifier());
>      System.out.println(root.getEpubPackage().getImageCover() != null ? root.getEpubPackage().getImageCover().length : 0);
>  }
>  
> ```
> ```


[Working with metadata in EPUB E-Books]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+EPUB+E-Books
## Methods

| Method | Description |
| --- | --- |
| [getEpubPackage()](#getEpubPackage--) | Gets the EPUB metadata package. |
| [getDublinCorePackage()](#getDublinCorePackage--) | Gets the Dublin Core metadata package extracted from the e-book. |
### getEpubPackage() {#getEpubPackage--}
```
public final EpubPackage getEpubPackage()
```


Gets the EPUB metadata package.

**Returns:**
[EpubPackage](../../com.groupdocs.metadata.core/epubpackage) - The EPUB metadata package.
### getDublinCorePackage() {#getDublinCorePackage--}
```
public final DublinCorePackage getDublinCorePackage()
```


Gets the Dublin Core metadata package extracted from the e-book.

**Returns:**
[DublinCorePackage](../../com.groupdocs.metadata.core/dublincorepackage) - The Dublin Core metadata package extracted from the e-book.
