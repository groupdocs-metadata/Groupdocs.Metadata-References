---
title: WordProcessingInspectionPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Contains information about document parts that can be considered as metadata in some cases.
type: docs
weight: 291
url: /nodejs-java/com.groupdocs.metadata.core/wordprocessinginspectionpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class WordProcessingInspectionPackage extends CustomPackage
```

Contains information about document parts that can be considered as metadata in some cases.

**Learn more**

 *  [Working with metadata in WordProcessing documents][]


[Working with metadata in WordProcessing documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Word+Processing+documents
## Methods

| Method | Description |
| --- | --- |
| [getComments()](#getComments--) | Gets an array of the user comments. |
| [getFields()](#getFields--) | Gets an array of document fields. |
| [getHiddenText()](#getHiddenText--) | Gets an array of hidden text fragments extracted from the document. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gets an array of digital signatures presented in the document. |
| [getRevisions()](#getRevisions--) | Gets an array of digital signatures presented in the document. |
| [removeProperties(Specification specification)](#removeProperties-com.groupdocs.metadata.search.Specification-) | Removes metadata properties satisfying a specification. |
| [clearComments()](#clearComments--) | Removes all detected user comments from the document. |
| [clearFields()](#clearFields--) | Removes all detected fields from the document. |
| [clearHiddenText()](#clearHiddenText--) | Removes all hidden text fragments from the document. |
| [acceptAllRevisions()](#acceptAllRevisions--) | Accepts all detected revisions in the document. |
| [rejectAllRevisions()](#rejectAllRevisions--) | Rejects all detected revisions in the document. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
### getComments() {#getComments--}
```
public final WordProcessingComment[] getComments()
```


Gets an array of the user comments.

**Returns:**
com.groupdocs.metadata.core.WordProcessingComment[] - The user comments.
### getFields() {#getFields--}
```
public final WordProcessingField[] getFields()
```


Gets an array of document fields.

**Returns:**
com.groupdocs.metadata.core.WordProcessingField[] - An array of document fields.
### getHiddenText() {#getHiddenText--}
```
public final String[] getHiddenText()
```


Gets an array of hidden text fragments extracted from the document.

**Returns:**
java.lang.String[] - An array of hidden text fragments extracted from the document.
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final DigitalSignature[] getDigitalSignatures()
```


Gets an array of digital signatures presented in the document.

**Returns:**
com.groupdocs.metadata.core.DigitalSignature[] - The digital signatures.
### getRevisions() {#getRevisions--}
```
public final WordProcessingRevision[] getRevisions()
```


Gets an array of digital signatures presented in the document.

**Returns:**
com.groupdocs.metadata.core.WordProcessingRevision[] - The digital signatures.
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
### clearComments() {#clearComments--}
```
public final void clearComments()
```


Removes all detected user comments from the document.

### clearFields() {#clearFields--}
```
public final void clearFields()
```


Removes all detected fields from the document.

### clearHiddenText() {#clearHiddenText--}
```
public final void clearHiddenText()
```


Removes all hidden text fragments from the document.

### acceptAllRevisions() {#acceptAllRevisions--}
```
public final void acceptAllRevisions()
```


Accepts all detected revisions in the document.

### rejectAllRevisions() {#rejectAllRevisions--}
```
public final void rejectAllRevisions()
```


Rejects all detected revisions in the document.

### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.
