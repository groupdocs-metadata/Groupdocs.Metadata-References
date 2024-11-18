---
title: FbxPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents .fbx file metadata.
type: docs
weight: 3490
url: /net/groupdocs.metadata.formats.threed.fbx/fbxpackage/
---
## FbxPackage class

Represents .fbx file metadata.

```csharp
public sealed class FbxPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [ApplicationName](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/applicationname) { get; set; } | Gets or sets the application name of this asset |
| [ApplicationVendor](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/applicationvendor) { get; set; } | Gets or sets the a application vendor of this asset |
| [ApplicationVersion](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/applicationversion) { get; set; } | Gets or sets the application version of this asset |
| [Author](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/author) { get; set; } | Gets or sets the author of this asset |
| [Comment](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/comment) { get; set; } | Gets or sets the comment of this asset. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Name](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/name) { get; } | Gets the node name. |
| [Nodes](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/nodes) { get; } | Gets an array of [`FbxNode`](../fbxnode) entries inside the Fbx file. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Url](../../groupdocs.metadata.formats.threed.fbx/fbxpackage/url) { get; set; } | Gets or sets the url of this asset |

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

using (Metadata metadata = new Metadata(Constants.InputFbx))
{
    var root = metadata.GetRootPackage<FbxPackage>();

    Console.WriteLine(root.Name);

    foreach (var node in root.FbxPackage.Nodes)
    {
        Console.WriteLine(node.Name);
    }
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.ThreeD.Fbx](../../groupdocs.metadata.formats.threed.fbx)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
