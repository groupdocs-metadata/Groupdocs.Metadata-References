---
title: RawDictionaryBasePackage
second_title: GroupDocs.Metadata for Java API Reference
description: Provides an abstract base class for EXIF metadata dictionaries.
type: docs
weight: 215
url: /java/com.groupdocs.metadata.core/rawdictionarybasepackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class RawDictionaryBasePackage extends CustomPackage
```

Provides an abstract base class for EXIF metadata dictionaries.

**Learn more**

 *  [Working with EXIF metadata][]


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
## Methods

| Method | Description |
| --- | --- |
| [toList()](#toList--) | Creates a list from the package. |
| [get_Item(long tagId)](#get-Item-long-) | Gets the Raw tag with the specified id. |
| [remove(long tagId)](#remove-long-) | Removes the property with the specified id. |
| [set(RawTag tag)](#set-com.groupdocs.metadata.core.RawTag-) | Adds or replaces the specified tag. |
| [clear()](#clear--) | Removes all Raw tags stored in the package. |
### toList() {#toList--}
```
public final IReadOnlyList<RawTag> toList()
```


Creates a list from the package.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A list that contains all Raw tags from the package.
### get_Item(long tagId) {#get-Item-long-}
```
public final RawTag get_Item(long tagId)
```


Gets the Raw tag with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | long | The id of the tag to retrieve. |

**Returns:**
[RawTag](../../com.groupdocs.metadata.core/rawtag) - The  RawTag  with the specified tag id.
### remove(long tagId) {#remove-long-}
```
public final boolean remove(long tagId)
```


Removes the property with the specified id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagId | long | A Raw tag id. |

**Returns:**
boolean - True if the specified Raw tag is found and removed; otherwise, false.
### set(RawTag tag) {#set-com.groupdocs.metadata.core.RawTag-}
```
public final void set(RawTag tag)
```


Adds or replaces the specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | [RawTag](../../com.groupdocs.metadata.core/rawtag) | The tag to set. |

### clear() {#clear--}
```
public final void clear()
```


Removes all Raw tags stored in the package.

