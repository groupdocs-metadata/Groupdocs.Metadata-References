---
title: ID3V2AttachedPictureFrame class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents an APIC frame in a ID3V2Tag."
type: docs
url: /python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/
is_root: false
weight: 50
---


## ID3V2AttachedPictureFrame class

Represents an APIC frame in a [`ID3V2Tag`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tag/).

Learn more

- [Handling the ID3v2 tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

The ID3V2AttachedPictureFrame type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/#encoding-mime_type-picture_type-description-picture_data) | Initializes a new ID3V2AttachedPictureFrame. |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/#picture_type-description-picture_data) | Initializes a new ID3V2AttachedPictureFrame instance. |
| [__init__](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/__init__/#picture_data) | Initializes a new instance of ID3V2AttachedPictureFrame. |

### Methods
| Method | Description |
| :- | :- |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [attached_picture_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/attached_picture_type/) | The type of the picture. |
| [description](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description/) | The picture description, with a maximum length of 64 characters (may be empty). |
| [description_encoding](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description_encoding/) | The encoding used to encode the picture description. |
| [mime_type](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/mime_type/) | The MIME type of the picture. |
| [picture_data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/picture_data/) | The picture data. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [data](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/data/) | The frame data. (inherited from [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/)) |
| [flags](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/flags/) | The frame flags. (inherited from [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/)) |
| [id](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/id/) | The id of the frame (four characters matching the pattern [A-Z0-9]). (inherited from [`ID3V2TagFrame`](/metadata/python-net/groupdocs.metadata.formats.audio/id3v2tagframe/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### See Also
* module [`groupdocs.metadata.formats.audio`](/metadata/python-net/groupdocs.metadata.formats.audio/)
