---
title: XmpBasicPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the XMP basic namespace.
type: docs
weight: 252
url: /java/com.groupdocs.metadata.core/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpBasicPackage extends XmpPackage
```

Represents the XMP basic namespace.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initializes a new instance of the  XmpBasicPackage  class. |
## Fields

| Field | Description |
| --- | --- |
| [RatingRejected](#RatingRejected) | Rating rejected value. |
| [RatingMin](#RatingMin) | Rating min value. |
| [RatingMax](#RatingMax) | Rating max value. |
## Methods

| Method | Description |
| --- | --- |
| [getBaseUrl()](#getBaseUrl--) | Gets the base URL for relative URLs in the document content. |
| [setBaseUrl(String value)](#setBaseUrl-java.lang.String-) | Sets the base URL for relative URLs in the document content. |
| [getCreateDate()](#getCreateDate--) | Gets the date and time the resource was created. |
| [setCreateDate(Date value)](#setCreateDate-java.util.Date-) | Sets the date and time the resource was created. |
| [getCreatorTool()](#getCreatorTool--) | Gets the name of the tool used to create the resource. |
| [setCreatorTool(String value)](#setCreatorTool-java.lang.String-) | Sets the name of the tool used to create the resource. |
| [getIdentifiers()](#getIdentifiers--) | Gets an unordered array of text strings that unambiguously identify the resource within a given context. |
| [setIdentifiers(String[] value)](#setIdentifiers-java.lang.String---) | Sets an unordered array of text strings that unambiguously identify the resource within a given context. |
| [getLabel()](#getLabel--) | Gets a word or short phrase that identifies the resource as a member of a user-defined collection. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Sets a word or short phrase that identifies the resource as a member of a user-defined collection. |
| [getMetadataDate()](#getMetadataDate--) | Gets the date and time that any metadata for this resource was last changed. |
| [setMetadataDate(Date value)](#setMetadataDate-java.util.Date-) | Sets the date and time that any metadata for this resource was last changed. |
| [getModifyDate()](#getModifyDate--) | Gets the date and time the resource was last modified. |
| [setModifyDate(Date value)](#setModifyDate-java.util.Date-) | Sets the date and time the resource was last modified. |
| [getNickname()](#getNickname--) | Gets a short informal name for the resource. |
| [setNickname(String value)](#setNickname-java.lang.String-) | Sets a short informal name for the resource. |
| [getRating()](#getRating--) | Gets a user-assigned rating for this file. |
| [setRating(double value)](#setRating-double-) | Sets a user-assigned rating for this file. |
| [getThumbnails()](#getThumbnails--) | Gets an array of thumbnail images for the file, which can differ in characteristics such as size or image encoding. |
| [setThumbnails(XmpThumbnail[] value)](#setThumbnails-com.groupdocs.metadata.core.XmpThumbnail---) | Sets an array of thumbnail images for the file, which can differ in characteristics such as size or image encoding. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Adds string property. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initializes a new instance of the  XmpBasicPackage  class.

### RatingRejected {#RatingRejected}
```
public static final float RatingRejected
```


Rating rejected value.

### RatingMin {#RatingMin}
```
public static final float RatingMin
```


Rating min value.

### RatingMax {#RatingMax}
```
public static final float RatingMax
```


Rating max value.

### getBaseUrl() {#getBaseUrl--}
```
public final String getBaseUrl()
```


Gets the base URL for relative URLs in the document content. If this document contains Internet links, and those links are relative, they are relative to this base URL.

**Returns:**
java.lang.String - The base URL.
### setBaseUrl(String value) {#setBaseUrl-java.lang.String-}
```
public final void setBaseUrl(String value)
```


Sets the base URL for relative URLs in the document content. If this document contains Internet links, and those links are relative, they are relative to this base URL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The base URL. |

### getCreateDate() {#getCreateDate--}
```
public final Date getCreateDate()
```


Gets the date and time the resource was created.

**Returns:**
java.util.Date - The resource creation date.
### setCreateDate(Date value) {#setCreateDate-java.util.Date-}
```
public final void setCreateDate(Date value)
```


Sets the date and time the resource was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The resource creation date. |

### getCreatorTool() {#getCreatorTool--}
```
public final String getCreatorTool()
```


Gets the name of the tool used to create the resource.

**Returns:**
java.lang.String - The name of the tool used to create the resource.
### setCreatorTool(String value) {#setCreatorTool-java.lang.String-}
```
public final void setCreatorTool(String value)
```


Sets the name of the tool used to create the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the tool used to create the resource. |

### getIdentifiers() {#getIdentifiers--}
```
public final String[] getIdentifiers()
```


Gets an unordered array of text strings that unambiguously identify the resource within a given context.

**Returns:**
java.lang.String[] - An array of the identifiers.
### setIdentifiers(String[] value) {#setIdentifiers-java.lang.String---}
```
public final void setIdentifiers(String[] value)
```


Sets an unordered array of text strings that unambiguously identify the resource within a given context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | An array of the identifiers. |

### getLabel() {#getLabel--}
```
public final String getLabel()
```


Gets a word or short phrase that identifies the resource as a member of a user-defined collection.

**Returns:**
java.lang.String - The label of the resource.
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Sets a word or short phrase that identifies the resource as a member of a user-defined collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The label of the resource. |

### getMetadataDate() {#getMetadataDate--}
```
public final Date getMetadataDate()
```


Gets the date and time that any metadata for this resource was last changed.

**Returns:**
java.util.Date - The metadata date.
### setMetadataDate(Date value) {#setMetadataDate-java.util.Date-}
```
public final void setMetadataDate(Date value)
```


Sets the date and time that any metadata for this resource was last changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The metadata date. |

### getModifyDate() {#getModifyDate--}
```
public final Date getModifyDate()
```


Gets the date and time the resource was last modified.

**Returns:**
java.util.Date - The last modification date.
### setModifyDate(Date value) {#setModifyDate-java.util.Date-}
```
public final void setModifyDate(Date value)
```


Sets the date and time the resource was last modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The last modification date. |

### getNickname() {#getNickname--}
```
public final String getNickname()
```


Gets a short informal name for the resource.

**Returns:**
java.lang.String - The nickname.
### setNickname(String value) {#setNickname-java.lang.String-}
```
public final void setNickname(String value)
```


Sets a short informal name for the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The nickname. |

### getRating() {#getRating--}
```
public final double getRating()
```


Gets a user-assigned rating for this file. The value shall be -1 or in the range [0..5], where -1 indicates \\u201crejected\\u201d and 0 indicates \\u201cunrated\\u201d.

**Returns:**
double - The rating.
### setRating(double value) {#setRating-double-}
```
public final void setRating(double value)
```


Sets a user-assigned rating for this file. The value shall be -1 or in the range [0..5], where -1 indicates \\u201crejected\\u201d and 0 indicates \\u201cunrated\\u201d.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The rating. |

### getThumbnails() {#getThumbnails--}
```
public final XmpThumbnail[] getThumbnails()
```


Gets an array of thumbnail images for the file, which can differ in characteristics such as size or image encoding.

**Returns:**
com.groupdocs.metadata.core.XmpThumbnail[] - The thumbnails.
### setThumbnails(XmpThumbnail[] value) {#setThumbnails-com.groupdocs.metadata.core.XmpThumbnail---}
```
public final void setThumbnails(XmpThumbnail[] value)
```


Sets an array of thumbnail images for the file, which can differ in characteristics such as size or image encoding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpThumbnail\[\]](../../com.groupdocs.metadata.core/xmpthumbnail) | The thumbnails. |

### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public void set(String name, String value)
```


Adds string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XmpBasic key. |
| value | java.lang.String | String value. |

