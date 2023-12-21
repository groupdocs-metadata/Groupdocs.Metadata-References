---
title: CmsPackage
second_title: GroupDocs.Signature for Java API Reference
description: Represents a CMS digital signature metadata package.
type: docs
weight: 38
url: /java/com.groupdocs.metadata.core/cmspackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class CmsPackage extends CustomPackage
```

Represents a CMS digital signature metadata package.
## Methods

| Method | Description |
| --- | --- |
| [getSignatures()](#getSignatures--) | Gets an array of the signatures extracted from the file. |
| [getFlags()](#getFlags--) | Gets the digital signature flags. |
### getSignatures() {#getSignatures--}
```
public final Cms[] getSignatures()
```


Gets an array of the signatures extracted from the file.

**Returns:**
com.groupdocs.metadata.core.Cms[] - An array of the signatures extracted from the file.
### getFlags() {#getFlags--}
```
public final Integer getFlags()
```


Gets the digital signature flags.

**Returns:**
java.lang.Integer - The digital signature flags.
