---
title: ExifGpsPackage class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/groupdocs.metadata.standards.exif/exifgpspackage/
is_root: false
---

## ExifGpsPackage class

Represents GPS metadata in an EXIF metadata package.



**Inheritance:** [`ExifGpsPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage) → 
[`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The ExifGpsPackage type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/__init__/#) | Initializes a new instance of the [`ExifGpsPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/count) | Gets the number of metadata properties. |
| [altitude](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/altitude) | Gets or sets the altitude based on the reference in [`ExifGpsPackage.altitude_ref`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage#altitude_ref).<br/>The reference unit is meters. |
| [altitude_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/altitude_ref) | Gets or sets the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given.<br/>If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the [`ExifGpsPackage.altitude`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage#altitude) tag. |
| [area_information](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/area_information) | Gets or sets the character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area. |
| [date_stamp](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/date_stamp) | Gets or sets the character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD. |
| [dest_bearing](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_bearing) | Gets or sets the GPS bearing to the destination point.<br/>The range of values is from 0.00 to 359.99. |
| [dest_bearing_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_bearing_ref) | Gets or sets the GPS reference used for giving the bearing to the destination point.<br/>'T' denotes true direction and 'M' is magnetic direction. |
| [dest_distance](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_distance) | Gets or sets the GPS distance to the destination point. |
| [dest_distance_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_distance_ref) | Gets or sets the GPS unit used to express the distance to the destination point.<br/>'K', 'M' and 'N' represent kilometers, miles and knots. |
| [dest_latitude](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_latitude) | Gets or sets the GPS latitude of the destination point. |
| [dest_latitude_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_latitude_ref) | Gets or sets the GPS value which indicates whether the latitude of the destination point is north or south latitude.<br/>The ASCII value 'N' indicates north latitude, and 'S' is south latitude. |
| [dest_longitude](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_longitude) | Gets or sets the GPS longitude of the destination point. |
| [dest_longitude_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/dest_longitude_ref) | Gets or sets the GPS value which indicates whether the longitude of the destination point is east or west longitude.<br/>ASCII 'E' indicates east longitude, and 'W' is west longitude. |
| [differential](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/differential) | Gets or sets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| [data_degree_of_precision](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/data_degree_of_precision) | Gets or sets the GPS DOP (data degree of precision).<br/>An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement. |
| [img_direction](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/img_direction) | Gets or sets the GPS direction of the image when it was captured.<br/>The range of values is from 0.00 to 359.99. |
| [img_direction_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/img_direction_ref) | Gets or sets the GPS reference for giving the direction of the image when it is captured.<br/>'T' denotes true direction and 'M' is magnetic direction. |
| [latitude](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/latitude) | Gets or sets the GPS latitude. |
| [latitude_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/latitude_ref) | Gets or sets a GPS value indicating whether the latitude is north or south latitude. |
| [longitude](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/longitude) | Gets or sets the GPS longitude. |
| [longitude_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/longitude_ref) | Gets or sets a GPS value indicating whether the longitude is east or west longitude. |
| [map_datum](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/map_datum) | Gets or sets the geodetic survey data used by the GPS receiver. |
| [measure_mode](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/measure_mode) | Gets or sets the GPS measurement mode. |
| [processing_method](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/processing_method) | Gets or sets a character string recording the name of the method used for location finding.<br/>The first byte indicates the character code used, and this is followed by the name of the method. |
| [satellites](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/satellites) | Gets or sets the GPS satellites used for measurements.<br/>This tag can be used to describe the number of satellites,<br/>their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not<br/>specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL. |
| [speed](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/speed) | Gets or sets the speed of GPS receiver movement. |
| [speed_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/speed_ref) | Gets or sets the unit used to express the GPS receiver speed of movement.<br/>'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots. |
| [status](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/status) | Gets or sets the status of the GPS receiver when the image is recorded. |
| [time_stamp](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/time_stamp) | Gets or sets the time as UTC (Coordinated Universal Time).<br/>TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second. |
| [gps_track](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/gps_track) | Gets or sets the direction of GPS receiver movement. |
| [track_ref](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/track_ref) | Gets or sets the reference for giving the direction of GPS receiver movement.<br/>'T' denotes true direction and 'M' is magnetic direction. |
| [version_id](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/version_id) | Gets or sets the version of GPS IFD. |


### Methods
| Method | Description |
| :- | :- |
| [`contains(self, property_name)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/contains/#system.string) | Determines whether the package contains a metadata property with the specified name. |
| [`find_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/find_properties/#groupdocs.metadata.search.specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [`update_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/update_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`remove_properties(self, specification)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/remove_properties/#groupdocs.metadata.search.specification) | Removes metadata properties satisfying a specification. |
| [`add_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/add_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [`set_properties(self, specification, value)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/set_properties/#groupdocs.metadata.search.specification-groupdocs.metadata.common.propertyvalue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [`sanitize(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [`to_list(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/to_list/#) | Creates a list from the package. |
| [`remove(self, tag_id)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/remove/#groupdocs.metadata.formats.image.tifftagid) | Removes the property with the specified id. |
| [`set(self, tag)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/set/#groupdocs.metadata.formats.image.tifftag) | Adds or replaces the specified tag. |
| [`clear(self)`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage/clear/#) | Removes all TIFF tags stored in the package. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.standards.exif`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`ExifDictionaryBasePackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifdictionarybasepackage)
* class [`ExifGpsPackage`](/metadata/python-net/groupdocs.metadata.standards.exif/exifgpspackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
