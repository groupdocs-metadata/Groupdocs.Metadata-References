---
title: PdfRootPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the root package allowing working with metadata in a PDF document.
type: docs
weight: 158
url: /java/com.groupdocs.metadata.core/pdfrootpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.RootMetadataPackage](../../com.groupdocs.metadata.core/rootmetadatapackage), com.groupdocs.metadata.core.DocumentRootPackage

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IXmp](../../com.groupdocs.metadata.core/ixmp)
```
public class PdfRootPackage extends DocumentRootPackage<PdfPackage> implements IXmp
```

Represents the root package allowing working with metadata in a PDF document.

**Learn more**

 *  [Working with metadata in PDF documents][]
 *  [Working with XMP metadata][]

This code sample shows how to extract built-in metadata properties from a PDF document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputPdf)) {
>      PdfRootPackage root = metadata.getRootPackageGeneric();
>      System.out.println(root.getDocumentProperties().getAuthor());
>      System.out.println(root.getDocumentProperties().getCreatedDate());
>      System.out.println(root.getDocumentProperties().getSubject());
>      System.out.println(root.getDocumentProperties().getProducer());
>      System.out.println(root.getDocumentProperties().getKeywords());
>      // ...
>  }
>  
> ```
> ```


[Working with metadata in PDF documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PDF+documents
[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
## Methods

| Method | Description |
| --- | --- |
| [getPdfType()](#getPdfType--) | Gets the file type metadata package. |
| [getInspectionPackage()](#getInspectionPackage--) | Gets a metadata package containing inspection results for the document. |
| [getDocumentStatistics()](#getDocumentStatistics--) | Gets the document statistics package. |
| [getXmpPackage()](#getXmpPackage--) | Gets the XMP metadata package. |
| [setXmpPackage(XmpPacketWrapper value)](#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-) | Sets the XMP metadata package. |
### getPdfType() {#getPdfType--}
```
public final PdfTypePackage getPdfType()
```


Gets the file type metadata package.

**Returns:**
[PdfTypePackage](../../com.groupdocs.metadata.core/pdftypepackage) - The file type metadata package.
### getInspectionPackage() {#getInspectionPackage--}
```
public final PdfInspectionPackage getInspectionPackage()
```


Gets a metadata package containing inspection results for the document. The package contains information about document parts that can be considered as metadata in some cases.

**Returns:**
[PdfInspectionPackage](../../com.groupdocs.metadata.core/pdfinspectionpackage) - A metadata package containing inspection results for the document.
### getDocumentStatistics() {#getDocumentStatistics--}
```
public final DocumentStatistics getDocumentStatistics()
```


Gets the document statistics package.

**Returns:**
[DocumentStatistics](../../com.groupdocs.metadata.core/documentstatistics) - The document statistics package.
### getXmpPackage() {#getXmpPackage--}
```
public final XmpPacketWrapper getXmpPackage()
```


Gets the XMP metadata package.

**Returns:**
[XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) - The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata
### setXmpPackage(XmpPacketWrapper value) {#setXmpPackage-com.groupdocs.metadata.core.XmpPacketWrapper-}
```
public final void setXmpPackage(XmpPacketWrapper value)
```


Sets the XMP metadata package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.groupdocs.metadata.core/xmppacketwrapper) | The XMP metadata package.

**Learn more**

 *  [Working with XMP metadata][]


[Working with XMP metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+XMP+metadata |

