---
title: XmpFont
second_title: GroupDocs.Signature for Java API Reference
description: A structure containing the characteristics of a font used in a document.
type: docs
weight: 307
url: /java/com.groupdocs.metadata.core/xmpfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public final class XmpFont extends XmpComplexType
```

A structure containing the characteristics of a font used in a document.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpFont()](#XmpFont--) | Initializes a new instance of the  XmpFont  class. |
| [XmpFont(String fontFamily)](#XmpFont-java.lang.String-) | Initializes a new instance of the  XmpFont  class. |
## Methods

| Method | Description |
| --- | --- |
| [getChildFontFiles()](#getChildFontFiles--) | Gets the list of file names for the fonts that make up a composite font. |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Sets the list of file names for the fonts that make up a composite font. |
| [isComposite()](#isComposite--) | Gets a value indicating whether whether the font is composite. |
| [setComposite(Boolean value)](#setComposite-java.lang.Boolean-) | Sets a value indicating whether whether the font is composite. |
| [getFontFace()](#getFontFace--) | Gets the font face name. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Sets the font face name. |
| [getFontFamily()](#getFontFamily--) | Gets the font family name. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Sets the font family name. |
| [getFontFileName()](#getFontFileName--) | Gets the font file name (not a complete path). |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Sets the font file name (not a complete path). |
| [getFontName()](#getFontName--) | Gets the PostScript name of the font. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Sets the PostScript name of the font. |
| [getFontType()](#getFontType--) | Gets the font type. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Sets the font type. |
| [getVersion()](#getVersion--) | Gets the font version. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Sets the font version. |
### XmpFont() {#XmpFont--}
```
public XmpFont()
```


Initializes a new instance of the  XmpFont  class.

### XmpFont(String fontFamily) {#XmpFont-java.lang.String-}
```
public XmpFont(String fontFamily)
```


Initializes a new instance of the  XmpFont  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Font family. |

### getChildFontFiles() {#getChildFontFiles--}
```
public final String[] getChildFontFiles()
```


Gets the list of file names for the fonts that make up a composite font.

**Returns:**
java.lang.String[] - The list of file names for the fonts that make up a composite font.
### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public final void setChildFontFiles(String[] value)
```


Sets the list of file names for the fonts that make up a composite font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The list of file names for the fonts that make up a composite font. |

### isComposite() {#isComposite--}
```
public final Boolean isComposite()
```


Gets a value indicating whether whether the font is composite.

**Returns:**
java.lang.Boolean -  true  if the font is composite; otherwise,  false .
### setComposite(Boolean value) {#setComposite-java.lang.Boolean-}
```
public final void setComposite(Boolean value)
```


Sets a value indicating whether whether the font is composite.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean |  true  if the font is composite; otherwise,  false . |

### getFontFace() {#getFontFace--}
```
public final String getFontFace()
```


Gets the font face name.

**Returns:**
java.lang.String - The font face name.
### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public final void setFontFace(String value)
```


Sets the font face name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The font face name. |

### getFontFamily() {#getFontFamily--}
```
public final String getFontFamily()
```


Gets the font family name.

**Returns:**
java.lang.String - The font family name.
### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public final void setFontFamily(String value)
```


Sets the font family name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The font family name. |

### getFontFileName() {#getFontFileName--}
```
public final String getFontFileName()
```


Gets the font file name (not a complete path).

**Returns:**
java.lang.String - The name of the font file.
### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public final void setFontFileName(String value)
```


Sets the font file name (not a complete path).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the font file. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Gets the PostScript name of the font.

**Returns:**
java.lang.String - The PostScript name of the font.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Sets the PostScript name of the font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The PostScript name of the font. |

### getFontType() {#getFontType--}
```
public final String getFontType()
```


Gets the font type.

**Returns:**
java.lang.String - The font type.

--------------------

TrueType, Type 1, Open Type, and so on.
### setFontType(String value) {#setFontType-java.lang.String-}
```
public final void setFontType(String value)
```


Sets the font type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The font type.

--------------------

TrueType, Type 1, Open Type, and so on. |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the font version.

**Returns:**
java.lang.String - The version.

--------------------

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts The empty string for bitmap fonts
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Sets the font version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The version.

--------------------

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts The empty string for bitmap fonts |

