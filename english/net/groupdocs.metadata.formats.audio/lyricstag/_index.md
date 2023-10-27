---
title: LyricsTag
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents Lyrics3 v2.00 metadata. Please find more information at http//id3.org/Lyrics3v2.
type: docs
weight: 600
url: /net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Represents Lyrics3 v2.00 metadata. Please find more information at http://id3.org/Lyrics3v2.

```csharp
public sealed class LyricsTag : CustomPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [LyricsTag](lyricstag)() | Initializes a new instance of the [`LyricsTag`](../lyricstag) class. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Gets or sets the additional information. This value is represented by the INF field. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Gets or sets the album name. This value is represented by the EAL field. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Gets or sets the artist name. This value is represented by the EAR field. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Gets or sets the author. This value is represented by the AUT field. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Gets or sets the lyrics. This value is represented by the LYR field. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Gets or sets the track title. This value is represented by the ETT field. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Gets the value of the field with the specified id. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Removes the field with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Adds or replaces the specified Lyrics3 field. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Creates a list from the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

Lyrics3 v2.00 uses fields to represent information. The data in a field can consist of ASCII characters in the range 01 to 254 according to the standard. As the ASCII character map is only defined from 00 to 128 ISO-8859-1 might be assumed. Numerical fields are 5 or 6 characters long, depending on location, and are padded with zeroes.

**Learn more**

* [Handling the Lyrics tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Examples

This code sample shows how to read the Lyrics tag from an MP3 file.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Alternatively, you can loop through a full list of tag fields
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
