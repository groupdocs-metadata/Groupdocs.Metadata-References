---
title: VCardCard
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a single card extracted from a VCard file.
type: docs
weight: 260
url: /java/com.groupdocs.metadata.core/vcardcard/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardCard extends VCardRecordset
```

Represents a single card extracted from a VCard file.

**Learn more**

 *  [Working with vCard metadata][]

This example shows how to use vCard property filters.

> ```
> ```
> 
>  public static void run() {
>      try (Metadata metadata = new Metadata(Constants.InputVcf)) {
>          VCardRootPackage root = metadata.getRootPackageGeneric();
>          for (VCardCard vCard : root.getVCardPackage().getCards()) {
>              // Print most preferred work phone numbers and work emails
>              VCardCard filtered = vCard.filterWorkTags().filterPreferred();
>              PrintArray(filtered.getCommunicationRecordset().getTelephones());
>              PrintArray(filtered.getCommunicationRecordset().getEmails());
>          }
>      }
>  }
>  private static void PrintArray(String[] values) {
>      if (values != null) {
>          for (String value : values) {
>              System.out.println(value);
>          }
>      }
>  }
>  
> ```
> ```


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getGeneralRecordset()](#getGeneralRecordset--) | Gets the general records. |
| [getIdentificationRecordset()](#getIdentificationRecordset--) | Gets the identification records. |
| [getDeliveryAddressingRecordset()](#getDeliveryAddressingRecordset--) | Gets the delivery addressing records. |
| [getCommunicationRecordset()](#getCommunicationRecordset--) | Gets the communication records. |
| [getGeographicalRecordset()](#getGeographicalRecordset--) | Gets the geographical records. |
| [getOrganizationalRecordset()](#getOrganizationalRecordset--) | Gets the organizational records. |
| [getExplanatoryRecordset()](#getExplanatoryRecordset--) | Gets the explanatory records. |
| [getSecurityRecordset()](#getSecurityRecordset--) | Gets the security records. |
| [getCalendarRecordset()](#getCalendarRecordset--) | Gets the calendar records. |
| [getExtensionRecords()](#getExtensionRecords--) | Gets the private extension records. |
| [getAvailableGroups()](#getAvailableGroups--) | Gets the available group names. |
| [filterByGroup(String groupName)](#filterByGroup-java.lang.String-) | Filters all vCard records by the group name passed as a parameter. |
| [filterHomeTags()](#filterHomeTags--) | Filters all vCard records marked with the HOME tag. |
| [filterWorkTags()](#filterWorkTags--) | Filters all vCard records marked with the WORK tag. |
| [filterPreferred()](#filterPreferred--) | Filters the preferred records. |
### getGeneralRecordset() {#getGeneralRecordset--}
```
public final VCardGeneralRecordset getGeneralRecordset()
```


Gets the general records.

**Returns:**
[VCardGeneralRecordset](../../com.groupdocs.metadata.core/vcardgeneralrecordset) - The general records.
### getIdentificationRecordset() {#getIdentificationRecordset--}
```
public final VCardIdentificationRecordset getIdentificationRecordset()
```


Gets the identification records.

**Returns:**
[VCardIdentificationRecordset](../../com.groupdocs.metadata.core/vcardidentificationrecordset) - The identification records.
### getDeliveryAddressingRecordset() {#getDeliveryAddressingRecordset--}
```
public final VCardDeliveryAddressingRecordset getDeliveryAddressingRecordset()
```


Gets the delivery addressing records.

**Returns:**
[VCardDeliveryAddressingRecordset](../../com.groupdocs.metadata.core/vcarddeliveryaddressingrecordset) - The delivery addressing records.
### getCommunicationRecordset() {#getCommunicationRecordset--}
```
public final VCardCommunicationRecordset getCommunicationRecordset()
```


Gets the communication records.

**Returns:**
[VCardCommunicationRecordset](../../com.groupdocs.metadata.core/vcardcommunicationrecordset) - The communication records.
### getGeographicalRecordset() {#getGeographicalRecordset--}
```
public final VCardGeographicalRecordset getGeographicalRecordset()
```


Gets the geographical records.

**Returns:**
[VCardGeographicalRecordset](../../com.groupdocs.metadata.core/vcardgeographicalrecordset) - The geographical records.
### getOrganizationalRecordset() {#getOrganizationalRecordset--}
```
public final VCardOrganizationalRecordset getOrganizationalRecordset()
```


Gets the organizational records.

**Returns:**
[VCardOrganizationalRecordset](../../com.groupdocs.metadata.core/vcardorganizationalrecordset) - The organizational records.
### getExplanatoryRecordset() {#getExplanatoryRecordset--}
```
public final VCardExplanatoryRecordset getExplanatoryRecordset()
```


Gets the explanatory records.

**Returns:**
[VCardExplanatoryRecordset](../../com.groupdocs.metadata.core/vcardexplanatoryrecordset) - The explanatory records.
### getSecurityRecordset() {#getSecurityRecordset--}
```
public final VCardSecurityRecordset getSecurityRecordset()
```


Gets the security records.

**Returns:**
[VCardSecurityRecordset](../../com.groupdocs.metadata.core/vcardsecurityrecordset) - The security records.
### getCalendarRecordset() {#getCalendarRecordset--}
```
public final VCardCalendarRecordset getCalendarRecordset()
```


Gets the calendar records.

**Returns:**
[VCardCalendarRecordset](../../com.groupdocs.metadata.core/vcardcalendarrecordset) - The calendar records.
### getExtensionRecords() {#getExtensionRecords--}
```
public final VCardTextRecord[] getExtensionRecords()
```


Gets the private extension records.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The private extension records.
### getAvailableGroups() {#getAvailableGroups--}
```
public final String[] getAvailableGroups()
```


Gets the available group names.

**Returns:**
java.lang.String[] - The available group names.
### filterByGroup(String groupName) {#filterByGroup-java.lang.String-}
```
public final VCardCard filterByGroup(String groupName)
```


Filters all vCard records by the group name passed as a parameter. For more information please see the method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| groupName | java.lang.String | The name of the group. |

**Returns:**
[VCardCard](../../com.groupdocs.metadata.core/vcardcard) - The filtered vCard instance.
### filterHomeTags() {#filterHomeTags--}
```
public final VCardCard filterHomeTags()
```


Filters all vCard records marked with the HOME tag.

**Returns:**
[VCardCard](../../com.groupdocs.metadata.core/vcardcard) - The filtered vCard instance.
### filterWorkTags() {#filterWorkTags--}
```
public final VCardCard filterWorkTags()
```


Filters all vCard records marked with the WORK tag.

**Returns:**
[VCardCard](../../com.groupdocs.metadata.core/vcardcard) - Filtered vCard instance.
### filterPreferred() {#filterPreferred--}
```
public final VCardCard filterPreferred()
```


Filters the preferred records.

**Returns:**
[VCardCard](../../com.groupdocs.metadata.core/vcardcard) - The filtered vCard instance.
