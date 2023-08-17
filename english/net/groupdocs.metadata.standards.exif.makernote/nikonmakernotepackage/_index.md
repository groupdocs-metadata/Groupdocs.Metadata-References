---
title: NikonMakerNotePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents NIKON MakerNote metadata.
type: docs
weight: 3770
url: /net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/
---
## NikonMakerNotePackage class

Represents NIKON MakerNote metadata.

```csharp
public sealed class NikonMakerNotePackage : MakerNotePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [NikonMakerNotePackage](nikonmakernotepackage)(TiffTag[]) | Initializes a new instance of the [`NikonMakerNotePackage`](../nikonmakernotepackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/colormode) { get; } | Gets the color mode. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [FlashSetting](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashsetting) { get; } | Gets the flash setting. |
| [FlashType](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashtype) { get; } | Gets the type of the flash. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/focusmode) { get; } | Gets the focus mode. |
| [Iso](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/iso) { get; } | Gets the iso. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Gets the TIFF tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MakerNoteVersion](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/makernoteversion) { get; } | Gets the MakerNote version. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/quality) { get; } | Gets the quality string. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sharpness) { get; } | Gets the sharpness. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/whitebalance) { get; } | Gets the white balance. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Removes all TIFF tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Adds or replaces the specified tag. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Creates a list from the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [MakerNotePackage](../makernotepackage)
* namespace [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
