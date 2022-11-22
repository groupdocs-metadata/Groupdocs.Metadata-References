---
title: ID3V1Tag
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents an ID3v1 tag. Please find more information at https//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1.
type: docs
weight: 410
url: /net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

Represents an ID3v1 tag. Please find more information at [https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1).

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## Constructors

| Name | Description |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | Initializes a new instance of the [`ID3V1Tag`](../id3v1tag) class. |

## Properties

| Name | Description |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | Gets or sets the album. Maximum length is 30 characters. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | Gets or sets the artist. Maximum length is 30 characters. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | Gets or sets the comment. Maximum length is 30 characters. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | Gets or sets the genre identifier. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | Gets or sets the title. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | Gets or sets the track number. Presented in a ID3v1.1 tag only. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | Gets the ID3 version. It can be ID3 or ID3v1.1 |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | Gets or sets the year. Maximum length is 4 characters. |

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

ID3(v1) tag is a small chunk of extra data at the end of MP3. Please find more information at [http://id3.org/ID3v1](http://id3.org/ID3v1).

**Learn more**

* [Handling the ID3v1 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### Examples

This code sample shows how to read the ID3v1 tag in an MP3 file.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### See Also

* class [ID3Tag](../id3tag)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
