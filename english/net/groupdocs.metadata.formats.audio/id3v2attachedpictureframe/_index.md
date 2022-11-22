---
title: ID3V2AttachedPictureFrame
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents an APIC frame in an ID3V2Tag./id3v2tag.
type: docs
weight: 420
url: /net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/
---
## ID3V2AttachedPictureFrame class

Represents an APIC frame in an [`ID3V2Tag`](../id3v2tag).

```csharp
public sealed class ID3V2AttachedPictureFrame : ID3V2TagFrame
```

## Constructors

| Name | Description |
| --- | --- |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor)(byte[]) | Initializes a new instance of the [`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) class. |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor_1)(ID3V2AttachedPictureType, string, byte[]) | Initializes a new instance of the [`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) class. |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor_2)(ID3V2EncodingType, string, ID3V2AttachedPictureType, string, byte[]) | Initializes a new instance of the [`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) class. |

## Properties

| Name | Description |
| --- | --- |
| [AttachedPictureType](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/attachedpicturetype) { get; } | Gets the type of the picture. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Gets the frame data. |
| [Description](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description) { get; } | Gets the picture description. The description has a maximum length of 64 characters, but may be empty. |
| [DescriptionEncoding](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/descriptionencoding) { get; } | Gets the encoding used to encode the picture description. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Gets the frame flags. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MimeType](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/mimetype) { get; } | Gets the MIME type of the picture. |
| [PictureData](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/picturedata) { get; } | Gets the picture data. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Handling the ID3v2 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### See Also

* class [ID3V2TagFrame](../id3v2tagframe)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
