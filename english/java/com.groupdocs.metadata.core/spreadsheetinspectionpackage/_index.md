---
title: SpreadsheetInspectionPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Contains information about spreadsheet parts that can be considered as metadata in some cases.
type: docs
weight: 228
url: /java/com.groupdocs.metadata.core/spreadsheetinspectionpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class SpreadsheetInspectionPackage extends CustomPackage
```

Contains information about spreadsheet parts that can be considered as metadata in some cases.

**Learn more**

 *  [Working with metadata in Spreadsheets][]


[Working with metadata in Spreadsheets]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Spreadsheets
## Methods

| Method | Description |
| --- | --- |
| [getComments()](#getComments--) | Gets an array of the user comments. |
| [getHiddenSheets()](#getHiddenSheets--) | Gets an array of the hidden sheets. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gets an array of digital signatures presented in the document. |
| [removeProperties(Specification specification)](#removeProperties-com.groupdocs.metadata.search.Specification-) | Removes metadata properties satisfying a specification. |
| [clearComments()](#clearComments--) | Removes all detected user comments from the spreadsheet. |
| [clearHiddenSheets()](#clearHiddenSheets--) | Removes all detected hidden sheets from the spreadsheet. |
| [clearDigitalSignatures()](#clearDigitalSignatures--) | Removes all detected digital signatures from the spreadsheet. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
### getComments() {#getComments--}
```
public final SpreadsheetComment[] getComments()
```


Gets an array of the user comments.

**Returns:**
com.groupdocs.metadata.core.SpreadsheetComment[] - The user comments.
### getHiddenSheets() {#getHiddenSheets--}
```
public final SpreadsheetSheet[] getHiddenSheets()
```


Gets an array of the hidden sheets.

**Returns:**
com.groupdocs.metadata.core.SpreadsheetSheet[] - The hidden sheets.
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final DigitalSignature[] getDigitalSignatures()
```


Gets an array of digital signatures presented in the document.

**Returns:**
com.groupdocs.metadata.core.DigitalSignature[] - The digital signatures.
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


Removes all detected user comments from the spreadsheet.

### clearHiddenSheets() {#clearHiddenSheets--}
```
public final void clearHiddenSheets()
```


Removes all detected hidden sheets from the spreadsheet.

### clearDigitalSignatures() {#clearDigitalSignatures--}
```
public final void clearDigitalSignatures()
```


Removes all detected digital signatures from the spreadsheet.

### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.
