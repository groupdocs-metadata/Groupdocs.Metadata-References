---
title: CorporateTagCategory
second_title: GroupDocs.Signature for Java API Reference
description: Provides tags intended to mark metadata properties related to a company that participated in file creation.
type: docs
weight: 11
url: /java/com.groupdocs.metadata.tagging/corporatetagcategory/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.tagging.TagCategory](../../com.groupdocs.metadata.tagging/tagcategory)
```
public class CorporateTagCategory extends TagCategory
```

Provides tags intended to mark metadata properties related to a company that participated in file creation.
## Methods

| Method | Description |
| --- | --- |
| [getCompany()](#getCompany--) | Gets the tag that labels a property containing information about a company contributed to file creation. |
| [getManager()](#getManager--) | Gets the tag that labels information about a person who managed the making process of a file. |
### getCompany() {#getCompany--}
```
public final PropertyTag getCompany()
```


Gets the tag that labels a property containing information about a company contributed to file creation. Alternatively, the tag can refer to a company the file content is about.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag)
### getManager() {#getManager--}
```
public final PropertyTag getManager()
```


Gets the tag that labels information about a person who managed the making process of a file.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels information about a person who managed the making process of a file.
