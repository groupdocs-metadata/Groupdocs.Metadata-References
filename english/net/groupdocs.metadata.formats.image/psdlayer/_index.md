---
title: PsdLayer
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a layer in a PSD file.
type: docs
weight: 2060
url: /net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

Represents a layer in a PSD file.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Gets the bits per pixel value. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Gets the bottom layer position. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Gets the number of channels. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Gets the layer flags. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Gets the height. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Gets the left layer position. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Gets the overall layer length in bytes. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Gets the layer name. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Gets the layer opacity. 0 = transparent, 255 = opaque. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Gets the right layer position. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Gets the top layer position. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Gets the width. |

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

* [Working with metadata in PSD images](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
