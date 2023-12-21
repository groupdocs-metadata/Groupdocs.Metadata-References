---
title: OpenTypeFont
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a single font extracted from a file.
type: docs
weight: 174
url: /java/com.groupdocs.metadata.core/opentypefont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public class OpenTypeFont extends CustomPackage
```

Represents a single font extracted from a file.

**Learn more**

 *  [Working with OpenType fonts][]


[Working with OpenType fonts]: https://docs.groupdocs.com/display/metadatajava/Working+with+OpenType+fonts
## Methods

| Method | Description |
| --- | --- |
| [getSfntVersion()](#getSfntVersion--) | Gets the header SFNT version. |
| [getMajorVersion()](#getMajorVersion--) | Gets the header major version. |
| [getMinorVersion()](#getMinorVersion--) | Gets the header minor version. |
| [getFontRevision()](#getFontRevision--) | Gets the font revision. |
| [getFlags()](#getFlags--) | Gets the header flags. |
| [getCreated()](#getCreated--) | Gets the created date. |
| [getModified()](#getModified--) | Gets the modified date. |
| [getGlyphBounds()](#getGlyphBounds--) | Gets the glyph bounds. |
| [getStyle()](#getStyle--) | Gets the font style. |
| [getDirectionHint()](#getDirectionHint--) | Gets the direction hint. |
| [getNames()](#getNames--) | Gets the name records. |
| [getFontFamilyName()](#getFontFamilyName--) | Gets the name of the font family. |
| [getFontSubfamilyName()](#getFontSubfamilyName--) | Gets the name of the font subfamily. |
| [getFullFontName()](#getFullFontName--) | Gets the full name of the font. |
| [getTypographicFamily()](#getTypographicFamily--) | Gets the typographic family. |
| [getTypographicSubfamily()](#getTypographicSubfamily--) | Gets the typographic subfamily. |
| [getWeight()](#getWeight--) | Gets the font weight. |
| [getWidth()](#getWidth--) | Gets the font width. |
| [getEmbeddingLicensingRights()](#getEmbeddingLicensingRights--) | Gets the embedding licensing rights type. |
### getSfntVersion() {#getSfntVersion--}
```
public final OpenTypeVersion getSfntVersion()
```


Gets the header SFNT version.

**Returns:**
[OpenTypeVersion](../../com.groupdocs.metadata.core/opentypeversion) - The header SFNT version.
### getMajorVersion() {#getMajorVersion--}
```
public final int getMajorVersion()
```


Gets the header major version.

**Returns:**
int - The header major version.
### getMinorVersion() {#getMinorVersion--}
```
public final int getMinorVersion()
```


Gets the header minor version.

**Returns:**
int - The header minor version.
### getFontRevision() {#getFontRevision--}
```
public final float getFontRevision()
```


Gets the font revision.

**Returns:**
float - The font revision.
### getFlags() {#getFlags--}
```
public final OpenTypeFlags getFlags()
```


Gets the header flags.

**Returns:**
[OpenTypeFlags](../../com.groupdocs.metadata.core/opentypeflags) - The header flags.
### getCreated() {#getCreated--}
```
public final Date getCreated()
```


Gets the created date.

**Returns:**
java.util.Date - The created date.
### getModified() {#getModified--}
```
public final Date getModified()
```


Gets the modified date.

**Returns:**
java.util.Date - The modified date.
### getGlyphBounds() {#getGlyphBounds--}
```
public final Rectangle getGlyphBounds()
```


Gets the glyph bounds.

**Returns:**
[Rectangle](../../com.groupdocs.metadata.core/rectangle) - The glyph bounds.
### getStyle() {#getStyle--}
```
public final OpenTypeStyles getStyle()
```


Gets the font style.

**Returns:**
[OpenTypeStyles](../../com.groupdocs.metadata.core/opentypestyles) - The font style.
### getDirectionHint() {#getDirectionHint--}
```
public final OpenTypeDirectionHint getDirectionHint()
```


Gets the direction hint.

**Returns:**
[OpenTypeDirectionHint](../../com.groupdocs.metadata.core/opentypedirectionhint) - The direction hint.
### getNames() {#getNames--}
```
public final OpenTypeBaseNameRecord[] getNames()
```


Gets the name records.

**Returns:**
com.groupdocs.metadata.core.OpenTypeBaseNameRecord[] - The name records.
### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Gets the name of the font family.

**Returns:**
java.lang.String - The name of the font family.
### getFontSubfamilyName() {#getFontSubfamilyName--}
```
public final String getFontSubfamilyName()
```


Gets the name of the font subfamily.

**Returns:**
java.lang.String - The name of the font subfamily.
### getFullFontName() {#getFullFontName--}
```
public final String getFullFontName()
```


Gets the full name of the font.

**Returns:**
java.lang.String - The full name of the font.
### getTypographicFamily() {#getTypographicFamily--}
```
public final String getTypographicFamily()
```


Gets the typographic family.

**Returns:**
java.lang.String - The typographic family.
### getTypographicSubfamily() {#getTypographicSubfamily--}
```
public final String getTypographicSubfamily()
```


Gets the typographic subfamily.

**Returns:**
java.lang.String - The typographic subfamily.
### getWeight() {#getWeight--}
```
public final OpenTypeWeight getWeight()
```


Gets the font weight.

**Returns:**
[OpenTypeWeight](../../com.groupdocs.metadata.core/opentypeweight) - The font weight.
### getWidth() {#getWidth--}
```
public final OpenTypeWidth getWidth()
```


Gets the font width.

**Returns:**
[OpenTypeWidth](../../com.groupdocs.metadata.core/opentypewidth) - The font width.
### getEmbeddingLicensingRights() {#getEmbeddingLicensingRights--}
```
public final OpenTypeLicensingRights getEmbeddingLicensingRights()
```


Gets the embedding licensing rights type.

**Returns:**
[OpenTypeLicensingRights](../../com.groupdocs.metadata.core/opentypelicensingrights) - The embedding licensing rights type.
