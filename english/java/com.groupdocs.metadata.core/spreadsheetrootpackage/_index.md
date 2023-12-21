---
title: SpreadsheetRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a spreadsheet.
type: docs
weight: 230
url: /java/com.groupdocs.metadata.core/spreadsheetrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), com.groupdocs.metadata.core.DocumentRootPackage
```
public class SpreadsheetRootPackage extends DocumentRootPackage<SpreadsheetPackage>
```

Represents the root package allowing working with metadata in a spreadsheet.

**Learn more**

 *  [Working with metadata in Spreadsheets][]

This code snippet demonstrates how to extract built-in metadata properties from a spreadsheet.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputXlsx)) {
>      SpreadsheetRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getDocumentProperties().getAuthor());
>      System.out.println(root.getDocumentProperties().getCreatedTime());
>      System.out.println(root.getDocumentProperties().getCompany());
>      System.out.println(root.getDocumentProperties().getCategory());
>      System.out.println(root.getDocumentProperties().getKeywords());
>      System.out.println(root.getDocumentProperties().getLanguage());
>      System.out.println(root.getDocumentProperties().getContentType());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in Spreadsheets]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Spreadsheets
## Methods

| Method | Description |
| --- | --- |
| [getSpreadsheetType()](#getSpreadsheetType--) | Gets the file type metadata package. |
| [getInspectionPackage()](#getInspectionPackage--) | Gets a metadata package containing inspection results for the document. |
| [getDocumentStatistics()](#getDocumentStatistics--) | Gets the document statistics package. |
### getSpreadsheetType() {#getSpreadsheetType--}
```
public final SpreadsheetTypePackage getSpreadsheetType()
```


Gets the file type metadata package.

**Returns:**
[SpreadsheetTypePackage](../../com.groupdocs.metadata.core/spreadsheettypepackage) - The file type metadata package.
### getInspectionPackage() {#getInspectionPackage--}
```
public final SpreadsheetInspectionPackage getInspectionPackage()
```


Gets a metadata package containing inspection results for the document. The package contains information about document parts that can be considered as metadata in some cases.

**Returns:**
[SpreadsheetInspectionPackage](../../com.groupdocs.metadata.core/spreadsheetinspectionpackage) - A metadata package containing inspection results for the document.
### getDocumentStatistics() {#getDocumentStatistics--}
```
public final DocumentStatistics getDocumentStatistics()
```


Gets the document statistics package.

**Returns:**
[DocumentStatistics](../../com.groupdocs.metadata.core/documentstatistics) - The document statistics package.
