---
title: ID3V2Tag class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 90
url: /python-net/groupdocs.metadata.formats.audio/id3v2tag/
is_root: false
---

## ID3V2Tag class

Represents an ID3v2 tag.
Please find more information at [https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2).



**Inheritance:** [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag) → 
[`ID3Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3tag) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ID3V2Tag type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/__init__/#) | Initializes a new instance of the [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/count) | Gets the number of metadata properties. |
| [version](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/version) | Gets the ID3 version. |
| [tag_size](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/tag_size) | Gets the size of the tag. |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/album) | Gets or sets the Album/Movie/Show title.<br/>This value is represented by the TALB frame. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/artist) | Gets or sets the Lead artist(s)/Lead performer(s)/Soloist(s)/Performing group.<br/>This value is represented by the TPE1 frame. |
| [band](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/band) | Gets or sets the Band/Orchestra/Accompaniment.<br/>This value is represented by the TPE2 frame. |
| [bits_per_minute](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/bits_per_minute) | Gets or sets the number of beats per minute in the main part of the audio.<br/>This value is represented by the TBPM frame. |
| [composers](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/composers) | Gets or sets the composers. The names are separated with the "/" character.<br/>This value is represented by the TCOM frame. |
| [content_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/content_type) | Gets or sets the content type.<br/>This value is represented by the TCON frame. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/copyright) | Gets or sets the copyright message.<br/>This value is represented by the TCOP frame. |
| [date](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/date) | Gets or sets a numeric string in the DDMM format containing the date for the recording. This field is always four characters long.<br/>This value is represented by the TDAT frame. |
| [encoded_by](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/encoded_by) | Gets or sets the name of the person or organization that encoded the audio file.<br/>This value is represented by the TENC frame. |
| [publisher](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/publisher) | Gets or sets the name of the label or publisher.<br/>This value is represented by the TPUB frame. |
| [time](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/time) | Gets or sets a numeric string in the HHMM format containing the time for the recording. This field is always four characters long.<br/>This value is represented by the TIME frame. |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/title) | Gets or sets the Title/Song name/Content description.<br/>This value is represented by the TIT2 frame. |
| [subtitle](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/subtitle) | Gets or sets the Subtitle/Description refinement.<br/>This value is represented by the TIT3 frame. |
| [musical_key](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/musical_key) | Gets or sets the musical key in which the sound starts.<br/>This value is represented by the TKEY frame. |
| [length_in_milliseconds](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/length_in_milliseconds) | Gets or sets the length of the audio file in milliseconds, represented as a numeric string.<br/>This value is represented by the TLEN frame. |
| [original_album](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/original_album) | Gets or sets the original album/movie/show title.<br/>This value is represented by the TOAL frame. |
| [track_number](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/track_number) | Gets or sets a numeric string containing the order number of the audio-file on its original recording.<br/>This value is represented by the TRCK frame. |
| [size_in_bytes](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/size_in_bytes) | Gets or sets the size of the audio file in bytes, excluding the ID3v2 tag, represented as a numeric string.<br/>This value is represented by the TSIZ frame. |
| [isrc](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/isrc) | Gets or sets the International Standard Recording Code (ISRC) (12 characters).<br/>This value is represented by the TSRC frame. |
| [software_hardware](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/software_hardware) | Gets or sets the used audio encoder and its settings when the file was encoded.<br/>This value is represented by the TSSE frame. |
| [year](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/year) | Gets or sets a numeric string with a year of the recording. This frames is always four characters long (until the year 10000).<br/>This value is represented by the TYER frame. |
| [comments](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/comments) | Gets or sets the user comments.<br/>This value is represented by the COMM frame.<br/>The frame is intended for any kind of full text information that does not fit in any other frame. |
| [attached_pictures](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/attached_pictures) | Gets or sets the attached pictures directly related to the audio file.<br/>This value is represented by the APIC frame. |
| [track_play_counter](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/track_play_counter) | Gets the number of times the file has been played.<br/>This value is represented by the PCNT frame. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/to_list/#) | Creates a list from the package. |
| [`remove_attached_pictures(self)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/remove_attached_pictures/#) | Removes all attached pictures stored in APIC frames. |
| [`get(self, frame_id)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/get/#system.string) | Gets an array of frames with the specified id. |
| [`set(self, frame)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/set/#groupdocs.metadata.formats.audio.id3v2tagframe) | Removes all frames having the same id as the specified one and adds the new frame to the tag. |
| [`clear(self, frame_id)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/clear/#system.string) | Removes all frames with the specified id. |
| [`add(self, frame)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/add/#groupdocs.metadata.formats.audio.id3v2tagframe) | Adds a frame to the tag. |
| [`remove(self, frame)`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/remove/#groupdocs.metadata.formats.audio.id3v2tagframe) | Removes the specified frame from the tag. |



### Remarks 


**Learn more** |
|
 |

### Example 


This example shows how to read the ID3v2 tag in an MP3 file.

### See Also
* module [`groupdocs.metadata.formats.audio`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ID3Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3tag)
* class [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
