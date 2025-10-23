---
title: OggPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/
is_root: false
weight: 10
---

## OggPackage class

Represents a native metadata package in a OGG audio file.



**Inheritance:** [`OggPackage`](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The OggPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/__init__/#) | Initializes a new instance of the [`OggPackage`](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/count) | Gets the number of metadata properties. |
| [vendor](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/vendor) | Vendor |
| [title](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/title) | Track/Work name |
| [version](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/version) | The version field may be used to differentiate multiple versions of the same track title in a single collection. (e.g. remix info) |
| [album](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/album) | The collection name to which this track belongs |
| [tracknumber](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/tracknumber) | The track number of this piece if part of a specific larger collection or album |
| [artist](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/artist) | The artist generally considered responsible for the work. In popular music this is usually the performing band or singer. For classical music it would be the composer. For an audio book it would be the author of the original text. |
| [performer](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/performer) | The artist(s) who performed the work. In classical music this would be the conductor, orchestra, soloists. In an audio book it would be the actor who did the reading. In popular music this is typically the same as the ARTIST and is omitted. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/copyright) | Copyright attribution, e.g., '2001 Nobody's Band' or '1999 Jack Moffitt' |
| [license](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/license) | License information, for example, 'All Rights Reserved', 'Any Use Permitted', a URL to a license such as a Creative Commons license (e.g. "creativecommons.org/licenses/by/4.0/"), or similar. |
| [organization](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/organization) | Name of the organization producing the track (i.e. the 'record label') |
| [description](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/description) | A short text description of the contents |
| [genre](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/genre) | A short text indication of music genre |
| [date](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/date) | Date the track was recorded |
| [location](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/location) | Location where track was recorded |
| [contact](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/contact) | Contact information for the creators or distributors of the track. This could be a URL, an email address, the physical address of the producing label. |
| [isrc](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/isrc) | ISRC number for the track |
| [ogg_user_comments](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/ogg_user_comments) | Gets an array of [`OggUserComment`](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggusercomment) entries inside the metadata. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### Example 


This code sample shows how to extract technical audio information from a OGG file.

### See Also
* module [`groupdocs.metadata.formats.audio.ogg`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`OggPackage`](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggpackage)
* class [`OggUserComment`](/metadata/python-net/groupdocs.metadata.formats.audio.ogg/oggusercomment)
