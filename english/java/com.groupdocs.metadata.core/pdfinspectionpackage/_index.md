---
title: PdfInspectionPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Contains information about PDF document parts that can be considered as metadata in some cases.
type: docs
weight: 188
url: /java/com.groupdocs.metadata.core/pdfinspectionpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class PdfInspectionPackage extends CustomPackage
```

Contains information about PDF document parts that can be considered as metadata in some cases.

**Learn more**

 *  [Working with metadata in PDF documents][]


[Working with metadata in PDF documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PDF+documents
## Methods

| Method | Description |
| --- | --- |
| [getAnnotations()](#getAnnotations--) | Gets an array of the annotations. |
| [getAttachments()](#getAttachments--) | Gets an array of the attachments. |
| [getBookmarks()](#getBookmarks--) | Gets an array of the bookmarks. |
| [getFields()](#getFields--) | Gets an array of the form fields. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gets an array of the digital signatures. |
| [removeProperties(Specification specification)](#removeProperties-com.groupdocs.metadata.search.Specification-) | Removes metadata properties satisfying a specification. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
| [clearAnnotations()](#clearAnnotations--) | Removes all detected annotations from the document. |
| [clearAttachments()](#clearAttachments--) | Removes all detected attachments from the document. |
| [clearBookmarks()](#clearBookmarks--) | Removes all detected bookmarks from the document. |
| [clearFields()](#clearFields--) | Removes all detected form fields from the document. |
| [clearDigitalSignatures()](#clearDigitalSignatures--) | Removes all detected digital signatures from the document. |
### getAnnotations() {#getAnnotations--}
```
public final PdfAnnotation[] getAnnotations()
```


Gets an array of the annotations.

**Returns:**
com.groupdocs.metadata.core.PdfAnnotation[] - An array of the annotations.
### getAttachments() {#getAttachments--}
```
public final PdfAttachment[] getAttachments()
```


Gets an array of the attachments.

**Returns:**
com.groupdocs.metadata.core.PdfAttachment[] - An array of the attachments.
### getBookmarks() {#getBookmarks--}
```
public final PdfBookmark[] getBookmarks()
```


Gets an array of the bookmarks.

**Returns:**
com.groupdocs.metadata.core.PdfBookmark[] - An array of the bookmarks.
### getFields() {#getFields--}
```
public final PdfFormField[] getFields()
```


Gets an array of the form fields.

**Returns:**
com.groupdocs.metadata.core.PdfFormField[] - An array of the form fields.
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final DigitalSignature[] getDigitalSignatures()
```


Gets an array of the digital signatures.

**Returns:**
com.groupdocs.metadata.core.DigitalSignature[] - An array of the digital signatures.
### removeProperties(Specification specification) {#removeProperties-com.groupdocs.metadata.search.Specification-}
```
public int removeProperties(Specification specification)
```


Removes metadata properties satisfying a specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to test each metadata property for a condition. |

**Returns:**
int - The number of affected properties.
### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.
### clearAnnotations() {#clearAnnotations--}
```
public final void clearAnnotations()
```


Removes all detected annotations from the document.

### clearAttachments() {#clearAttachments--}
```
public final void clearAttachments()
```


Removes all detected attachments from the document.

### clearBookmarks() {#clearBookmarks--}
```
public final void clearBookmarks()
```


Removes all detected bookmarks from the document.

### clearFields() {#clearFields--}
```
public final void clearFields()
```


Removes all detected form fields from the document.

### clearDigitalSignatures() {#clearDigitalSignatures--}
```
public final void clearDigitalSignatures()
```


Removes all detected digital signatures from the document.

