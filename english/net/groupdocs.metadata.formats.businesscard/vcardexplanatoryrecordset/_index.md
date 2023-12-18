---
title: VCardExplanatoryRecordset
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a set of Explanatory vCard records. These properties are concerned with additional explanations such as that related to informational notes or revisions specific to the vCard.
type: docs
weight: 760
url: /net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/
---
## VCardExplanatoryRecordset class

Represents a set of Explanatory vCard records. These properties are concerned with additional explanations, such as that related to informational notes or revisions specific to the vCard.

```csharp
public class VCardExplanatoryRecordset : VCardRecordset
```

## Properties

| Name | Description |
| --- | --- |
| [BinarySounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/binarysounds) { get; } | Gets the digital sound content information that annotates some aspects of the vCard. |
| [Categories](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categories) { get; } | Gets the application category information about the vCard, also known as "tags". |
| [CategoryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categoryrecords) { get; } | Gets the application category information about the vCard, also known as "tags". |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NoteRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/noterecords) { get; } | Gets the supplemental information or comments that are associated with the vCard. |
| [Notes](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/notes) { get; } | Gets the supplemental information or comments that are associated with the vCard. |
| [PidIdentifierRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifierrecords) { get; } | Gets the global meaning of the local PID source identifier. |
| [PidIdentifiers](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifiers) { get; } | Gets the global meaning of the local PID source identifier. |
| [ProductIdentifier](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifier) { get; } | Gets the identifier of the product that created the vCard object. |
| [ProductIdentifierRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifierrecord) { get; } | Gets the identifier of the product that created the vCard object. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Revision](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/revision) { get; } | Gets the revision information about the current vCard. |
| [SortString](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sortstring) { get; } | Gets the family name or given name text to be used for national-language-specific sorting of the [`FormattedNames`](../vcardidentificationrecordset/formattednames) and [`Name`](../vcardidentificationrecordset/name) types. |
| [SoundBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundbinaryrecords) { get; } | Gets the digital sound content information that annotates some aspects of the vCard. |
| [SoundRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundrecords) { get; } | Gets the digital sound content information that annotates some aspects of the vCard. |
| [SoundUriRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundurirecords) { get; } | Gets the digital sound content information that annotates some aspects of the vCard. |
| [Uid](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid) { get; } | Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard. |
| [UidRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uidrecord) { get; } | Gets the value that represents a globally unique identifier corresponding to the individual or resource associated with the vCard. |
| [UriSounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urisounds) { get; } | Gets the digital sound content information that annotates some aspects of the vCard. |
| [UrlRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urlrecords) { get; } | Gets an array of URLs pointing to websites that represent the person in some way. |
| [Urls](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urls) { get; } | Gets an array of URLs pointing to websites that represent the person in some way. |
| [Version](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/version) { get; } | Gets the version of the vCard specification. |

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

* [Working with vCard metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### See Also

* class [VCardRecordset](../vcardrecordset)
* namespace [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
