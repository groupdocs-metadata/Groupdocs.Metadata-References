---
title: XmpRenditionClass
second_title: GroupDocs.Metadata for Java API Reference
description: Represents XMP RenditionClass.
type: docs
weight: 288
url: /java/com.groupdocs.metadata.core/xmprenditionclass/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase), [com.groupdocs.metadata.core.XmpText](../../com.groupdocs.metadata.core/xmptext)
```
public final class XmpRenditionClass extends XmpText
```

Represents XMP RenditionClass.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpRenditionClass(String[] tokens)](#XmpRenditionClass-java.lang.String...-) | Initializes a new instance of the  XmpRenditionClass  class. |
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | The master resource; no additional tokens allowed. |
| [Draft](#Draft) | A review rendition. |
| [LowRes](#LowRes) | A low-resolution, full-size stand-in. |
| [Proof](#Proof) | A review proof. |
| [Screen](#Screen) | Screen resolution or Web rendition. |
| [Thumbnail](#Thumbnail) | A simplified or reduced preview. |
### XmpRenditionClass(String[] tokens) {#XmpRenditionClass-java.lang.String...-}
```
public XmpRenditionClass(String[] tokens)
```


Initializes a new instance of the  XmpRenditionClass  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tokens | java.lang.String[] | The token. |

### Default {#Default}
```
public static final String Default
```


The master resource; no additional tokens allowed.

### Draft {#Draft}
```
public static final String Draft
```


A review rendition.

### LowRes {#LowRes}
```
public static final String LowRes
```


A low-resolution, full-size stand-in.

### Proof {#Proof}
```
public static final String Proof
```


A review proof.

### Screen {#Screen}
```
public static final String Screen
```


Screen resolution or Web rendition.

### Thumbnail {#Thumbnail}
```
public static final String Thumbnail
```


A simplified or reduced preview. Additional tokens can provide characteristics. The recommended order is thumbnail:format:size:colorspace.

