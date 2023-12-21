---
title: DocumentRootPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents a root package for document formats such as PDF WordProcessing Spreadsheet Presentation etc.
type: docs
weight: 83
url: /java/com.groupdocs.metadata.core/documentrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage)
```
public abstract class DocumentRootPackage<TPackage> extends RootMetadataPackage
```

Represents a root package for document formats such as PDF, WordProcessing, Spreadsheet, Presentation, etc.

 TPackage : The type of the native metadata package.
## Methods

| Method | Description |
| --- | --- |
| [getDocumentProperties()](#getDocumentProperties--) | Gets the native metadata properties presented in the document. |
### getDocumentProperties() {#getDocumentProperties--}
```
public TPackage getDocumentProperties()
```


Gets the native metadata properties presented in the document.

**Returns:**
TPackage - The document properties.
