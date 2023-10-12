---
title: RawTypePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a metadata package containing image-specific file format information.
type: docs
weight: 221
url: /java/com.groupdocs.metadata.core/rawtypepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.FileTypePackage](../../com.groupdocs.metadata.core/filetypepackage)
```
public class RawTypePackage extends FileTypePackage
```

Represents a metadata package containing image-specific file format information.
## Methods

| Method | Description |
| --- | --- |
| [getByteOrder()](#getByteOrder--) | Gets the byte-order of the image. |
### getByteOrder() {#getByteOrder--}
```
public final ByteOrder getByteOrder()
```


Gets the byte-order of the image. Please see  https://en.wikipedia.org/wiki/Endianness  for more information.

**Returns:**
[ByteOrder](../../com.groupdocs.metadata.core/byteorder) - The byte-order value.
