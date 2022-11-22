---
title: WavRootPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the root package allowing working with metadata in a WAV audio.
type: docs
weight: 600
url: /net/groupdocs.metadata.formats.audio/wavrootpackage/
---
## WavRootPackage class

Represents the root package allowing working with metadata in a WAV audio.

```csharp
public class WavRootPackage : RootMetadataPackage, IXmp
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Gets the file type metadata package. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RiffInfoPackage](../../groupdocs.metadata.formats.audio/wavrootpackage/riffinfopackage) { get; } | Gets the package containing RIFF Info tags. |
| [WavPackage](../../groupdocs.metadata.formats.audio/wavrootpackage/wavpackage) { get; } | Gets the WAV native metadata package. |
| [XmpPackage](../../groupdocs.metadata.formats.audio/wavrootpackage/xmppackage) { get; set; } | Gets or sets the XMP metadata package. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Handling metadata in WAV files](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+WAV+files)
* [Working with XMP metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Examples

This code sample shows how to extract technical audio information from a WAV file.

```csharp
using (Metadata metadata = new Metadata(Constants.InputWav))
{
    var root = metadata.GetRootPackage<WavRootPackage>();
    if (root.WavPackage != null)
    {
        Console.WriteLine(root.WavPackage.AudioFormat);
        Console.WriteLine(root.WavPackage.BitsPerSample);
        Console.WriteLine(root.WavPackage.BlockAlign);
        Console.WriteLine(root.WavPackage.ByteRate);
        Console.WriteLine(root.WavPackage.NumberOfChannels);
        Console.WriteLine(root.WavPackage.SampleRate);
    }
}
```

### See Also

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
