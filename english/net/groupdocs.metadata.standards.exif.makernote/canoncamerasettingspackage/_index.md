---
title: CanonCameraSettingsPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents CANON camera settings.
type: docs
weight: 4340
url: /net/groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/
---
## CanonCameraSettingsPackage class

Represents CANON camera settings.

```csharp
public sealed class CanonCameraSettingsPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [AFPoint](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/afpoint) { get; } | Gets the AFPoint. |
| [CameraIso](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/cameraiso) { get; } | Gets the camera iso. |
| [CanonExposureMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonexposuremode) { get; } | Gets the canon exposure mode. |
| [CanonFlashMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonflashmode) { get; } | Gets the canon flash mode. |
| [CanonImageSize](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonimagesize) { get; } | Gets the size of the canon image. |
| [ContinuousDrive](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/continuousdrive) { get; } | Gets the continuous drive. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/contrast) { get; } | Gets the contrast. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DigitalZoom](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/digitalzoom) { get; } | Gets the digital zoom. |
| [EasyMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/easymode) { get; } | Gets the easy mode. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusmode) { get; } | Gets the focus mode. |
| [FocusRange](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusrange) { get; } | Gets the focus range. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/imagestabilization) { get; } | Gets the image stabilization. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/lenstype) { get; } | Gets the type of the lens. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/macromode) { get; } | Gets the macro mode. |
| [MaxFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/maxfocallength) { get; } | Gets the maximum length of the focal. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MeteringMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/meteringmode) { get; } | Gets the metering mode. |
| [MinFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/minfocallength) { get; } | Gets the minimum length of the focal. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/quality) { get; } | Gets the quality. |
| [RecordMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/recordmode) { get; } | Gets the record mode. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/saturation) { get; } | Gets the saturation. |
| [SelfTimer](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/selftimer) { get; } | Gets the self timer. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/sharpness) { get; } | Gets the sharpness. |

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

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
