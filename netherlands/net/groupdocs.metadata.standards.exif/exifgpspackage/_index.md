---
title: ExifGpsPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt GPSmetadata in een EXIFmetadatapakket.
type: docs
weight: 2770
url: /nl/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Vertegenwoordigt GPS-metadata in een EXIF-metadatapakket.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Initialiseert een nieuw exemplaar van het[`ExifGpsPackage`](../exifgpspackage) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Haalt de hoogte op of stelt deze in op basis van de referentie in[`AltitudeRef`](./altituderef) . De referentie-eenheid is meter. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Haalt de hoogte op of stelt deze in als referentiehoogte. Als de referentie zeeniveau is en de hoogte boven zeeniveau, wordt 0 gegeven. Als de hoogte onder zeeniveau ligt, wordt een waarde van 1 gegeven en wordt de hoogte aangegeven als een absolute waarde in de[`Altitude`](./altitude) tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Haalt of stelt de tekenreeks in die de naam van het GPS-gebied vastlegt. De eerste byte geeft de gebruikte tekencode aan, gevolgd door de naam van het GPS-gebied. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Ontvangt of stelt de GPS DOP (gegevensgraad van precisie) in. Een HDOP-waarde wordt geschreven tijdens tweedimensionale meting, en PDOP tijdens driedimensionale meting. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Haalt of stelt de tekenreeks opnamedatum- en tijdinformatie in ten opzichte van UTC (Coordinated Universal Time). Het formaat is JJJJ:MM:DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Haalt de GPS-peiling op of stelt deze in op het bestemmingspunt. Het waardenbereik loopt van 0,00 tot 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Haalt of stelt de GPS-referentie in die wordt gebruikt voor het geven van de peiling naar het bestemmingspunt. 'T' geeft de ware richting aan en 'M' is de magnetische richting. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Haalt de GPS-afstand tot het bestemmingspunt op of stelt deze in. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Haalt of stelt de GPS-eenheid in die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken. 'K', 'M' en 'N' vertegenwoordigen kilometers, mijlen en knopen. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Haalt de GPS-breedtegraad van het bestemmingspunt op of stelt deze in. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Ontvangt of stelt de GPS-waarde in die aangeeft of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is. De ASCII-waarde 'N' geeft noorderbreedte aan en 'S' is zuiderbreedte. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Haalt de GPS-lengtegraad van het bestemmingspunt op of stelt deze in. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Haalt of stelt de GPS-waarde in die aangeeft of de lengtegraad van het bestemmingspunt oost- of westlengte is. ASCII 'E' geeft oosterlengte aan en 'W' is westerlengte. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Ontvangt of stelt een GPS-waarde in die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Ontvangt of stelt de richting van de beweging van de GPS-ontvanger in. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Hiermee wordt de GPS-richting van het beeld opgehaald of ingesteld toen het werd vastgelegd. Het waardenbereik loopt van 0,00 tot 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Haalt de GPS-referentie op of stelt deze in om de richting van het beeld aan te geven wanneer het wordt vastgelegd. 'T' geeft de ware richting aan en 'M' is de magnetische richting. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Haalt de TIFF-tag op met de opgegeven id. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Haalt de GPS-breedtegraad op of stelt deze in. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Haalt of stelt een GPS-waarde in die aangeeft of de breedtegraad noord- of zuiderbreedte is. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Haalt of stelt de GPS-lengtegraad in. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Haalt of stelt een GPS-waarde in die aangeeft of de lengtegraad oost- of westlengte is. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Haalt of stelt de geodetische onderzoeksgegevens in die door de GPS-ontvanger worden gebruikt. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Ontvangt of stelt de GPS-meetmodus in. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Haalt of stelt een tekenreeks in die de naam vastlegt van de methode die wordt gebruikt voor het vinden van een locatie. De eerste byte geeft de gebruikte tekencode aan, gevolgd door de naam van de methode. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Ontvangt of stelt de GPS-satellieten in die voor metingen worden gebruikt. Deze tag kan worden gebruikt om het aantal satellieten, hun ID-nummer, elevatiehoek, azimut, SNR en andere informatie in ASCII-notatie te beschrijven. Het formaat is not gespecificeerd. Als de GPS-ontvanger geen metingen kan uitvoeren, wordt de waarde van de tag ingesteld op NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Haalt of stelt de snelheid van de beweging van de GPS-ontvanger in. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Hiermee wordt de eenheid opgehaald of ingesteld die wordt gebruikt om de bewegingssnelheid van de GPS-ontvanger uit te drukken. 'K' 'M' en 'N' staan voor kilometer per uur, mijl per uur en knopen. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Ontvangt of stelt de status van de GPS-ontvanger in wanneer het beeld wordt opgenomen. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Haalt de tijd op of stelt deze in als UTC (Coordinated Universal Time). Tijdstempel wordt uitgedrukt als drie RATIONELE waarden die het uur, de minuut en de seconde aangeven. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Haalt of stelt de referentie in voor het aangeven van de richting van de beweging van de GPS-ontvanger. 'T' geeft de ware richting aan en 'M' is de magnetische richting. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Haalt de versie van GPS IFD op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Verwijdert alle TIFF-tags die in het pakket zijn opgeslagen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Verwijdert de eigenschap met de opgegeven id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Voegt de opgegeven tag toe of vervangt deze. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Maakt een lijst van het pakket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met EXIF-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Zie ook

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* naamruimte [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
