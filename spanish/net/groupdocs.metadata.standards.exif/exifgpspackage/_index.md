---
title: ExifGpsPackage
second_title: Referencia de API de GroupDocs.Metadata para .NET
description: Representa metadatos GPS en un paquete de metadatos EXIF.
type: docs
weight: 2770
url: /es/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Representa metadatos GPS en un paquete de metadatos EXIF.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Inicializa una nueva instancia del[`ExifGpsPackage`](../exifgpspackage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Obtiene o establece la altitud en función de la referencia en[`AltitudeRef`](./altituderef) . La unidad de referencia es metros. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Obtiene o establece la altitud utilizada como altitud de referencia. Si la referencia es el nivel del mar y la altitud es sobre el nivel del mar, se da 0. Si la altitud es bajo el nivel del mar, se da el valor 1 y la altitud se indica en valor absoluto en el[`Altitude`](./altitude) etiqueta. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Obtiene o establece la cadena de caracteres que registra el nombre del área GPS. El primer byte indica el código de carácter utilizado, seguido del nombre de la zona GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Obtiene el número de propiedades de metadatos. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Obtiene o establece el DOP (grado de precisión de los datos) del GPS. Se escribe un valor HDOP durante la medición bidimensional y PDOP durante la medición tridimensional. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Obtiene o establece la cadena de caracteres que registra la información de fecha y hora relativa a UTC (hora universal coordinada). El formato es AAAA:MM:DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Obtiene o establece el rumbo GPS hacia el punto de destino. El rango de valores es de 0.00 a 359.99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Obtiene o establece la referencia de GPS utilizada para dar el rumbo al punto de destino. 'T' indica la dirección verdadera y 'M' es la dirección magnética. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Obtiene o establece la distancia GPS al punto de destino. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. 'K', 'M' y 'N' representan kilómetros, millas y nudos. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Obtiene o establece la latitud GPS del punto de destino. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es latitud norte o sur. El valor ASCII 'N' indica latitud norte y 'S' es latitud sur. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Obtiene o establece la longitud GPS del punto de destino. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es longitud este u oeste. ASCII 'E' indica longitud este y 'W' es longitud oeste. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Obtiene o establece la dirección del movimiento del receptor GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Obtiene o establece la dirección GPS de la imagen cuando fue capturada. El rango de valores es de 0.00 a 359.99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Obtiene o establece la referencia GPS para dar la dirección de la imagen cuando se captura. 'T' indica la dirección verdadera y 'M' es la dirección magnética. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Obtiene la etiqueta TIFF con el id especificado. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Obtiene una colección de nombres de propiedades de metadatos. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Obtiene o establece la latitud del GPS. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Obtiene o establece un valor de GPS que indica si la latitud es norte o sur. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Obtiene o establece la longitud del GPS. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Obtiene o establece un valor de GPS que indica si la longitud es este u oeste. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Obtiene o establece los datos del levantamiento geodésico utilizados por el receptor GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Obtiene o establece el modo de medición GPS. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Obtiene el tipo de metadato. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Obtiene o establece una cadena de caracteres que registra el nombre del método utilizado para buscar la ubicación. El primer byte indica el código de carácter utilizado, seguido del nombre del método. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Obtiene una colección de descriptores que contienen información sobre propiedades accesibles a través del motor de búsqueda GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Obtiene o establece los satélites GPS utilizados para las mediciones. Esta etiqueta se puede utilizar para describir el número de satélites, su número de ID, ángulo de elevación, acimut, SNR y otra información en notación ASCII. El formato no está especificado. Si el receptor GPS no puede tomar medidas, el valor de la etiqueta se establecerá en NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Obtiene o establece la velocidad de movimiento del receptor GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. 'K' 'M' y 'N' representan kilómetros por hora, millas por hora y nudos. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Obtiene o establece el estado del receptor GPS cuando se graba la imagen. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Obtiene o establece la hora como UTC (Tiempo Universal Coordinado). TimeStamp se expresa como tres valores RACIONALES que dan la hora, el minuto y el segundo. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Obtiene o establece la referencia para dar la dirección del movimiento del receptor GPS. 'T' indica la dirección verdadera y 'M' es la dirección magnética. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Obtiene o establece la versión de GPS IFD. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Agrega propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Elimina todas las etiquetas TIFF almacenadas en el paquete. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina si el paquete contiene una propiedad de metadatos con el nombre especificado. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Encuentra las propiedades de metadatos que satisfacen el predicado especificado. La búsqueda es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Elimina la propiedad con el id especificado. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Elimina las propiedades de metadatos que cumplen el predicado especificado. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Elimina las propiedades de metadatos de escritura del paquete. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Agrega o reemplaza la etiqueta especificada. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Establece propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. Este método es una combinación de[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) y[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Si una propiedad existente satisface el predicado, su valor se actualiza. Si falta una propiedad conocida en el paquete que satisface el predicado, se agrega al paquete. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crea una lista a partir del paquete. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Actualiza las propiedades de metadatos conocidas que satisfacen el predicado especificado. La operación es recursiva, por lo que también afecta a todos los paquetes anidados. |

### Observaciones

**Aprende más**

* [Trabajar con metadatos EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Ver también

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* espacio de nombres [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* asamblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
