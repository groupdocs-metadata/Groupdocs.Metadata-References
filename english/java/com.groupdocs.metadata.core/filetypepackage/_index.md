---
title: FileTypePackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents a metadata package containing file format information.
type: docs
weight: 101
url: /java/com.groupdocs.metadata.core/filetypepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class FileTypePackage extends CustomPackage
```

Represents a metadata package containing file format information.

**Learn more**

 *  [Get document info][]
 *  [Supported file formats][]


[Get document info]: https://docs.groupdocs.com/display/metadatajava/Get+document+info
[Supported file formats]: https://docs.groupdocs.com/display/metadatajava/Supported+File+Formats
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Gets the file format. |
| [getMimeType()](#getMimeType--) | Gets the MIME type. |
| [getExtension()](#getExtension--) | Gets the file extension. |
### getFileFormat() {#getFileFormat--}
```
public final FileFormat getFileFormat()
```


Gets the file format.

**Returns:**
[FileFormat](../../com.groupdocs.metadata.core/fileformat) - The file format.
### getMimeType() {#getMimeType--}
```
public final String getMimeType()
```


Gets the MIME type.

**Returns:**
java.lang.String - The MIME type value.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Gets the file extension.

**Returns:**
java.lang.String - The file extension.
