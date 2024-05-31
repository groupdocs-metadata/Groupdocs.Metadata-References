---
title: ExifGpsPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents GPS metadata in an EXIF metadata package.
type: docs
weight: 97
url: /nodejs-java/com.groupdocs.metadata.core/exifgpspackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.ExifDictionaryBasePackage](../../com.groupdocs.metadata.core/exifdictionarybasepackage)
```
public final class ExifGpsPackage extends ExifDictionaryBasePackage
```

Represents GPS metadata in an EXIF metadata package.

**Learn more**

 *  [Working with EXIF metadata][]


[Working with EXIF metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+EXIF+metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [ExifGpsPackage()](#ExifGpsPackage--) | Initializes a new instance of the  ExifGpsPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getAltitude()](#getAltitude--) | Gets the altitude based on the reference in  AltitudeRef . |
| [setAltitude(TiffRational value)](#setAltitude-com.groupdocs.metadata.core.TiffRational-) | Sets the altitude based on the reference in  AltitudeRef . |
| [getAltitudeRef()](#getAltitudeRef--) | Gets the altitude used as the reference altitude. |
| [setAltitudeRef(ExifGpsAltitudeRef value)](#setAltitudeRef-com.groupdocs.metadata.core.ExifGpsAltitudeRef-) | Sets the altitude used as the reference altitude. |
| [getAreaInformation()](#getAreaInformation--) | Gets the character string recording the name of the GPS area. |
| [setAreaInformation(byte[] value)](#setAreaInformation-byte---) | Sets the character string recording the name of the GPS area. |
| [getDateStamp()](#getDateStamp--) | Gets the character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [setDateStamp(String value)](#setDateStamp-java.lang.String-) | Sets the character string recording date and time information relative to UTC (Coordinated Universal Time). |
| [getDestBearing()](#getDestBearing--) | Gets the GPS bearing to the destination point. |
| [setDestBearing(TiffRational value)](#setDestBearing-com.groupdocs.metadata.core.TiffRational-) | Sets the GPS bearing to the destination point. |
| [getDestBearingRef()](#getDestBearingRef--) | Gets the GPS reference used for giving the bearing to the destination point. |
| [setDestBearingRef(String value)](#setDestBearingRef-java.lang.String-) | Sets the GPS reference used for giving the bearing to the destination point. |
| [getDestDistance()](#getDestDistance--) | Gets the GPS distance to the destination point. |
| [setDestDistance(TiffRational value)](#setDestDistance-com.groupdocs.metadata.core.TiffRational-) | Sets the GPS distance to the destination point. |
| [getDestDistanceRef()](#getDestDistanceRef--) | Gets the GPS unit used to express the distance to the destination point. |
| [setDestDistanceRef(String value)](#setDestDistanceRef-java.lang.String-) | Sets the GPS unit used to express the distance to the destination point. |
| [getDestLatitude()](#getDestLatitude--) | Gets the GPS latitude of the destination point. |
| [setDestLatitude(TiffRational[] value)](#setDestLatitude-com.groupdocs.metadata.core.TiffRational---) | Sets the GPS latitude of the destination point. |
| [getDestLatitudeRef()](#getDestLatitudeRef--) | Gets the GPS value which indicates whether the latitude of the destination point is north or south latitude. |
| [setDestLatitudeRef(String value)](#setDestLatitudeRef-java.lang.String-) | Sets the GPS value which indicates whether the latitude of the destination point is north or south latitude. |
| [getDestLongitude()](#getDestLongitude--) | Gets the GPS longitude of the destination point. |
| [setDestLongitude(TiffRational[] value)](#setDestLongitude-com.groupdocs.metadata.core.TiffRational---) | Sets the GPS longitude of the destination point. |
| [getDestLongitudeRef()](#getDestLongitudeRef--) | Gets the GPS value which indicates whether the longitude of the destination point is east or west longitude. |
| [setDestLongitudeRef(String value)](#setDestLongitudeRef-java.lang.String-) | Sets the GPS value which indicates whether the longitude of the destination point is east or west longitude. |
| [getDifferential()](#getDifferential--) | Gets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| [setDifferential(Integer value)](#setDifferential-java.lang.Integer-) | Sets a GPS value which indicates whether differential correction is applied to the GPS receiver. |
| [getDataDegreeOfPrecision()](#getDataDegreeOfPrecision--) | Gets the GPS DOP (data degree of precision). |
| [setDataDegreeOfPrecision(TiffRational value)](#setDataDegreeOfPrecision-com.groupdocs.metadata.core.TiffRational-) | Sets the GPS DOP (data degree of precision). |
| [getImgDirection()](#getImgDirection--) | Gets the GPS direction of the image when it was captured. |
| [setImgDirection(TiffRational value)](#setImgDirection-com.groupdocs.metadata.core.TiffRational-) | Sets the GPS direction of the image when it was captured. |
| [getImgDirectionRef()](#getImgDirectionRef--) | Gets the GPS reference for giving the direction of the image when it is captured. |
| [setImgDirectionRef(String value)](#setImgDirectionRef-java.lang.String-) | Sets the GPS reference for giving the direction of the image when it is captured. |
| [getLatitude()](#getLatitude--) | Gets the GPS latitude. |
| [setLatitude(TiffRational[] value)](#setLatitude-com.groupdocs.metadata.core.TiffRational---) | Sets the GPS latitude. |
| [getLatitudeRef()](#getLatitudeRef--) | Gets a GPS value indicating whether the latitude is north or south latitude. |
| [setLatitudeRef(String value)](#setLatitudeRef-java.lang.String-) | Sets a GPS value indicating whether the latitude is north or south latitude. |
| [getLongitude()](#getLongitude--) | Gets the GPS longitude. |
| [setLongitude(TiffRational[] value)](#setLongitude-com.groupdocs.metadata.core.TiffRational---) | Sets the GPS longitude. |
| [getLongitudeRef()](#getLongitudeRef--) | Gets a GPS value indicating whether the longitude is east or west longitude. |
| [setLongitudeRef(String value)](#setLongitudeRef-java.lang.String-) | Sets a GPS value indicating whether the longitude is east or west longitude. |
| [getMapDatum()](#getMapDatum--) | Gets the geodetic survey data used by the GPS receiver. |
| [setMapDatum(String value)](#setMapDatum-java.lang.String-) | Sets the geodetic survey data used by the GPS receiver. |
| [getMeasureMode()](#getMeasureMode--) | Gets the GPS measurement mode. |
| [setMeasureMode(String value)](#setMeasureMode-java.lang.String-) | Sets the GPS measurement mode. |
| [getProcessingMethod()](#getProcessingMethod--) | Gets a character string recording the name of the method used for location finding. |
| [setProcessingMethod(byte[] value)](#setProcessingMethod-byte---) | Sets a character string recording the name of the method used for location finding. |
| [getSatellites()](#getSatellites--) | Gets the GPS satellites used for measurements. |
| [setSatellites(String value)](#setSatellites-java.lang.String-) | Sets the GPS satellites used for measurements. |
| [getSpeed()](#getSpeed--) | Gets the speed of GPS receiver movement. |
| [setSpeed(TiffRational value)](#setSpeed-com.groupdocs.metadata.core.TiffRational-) | Sets the speed of GPS receiver movement. |
| [getSpeedRef()](#getSpeedRef--) | Gets the unit used to express the GPS receiver speed of movement. |
| [setSpeedRef(String value)](#setSpeedRef-java.lang.String-) | Sets the unit used to express the GPS receiver speed of movement. |
| [getStatus()](#getStatus--) | Gets the status of the GPS receiver when the image is recorded. |
| [setStatus(String value)](#setStatus-java.lang.String-) | Sets the status of the GPS receiver when the image is recorded. |
| [getTimeStamp()](#getTimeStamp--) | Gets the time as UTC (Coordinated Universal Time). |
| [setTimeStamp(TiffRational[] value)](#setTimeStamp-com.groupdocs.metadata.core.TiffRational---) | Sets the time as UTC (Coordinated Universal Time). |
| [getGpsTrack()](#getGpsTrack--) | Gets the direction of GPS receiver movement. |
| [setGpsTrack(TiffRational value)](#setGpsTrack-com.groupdocs.metadata.core.TiffRational-) | Sets the direction of GPS receiver movement. |
| [getTrackRef()](#getTrackRef--) | Gets the reference for giving the direction of GPS receiver movement. |
| [setTrackRef(String value)](#setTrackRef-java.lang.String-) | Sets the reference for giving the direction of GPS receiver movement. |
| [getVersionID()](#getVersionID--) | Gets the version of GPS IFD. |
| [setVersionID(byte[] value)](#setVersionID-byte---) | Sets the version of GPS IFD. |
### ExifGpsPackage() {#ExifGpsPackage--}
```
public ExifGpsPackage()
```


Initializes a new instance of the  ExifGpsPackage  class.

### getAltitude() {#getAltitude--}
```
public final TiffRational getAltitude()
```


Gets the altitude based on the reference in  AltitudeRef . The reference unit is meters.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The altitude based on the reference in  AltitudeRef .
### setAltitude(TiffRational value) {#setAltitude-com.groupdocs.metadata.core.TiffRational-}
```
public final void setAltitude(TiffRational value)
```


Sets the altitude based on the reference in  AltitudeRef . The reference unit is meters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The altitude based on the reference in  AltitudeRef . |

### getAltitudeRef() {#getAltitudeRef--}
```
public final ExifGpsAltitudeRef getAltitudeRef()
```


Gets the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the  Altitude  tag.

**Returns:**
[ExifGpsAltitudeRef](../../com.groupdocs.metadata.core/exifgpsaltituderef) - The altitude used as the reference altitude
### setAltitudeRef(ExifGpsAltitudeRef value) {#setAltitudeRef-com.groupdocs.metadata.core.ExifGpsAltitudeRef-}
```
public final void setAltitudeRef(ExifGpsAltitudeRef value)
```


Sets the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the  Altitude  tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExifGpsAltitudeRef](../../com.groupdocs.metadata.core/exifgpsaltituderef) | The altitude used as the reference altitude |

### getAreaInformation() {#getAreaInformation--}
```
public final byte[] getAreaInformation()
```


Gets the character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area.

**Returns:**
byte[] - The character string recording the name of the GPS area.
### setAreaInformation(byte[] value) {#setAreaInformation-byte---}
```
public final void setAreaInformation(byte[] value)
```


Sets the character string recording the name of the GPS area. The first byte indicates the character code used, and this is followed by the name of the GPS area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The character string recording the name of the GPS area. |

### getDateStamp() {#getDateStamp--}
```
public final String getDateStamp()
```


Gets the character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD.

**Returns:**
java.lang.String - The character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD.
### setDateStamp(String value) {#setDateStamp-java.lang.String-}
```
public final void setDateStamp(String value)
```


Sets the character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The character string recording date and time information relative to UTC (Coordinated Universal Time). The format is YYYY:MM:DD. |

### getDestBearing() {#getDestBearing--}
```
public final TiffRational getDestBearing()
```


Gets the GPS bearing to the destination point. The range of values is from 0.00 to 359.99.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The bearing to the destination point.
### setDestBearing(TiffRational value) {#setDestBearing-com.groupdocs.metadata.core.TiffRational-}
```
public final void setDestBearing(TiffRational value)
```


Sets the GPS bearing to the destination point. The range of values is from 0.00 to 359.99.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The bearing to the destination point. |

### getDestBearingRef() {#getDestBearingRef--}
```
public final String getDestBearingRef()
```


Gets the GPS reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is magnetic direction.

**Returns:**
java.lang.String - The GPS reference used for giving the bearing to the destination point.
### setDestBearingRef(String value) {#setDestBearingRef-java.lang.String-}
```
public final void setDestBearingRef(String value)
```


Sets the GPS reference used for giving the bearing to the destination point. 'T' denotes true direction and 'M' is magnetic direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The GPS reference used for giving the bearing to the destination point. |

### getDestDistance() {#getDestDistance--}
```
public final TiffRational getDestDistance()
```


Gets the GPS distance to the destination point.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The distance to the destination point.
### setDestDistance(TiffRational value) {#setDestDistance-com.groupdocs.metadata.core.TiffRational-}
```
public final void setDestDistance(TiffRational value)
```


Sets the GPS distance to the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The distance to the destination point. |

### getDestDistanceRef() {#getDestDistanceRef--}
```
public final String getDestDistanceRef()
```


Gets the GPS unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles and knots.

**Returns:**
java.lang.String - The GPS unit used to express the distance to the destination point.
### setDestDistanceRef(String value) {#setDestDistanceRef-java.lang.String-}
```
public final void setDestDistanceRef(String value)
```


Sets the GPS unit used to express the distance to the destination point. 'K', 'M' and 'N' represent kilometers, miles and knots.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The GPS unit used to express the distance to the destination point. |

### getDestLatitude() {#getDestLatitude--}
```
public final TiffRational[] getDestLatitude()
```


Gets the GPS latitude of the destination point.

**Returns:**
com.groupdocs.metadata.core.TiffRational[] - The latitude of the destination point.
### setDestLatitude(TiffRational[] value) {#setDestLatitude-com.groupdocs.metadata.core.TiffRational---}
```
public final void setDestLatitude(TiffRational[] value)
```


Sets the GPS latitude of the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.groupdocs.metadata.core/tiffrational) | The latitude of the destination point. |

### getDestLatitudeRef() {#getDestLatitudeRef--}
```
public final String getDestLatitudeRef()
```


Gets the GPS value which indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north latitude, and 'S' is south latitude.

**Returns:**
java.lang.String - The GPS value which indicates whether the latitude of the destination point is north or south latitude.
### setDestLatitudeRef(String value) {#setDestLatitudeRef-java.lang.String-}
```
public final void setDestLatitudeRef(String value)
```


Sets the GPS value which indicates whether the latitude of the destination point is north or south latitude. The ASCII value 'N' indicates north latitude, and 'S' is south latitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The GPS value which indicates whether the latitude of the destination point is north or south latitude. |

### getDestLongitude() {#getDestLongitude--}
```
public final TiffRational[] getDestLongitude()
```


Gets the GPS longitude of the destination point.

**Returns:**
com.groupdocs.metadata.core.TiffRational[] - The GPS longitude of the destination point.
### setDestLongitude(TiffRational[] value) {#setDestLongitude-com.groupdocs.metadata.core.TiffRational---}
```
public final void setDestLongitude(TiffRational[] value)
```


Sets the GPS longitude of the destination point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.groupdocs.metadata.core/tiffrational) | The GPS longitude of the destination point. |

### getDestLongitudeRef() {#getDestLongitudeRef--}
```
public final String getDestLongitudeRef()
```


Gets the GPS value which indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude, and 'W' is west longitude.

**Returns:**
java.lang.String - The GPS value which indicates whether the longitude of the destination point is east or west longitude.
### setDestLongitudeRef(String value) {#setDestLongitudeRef-java.lang.String-}
```
public final void setDestLongitudeRef(String value)
```


Sets the GPS value which indicates whether the longitude of the destination point is east or west longitude. ASCII 'E' indicates east longitude, and 'W' is west longitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The GPS value which indicates whether the longitude of the destination point is east or west longitude. |

### getDifferential() {#getDifferential--}
```
public final Integer getDifferential()
```


Gets a GPS value which indicates whether differential correction is applied to the GPS receiver.

**Returns:**
java.lang.Integer - A GPS value which indicates whether differential correction is applied to the GPS receiver.
### setDifferential(Integer value) {#setDifferential-java.lang.Integer-}
```
public final void setDifferential(Integer value)
```


Sets a GPS value which indicates whether differential correction is applied to the GPS receiver.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | A GPS value which indicates whether differential correction is applied to the GPS receiver. |

### getDataDegreeOfPrecision() {#getDataDegreeOfPrecision--}
```
public final TiffRational getDataDegreeOfPrecision()
```


Gets the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The data degree of precision.
### setDataDegreeOfPrecision(TiffRational value) {#setDataDegreeOfPrecision-com.groupdocs.metadata.core.TiffRational-}
```
public final void setDataDegreeOfPrecision(TiffRational value)
```


Sets the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The data degree of precision. |

### getImgDirection() {#getImgDirection--}
```
public final TiffRational getImgDirection()
```


Gets the GPS direction of the image when it was captured. The range of values is from 0.00 to 359.99.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The GPS direction of the image when it was captured.
### setImgDirection(TiffRational value) {#setImgDirection-com.groupdocs.metadata.core.TiffRational-}
```
public final void setImgDirection(TiffRational value)
```


Sets the GPS direction of the image when it was captured. The range of values is from 0.00 to 359.99.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The GPS direction of the image when it was captured. |

### getImgDirectionRef() {#getImgDirectionRef--}
```
public final String getImgDirectionRef()
```


Gets the GPS reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is magnetic direction.

**Returns:**
java.lang.String - The GPS reference for giving the direction of the image when it is captured.
### setImgDirectionRef(String value) {#setImgDirectionRef-java.lang.String-}
```
public final void setImgDirectionRef(String value)
```


Sets the GPS reference for giving the direction of the image when it is captured. 'T' denotes true direction and 'M' is magnetic direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The GPS reference for giving the direction of the image when it is captured. |

### getLatitude() {#getLatitude--}
```
public final TiffRational[] getLatitude()
```


Gets the GPS latitude.

**Returns:**
com.groupdocs.metadata.core.TiffRational[] - The latitude.
### setLatitude(TiffRational[] value) {#setLatitude-com.groupdocs.metadata.core.TiffRational---}
```
public final void setLatitude(TiffRational[] value)
```


Sets the GPS latitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.groupdocs.metadata.core/tiffrational) | The latitude. |

### getLatitudeRef() {#getLatitudeRef--}
```
public final String getLatitudeRef()
```


Gets a GPS value indicating whether the latitude is north or south latitude.

**Returns:**
java.lang.String - A GPS value indicating whether the latitude is north or south latitude.
### setLatitudeRef(String value) {#setLatitudeRef-java.lang.String-}
```
public final void setLatitudeRef(String value)
```


Sets a GPS value indicating whether the latitude is north or south latitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A GPS value indicating whether the latitude is north or south latitude. |

### getLongitude() {#getLongitude--}
```
public final TiffRational[] getLongitude()
```


Gets the GPS longitude.

**Returns:**
com.groupdocs.metadata.core.TiffRational[] - The longitude.
### setLongitude(TiffRational[] value) {#setLongitude-com.groupdocs.metadata.core.TiffRational---}
```
public final void setLongitude(TiffRational[] value)
```


Sets the GPS longitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.groupdocs.metadata.core/tiffrational) | The longitude. |

### getLongitudeRef() {#getLongitudeRef--}
```
public final String getLongitudeRef()
```


Gets a GPS value indicating whether the longitude is east or west longitude.

**Returns:**
java.lang.String - A GPS value indicating whether the longitude is east or west longitude.
### setLongitudeRef(String value) {#setLongitudeRef-java.lang.String-}
```
public final void setLongitudeRef(String value)
```


Sets a GPS value indicating whether the longitude is east or west longitude.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A GPS value indicating whether the longitude is east or west longitude. |

### getMapDatum() {#getMapDatum--}
```
public final String getMapDatum()
```


Gets the geodetic survey data used by the GPS receiver.

**Returns:**
java.lang.String - The geodetic survey data used by the GPS receiver.
### setMapDatum(String value) {#setMapDatum-java.lang.String-}
```
public final void setMapDatum(String value)
```


Sets the geodetic survey data used by the GPS receiver.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The geodetic survey data used by the GPS receiver. |

### getMeasureMode() {#getMeasureMode--}
```
public final String getMeasureMode()
```


Gets the GPS measurement mode.

**Returns:**
java.lang.String - The measure mode.
### setMeasureMode(String value) {#setMeasureMode-java.lang.String-}
```
public final void setMeasureMode(String value)
```


Sets the GPS measurement mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The measure mode. |

### getProcessingMethod() {#getProcessingMethod--}
```
public final byte[] getProcessingMethod()
```


Gets a character string recording the name of the method used for location finding. The first byte indicates the character code used, and this is followed by the name of the method.

**Returns:**
byte[] - A character string recording the name of the method used for location finding.
### setProcessingMethod(byte[] value) {#setProcessingMethod-byte---}
```
public final void setProcessingMethod(byte[] value)
```


Sets a character string recording the name of the method used for location finding. The first byte indicates the character code used, and this is followed by the name of the method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | A character string recording the name of the method used for location finding. |

### getSatellites() {#getSatellites--}
```
public final String getSatellites()
```


Gets the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL.

**Returns:**
java.lang.String - The GPS satellites used for measurements.
### setSatellites(String value) {#setSatellites-java.lang.String-}
```
public final void setSatellites(String value)
```


Sets the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The GPS satellites used for measurements. |

### getSpeed() {#getSpeed--}
```
public final TiffRational getSpeed()
```


Gets the speed of GPS receiver movement.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The speed of GPS receiver movement.
### setSpeed(TiffRational value) {#setSpeed-com.groupdocs.metadata.core.TiffRational-}
```
public final void setSpeed(TiffRational value)
```


Sets the speed of GPS receiver movement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The speed of GPS receiver movement. |

### getSpeedRef() {#getSpeedRef--}
```
public final String getSpeedRef()
```


Gets the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots.

**Returns:**
java.lang.String - The unit used to express the GPS receiver speed of movement.
### setSpeedRef(String value) {#setSpeedRef-java.lang.String-}
```
public final void setSpeedRef(String value)
```


Sets the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The unit used to express the GPS receiver speed of movement. |

### getStatus() {#getStatus--}
```
public final String getStatus()
```


Gets the status of the GPS receiver when the image is recorded.

**Returns:**
java.lang.String - The status of the GPS receiver when the image is recorded.
### setStatus(String value) {#setStatus-java.lang.String-}
```
public final void setStatus(String value)
```


Sets the status of the GPS receiver when the image is recorded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The status of the GPS receiver when the image is recorded. |

### getTimeStamp() {#getTimeStamp--}
```
public final TiffRational[] getTimeStamp()
```


Gets the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second.

**Returns:**
com.groupdocs.metadata.core.TiffRational[] - The time as UTC (Coordinated Universal Time).
### setTimeStamp(TiffRational[] value) {#setTimeStamp-com.groupdocs.metadata.core.TiffRational---}
```
public final void setTimeStamp(TiffRational[] value)
```


Sets the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.groupdocs.metadata.core/tiffrational) | The time as UTC (Coordinated Universal Time). |

### getGpsTrack() {#getGpsTrack--}
```
public final TiffRational getGpsTrack()
```


Gets the direction of GPS receiver movement.

**Returns:**
[TiffRational](../../com.groupdocs.metadata.core/tiffrational) - The direction of GPS receiver movement.
### setGpsTrack(TiffRational value) {#setGpsTrack-com.groupdocs.metadata.core.TiffRational-}
```
public final void setGpsTrack(TiffRational value)
```


Sets the direction of GPS receiver movement.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TiffRational](../../com.groupdocs.metadata.core/tiffrational) | The direction of GPS receiver movement. |

### getTrackRef() {#getTrackRef--}
```
public final String getTrackRef()
```


Gets the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is magnetic direction.

**Returns:**
java.lang.String - The reference for giving the direction of GPS receiver movement.
### setTrackRef(String value) {#setTrackRef-java.lang.String-}
```
public final void setTrackRef(String value)
```


Sets the reference for giving the direction of GPS receiver movement. 'T' denotes true direction and 'M' is magnetic direction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The reference for giving the direction of GPS receiver movement. |

### getVersionID() {#getVersionID--}
```
public final byte[] getVersionID()
```


Gets the version of GPS IFD.

**Returns:**
byte[] - The version of GPS IFD
### setVersionID(byte[] value) {#setVersionID-byte---}
```
public final void setVersionID(byte[] value)
```


Sets the version of GPS IFD.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The version of GPS IFD |

