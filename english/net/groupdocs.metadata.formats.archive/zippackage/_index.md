---
title: ZipPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents ZIP archive metadata.
type: docs
weight: 400
url: /net/groupdocs.metadata.formats.archive/zippackage/
---
## ZipPackage class

Represents ZIP archive metadata.

```csharp
public sealed class ZipPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Comment](../../groupdocs.metadata.formats.archive/zippackage/comment) { get; set; } | Gets or sets the ZIP archive comment created by a user. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Files](../../groupdocs.metadata.formats.archive/zippackage/files) { get; } | Gets an array of [`ZipFile`](../zipfile) entries inside the ZIP archive. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [TotalEntries](../../groupdocs.metadata.formats.archive/zippackage/totalentries) { get; } | Gets the total number of entries inside the ZIP archive. |

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

* [Working with ZIP archives](https://docs.groupdocs.com/display/metadatanet/Working+with+ZIP+archives)

### Examples

The following code snippet shows how to get metadata from a ZIP archive.

```csharp
Encoding encoding = Encoding.GetEncoding(866);

using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    Console.WriteLine(root.ZipPackage.Comment);
    Console.WriteLine(root.ZipPackage.TotalEntries);

    foreach (var file in root.ZipPackage.Files)
    {
        Console.WriteLine(file.Name);
        Console.WriteLine(file.CompressedSize);
        Console.WriteLine(file.CompressionMethod);
        Console.WriteLine(file.Flags);
        Console.WriteLine(file.ModificationDateTime);
        Console.WriteLine(file.UncompressedSize);

        // Use a specific encoding for the file names
        Console.WriteLine(encoding.GetString(file.RawName));
    }
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Archive](../../groupdocs.metadata.formats.archive)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
