---
title: ID3V2CommentFrame
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a COMM frame in an ID3V2Tag./id3v2tag.
type: docs
weight: 470
url: /net/groupdocs.metadata.formats.audio/id3v2commentframe/
---
## ID3V2CommentFrame class

Represents a COMM frame in an [`ID3V2Tag`](../id3v2tag).

```csharp
public sealed class ID3V2CommentFrame : ID3V2TagFrame
```

## Constructors

| Name | Description |
| --- | --- |
| [ID3V2CommentFrame](id3v2commentframe)(ID3V2EncodingType, string, string, string) | Initializes a new instance of the [`ID3V2CommentFrame`](../id3v2commentframe) class. |

## Properties

| Name | Description |
| --- | --- |
| [CommentEncoding](../../groupdocs.metadata.formats.audio/id3v2commentframe/commentencoding) { get; } | Gets the encoding of the comment. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Gets the frame data. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Gets the frame flags. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Gets the id of the frame (four characters matching the pattern [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Language](../../groupdocs.metadata.formats.audio/id3v2commentframe/language) { get; } | Gets the language of the comment (3 characters). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [ShortContentDescription](../../groupdocs.metadata.formats.audio/id3v2commentframe/shortcontentdescription) { get; } | Gets the short content description. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2commentframe/text) { get; } | Gets the text of the comment. |

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

This frame is intended for any kind of full text information that does not fit in any other frame.

**Learn more**

* [Handling the ID3v2 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### See Also

* class [ID3V2TagFrame](../id3v2tagframe)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
