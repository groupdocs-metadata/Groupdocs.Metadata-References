---
title: XmpPagedTextPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the XMP Paged-Text package.
type: docs
weight: 324
url: /java/com.groupdocs.metadata.core/xmppagedtextpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpPagedTextPackage extends XmpPackage
```

Represents the XMP Paged-Text package.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPagedTextPackage()](#XmpPagedTextPackage--) | Initializes a new instance of the  XmpPagedTextPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getColorants()](#getColorants--) | Gets an ordered array of colorants (swatches) that are used in the document (including any in contained documents). |
| [setColorants(XmpColorantBase[] value)](#setColorants-com.groupdocs.metadata.core.XmpColorantBase---) | Sets an ordered array of colorants (swatches) that are used in the document (including any in contained documents). |
| [getFonts()](#getFonts--) | Gets an unordered array of fonts that are used in the document (including any in contained documents). |
| [setFonts(XmpFont[] value)](#setFonts-com.groupdocs.metadata.core.XmpFont---) | Sets an unordered array of fonts that are used in the document (including any in contained documents). |
| [getMaxPageSize()](#getMaxPageSize--) | Gets the size of the largest page in the document (including any in contained documents). |
| [setMaxPageSize(XmpDimensions value)](#setMaxPageSize-com.groupdocs.metadata.core.XmpDimensions-) | Sets the size of the largest page in the document (including any in contained documents). |
| [getNumberOfPages()](#getNumberOfPages--) | Gets the number of pages in the document. |
| [setNumberOfPages(Integer value)](#setNumberOfPages-java.lang.Integer-) | Sets the number of pages in the document. |
| [getPlateNames()](#getPlateNames--) | Gets or set an ordered array of plate names that are needed to print the document (including any in contained documents). |
| [setPlateNames(String[] value)](#setPlateNames-java.lang.String---) | Gets or set an ordered array of plate names that are needed to print the document (including any in contained documents). |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
| [set(String name, XmpArray value)](#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-) | Sets the value inherited from  XmpArray  . |
### XmpPagedTextPackage() {#XmpPagedTextPackage--}
```
public XmpPagedTextPackage()
```


Initializes a new instance of the  XmpPagedTextPackage  class.

### getColorants() {#getColorants--}
```
public final XmpColorantBase[] getColorants()
```


Gets an ordered array of colorants (swatches) that are used in the document (including any in contained documents).

**Returns:**
com.groupdocs.metadata.core.XmpColorantBase[] - An array of the colorants.
### setColorants(XmpColorantBase[] value) {#setColorants-com.groupdocs.metadata.core.XmpColorantBase---}
```
public final void setColorants(XmpColorantBase[] value)
```


Sets an ordered array of colorants (swatches) that are used in the document (including any in contained documents).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpColorantBase\[\]](../../com.groupdocs.metadata.core/xmpcolorantbase) | An array of the colorants. |

### getFonts() {#getFonts--}
```
public final XmpFont[] getFonts()
```


Gets an unordered array of fonts that are used in the document (including any in contained documents).

**Returns:**
com.groupdocs.metadata.core.XmpFont[] - An array of the fonts.
### setFonts(XmpFont[] value) {#setFonts-com.groupdocs.metadata.core.XmpFont---}
```
public final void setFonts(XmpFont[] value)
```


Sets an unordered array of fonts that are used in the document (including any in contained documents).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpFont\[\]](../../com.groupdocs.metadata.core/xmpfont) | An array of the fonts. |

### getMaxPageSize() {#getMaxPageSize--}
```
public final XmpDimensions getMaxPageSize()
```


Gets the size of the largest page in the document (including any in contained documents).

**Returns:**
[XmpDimensions](../../com.groupdocs.metadata.core/xmpdimensions) - The size of the largest page.
### setMaxPageSize(XmpDimensions value) {#setMaxPageSize-com.groupdocs.metadata.core.XmpDimensions-}
```
public final void setMaxPageSize(XmpDimensions value)
```


Sets the size of the largest page in the document (including any in contained documents).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpDimensions](../../com.groupdocs.metadata.core/xmpdimensions) | The size of the largest page. |

### getNumberOfPages() {#getNumberOfPages--}
```
public final Integer getNumberOfPages()
```


Gets the number of pages in the document.

**Returns:**
java.lang.Integer - The number of pages.
### setNumberOfPages(Integer value) {#setNumberOfPages-java.lang.Integer-}
```
public final void setNumberOfPages(Integer value)
```


Sets the number of pages in the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The number of pages. |

### getPlateNames() {#getPlateNames--}
```
public final String[] getPlateNames()
```


Gets or set an ordered array of plate names that are needed to print the document (including any in contained documents).

**Returns:**
java.lang.String[] - The plate names.
### setPlateNames(String[] value) {#setPlateNames-java.lang.String---}
```
public final void setPlateNames(String[] value)
```


Gets or set an ordered array of plate names that are needed to print the document (including any in contained documents).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public void set(String name, String value)
```


Sets string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | java.lang.String | XMP metadata property value. |

### set(String name, XmpArray value) {#set-java.lang.String-com.groupdocs.metadata.core.XmpArray-}
```
public void set(String name, XmpArray value)
```


Sets the value inherited from  XmpArray  .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | [XmpArray](../../com.groupdocs.metadata.core/xmparray) | XMP metadata property value. |

