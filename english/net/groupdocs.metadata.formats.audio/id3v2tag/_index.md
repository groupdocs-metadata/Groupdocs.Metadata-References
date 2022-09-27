---
title: ID3V2Tag
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents an ID3v2 tag. Please find more information at https//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2.
type: docs
weight: 480
url: /net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Represents an ID3v2 tag. Please find more information at [https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2).

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Constructors

| Name | Description |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Initializes a new instance of the [`ID3V2Tag`](../id3v2tag) class. |

## Properties

| Name | Description |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Gets or sets the Album/Movie/Show title. This value is represented by the TALB frame. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Gets or sets the Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group. This value is represented by the TPE1 frame. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Gets or sets the attached pictures directly related to the audio file. This value is represented by the APIC frame. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Gets or sets the Band/Orchestra/Accompaniment. This value is represented by the TPE2 frame. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Gets or sets the number of beats per minute in the main part of the audio. This value is represented by the TBPM frame. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Gets or sets the user comments. This value is represented by the COMM frame. The frame is intended for any kind of full text information that does not fit in any other frame. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Gets or sets the composers. The names are separated with the "/" character. This value is represented by the TCOM frame. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Gets or sets the content type. This value is represented by the TCON frame. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Gets or sets the copyright message. This value is represented by the TCOP frame. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Gets or sets a numeric string in the DDMM format containing the date for the recording. This field is always four characters long. This value is represented by the TDAT frame. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Gets or sets the name of the person or organization that encoded the audio file. This value is represented by the TENC frame. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Gets or sets the International Standard Recording Code (ISRC) (12 characters). This value is represented by the TSRC frame. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Gets or sets the length of the audio file in milliseconds, represented as a numeric string. This value is represented by the TLEN frame. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Gets or sets the musical key in which the sound starts. This value is represented by the TKEY frame. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Gets or sets the original album/movie/show title. This value is represented by the TOAL frame. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Gets or sets the name of the label or publisher. This value is represented by the TPUB frame. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Gets or sets the size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string. This value is represented by the TSIZ frame. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Gets or sets the used audio encoder and its settings when the file was encoded. This value is represented by the TSSE frame. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Gets or sets the Subtitle/Description refinement. This value is represented by the TIT3 frame. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Gets the size of the tag. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Gets or sets a numeric string in the HHMM format containing the time for the recording. This field is always four characters long. This value is represented by the TIME frame. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Gets or sets the Title/Song name/Content description. This value is represented by the TIT2 frame. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Gets or sets a numeric string containing the order number of the audio-file on its original recording. This value is represented by the TRCK frame. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Gets the number of times the file has been played. This value is represented by the PCNT frame. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Gets the ID3 version. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Gets or sets a numeric string with a year of the recording. This frames is always four characters long (until the year 10000). This value is represented by the TYER frame. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Adds a frame to the tag. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Removes all frames with the specified id. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Gets an array of frames with the specified id. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Removes the specified frame from the tag. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Removes all attached pictures stored in APIC frames. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Removes all frames having the same id as the specified one and adds the new frame to the tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Creates a list from the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Handling the ID3v2 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Examples

This example shows how to read the ID3v2 tag in an MP3 file.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### See Also

* class [ID3Tag](../id3tag)
* namespace [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
