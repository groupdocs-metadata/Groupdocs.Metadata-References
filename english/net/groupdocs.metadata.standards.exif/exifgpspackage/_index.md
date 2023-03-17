---
title: ExifGpsPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents GPS metadata in an EXIF metadata package.
type: docs
weight: 3680
url: /net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Represents GPS metadata in an EXIF metadata package.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Constructors

| Name | Description |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Initializes a new instance of the [`ExifGpsPackage`](../exifgpspackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Gets or sets the altitude based on the reference in [`AltitudeRef`](./altituderef). The reference unit is meters. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Gets or sets the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the [`Altitude`](./altitude) tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Gets or sets the character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Gets or sets the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Gets or sets the character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Gets or sets the GPS bearing to the destination point. The range of values is from 0.00 to 359.99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Gets or sets the GPS reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is magnetic direction. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Gets or sets the GPS distance to the destination point. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Gets or sets the GPS unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles and knots. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Gets or sets the GPS latitude of the destination point. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north latitude, and 'S' is south latitude. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Gets or sets the GPS longitude of the destination point. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude, and 'W' is west longitude. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Gets or sets the direction of GPS receiver movement. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Gets or sets the GPS direction of the image when it was captured. The range of values is from 0.00 to 359.99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Gets or sets the GPS reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is magnetic direction. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Gets the TIFF tag with the specified id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Gets or sets the GPS latitude. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Gets or sets a GPS value indicating whether the latitude is north or south latitude. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Gets or sets the GPS longitude. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Gets or sets a GPS value indicating whether the longitude is east or west longitude. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Gets or sets the geodetic survey data used by the GPS receiver. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Gets or sets the GPS measurement mode. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Gets or sets a character string recording the name of the method used for location finding. The first byte indicates the character code used, and this is followed by the name of the method. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Gets or sets the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Gets or sets the speed of GPS receiver movement. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Gets or sets the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Gets or sets the status of the GPS receiver when the image is recorded. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Gets or sets the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Gets or sets the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is magnetic direction. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Gets or sets the version of GPS IFD. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Removes all TIFF tags stored in the package. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Removes the property with the specified id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Adds or replaces the specified tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Creates a list from the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with EXIF metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### See Also

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* namespace [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
