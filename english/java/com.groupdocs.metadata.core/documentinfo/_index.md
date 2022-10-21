---
title: DocumentInfo
second_title: GroupDocs.Metadata for Java API Reference
description: Provides common information about a loaded document.
type: docs
weight: 49
url: /java/com.groupdocs.metadata.core/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IDocumentInfo](../../com.groupdocs.metadata.core/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Provides common information about a loaded document.

**Learn more**

 *  [Get document info][]


[Get document info]: https://docs.groupdocs.com/display/metadatajava/Get+document+info
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Gets the file type of the loaded document. |
| [getSize()](#getSize--) | Gets the size of the loaded document in bytes. |
| [getPageCount()](#getPageCount--) | Gets the number of pages (slides, worksheets, etc) in the loaded document. |
| [getPages()](#getPages--) | Gets a collection of objects representing common information about the document pages (slides, worksheets, etc). |
| [isEncrypted()](#isEncrypted--) | Gets a value indicating whether the document is encrypted and requires a password to open. |
### getFileType() {#getFileType--}
```
public final FileTypePackage getFileType()
```


Gets the file type of the loaded document.

**Returns:**
[FileTypePackage](../../com.groupdocs.metadata.core/filetypepackage) - The file type of the loaded document.
### getSize() {#getSize--}
```
public final long getSize()
```


Gets the size of the loaded document in bytes.

**Returns:**
long - The size of the loaded document in bytes.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gets the number of pages (slides, worksheets, etc) in the loaded document.

**Returns:**
int - The number of pages (slides, worksheets, etc) in the loaded document.
### getPages() {#getPages--}
```
public final IReadOnlyList<PageInfo> getPages()
```


Gets a collection of objects representing common information about the document pages (slides, worksheets, etc).

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A collection of objects representing common information about the document pages (slides, worksheets, etc).
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gets a value indicating whether the document is encrypted and requires a password to open.

**Returns:**
boolean - A value indicating whether the document is encrypted and requires a password to open.
