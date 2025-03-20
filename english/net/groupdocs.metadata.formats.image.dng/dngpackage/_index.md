---
title: DngPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents native DNG metadata.
type: docs
weight: 2060
url: /net/groupdocs.metadata.formats.image.dng/dngpackage/
---
## DngPackage class

Represents native DNG metadata.

```csharp
public sealed class DngPackage : CustomPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [DngPackage](dngpackage)() | Initializes a new instance of the [`Metadata`](../../groupdocs.metadata/metadata) class. |

## Properties

| Name | Description |
| --- | --- |
| [Aperture](../../groupdocs.metadata.formats.image.dng/dngpackage/aperture) { get; } | Gets the aperture. |
| [Artist](../../groupdocs.metadata.formats.image.dng/dngpackage/artist) { get; } | Gets the author of image. |
| [CameraManufacturer](../../groupdocs.metadata.formats.image.dng/dngpackage/cameramanufacturer) { get; } | Gets the camera manufacturer. |
| [ColorsCount](../../groupdocs.metadata.formats.image.dng/dngpackage/colorscount) { get; } | Gets the colors. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Description](../../groupdocs.metadata.formats.image.dng/dngpackage/description) { get; } | Gets the description of colors (RGBG,RGBE,GMCY, or GBTG). |
| [DngVersion](../../groupdocs.metadata.formats.image.dng/dngpackage/dngversion) { get; } | Gets the DNG version. |
| [Filters](../../groupdocs.metadata.formats.image.dng/dngpackage/filters) { get; } | Gets the Bit mask describing the order of color pixels in the matrix. |
| [FocalLength](../../groupdocs.metadata.formats.image.dng/dngpackage/focallength) { get; } | Gets the length of the focal. |
| [GpsData](../../groupdocs.metadata.formats.image.dng/dngpackage/gpsdata) { get; } | Gets the GPS data. |
| [IsFoveon](../../groupdocs.metadata.formats.image.dng/dngpackage/isfoveon) { get; } | Gets the is foveon matrix. |
| [IsoSpeed](../../groupdocs.metadata.formats.image.dng/dngpackage/isospeed) { get; } | Gets the ISO sensitivity. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Model](../../groupdocs.metadata.formats.image.dng/dngpackage/model) { get; } | Gets the camera model. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RawCount](../../groupdocs.metadata.formats.image.dng/dngpackage/rawcount) { get; } | Gets the number of RAW images in file (0 means that the file has not been recognized). |
| [ShotOrder](../../groupdocs.metadata.formats.image.dng/dngpackage/shotorder) { get; } | Gets serial number of image. |
| [ShutterSpeed](../../groupdocs.metadata.formats.image.dng/dngpackage/shutterspeed) { get; } | Gets the shutter speed. |
| [Software](../../groupdocs.metadata.formats.image.dng/dngpackage/software) { get; } | Gets the software. |
| [Timestamp](../../groupdocs.metadata.formats.image.dng/dngpackage/timestamp) { get; } | Gets the date of shooting. |
| [TranslationCfaDng](../../groupdocs.metadata.formats.image.dng/dngpackage/translationcfadng) { get; } | Gets the translation array for CFA mosaic DNG format. |

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

* [Working with DNG metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+DNG+metadata)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Image.Dng](../../groupdocs.metadata.formats.image.dng)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
