---
title: MovPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents QuickTime metadata.
type: docs
weight: 4040
url: /net/groupdocs.metadata.formats.video/movpackage/
---
## MovPackage class

Represents QuickTime metadata.

```csharp
public sealed class MovPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.video/movpackage/album) { get; } | Album or collection name of which the movie content forms a part |
| [Artist](../../groupdocs.metadata.formats.video/movpackage/artist) { get; } | Name of the artist who created the movie file content. |
| [Artwork](../../groupdocs.metadata.formats.video/movpackage/artwork) { get; } | A single image that can represent the movie file content. |
| [Atoms](../../groupdocs.metadata.formats.video/movpackage/atoms) { get; } | Gets an array of [`MovAtom`](../movatom) atoms. |
| [Author](../../groupdocs.metadata.formats.video/movpackage/author) { get; } | Name of the author of the movie file content. |
| [Comment](../../groupdocs.metadata.formats.video/movpackage/comment) { get; } | User entered comment regarding the movie file content. |
| [Copyright](../../groupdocs.metadata.formats.video/movpackage/copyright) { get; } | Copyright statement for the movie file content. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreationDate](../../groupdocs.metadata.formats.video/movpackage/creationdate) { get; } | The date the movie file content was created. |
| [Description](../../groupdocs.metadata.formats.video/movpackage/description) { get; } | Description of the movie file content. |
| [Director](../../groupdocs.metadata.formats.video/movpackage/director) { get; } | Name of the director of the movie content. |
| [Genre](../../groupdocs.metadata.formats.video/movpackage/genre) { get; } | Text describing the genre or genres to which the movie content conforms. |
| [Information](../../groupdocs.metadata.formats.video/movpackage/information) { get; } | Information about the movie file content. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.video/movpackage/keywords) { get; } | Keywords associated with the movie file content. |
| [LocationBody](../../groupdocs.metadata.formats.video/movpackage/locationbody) { get; } | The astronomical body, for compatibility with the 3GPP format |
| [LocationDate](../../groupdocs.metadata.formats.video/movpackage/locationdate) { get; } | A date and time, stored using the extended format defined in ISO 8601:2004- Data elements and interchange format. |
| [LocationFacing](../../groupdocs.metadata.formats.video/movpackage/locationfacing) { get; } | An indication of the direction the camera is facing during the shot. |
| [LocationMotion](../../groupdocs.metadata.formats.video/movpackage/locationmotion) { get; } | An indication of the direction the camera is moving during the shot. |
| [LocationName](../../groupdocs.metadata.formats.video/movpackage/locationname) { get; } | Name of the location. |
| [LocationNote](../../groupdocs.metadata.formats.video/movpackage/locationnote) { get; } | Descriptive comment. |
| [LocationRole](../../groupdocs.metadata.formats.video/movpackage/locationrole) { get; } | A single byte, binary value containing a value from the set: 0 indicates “shooting location”, 1 indicates “real location”, 2 indicates “fictional location”. Other values are reserved. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [MovieCreationTime](../../groupdocs.metadata.formats.video/movpackage/moviecreationtime) { get; set; } | A 32-bit integer that specifies the creation calendar date and time for the movie atom. |
| [MovieDuration](../../groupdocs.metadata.formats.video/movpackage/movieduration) { get; } | A time value that indicates the duration of the movie in seconds. |
| [MovieModificationTime](../../groupdocs.metadata.formats.video/movpackage/moviemodificationtime) { get; set; } | A 32-bit integer that specifies the calendar date and time of the last change to the movie atom. |
| [Producer](../../groupdocs.metadata.formats.video/movpackage/producer) { get; } | Name of producer of movie file content. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Publisher](../../groupdocs.metadata.formats.video/movpackage/publisher) { get; } | Name of publisher of movie file content. |
| [Software](../../groupdocs.metadata.formats.video/movpackage/software) { get; } | Name of software used to create the movie file content. |
| [Title](../../groupdocs.metadata.formats.video/movpackage/title) { get; } | The title of the movie file content. |
| [UserRatings](../../groupdocs.metadata.formats.video/movpackage/userratings) { get; } | A number, assigned by the user, that indicates the rating or relative value of the movie. This number can range from 0.0 to 5.0. A value of 0.0 indicates that the user has not rated the movie. |
| [Users](../../groupdocs.metadata.formats.video/movpackage/users) { get; } | A name indicating a user-defined collection that includes this movie. |
| [Year](../../groupdocs.metadata.formats.video/movpackage/year) { get; } | Year when the movie file or the original content was created or recorded. |

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

* [Working with metadata in MOV Files](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+MOV+Files)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
