---
title: XmpColorantBase
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: A structure containing the characteristics of a colorant swatch used in a document.
type: docs
weight: 304
url: /nodejs-java/com.groupdocs.metadata.core/xmpcolorantbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public class XmpColorantBase extends XmpComplexType
```

A structure containing the characteristics of a colorant (swatch) used in a document.
## Methods

| Method | Description |
| --- | --- |
| [getMode()](#getMode--) | Gets the colour space in which the colour is defined. |
| [getSwatchName()](#getSwatchName--) | Gets the name of the swatch. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Sets the name of the swatch. |
| [getColorType()](#getColorType--) | Gets the type of color. |
| [setColorType(XmpColorType value)](#setColorType-com.groupdocs.metadata.core.XmpColorType-) | Sets the type of color. |
### getMode() {#getMode--}
```
public final XmpColorantColorMode getMode()
```


Gets the colour space in which the colour is defined. One of: CMYK, RGB, LAB.

**Returns:**
[XmpColorantColorMode](../../com.groupdocs.metadata.core/xmpcolorantcolormode) - The color mode.
### getSwatchName() {#getSwatchName--}
```
public final String getSwatchName()
```


Gets the name of the swatch.

**Returns:**
java.lang.String - The name of the swatch.
### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public final void setSwatchName(String value)
```


Sets the name of the swatch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the swatch. |

### getColorType() {#getColorType--}
```
public final XmpColorType getColorType()
```


Gets the type of color.

**Returns:**
[XmpColorType](../../com.groupdocs.metadata.core/xmpcolortype) - The color type.
### setColorType(XmpColorType value) {#setColorType-com.groupdocs.metadata.core.XmpColorType-}
```
public final void setColorType(XmpColorType value)
```


Sets the type of color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpColorType](../../com.groupdocs.metadata.core/xmpcolortype) | The color type. |

