---
title: DaePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents .dae file metadata.
type: docs
weight: 3440
url: /net/groupdocs.metadata.formats.threed.dae/daepackage/
---
## DaePackage class

Represents .dae file metadata.

```csharp
public sealed class DaePackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.threed.dae/daepackage/author) { get; set; } | Gets or sets the author of this asset |
| [Comment](../../groupdocs.metadata.formats.threed.dae/daepackage/comment) { get; set; } | Gets or sets the comment of this asset. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreationTime](../../groupdocs.metadata.formats.threed.dae/daepackage/creationtime) { get; set; } | Gets or Sets the creation time of this asset. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ModificationTime](../../groupdocs.metadata.formats.threed.dae/daepackage/modificationtime) { get; set; } | Gets or Sets the modification time of this asset. |
| [Name](../../groupdocs.metadata.formats.threed.dae/daepackage/name) { get; } | Gets the node name. |
| [Nodes](../../groupdocs.metadata.formats.threed.dae/daepackage/nodes) { get; } | Gets an array of [`DaeNode`](../daenode) entries inside the dae file. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Title](../../groupdocs.metadata.formats.threed.dae/daepackage/title) { get; set; } | Gets or sets the title of this asset |

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

* [Working with 3D files](https://docs.groupdocs.com/display/metadatanet/Working+with+ThreeD)

### Examples

The following code snippet shows how to get metadata from a 3D file.

```csharp
Encoding encoding = Encoding.GetEncoding(866);

using (Metadata metadata = new Metadata(Constants.InputDae))
{
    var root = metadata.GetRootPackage<DaePackage>();

    Console.WriteLine(root.Name);

    foreach (var node in root.DaePackage.Nodes)
    {
        Console.WriteLine(node.Name);
    }
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.ThreeD.Dae](../../groupdocs.metadata.formats.threed.dae)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
