---
title: GpsIfdPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents GPS IFD.
type: docs
weight: 3320
url: /net/groupdocs.metadata.formats.raw/gpsifdpackage/
---
## GpsIfdPackage class

Represents GPS IFD.

```csharp
public sealed class GpsIfdPackage : RawDictionaryBasePackage
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [GPSAltitude](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsaltitude) { get; } | Gets the GPSAltitude. |
| [GPSAltitudeRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsaltituderef) { get; } | Gets the GPSAltitudeRef. |
| [GPSAreaInformation](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsareainformation) { get; } | Gets the GPSAreaInformation. |
| [GPSDateStamp](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdatestamp) { get; } | Gets the GPSDateStamp. |
| [GPSDestBearing](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestbearing) { get; } | Gets the GPSDestBearing. |
| [GPSDestBearingRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestbearingref) { get; } | Gets the GPSDestBearingRef. |
| [GPSDestDistance](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestdistance) { get; } | Gets the GPSDestDistance. |
| [GPSDestDistanceRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestdistanceref) { get; } | Gets the GPSDestDistanceRef. |
| [GPSDestLatitude](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestlatitude) { get; } | Gets the GPSDestLatitude. |
| [GPSDestLatitudeRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestlatituderef) { get; } | Gets the GPSDestLatitudeRef. |
| [GPSDestLongitude](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestlongitude) { get; } | Gets the GPSDestLongitude. |
| [GPSDestLongitudeRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdestlongituderef) { get; } | Gets the GPSDestLongitudeRef. |
| [GPSDifferential](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdifferential) { get; } | Gets the GPSDifferential. |
| [GPSDOP](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsdop) { get; } | Gets the GPSDOP. |
| [GPSHPositioningError](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpshpositioningerror) { get; } | Gets the GPSHPositioningError. |
| [GPSImgDirection](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsimgdirection) { get; } | Gets the GPSImgDirection. |
| [GPSImgDirectionRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsimgdirectionref) { get; } | Gets the GPSImgDirectionRef. |
| [GPSLatitude](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpslatitude) { get; } | Gets the GPSLatitude. |
| [GPSLatitudeRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpslatituderef) { get; } | Gets the GPSLatitudeRef. |
| [GPSLongitude](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpslongitude) { get; } | Gets the GPSLongitude. |
| [GPSLongitudeRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpslongituderef) { get; } | Gets the GPSLongitudeRef. |
| [GPSMapDatum](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsmapdatum) { get; } | Gets the GPSMapDatum. |
| [GPSMeasureMode](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsmeasuremode) { get; } | Gets the GPSMeasureMode. |
| [GPSProcessingMethod](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsprocessingmethod) { get; } | Gets the GPSProcessingMethod. |
| [GPSSatellites](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpssatellites) { get; } | Gets the GPSSatellites. |
| [GPSSpeed](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsspeed) { get; } | Gets the GPSSpeed. |
| [GPSSpeedRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsspeedref) { get; } | Gets the GPSSpeedRef. |
| [GPSStatus](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsstatus) { get; } | Gets the GPSStatus. |
| [GPSTimeStamp](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpstimestamp) { get; } | Gets the GPSTimeStamp. |
| [GPSTrack](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpstrack) { get; } | Gets the GPSTrack. |
| [GPSTrackRef](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpstrackref) { get; } | Gets the GPSTrackRef. |
| [GPSVersionID](../../groupdocs.metadata.formats.raw/gpsifdpackage/gpsversionid) { get; } | Gets the GPSVersionID. |
| [Item](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/item) { get; } | Gets the Raw tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/clear)() | Removes all Raw tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/remove)(uint) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/set)(RawTag) | Adds or replaces the specified tag. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.formats.raw/rawdictionarybasepackage/tolist)() | Creates a list from the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [RawDictionaryBasePackage](../rawdictionarybasepackage)
* namespace [GroupDocs.Metadata.Formats.Raw](../../groupdocs.metadata.formats.raw)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
