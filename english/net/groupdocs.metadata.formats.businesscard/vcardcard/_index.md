---
title: VCardCard
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a single card extracted from a VCard file.
type: docs
weight: 700
url: /net/groupdocs.metadata.formats.businesscard/vcardcard/
---
## VCardCard class

Represents a single card extracted from a VCard file.

```csharp
public class VCardCard : VCardRecordset
```

## Properties

| Name | Description |
| --- | --- |
| [CalendarRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/calendarrecordset) { get; } | Gets the calendar records. |
| [CommunicationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/communicationrecordset) { get; } | Gets the communication records. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DeliveryAddressingRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/deliveryaddressingrecordset) { get; } | Gets the delivery addressing records. |
| [ExplanatoryRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/explanatoryrecordset) { get; } | Gets the explanatory records. |
| [ExtensionRecords](../../groupdocs.metadata.formats.businesscard/vcardcard/extensionrecords) { get; } | Gets the private extension records. |
| [GeneralRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/generalrecordset) { get; } | Gets the general records. |
| [GeographicalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/geographicalrecordset) { get; } | Gets the geographical records. |
| [IdentificationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/identificationrecordset) { get; } | Gets the identification records. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [OrganizationalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/organizationalrecordset) { get; } | Gets the organizational records. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [SecurityRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/securityrecordset) { get; } | Gets the security records. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| [FilterByGroup](../../groupdocs.metadata.formats.businesscard/vcardcard/filterbygroup)(string) | Filters all vCard records by the group name passed as a parameter. For more information please see the  method. |
| [FilterHomeTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterhometags)() | Filters all vCard records marked with the HOME tag. |
| [FilterPreferred](../../groupdocs.metadata.formats.businesscard/vcardcard/filterpreferred)() | Filters the preferred records. |
| [FilterWorkTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterworktags)() | Filters all vCard records marked with the WORK tag. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetAvailableGroups](../../groupdocs.metadata.formats.businesscard/vcardcard/getavailablegroups)() | Gets the available group names. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with vCard metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Examples

This example shows how to use vCard property filters.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.InputVcf))
    {
        var root = metadata.GetRootPackage<VCardRootPackage>();

        foreach (var vCard in root.VCardPackage.Cards)
        {
            // Print most preferred work phone numbers and work emails
            var filtered = vCard.FilterWorkTags().FilterPreferred();
            PrintArray(filtered.CommunicationRecordset.Telephones);
            PrintArray(filtered.CommunicationRecordset.Emails);
        }
    }
}

private static void PrintArray(string[] values)
{
    if (values != null)
    {
        foreach (string value in values)
        {
            Console.WriteLine(value);
        }
    }
}
```

### See Also

* class [VCardRecordset](../vcardrecordset)
* namespace [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
