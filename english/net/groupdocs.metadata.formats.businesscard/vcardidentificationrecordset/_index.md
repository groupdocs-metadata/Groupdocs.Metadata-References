---
title: VCardIdentificationRecordset
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a set of Identification vCard records. These types are used to capture information associated with the identification and naming of the entity associated with the vCard.
type: docs
weight: 880
url: /net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/
---
## VCardIdentificationRecordset class

Represents a set of Identification vCard records. These types are used to capture information associated with the identification and naming of the entity associated with the vCard.

```csharp
public class VCardIdentificationRecordset : VCardRecordset
```

## Properties

| Name | Description |
| --- | --- |
| [AnniversaryDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarydatetimerecord) { get; } | Gets the date of marriage represented as a single date-and-or-time value. |
| [AnniversaryRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversaryrecord) { get; } | Gets the date of marriage, or equivalent, of the object. |
| [AnniversaryTextRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarytextrecord) { get; } | Gets the date of marriage represented as a single text value. |
| [BinaryPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/binaryphotos) { get; } | Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object. |
| [BirthdateDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatedatetimerecord) { get; } | Gets the birth date of the object. |
| [BirthdateRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdaterecords) { get; } | Gets an array containing the birth date of the object in different representations. |
| [BirthdateTextRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatetextrecords) { get; } | Gets an array containing the birth date of the object in different text representations. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DateTimeAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimeanniversary) { get; } | Gets the date of marriage represented as a single date-and-or-time value. |
| [DateTimeBirthdate](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimebirthdate) { get; } | Gets the birth date of the object. |
| [FormattedNameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednamerecords) { get; } | Gets an array containing the formatted text corresponding to the name of the object. |
| [FormattedNames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednames) { get; } | Gets an array containing the formatted text corresponding to the name of the object. |
| [Gender](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender) { get; } | Gets the components of the sex and gender identity of the object. |
| [GenderRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/genderrecord) { get; } | Gets the components of the sex and gender identity of the object. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Name](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name) { get; } | Gets the components of the name of the object. |
| [NameRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/namerecord) { get; } | Gets the components of the name of the object. |
| [NicknameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknamerecords) { get; } | Gets an array containing the text corresponding to the nickname of the object. |
| [Nicknames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknames) { get; } | Gets an array containing the text corresponding to the nickname of the object. |
| [PhotoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photobinaryrecords) { get; } | Gets an array containing the image or photograph information represented as binary data that annotates some aspects of the object. |
| [PhotoRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photorecords) { get; } | Gets an array containing the image or photograph information that annotates some aspects of the object. |
| [PhotoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photourirecords) { get; } | Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [TextAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textanniversary) { get; } | Gets the date of marriage represented as a single text value. |
| [TextBirthdates](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textbirthdates) { get; } | Gets an array containing the birth date of the object in different text representations. |
| [UriPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/uriphotos) { get; } | Gets an array containing the image or photograph information represented by URIs that annotates some aspects of the object. |

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
