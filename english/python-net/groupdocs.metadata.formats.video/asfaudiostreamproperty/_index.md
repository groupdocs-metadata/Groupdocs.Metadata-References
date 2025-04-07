---
title: AsfAudioStreamProperty class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/
is_root: false
weight: 10
---

## AsfAudioStreamProperty class

Represents Audio stream property metadata in the ASF media container.



**Inheritance:** [`AsfAudioStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty) → 
[`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The AsfAudioStreamProperty type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/count) | Gets the number of metadata properties. |
| [stream_type](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/stream_type) | Gets the type of this stream. |
| [stream_number](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/stream_number) | Gets the number of this stream. |
| [start_time](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/start_time) | Gets the presentation time of the first object, indicating where this digital media stream <br/>starts within the context of the timeline of the ASF file as a whole. |
| [end_time](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/end_time) | Gets the presentation time of the last object plus the duration of play, indicating where <br/>this digital media stream ends within the context of the timeline of the ASF file as a whole. |
| [bitrate](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/bitrate) | Gets the leak rate R, in bits per second, of a leaky bucket that contains the data portion <br/>of the stream without overflowing, excluding all ASF Data Packet overhead. |
| [alternate_bitrate](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/alternate_bitrate) | Gets the leak rate RAlt, in bits per second, of a leaky bucket that contains the data portion <br/>of the stream without overflowing, excluding all ASF Data Packet overhead. |
| [flags](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/flags) | Gets the flags. |
| [language](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/language) | Gets the stream language. |
| [average_time_per_frame](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/average_time_per_frame) | Gets the average time duration, measured in 100-nanosecond units, of each frame. |
| [average_bitrate](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/average_bitrate) | Gets the average bitrate. |
| [format_tag](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/format_tag) | Gets the unique ID of the codec used to encode the audio data. |
| [channels](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/channels) | Gets the number of audio channels. |
| [samples_per_second](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/samples_per_second) | Gets a value in Hertz (cycles per second) that represents the sampling rate of the audio stream. |
| [bits_per_sample](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/bits_per_sample) | Gets the number of bits per sample of monaural data. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`AsfAudioStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfaudiostreamproperty)
* class [`AsfBaseStreamProperty`](/metadata/python-net/groupdocs.metadata.formats.video/asfbasestreamproperty)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
