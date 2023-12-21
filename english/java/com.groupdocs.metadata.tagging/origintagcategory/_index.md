---
title: OriginTagCategory
second_title: GroupDocs.Signature for Java API Reference
description: Provides tags that help a user to determine the origin of a file e.g.
type: docs
weight: 14
url: /java/com.groupdocs.metadata.tagging/origintagcategory/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.tagging.TagCategory](../../com.groupdocs.metadata.tagging/tagcategory)
```
public class OriginTagCategory extends TagCategory
```

Provides tags that help a user to determine the origin of a file (e.g. template or another source).
## Methods

| Method | Description |
| --- | --- |
| [getTemplate()](#getTemplate--) | Gets the tag that denotes the template from which the file was created. |
| [getSource()](#getSource--) | Gets the tag that labels a reference to a resource from which the file content is derived. |
### getTemplate() {#getTemplate--}
```
public final PropertyTag getTemplate()
```


Gets the tag that denotes the template from which the file was created.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes the template from which the file was created.
### getSource() {#getSource--}
```
public final PropertyTag getSource()
```


Gets the tag that labels a reference to a resource from which the file content is derived.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a reference to a resource from which the file content is derived.
