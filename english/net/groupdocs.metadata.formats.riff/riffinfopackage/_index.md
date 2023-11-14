---
title: RiffInfoPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the metadata package containing properties extracted from the RIFF INFO chunk.
type: docs
weight: 3190
url: /net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Represents the metadata package containing properties extracted from the RIFF INFO chunk.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Gets the artist of the original subject of the file. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Gets the comment about the file or the subject of the file. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Gets the copyright information for the file. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Gets the date the subject of the file was created. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Gets the name of the engineer who worked on the file. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Gets the genre of the original work. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Gets the keywords that refer to the file or subject of the file. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Gets the title of the subject of the file. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Gets the name of the software package used to create the file. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Gets the name of the person or organization who supplied the original subject of the file. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Gets a description of the file contents, such as "Aerial view of Seattle." |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Gets the technician who digitized the subject file. |

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

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
