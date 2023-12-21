---
title: LegalTagCategory
second_title: GroupDocs.Metadata for Java API Reference
description: Provides tags that are attached to metadata properties holding information about the owners of the file content and the rules under which the content can be used.
type: docs
weight: 13
url: /java/com.groupdocs.metadata.tagging/legaltagcategory/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.tagging.TagCategory](../../com.groupdocs.metadata.tagging/tagcategory)
```
public class LegalTagCategory extends TagCategory
```

Provides tags that are attached to metadata properties holding information about the owners of the file content and the rules under which the content can be used.
## Methods

| Method | Description |
| --- | --- |
| [getCopyright()](#getCopyright--) | Gets the tag that labels a copyright notice provided by the owner. |
| [getOwner()](#getOwner--) | Gets the tag that denotes information about the owners of a file. |
| [getUsageTerms()](#getUsageTerms--) | Gets the tag that labels instructions on how the file can be used. |
### getCopyright() {#getCopyright--}
```
public final PropertyTag getCopyright()
```


Gets the tag that labels a copyright notice provided by the owner.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a copyright notice provided by the owner.
### getOwner() {#getOwner--}
```
public final PropertyTag getOwner()
```


Gets the tag that denotes information about the owners of a file.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes information about the owners of a file.
### getUsageTerms() {#getUsageTerms--}
```
public final PropertyTag getUsageTerms()
```


Gets the tag that labels instructions on how the file can be used.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels instructions on how the file can be used.
