---
title: ApePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents an APE v2 metadata package. Please find more information at http//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key.
type: docs
weight: 500
url: /net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

Represents an APE v2 metadata package. Please find more information at [http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key).

```csharp
public sealed class ApePackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | Gets the abstract link. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | Gets the album. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | Gets the artist. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | Gets the bibliography. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | Gets the comment. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | Gets the composer. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | Gets the conductor. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | Gets the copyright. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | Gets the debut album. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | Gets the file. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | Gets the genre. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | Gets the ISBN number with check digit. See more: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | Gets the International Standard Recording Number. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | Gets the language. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | Gets the publication right. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | Gets the publisher. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | Gets the record location. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | Gets the subtitle. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | Gets the title. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | Gets the track number. |

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

* [Handling the APEv2 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### Examples

This example demonstrates how to read the APEv2 tag in an MP3 file.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
