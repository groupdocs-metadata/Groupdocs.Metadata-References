---
title: ExifPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents an EXIF metadata package Exchangeable Image File Format.
type: docs
weight: 4030
url: /net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Represents an EXIF metadata package (Exchangeable Image File Format).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [ExifPackage](exifpackage)() | Initializes a new instance of the [`ExifPackage`](../exifpackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Gets or sets the name of the camera owner, photographer or image creator. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Gets or sets the copyright notice. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Gets or sets the date and time of image creation. In the EXIF standard, it is the date and time the file was changed. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Gets the EXIF IFD data. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Gets the GPS data. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Gets or sets a character string giving the title of the image. It may be a comment such as "1988 company picnic" or the like. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Gets or sets the number of rows of image data. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Gets or sets the number of columns of image data, equal to the number of pixels per row. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Gets the TIFF tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Gets or sets the manufacturer of the recording equipment. This is the manufacturer of the DSC, scanner, video digitizer or other equipment that generated the image. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Gets or sets the model name or model number of the equipment. This is the model name or number of the DSC, scanner, video digitizer or other equipment that generated the image. |
| [Orientation](../../groupdocs.metadata.standards.exif/exifpackage/orientation) { get; set; } | Gets or sets the orientation. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Gets or sets the name and version of the software or firmware of the camera or image input device used to generate the image. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Gets the image thumbnail represented as an array of bytes. |

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

### Remarks

**Learn more**

* [Working with EXIF metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Examples

This code sample demonstrates how to update common EXIF properties.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Set the EXIF package if it's missing
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2024 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### See Also

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* namespace [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
