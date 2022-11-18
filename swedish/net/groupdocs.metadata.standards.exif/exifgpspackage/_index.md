---
title: ExifGpsPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar GPSmetadata i ett EXIFmetadatapaket.
type: docs
weight: 2770
url: /sv/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Representerar GPS-metadata i ett EXIF-metadatapaket.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Initierar en ny instans av[`ExifGpsPackage`](../exifgpspackage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Hämtar eller ställer in höjden baserat på referensen i[`AltitudeRef`](./altituderef) . Referensenheten är meter. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Hämtar eller ställer in höjden som används som referenshöjd. Om referensen är havsnivån och höjden över havet ges 0. Om höjden är under havsytan ges ett värde på 1 och höjden anges som ett absolut värde i[`Altitude`](./altitude) tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Hämtar eller ställer in teckensträngen som registrerar namnet på GPS-området. Den första byten anger teckenkoden som används, och denna följs av namnet på GPS-området. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Hämtar eller ställer in GPS DOP (datagrad av precision). Ett HDOP-värde skrivs under tvådimensionell mätning och PDOP under tredimensionell mätning. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Hämtar eller ställer in teckensträngens inspelningsdatum och tidsinformation i förhållande till UTC (Coordinated Universal Time). Formatet är ÅÅÅÅ:MM:DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Hämtar eller ställer in GPS-bäringen till destinationspunkten. Värdeintervallet är från 0,00 till 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Hämtar eller ställer in GPS-referensen som används för att ge bäringen till destinationspunkten. 'T' anger sann riktning och 'M' är magnetisk riktning. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Hämtar eller ställer in GPS-avståndet till destinationspunkten. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Hämtar eller ställer in GPS-enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles och knop. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Hämtar eller ställer in GPS-latitud för destinationspunkten. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Hämtar eller ställer in GPS-värdet som anger om latituden för destinationspunkten är nordlig eller sydlig latitud. ASCII-värdet 'N' indikerar nordlig latitud och 'S' är sydlig latitud. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Hämtar eller ställer in GPS-longituden för destinationspunkten. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Hämtar eller ställer in GPS-värdet som indikerar om longituden för destinationspunkten är östlig eller västlig longitud. ASCII 'E' anger östlig longitud och 'W' är västlig longitud. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Hämtar eller ställer in ett GPS-värde som indikerar om differentiell korrigering tillämpas på GPS-mottagaren. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Hämtar eller ställer in riktningen för GPS-mottagarens rörelse. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Hämtar eller ställer in GPS-riktningen för bilden när den togs. Värdeintervallet är från 0,00 till 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Hämtar eller ställer in GPS-referensen för att ge bildens riktning när den tas. 'T' anger sann riktning och 'M' är magnetisk riktning. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Hämtar TIFF-taggen med angivet id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Hämtar eller ställer in GPS-latitud. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Hämtar eller ställer in ett GPS-värde som anger om latituden är nordlig eller sydlig latitud. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Hämtar eller ställer in GPS-längdgraden. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Hämtar eller ställer in ett GPS-värde som indikerar om longituden är östlig eller västlig longitud. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Hämtar eller ställer in geodetiska mätdata som används av GPS-mottagaren. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Hämtar eller ställer in GPS-mätläget. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Hämtar eller ställer in en teckensträng som registrerar namnet på metoden som används för att hitta plats. Den första byten indikerar teckenkoden som används, och detta följs av namnet på metoden. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Hämtar eller ställer in GPS-satelliterna som används för mätningar. Denna tagg kan användas för att beskriva antalet satelliter, deras ID-nummer, höjdvinkel, azimut, SNR och annan information i ASCII-notation. Formatet är inte specificerat. Om GPS-mottagaren inte kan göra mätningar ska värdet på taggen sättas till NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Hämtar eller ställer in hastigheten för GPS-mottagarens rörelse. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Hämtar eller ställer in enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. 'K' 'M' och 'N' representerar kilometer per timme, miles per timme och knop. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Hämtar eller ställer in GPS-mottagarens status när bilden spelas in. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Hämtar eller ställer in tiden som UTC (Coordinated Universal Time). TimeStamp uttrycks som tre RATIONELLA värden som ger timme, minut och sekund. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Hämtar eller ställer in referensen för att ge GPS-mottagarens rörelseriktning. 'T' anger sann riktning och 'M' är magnetisk riktning. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Hämtar eller ställer in versionen av GPS IFD. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Tar bort alla TIFF-taggar som är lagrade i paketet. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Tar bort egenskapen med angivet id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Lägger till eller ersätter den angivna taggen. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Skapar en lista från paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Arbeta med EXIF-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Se även

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* namnutrymme [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
