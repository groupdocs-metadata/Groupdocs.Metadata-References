---
title: XmpPacketWrapper
second_title: GroupDocs.Metadata for .NET API Reference
description: Contains serialized XMP package including header and trailer. A wrapper consisting of a pair of XML processing instructions PIs may be placed around the rdfRDF element.
type: docs
weight: 4490
url: /net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Contains serialized XMP package including header and trailer. A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.

```csharp
public class XmpPacketWrapper : MetadataPackage, IXmpType
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | Initializes a new instance of the [`XmpPacketWrapper`](../xmppacketwrapper) class. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPI, XmpTrailerPI, XmpMeta) | Initializes a new instance of the [`XmpPacketWrapper`](../xmppacketwrapper) class. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [HeaderPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/headerpi) { get; set; } | Gets or sets the header processing instruction. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Meta](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/meta) { get; set; } | Gets or sets the XMP meta. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PackageCount](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packagecount) { get; } | Gets the number of packages inside the XMP structure. |
| [Packages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packages) { get; } | Gets array of [`XmpPackage`](../xmppackage) inside XMP. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Schemes](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes) { get; } | Provides access to known XMP schemas. |
| [TrailerPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/trailerpi) { get; set; } | Gets or sets the trailer processing instruction. |

## Methods

| Name | Description |
| --- | --- |
| [AddPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage)(XmpPackage) | Adds the package. |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [ClearPackages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/clearpackages)() | Removes all [`XmpPackage`](../xmppackage) inside XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| [ContainsPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/containspackage)(string) | Determines whether package is exist in XMP wrapper. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [GetPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getpackage)(string) | Gets package by namespace uri. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getxmprepresentation)() | Returns string contained value in XMP format. |
| [RemovePackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/removepackage)(XmpPackage) | Removes the specified package. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with XMP metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Examples

This example shows how to update XMP metadata properties.

```csharp
using (Metadata metadata = new Metadata(Constants.GifWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null && root.XmpPackage != null)
    {
        // if there is no such scheme in the XMP package we should create it
        if (root.XmpPackage.Schemes.DublinCore == null)
        {
            root.XmpPackage.Schemes.DublinCore = new XmpDublinCorePackage();
        }
        root.XmpPackage.Schemes.DublinCore.Format = "image/gif";
        root.XmpPackage.Schemes.DublinCore.SetRights("Copyright (C) 2011-2022 GroupDocs. All Rights Reserved");
        root.XmpPackage.Schemes.DublinCore.SetSubject("test");

        if (root.XmpPackage.Schemes.CameraRaw == null)
        {
            root.XmpPackage.Schemes.CameraRaw = new XmpCameraRawPackage();
        }
        root.XmpPackage.Schemes.CameraRaw.Shadows = 50;
        root.XmpPackage.Schemes.CameraRaw.AutoBrightness = true;
        root.XmpPackage.Schemes.CameraRaw.AutoExposure = true;
        root.XmpPackage.Schemes.CameraRaw.CameraProfile = "test";
        root.XmpPackage.Schemes.CameraRaw.Exposure = 0.0001;

        // If you don't want to keep the old values just replace the whole scheme
        root.XmpPackage.Schemes.XmpBasic = new XmpBasicPackage();
        root.XmpPackage.Schemes.XmpBasic.CreateDate = DateTime.Today;
        root.XmpPackage.Schemes.XmpBasic.BaseUrl = "https://groupdocs.com";
        root.XmpPackage.Schemes.XmpBasic.Rating = 5;

        root.XmpPackage.Schemes.BasicJobTicket = new XmpBasicJobTicketPackage();

        // Set a complex type property
        root.XmpPackage.Schemes.BasicJobTicket.Jobs = new[]
        {
            new XmpJob
            {
                ID = "1",
                Name = "test job",
                Url = "https://groupdocs.com"
            },
        };

        // ... 

        metadata.Save(Constants.OutputGif);
    }
}
```

### See Also

* class [MetadataPackage](../../groupdocs.metadata.common/metadatapackage)
* interface [IXmpType](../ixmptype)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
