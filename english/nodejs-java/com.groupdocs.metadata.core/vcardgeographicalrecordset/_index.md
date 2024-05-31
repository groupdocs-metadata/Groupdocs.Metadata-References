---
title: VCardGeographicalRecordset
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a set of Geographical vCard records.
type: docs
weight: 274
url: /nodejs-java/com.groupdocs.metadata.core/vcardgeographicalrecordset/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecordset](../../com.groupdocs.metadata.core/vcardrecordset)
```
public class VCardGeographicalRecordset extends VCardRecordset
```

Represents a set of Geographical vCard records. These properties are concerned with information associated with geographical positions or regions associated with the object the vCard represents.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getTimeZoneRecords()](#getTimeZoneRecords--) | Gets the time zones of the object. |
| [getTimeZones()](#getTimeZones--) | Gets the time zones of the object. |
| [getGeographicPositionRecords()](#getGeographicPositionRecords--) | Gets the information related to the global positioning of the object. |
| [getGeographicPositions()](#getGeographicPositions--) | Gets the information related to the global positioning of the object. |
### getTimeZoneRecords() {#getTimeZoneRecords--}
```
public final VCardTextRecord[] getTimeZoneRecords()
```


Gets the time zones of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The time zones of the object.
### getTimeZones() {#getTimeZones--}
```
public final String[] getTimeZones()
```


Gets the time zones of the object.

**Returns:**
java.lang.String[] - The time zones of the object.

--------------------

This property is a simplified version of  TimeZoneRecords .
### getGeographicPositionRecords() {#getGeographicPositionRecords--}
```
public final VCardTextRecord[] getGeographicPositionRecords()
```


Gets the information related to the global positioning of the object.

**Returns:**
com.groupdocs.metadata.core.VCardTextRecord[] - The information related to the global positioning of the object.
### getGeographicPositions() {#getGeographicPositions--}
```
public final String[] getGeographicPositions()
```


Gets the information related to the global positioning of the object.

**Returns:**
java.lang.String[] - The information related to the global positioning of the object.

--------------------

This property is a simplified version of  GeographicPositionRecords .
