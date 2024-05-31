---
title: CmsEncapsulatedContent
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a signed content container consisting of a content type identifier and the content itself.
type: docs
weight: 37
url: /nodejs-java/com.groupdocs.metadata.core/cmsencapsulatedcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class CmsEncapsulatedContent extends CustomPackage
```

Represents a signed content container, consisting of a content type identifier and the content itself.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Gets the object identifier uniquely specifies the content type. |
| [getContentRawData()](#getContentRawData--) | Gets the raw data of content info. |
### getContentType() {#getContentType--}
```
public final Oid getContentType()
```


Gets the object identifier uniquely specifies the content type.

**Returns:**
[Oid](../../com.groupdocs.metadata.core/oid) - The object identifier uniquely specifies the content type.
### getContentRawData() {#getContentRawData--}
```
public final byte[] getContentRawData()
```


Gets the raw data of content info.

**Returns:**
byte[] - The raw data of content info.
