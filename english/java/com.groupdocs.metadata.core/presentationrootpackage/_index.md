---
title: PresentationRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents the root package intended to work with metadata in a presentation.
type: docs
weight: 200
url: /java/com.groupdocs.metadata.core/presentationrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), com.groupdocs.metadata.core.DocumentRootPackage
```
public class PresentationRootPackage extends DocumentRootPackage<PresentationPackage>
```

Represents the root package intended to work with metadata in a presentation.

**Learn more**

 *  [Working with metadata in Presentations][]

This example shows how to extract built-in metadata properties from a presentation.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputPpt)) {
>      PresentationRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getDocumentProperties().getAuthor());
>      System.out.println(root.getDocumentProperties().getCreatedTime());
>      System.out.println(root.getDocumentProperties().getCompany());
>      System.out.println(root.getDocumentProperties().getCategory());
>      System.out.println(root.getDocumentProperties().getKeywords());
>      System.out.println(root.getDocumentProperties().getLastPrintedDate());
>      System.out.println(root.getDocumentProperties().getNameOfApplication());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in Presentations]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Presentations
## Methods

| Method | Description |
| --- | --- |
| [getPresentationType()](#getPresentationType--) | Gets the file type metadata package. |
| [getInspectionPackage()](#getInspectionPackage--) | Gets a metadata package containing inspection results for the document. |
| [getDocumentStatistics()](#getDocumentStatistics--) | Gets the document statistics package. |
### getPresentationType() {#getPresentationType--}
```
public final PresentationTypePackage getPresentationType()
```


Gets the file type metadata package.

**Returns:**
[PresentationTypePackage](../../com.groupdocs.metadata.core/presentationtypepackage) - The file type metadata package.
### getInspectionPackage() {#getInspectionPackage--}
```
public final PresentationInspectionPackage getInspectionPackage()
```


Gets a metadata package containing inspection results for the document. The package contains information about document parts that can be considered as metadata in some cases.

**Returns:**
[PresentationInspectionPackage](../../com.groupdocs.metadata.core/presentationinspectionpackage) - A metadata package containing inspection results for the document.
### getDocumentStatistics() {#getDocumentStatistics--}
```
public final DocumentStatistics getDocumentStatistics()
```


Gets the document statistics package.

**Returns:**
[DocumentStatistics](../../com.groupdocs.metadata.core/documentstatistics) - The document statistics package.
