---
title: OggPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a native metadata package in a OGG audio file.
type: docs
weight: 730
url: /net/groupdocs.metadata.formats.audio.ogg/oggpackage/
---
## OggPackage class

Represents a native metadata package in a OGG audio file.

```csharp
public sealed class OggPackage : CustomPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [OggPackage](oggpackage)() | Initializes a new instance of the [`OggPackage`](../oggpackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio.ogg/oggpackage/album) { get; } | The collection name to which this track belongs |
| [Artist](../../groupdocs.metadata.formats.audio.ogg/oggpackage/artist) { get; } | The artist generally considered responsible for the work. In popular music this is usually the performing band or singer. For classical music it would be the composer. For an audio book it would be the author of the original text. |
| [Contact](../../groupdocs.metadata.formats.audio.ogg/oggpackage/contact) { get; } | Contact information for the creators or distributors of the track. This could be a URL, an email address, the physical address of the producing label. |
| [Copyright](../../groupdocs.metadata.formats.audio.ogg/oggpackage/copyright) { get; } | Copyright attribution, e.g., '2001 Nobody's Band' or '1999 Jack Moffitt' |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Date](../../groupdocs.metadata.formats.audio.ogg/oggpackage/date) { get; } | Date the track was recorded |
| [Description](../../groupdocs.metadata.formats.audio.ogg/oggpackage/description) { get; } | A short text description of the contents |
| [Genre](../../groupdocs.metadata.formats.audio.ogg/oggpackage/genre) { get; } | A short text indication of music genre |
| [Isrc](../../groupdocs.metadata.formats.audio.ogg/oggpackage/isrc) { get; } | ISRC number for the track |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [License](../../groupdocs.metadata.formats.audio.ogg/oggpackage/license) { get; } | License information, for example, 'All Rights Reserved', 'Any Use Permitted', a URL to a license such as a Creative Commons license (e.g. "creativecommons.org/licenses/by/4.0/"), or similar. |
| [Location](../../groupdocs.metadata.formats.audio.ogg/oggpackage/location) { get; } | Location where track was recorded |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [OggUserComments](../../groupdocs.metadata.formats.audio.ogg/oggpackage/oggusercomments) { get; } | Gets an array of [`OggUserComment`](../oggusercomment) entries inside the metadata. |
| [Organization](../../groupdocs.metadata.formats.audio.ogg/oggpackage/organization) { get; } | Name of the organization producing the track (i.e. the 'record label') |
| [Performer](../../groupdocs.metadata.formats.audio.ogg/oggpackage/performer) { get; } | The artist(s) who performed the work. In classical music this would be the conductor, orchestra, soloists. In an audio book it would be the actor who did the reading. In popular music this is typically the same as the ARTIST and is omitted. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Title](../../groupdocs.metadata.formats.audio.ogg/oggpackage/title) { get; } | Track/Work name |
| [Tracknumber](../../groupdocs.metadata.formats.audio.ogg/oggpackage/tracknumber) { get; } | The track number of this piece if part of a specific larger collection or album |
| [Vendor](../../groupdocs.metadata.formats.audio.ogg/oggpackage/vendor) { get; } | Vendor |
| [Version](../../groupdocs.metadata.formats.audio.ogg/oggpackage/version) { get; } | The version field may be used to differentiate multiple versions of the same track title in a single collection. (e.g. remix info) |

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

* [Handling metadata in OGG files](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+OGG+files)

### Examples

This code sample shows how to extract technical audio information from a OGG file.

```csharp
using (Metadata metadata = new Metadata("input.ogg"))
{
    var root = metadata.GetRootPackage<OggRootPackage>();
    if (root.OggPackage != null)
    {
        Console.WriteLine(root.OggPackage.Title);
        Console.WriteLine(root.OggPackage.Version);
        Console.WriteLine(root.OggPackage.Album);
    }
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Audio.Ogg](../../groupdocs.metadata.formats.audio.ogg)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
