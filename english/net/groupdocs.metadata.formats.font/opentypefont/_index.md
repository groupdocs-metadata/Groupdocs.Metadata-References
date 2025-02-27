---
title: OpenTypeFont
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a single font extracted from a file.
type: docs
weight: 1740
url: /net/groupdocs.metadata.formats.font/opentypefont/
---
## OpenTypeFont class

Represents a single font extracted from a file.

```csharp
public class OpenTypeFont : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Created](../../groupdocs.metadata.formats.font/opentypefont/created) { get; } | Gets the created date. |
| [DirectionHint](../../groupdocs.metadata.formats.font/opentypefont/directionhint) { get; } | Gets the direction hint. |
| [EmbeddingLicensingRights](../../groupdocs.metadata.formats.font/opentypefont/embeddinglicensingrights) { get; } | Gets the embedding licensing rights type. |
| [Flags](../../groupdocs.metadata.formats.font/opentypefont/flags) { get; } | Gets the header flags. |
| [FontFamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontfamilyname) { get; } | Gets the name of the font family. |
| [FontRevision](../../groupdocs.metadata.formats.font/opentypefont/fontrevision) { get; } | Gets the font revision. |
| [FontSubfamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontsubfamilyname) { get; } | Gets the name of the font subfamily. |
| [FullFontName](../../groupdocs.metadata.formats.font/opentypefont/fullfontname) { get; } | Gets the full name of the font. |
| [GlyphBounds](../../groupdocs.metadata.formats.font/opentypefont/glyphbounds) { get; } | Gets the glyph bounds. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MajorVersion](../../groupdocs.metadata.formats.font/opentypefont/majorversion) { get; } | Gets the header major version. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MinorVersion](../../groupdocs.metadata.formats.font/opentypefont/minorversion) { get; } | Gets the header minor version. |
| [Modified](../../groupdocs.metadata.formats.font/opentypefont/modified) { get; } | Gets the modified date. |
| [Names](../../groupdocs.metadata.formats.font/opentypefont/names) { get; } | Gets the name records. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [SfntVersion](../../groupdocs.metadata.formats.font/opentypefont/sfntversion) { get; } | Gets the header SFNT version. |
| [Style](../../groupdocs.metadata.formats.font/opentypefont/style) { get; } | Gets the font style. |
| [TypographicFamily](../../groupdocs.metadata.formats.font/opentypefont/typographicfamily) { get; } | Gets the typographic family. |
| [TypographicSubfamily](../../groupdocs.metadata.formats.font/opentypefont/typographicsubfamily) { get; } | Gets the typographic subfamily. |
| [Weight](../../groupdocs.metadata.formats.font/opentypefont/weight) { get; } | Gets the font weight. |
| [Width](../../groupdocs.metadata.formats.font/opentypefont/width) { get; } | Gets the font width. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with OpenType fonts](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
