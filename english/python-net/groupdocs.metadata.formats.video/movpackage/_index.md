---
title: MovPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.video/movpackage/
is_root: false
weight: 280
---

## MovPackage class

Represents QuickTime metadata.



**Inheritance:** [`MovPackage`](/metadata/python-net/groupdocs.metadata.formats.video/movpackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The MovPackage type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/count) | Gets the number of metadata properties. |
| [director](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/director) | Name of the director of the movie content. |
| [description](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/description) | Description of the movie file content. |
| [location_motion](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_motion) | An indication of the direction the camera is moving during the shot. |
| [location_facing](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_facing) | An indication of the direction the camera is facing during the shot. |
| [location_date](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_date) | A date and time, stored using the extended format defined in ISO 8601:2004- Data elements and interchange format. |
| [location_role](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_role) | A single byte, binary value containing a value from the set: 0 indicates “shooting location”, 1 indicates “real location”, 2 indicates “fictional location”.<br/>Other values are reserved. |
| [location_note](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_note) | Descriptive comment. |
| [location_body](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_body) | The astronomical body, for compatibility with the 3GPP format |
| [location_name](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/location_name) | Name of the location. |
| [user_ratings](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/user_ratings) | A number, assigned by the user, that indicates the rating or relative value of the movie.<br/>This number can range from 0.0 to 5.0. A value of 0.0 indicates that the user has not rated the movie. |
| [users](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/users) | A name indicating a user-defined collection that includes this movie. |
| [year](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/year) | Year when the movie file or the original content was created or recorded. |
| [software](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/software) | Name of software used to create the movie file content. |
| [producer](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/producer) | Name of producer of movie file content. |
| [album](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/album) | Album or collection name of which the movie content forms a part |
| [keywords](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/keywords) | Keywords associated with the movie file content. |
| [information](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/information) | Information about the movie file content. |
| [genre](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/genre) | Text describing the genre or genres to which the movie content conforms. |
| [title](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/title) | The title of the movie file content. |
| [creation_date](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/creation_date) | The date the movie file content was created. |
| [copyright](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/copyright) | Copyright statement for the movie file content. |
| [comment](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/comment) | User entered comment regarding the movie file content. |
| [author](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/author) | Name of the author of the movie file content. |
| [artwork](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/artwork) | A single image that can represent the movie file content. |
| [artist](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/artist) | Name of the artist who created the movie file content. |
| [publisher](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/publisher) | Name of publisher of movie file content. |
| [movie_creation_time](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/movie_creation_time) | A 32-bit integer that specifies the creation calendar date and time for the movie atom. |
| [movie_modification_time](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/movie_modification_time) | A 32-bit integer that specifies the calendar date and time of the last change to the movie atom. |
| [movie_duration](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/movie_duration) | A time value that indicates the duration of the movie in seconds. |
| [atoms](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/atoms) | Gets an array of [`MovAtom`](/metadata/python-net/groupdocs.metadata.formats.video/movatom) atoms. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.video/movpackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.video`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`MovAtom`](/metadata/python-net/groupdocs.metadata.formats.video/movatom)
* class [`MovPackage`](/metadata/python-net/groupdocs.metadata.formats.video/movpackage)
