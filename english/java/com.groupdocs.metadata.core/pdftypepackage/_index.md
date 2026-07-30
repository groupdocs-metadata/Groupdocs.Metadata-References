---
title: PdfTypePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a metadata package containing PDF-specific file format information.
type: docs
weight: 191
url: /java/com.groupdocs.metadata.core/pdftypepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.FileTypePackage](../../com.groupdocs.metadata.core/filetypepackage)
```
public class PdfTypePackage extends FileTypePackage
```

Represents a metadata package containing PDF-specific file format information.

## Methods

| Method | Description |
| --- | --- |
| [getPdfFormat()](#getPdfFormat--) | Gets the detected PDF format.
 |
| [isPdfA()](#isPdfA--) | Gets a value indicating whether the document conforms to any PDF/A standard.
 |
| [isPdfX()](#isPdfX--) | Gets a value indicating whether the document conforms to any PDF/X standard.
 |
| [getVersion()](#getVersion--) | Gets the version of the format.
 |
### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormat getPdfFormat()
```


Gets the detected PDF format.


**Returns:**
[PdfFormat](../../com.groupdocs.metadata.core/pdfformat) - The detected PDF format.

### isPdfA() {#isPdfA--}
```
public final boolean isPdfA()
```


Gets a value indicating whether the document conforms to any PDF/A standard.


**Returns:**
boolean -  true  if the document is identified as PDF/A; otherwise,  false .

### isPdfX() {#isPdfX--}
```
public final boolean isPdfX()
```


Gets a value indicating whether the document conforms to any PDF/X standard.


**Returns:**
boolean -  true  if the document is identified as PDF/X; otherwise,  false .

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the version of the format.


**Returns:**
java.lang.String - The version of the format.

