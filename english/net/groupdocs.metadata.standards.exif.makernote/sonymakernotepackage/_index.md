---
title: SonyMakerNotePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents SONY MakerNote metadata.
type: docs
weight: 2860
url: /net/groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/
---
## SonyMakerNotePackage class

Represents SONY MakerNote metadata.

```csharp
public sealed class SonyMakerNotePackage : MakerNotePackage
```

## Properties

| Name | Description |
| --- | --- |
| [AFIlluminator](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/afilluminator) { get; } | Gets the AF illuminator type. |
| [Brightness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/brightness) { get; } | Gets the brightness. |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colormode) { get; } | Gets the color mode. |
| [ColorTemperature](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colortemperature) { get; } | Gets the color temperature. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/contrast) { get; } | Gets the contrast. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreativeStyle](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/creativestyle) { get; } | Gets the creative style. |
| [ExposureMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/exposuremode) { get; } | Gets the exposure mode. |
| [FlashLevel](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/flashlevel) { get; } | Gets the flash level. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/focusmode) { get; } | Gets the focus mode. |
| [Header](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/header) { get; } | Gets the MakerNote header. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Gets the TIFF tag with the specified id. (2 indexers) |
| [JpegQuality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/jpegquality) { get; } | Gets the JPEG quality. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Macro](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/macro) { get; } | Gets the macro. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MultiBurstImageHeight](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimageheight) { get; } | Gets the height of the multi burst image. |
| [MultiBurstImageWidth](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimagewidth) { get; } | Gets the width of the multi burst image. |
| [MultiBurstMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstmode) { get; } | Gets a value indicating whether the multi burst mode is on. |
| [PictureEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/pictureeffect) { get; } | Gets the picture effect. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/quality) { get; } | Gets the image quality. |
| [Rating](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/rating) { get; } | Gets the rating. |
| [ReleaseMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/releasemode) { get; } | Gets the release mode. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/saturation) { get; } | Gets the saturation. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sharpness) { get; } | Gets the sharpness. |
| [SoftSkinEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/softskineffect) { get; } | Gets the soft skin effect. |
| [SonyModelID](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sonymodelid) { get; } | Gets the sony model identifier. |
| [Teleconverter](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/teleconverter) { get; } | Gets the teleconverter type. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/whitebalance) { get; } | Gets the white balance. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Removes all TIFF tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Adds or replaces the specified tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Creates a list from the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [MakerNotePackage](../makernotepackage)
* namespace [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
