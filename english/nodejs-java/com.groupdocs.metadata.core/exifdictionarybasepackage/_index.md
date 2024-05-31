---
title: ExifDictionaryBasePackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Provides an abstract base class for EXIF metadata dictionaries.
type: docs
weight: 96
url: /nodejs-java/com.groupdocs.metadata.core/exifdictionarybasepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class ExifDictionaryBasePackage extends CustomPackage
```

Provides an abstract base class for EXIF metadata dictionaries.

**Learn more**

 *  [Working with EXIF metadata][]


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
## Methods

| Method | Description |
| --- | --- |
| [toList()](#toList--) | Creates a list from the package. |
| [getByTiffTagID(TiffTagID tagId)](#getByTiffTagID-com.groupdocs.metadata.core.TiffTagID-) | Gets the TIFF tag with the specified id. |
| [remove(TiffTagID tagId)](#remove-com.groupdocs.metadata.core.TiffTagID-) | Removes the property with the specified id. |
| [set(TiffTag tag)](#set-com.groupdocs.metadata.core.TiffTag-) | Adds or replaces the specified tag. |
| [clear()](#clear--) | Removes all TIFF tags stored in the package. |
### toList() {#toList--}
```
public final IReadOnlyList<TiffTag> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list that contains all TIFF tags from the package.
### getByTiffTagID(TiffTagID tagId) {#getByTiffTagID-com.groupdocs.metadata.core.TiffTagID-}
```
public final TiffTag getByTiffTagID(TiffTagID tagId)
```


Gets the TIFF tag with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | [TiffTagID](../../com.groupdocs.metadata.core/tifftagid) | The id of the tag to retrieve. |

**Returns:**
[TiffTag](../../com.groupdocs.metadata.core/tifftag) - The  TiffTag  with the specified tag id.
### remove(TiffTagID tagId) {#remove-com.groupdocs.metadata.core.TiffTagID-}
```
public final boolean remove(TiffTagID tagId)
```


Removes the property with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | [TiffTagID](../../com.groupdocs.metadata.core/tifftagid) | A TIFF tag id. |

**Returns:**
boolean - True if the specified TIFF tag is found and removed; otherwise, false.
### set(TiffTag tag) {#set-com.groupdocs.metadata.core.TiffTag-}
```
public final void set(TiffTag tag)
```


Adds or replaces the specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | [TiffTag](../../com.groupdocs.metadata.core/tifftag) | The tag to set. |

### clear() {#clear--}
```
public final void clear()
```


Removes all TIFF tags stored in the package.

