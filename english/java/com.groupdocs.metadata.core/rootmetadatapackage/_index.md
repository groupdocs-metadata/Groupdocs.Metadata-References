---
title: RootMetadataPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents an entry point to all metadata packages presented in a particular file.
type: docs
weight: 184
url: /java/com.groupdocs.metadata.core/rootmetadatapackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage)
```
public abstract class RootMetadataPackage extends MetadataPackage
```

Represents an entry point to all metadata packages presented in a particular file.
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Gets the file type metadata package. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
### getFileType() {#getFileType--}
```
public final FileTypePackage getFileType()
```


Gets the file type metadata package.

**Returns:**
[FileTypePackage](../../com.groupdocs.metadata.core/filetypepackage) - The file type metadata package.
### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.

**Learn more**

 *  More examples demonstrating usages of this method: [Clean metadata][]


[Clean metadata]: https://docs.groupdocs.com/display/metadatajava/Clean+metadata
