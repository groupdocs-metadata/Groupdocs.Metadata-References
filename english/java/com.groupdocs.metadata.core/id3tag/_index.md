---
title: ID3Tag
second_title: GroupDocs.Signature for Java API Reference
description: Represents a base abstract class for the ID3v1 and ID3v2 audio tags.
type: docs
weight: 109
url: /java/com.groupdocs.metadata.core/id3tag/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public abstract class ID3Tag extends CustomPackage
```

Represents a base abstract class for the ID3(v1) and ID3(v2) audio tags.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets the version of the ID3 tag in string format. |
### getVersion() {#getVersion--}
```
public abstract String getVersion()
```


Gets the version of the ID3 tag in string format. For example: 'ID3v1.1'.

**Returns:**
java.lang.String - The ID3 version.
