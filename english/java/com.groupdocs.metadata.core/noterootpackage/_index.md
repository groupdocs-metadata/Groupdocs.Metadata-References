---
title: NoteRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package intended to work with metadata in an electronic note file.
type: docs
weight: 170
url: /java/com.groupdocs.metadata.core/noterootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public class NoteRootPackage extends RootMetadataPackage
```

Represents the root package intended to work with metadata in an electronic note file.

**Learn more**

 *  [Working with metadata in Note formats][]

This code sample demonstrates how to inspect a note document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputOne)) {
>      NoteRootPackage root = metadata.getRootPackageGeneric();
>      if (root.getInspectionPackage().getPages() != null) {
>          for (NotePage page : root.getInspectionPackage().getPages()) {
>              System.out.println(page.getTitle());
>              System.out.println(page.getAuthor());
>              System.out.println(page.getCreationTime());
>              System.out.println(page.getLastModificationTime());
>          }
>      }
>  }
>  
> ```
> ```


[Working with metadata in Note formats]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Note+formats
## Methods

| Method | Description |
| --- | --- |
| [getInspectionPackage()](#getInspectionPackage--) | Gets a metadata package containing inspection results for the document. |
| [getDocumentStatistics()](#getDocumentStatistics--) | Gets the document statistics package. |
### getInspectionPackage() {#getInspectionPackage--}
```
public final NoteInspectionPackage getInspectionPackage()
```


Gets a metadata package containing inspection results for the document. The package contains information about document parts that can be considered as metadata in some cases.

**Returns:**
[NoteInspectionPackage](../../com.groupdocs.metadata.core/noteinspectionpackage) - A metadata package containing inspection results for the document.
### getDocumentStatistics() {#getDocumentStatistics--}
```
public final DocumentStatistics getDocumentStatistics()
```


Gets the document statistics package.

**Returns:**
[DocumentStatistics](../../com.groupdocs.metadata.core/documentstatistics) - The document statistics package.
