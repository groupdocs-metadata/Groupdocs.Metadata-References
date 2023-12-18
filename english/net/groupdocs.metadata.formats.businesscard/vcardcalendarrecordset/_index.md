---
title: VCardCalendarRecordset
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a set of Calendar vCard records.
type: docs
weight: 690
url: /net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/
---
## VCardCalendarRecordset class

Represents a set of Calendar vCard records.

```csharp
public class VCardCalendarRecordset : VCardRecordset
```

## Properties

| Name | Description |
| --- | --- |
| [BusyTimeEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimeentries) { get; } | Gets the URIs for the busy time associated with the object. |
| [BusyTimeRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimerecords) { get; } | Gets the URIs for the busy time associated with the object. |
| [CalendarAddresses](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddresses) { get; } | Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard. |
| [CalendarAddressRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddressrecords) { get; } | Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard. |
| [CalendarUriRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendarurirecords) { get; } | Gets the URIs for the calendar associated with the object represented by the vCard. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [UriCalendarEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/uricalendarentries) { get; } | Gets the URIs for the calendar associated with the object represented by the vCard. |

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
