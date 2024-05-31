---
title: VCardCalendarRecordset
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a set of Calendar vCard records.
type: docs
weight: 266
url: /java/com.groupdocs.metadata.core/vcardcalendarrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardCalendarRecordset extends VCardRecordset
```

Represents a set of Calendar vCard records.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getBusyTimeRecords()](#getBusyTimeRecords--) | Gets the URIs for the busy time associated with the object. |
| [getBusyTimeEntries()](#getBusyTimeEntries--) | Gets the URIs for the busy time associated with the object. |
| [getCalendarAddressRecords()](#getCalendarAddressRecords--) | Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard. |
| [getCalendarAddresses()](#getCalendarAddresses--) | Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard. |
| [getCalendarUriRecords()](#getCalendarUriRecords--) | Gets the URIs for the calendar associated with the object represented by the vCard. |
| [getUriCalendarEntries()](#getUriCalendarEntries--) | Gets the URIs for the calendar associated with the object represented by the vCard. |
### getBusyTimeRecords() {#getBusyTimeRecords--}
```
public final VCardTextRecord[] getBusyTimeRecords()
```


Gets the URIs for the busy time associated with the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The URIs for the busy time associated with the object.
### getBusyTimeEntries() {#getBusyTimeEntries--}
```
public final String[] getBusyTimeEntries()
```


Gets the URIs for the busy time associated with the object.

**Returns:**
java.lang.String[] - The URIs for the busy time associated with the object.

--------------------

This property is a simplified version of  BusyTimeRecords .
### getCalendarAddressRecords() {#getCalendarAddressRecords--}
```
public final VCardTextRecord[] getCalendarAddressRecords()
```


Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The calendar user addresses to which a scheduling request should be sent for the object represented by the vCard.
### getCalendarAddresses() {#getCalendarAddresses--}
```
public final String[] getCalendarAddresses()
```


Gets the calendar user addresses to which a scheduling request should be sent for the object represented by the vCard.

**Returns:**
java.lang.String[] - The calendar user addresses to which a scheduling request should be sent for the object represented by the vCard.

--------------------

This property is a simplified version of  CalendarAddressRecords .
### getCalendarUriRecords() {#getCalendarUriRecords--}
```
public final VCardTextRecord[] getCalendarUriRecords()
```


Gets the URIs for the calendar associated with the object represented by the vCard.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The URIs for the calendar associated with the object represented by the vCard.
### getUriCalendarEntries() {#getUriCalendarEntries--}
```
public final String[] getUriCalendarEntries()
```


Gets the URIs for the calendar associated with the object represented by the vCard.

**Returns:**
java.lang.String[] - The URIs for the calendar associated with the object represented by the vCard.

--------------------

This property is a simplified version of  CalendarUriRecords .
