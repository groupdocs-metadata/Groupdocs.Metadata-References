---
title: XmpThumbnail
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a thumbnail image for a file.
type: docs
weight: 294
url: /java/com.groupdocs.metadata.core/xmpthumbnail/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public final class XmpThumbnail extends XmpComplexType
```

Represents a thumbnail image for a file.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpThumbnail()](#XmpThumbnail--) | Initializes a new instance of the  XmpThumbnail  class. |
| [XmpThumbnail(int width, int height)](#XmpThumbnail-int-int-) | Initializes a new instance of the  XmpThumbnail  class. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets the image width in pixels. |
| [setWidth(Integer value)](#setWidth-java.lang.Integer-) | Sets the image width in pixels. |
| [getHeight()](#getHeight--) | Gets the image height in pixels. |
| [setHeight(Integer value)](#setHeight-java.lang.Integer-) | Sets the image height in pixels. |
| [getImageBase64()](#getImageBase64--) | Gets the full thumbnail image data, converted to base 64 notation. |
| [setImageBase64(String value)](#setImageBase64-java.lang.String-) | Sets the full thumbnail image data, converted to base 64 notation. |
| [getImageData()](#getImageData--) | Gets the image data. |
| [getFormat()](#getFormat--) | Gets the image format. |
| [setFormat(String value)](#setFormat-java.lang.String-) | Sets the image format. |
### XmpThumbnail() {#XmpThumbnail--}
```
public XmpThumbnail()
```


Initializes a new instance of the  XmpThumbnail  class.

### XmpThumbnail(int width, int height) {#XmpThumbnail-int-int-}
```
public XmpThumbnail(int width, int height)
```


Initializes a new instance of the  XmpThumbnail  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width. |
| height | int | The height. |

### getWidth() {#getWidth--}
```
public final Integer getWidth()
```


Gets the image width in pixels.

**Returns:**
java.lang.Integer - The thumbnail width.
### setWidth(Integer value) {#setWidth-java.lang.Integer-}
```
public final void setWidth(Integer value)
```


Sets the image width in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The thumbnail width. |

### getHeight() {#getHeight--}
```
public final Integer getHeight()
```


Gets the image height in pixels.

**Returns:**
java.lang.Integer - The thumbnail height.
### setHeight(Integer value) {#setHeight-java.lang.Integer-}
```
public final void setHeight(Integer value)
```


Sets the image height in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The thumbnail height. |

### getImageBase64() {#getImageBase64--}
```
public final String getImageBase64()
```


Gets the full thumbnail image data, converted to base 64 notation.

**Returns:**
java.lang.String - The full thumbnail image data, converted to base 64 notation.
### setImageBase64(String value) {#setImageBase64-java.lang.String-}
```
public final void setImageBase64(String value)
```


Sets the full thumbnail image data, converted to base 64 notation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The full thumbnail image data, converted to base 64 notation. |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Gets the image data.

**Returns:**
byte[] - The image data.
### getFormat() {#getFormat--}
```
public final String getFormat()
```


Gets the image format. Defined value: JPEG.

**Returns:**
java.lang.String - The thumbnail format.
### setFormat(String value) {#setFormat-java.lang.String-}
```
public final void setFormat(String value)
```


Sets the image format. Defined value: JPEG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The thumbnail format. |

