---
title: IptcApplicationRecord
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents an IPTC Application Record.
type: docs
weight: 4120
url: /net/groupdocs.metadata.standards.iptc/iptcapplicationrecord/
---
## IptcApplicationRecord class

Represents an IPTC Application Record.

```csharp
public sealed class IptcApplicationRecord : IptcRecord
```

## Constructors

| Name | Description |
| --- | --- |
| [IptcApplicationRecord](iptcapplicationrecord)() | Initializes a new instance of the [`IptcApplicationRecord`](../iptcapplicationrecord) class. |

## Properties

| Name | Description |
| --- | --- |
| [AllKeywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/allkeywords) { get; set; } | Gets or sets the keywords. |
| [ByLine](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/byline) { get; set; } | Gets or sets the name of the creator of the object, e.g. writer, photographer or graphic artist. |
| [ByLines](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylines) { get; set; } | Gets or sets the names of the creators of the object, e.g. writer, photographer or graphic artist. |
| [ByLineTitle](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitle) { get; set; } | Gets or sets the title of the creator or creators of the object. |
| [ByLineTitles](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitles) { get; set; } | Gets or sets the titles of the creator or creators of the object. |
| [CaptionAbstract](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/captionabstract) { get; set; } | Gets or sets a textual description of the object, particularly used where the object is not text. |
| [City](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/city) { get; set; } | Gets or sets the city. |
| [Contact](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contact) { get; set; } | Gets or sets information about the person or organisation which can provide further background information on the object. |
| [Contacts](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contacts) { get; set; } | Gets or sets information about the person or organisation which can provide further background information on the object. |
| [ContentLocationCode](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcode) { get; set; } | Gets or sets the content location code. |
| [ContentLocationCodes](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcodes) { get; set; } | Gets or sets the content location codes. |
| [ContentLocationName](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationname) { get; set; } | Gets or sets the content location name. |
| [ContentLocationNames](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationnames) { get; set; } | Gets or sets the content location names. |
| [CopyrightNotice](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/copyrightnotice) { get; set; } | Gets or sets the copyright notice. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Credit](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/credit) { get; set; } | Gets or sets information about the provider of the object, not necessarily the owner/creator. |
| [DateCreated](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/datecreated) { get; set; } | Gets or sets the date the intellectual content of the object was created. |
| [Headline](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/headline) { get; set; } | Gets or sets a publishable entry providing a synopsis of the contents of the object. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/item) { get; } | Gets the [`IptcDataSet`](../iptcdataset) with the specified number. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/keywords) { get; set; } | Gets or sets the keywords. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ProgramVersion](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/programversion) { get; set; } | Gets or sets the program version. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Gets the record number. |
| [ReferenceDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedate) { get; set; } | Gets or sets the date of a prior envelope to which the current object refers. |
| [ReferenceDates](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedates) { get; } | Gets the dates of a prior envelope to which the current object refers. |
| [ReleaseDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/releasedate) { get; set; } | Gets or sets the release date. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Creates a list from the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with IPTC IIM metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### See Also

* class [IptcRecord](../iptcrecord)
* namespace [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
