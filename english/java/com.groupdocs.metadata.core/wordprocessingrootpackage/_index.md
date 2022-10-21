---
title: WordProcessingRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a word processing document.
type: docs
weight: 246
url: /java/com.groupdocs.metadata.core/wordprocessingrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), com.groupdocs.metadata.core.DocumentRootPackage

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IDublinCore](../../com.groupdocs.metadata.core/idublincore)
```
public class WordProcessingRootPackage extends DocumentRootPackage<WordProcessingPackage> implements IDublinCore
```

Represents the root package allowing working with metadata in a word processing document.

**Learn more**

 *  [Working with metadata in WordProcessing documents][]

This code sample demonstrates how to read built-in metadata properties of a WordProcessing document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputDocx)) {
>      WordProcessingRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getDocumentProperties().getAuthor());
>      System.out.println(root.getDocumentProperties().getCreatedTime());
>      System.out.println(root.getDocumentProperties().getCompany());
>      System.out.println(root.getDocumentProperties().getCategory());
>      System.out.println(root.getDocumentProperties().getKeywords());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in WordProcessing documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Word+Processing+documents
## Methods

| Method | Description |
| --- | --- |
| [getWordProcessingType()](#getWordProcessingType--) | Gets the file type metadata package. |
| [getDublinCorePackage()](#getDublinCorePackage--) | Gets the Dublin Core metadata package extracted from the document. |
| [getInspectionPackage()](#getInspectionPackage--) | Gets a metadata package containing inspection results for the document. |
| [getDocumentStatistics()](#getDocumentStatistics--) | Gets the document statistics package. |
| [updateDocumentStatistics()](#updateDocumentStatistics--) | Recalculates count of pages, paragraphs, words, lines, characters in the document and updates appropriate metadata packages. |
### getWordProcessingType() {#getWordProcessingType--}
```
public final WordProcessingTypePackage getWordProcessingType()
```


Gets the file type metadata package.

**Returns:**
[WordProcessingTypePackage](../../com.groupdocs.metadata.core/wordprocessingtypepackage) - The file type metadata package.
### getDublinCorePackage() {#getDublinCorePackage--}
```
public final DublinCorePackage getDublinCorePackage()
```


Gets the Dublin Core metadata package extracted from the document.

**Returns:**
[DublinCorePackage](../../com.groupdocs.metadata.core/dublincorepackage) - The Dublin Core metadata package extracted from the document.
### getInspectionPackage() {#getInspectionPackage--}
```
public final WordProcessingInspectionPackage getInspectionPackage()
```


Gets a metadata package containing inspection results for the document. The package contains information about document parts that can be considered as metadata in some cases.

**Returns:**
[WordProcessingInspectionPackage](../../com.groupdocs.metadata.core/wordprocessinginspectionpackage) - A metadata package containing inspection results for the document.
### getDocumentStatistics() {#getDocumentStatistics--}
```
public final DocumentStatistics getDocumentStatistics()
```


Gets the document statistics package.

**Returns:**
[DocumentStatistics](../../com.groupdocs.metadata.core/documentstatistics) - The document statistics package.
### updateDocumentStatistics() {#updateDocumentStatistics--}
```
public final void updateDocumentStatistics()
```


Recalculates count of pages, paragraphs, words, lines, characters in the document and updates appropriate metadata packages.

