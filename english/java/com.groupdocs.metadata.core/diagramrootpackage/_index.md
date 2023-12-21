---
title: DiagramRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package intended to work with metadata in a diagram.
type: docs
weight: 71
url: /java/com.groupdocs.metadata.core/diagramrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), com.groupdocs.metadata.core.DocumentRootPackage
```
public class DiagramRootPackage extends DocumentRootPackage<DiagramPackage>
```

Represents the root package intended to work with metadata in a diagram.

**Learn more**

 *  [Working with metadata in Diagrams][]

This code sample demonstrates how to extract built-in metadata properties from a diagram.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputVsdx)) {
>      DiagramRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getDocumentProperties().getCreator());
>      System.out.println(root.getDocumentProperties().getCompany());
>      System.out.println(root.getDocumentProperties().getKeywords());
>      System.out.println(root.getDocumentProperties().getLanguage());
>      System.out.println(root.getDocumentProperties().getTimeCreated());
>      System.out.println(root.getDocumentProperties().getCategory());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in Diagrams]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Diagrams
## Methods

| Method | Description |
| --- | --- |
| [getDiagramType()](#getDiagramType--) | Gets the file type metadata package. |
| [getDocumentStatistics()](#getDocumentStatistics--) | Gets the document statistics package. |
### getDiagramType() {#getDiagramType--}
```
public final DiagramTypePackage getDiagramType()
```


Gets the file type metadata package.

**Returns:**
[DiagramTypePackage](../../com.groupdocs.metadata.core/diagramtypepackage) - The file type metadata package.
### getDocumentStatistics() {#getDocumentStatistics--}
```
public final DocumentStatistics getDocumentStatistics()
```


Gets the document statistics package.

**Returns:**
[DocumentStatistics](../../com.groupdocs.metadata.core/documentstatistics) - The document statistics package.
