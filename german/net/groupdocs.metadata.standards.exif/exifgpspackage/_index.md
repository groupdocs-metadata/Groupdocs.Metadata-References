---
title: ExifGpsPackage
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Stellt GPSMetadaten in einem EXIFMetadatenpaket dar.
type: docs
weight: 2770
url: /de/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Stellt GPS-Metadaten in einem EXIF-Metadatenpaket dar.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Initialisiert eine neue Instanz von[`ExifGpsPackage`](../exifgpspackage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Holt oder setzt die Höhe basierend auf der Referenz in[`AltitudeRef`](./altituderef) . Die Referenzeinheit ist Meter. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Ermittelt oder setzt die Höhe, die als Referenzhöhe verwendet wird. Wenn die Referenz der Meeresspiegel ist und die Höhe über dem Meeresspiegel liegt, wird 0 angegeben. Wenn die Höhe unter dem Meeresspiegel liegt, wird der Wert 1 angegeben und die Höhe wird als absoluter Wert in angegeben[`Altitude`](./altitude) tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Ermittelt oder setzt die Zeichenfolge, die den Namen des GPS-Bereichs aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen des GPS-Bereichs. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ruft die Anzahl der Metadateneigenschaften ab. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Ruft den GPS-DOP (Datengenauigkeitsgrad) ab oder legt ihn fest. Während der zweidimensionalen Messung wird ein HDOP-Wert und während der dreidimensionalen Messung ein PDOP-Wert geschrieben. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Ruft die Datums- und Zeitinformationen der Zeichenkette für die Aufzeichnung relativ zur UTC (Koordinierte Weltzeit) ab oder legt sie fest. Das Format ist JJJJ:MM:TT. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Ruft die GPS-Peilung zum Zielpunkt ab oder setzt sie. Der Wertebereich reicht von 0,00 bis 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Ruft die GPS-Referenz ab oder legt sie fest, die für die Peilung zum Zielpunkt verwendet wird. „T“ bezeichnet die wahre Richtung und „M“ die magnetische Richtung. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Ruft die GPS-Entfernung zum Zielpunkt ab oder legt sie fest. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Ruft die GPS-Einheit ab oder legt sie fest, die verwendet wird, um die Entfernung zum Zielpunkt auszudrücken. „K“, „M“ und „N“ stehen für Kilometer, Meilen und Knoten. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Ruft den GPS-Breitengrad des Zielpunkts ab oder legt ihn fest. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Ruft den GPS-Wert ab oder legt ihn fest, der angibt, ob der Breitengrad des Zielpunkts der nördliche oder der südliche Breitengrad ist. Der ASCII-Wert „N“ gibt den nördlichen Breitengrad und „S“ den südlichen Breitengrad an. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Ruft den GPS-Längengrad des Zielpunkts ab oder legt ihn fest. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Ruft den GPS-Wert ab oder legt ihn fest, der angibt, ob der Längengrad des Zielpunkts der östliche oder der westliche Längengrad ist. ASCII „E“ steht für den östlichen Längengrad und „W“ für den westlichen Längengrad. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Ruft einen GPS-Wert ab oder legt ihn fest, der angibt, ob eine Differentialkorrektur auf den GPS-Empfänger angewendet wird. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Ruft die Bewegungsrichtung des GPS-Empfängers ab oder legt sie fest. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Ruft die GPS-Richtung des Bildes bei der Aufnahme ab oder legt sie fest. Der Wertebereich reicht von 0,00 bis 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Ruft die GPS-Referenz ab oder legt sie fest, um die Richtung des Bildes bei der Aufnahme anzugeben. „T“ bezeichnet die wahre Richtung und „M“ die magnetische Richtung. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Ruft das TIFF-Tag mit der angegebenen ID ab. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ruft eine Sammlung der Metadaten-Eigenschaftsnamen ab. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Ruft den GPS-Breitengrad ab oder legt ihn fest. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Ruft einen GPS-Wert ab oder legt ihn fest, der angibt, ob der Breitengrad der nördliche oder der südliche Breitengrad ist. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Ruft den GPS-Längengrad ab oder legt ihn fest. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Ruft einen GPS-Wert ab oder legt ihn fest, der angibt, ob der Längengrad der östliche oder der westliche Längengrad ist. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Ruft die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten ab oder legt sie fest. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Ruft den GPS-Messmodus ab oder legt ihn fest. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ruft den Metadatentyp ab. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Erhält oder setzt eine Zeichenkette, die den Namen der für die Standortbestimmung verwendeten Methode aufzeichnet. Das erste Byte gibt den verwendeten Zeichencode an, gefolgt vom Namen der Methode. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ruft eine Sammlung von Deskriptoren ab, die Informationen zu Eigenschaften enthalten, auf die über die Suchmaschine GroupDocs.Metadata zugegriffen werden kann. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Ruft die für Messungen verwendeten GPS-Satelliten ab oder setzt sie. Dieses Tag kann verwendet werden, um die Anzahl der Satelliten, ihre ID-Nummer, Höhenwinkel, Azimut, SNR und andere Informationen in ASCII-Notation zu beschreiben. Das Format ist not angegeben. Wenn der GPS-Empfänger keine Messungen vornehmen kann, muss der Wert des Tags auf NULL gesetzt werden. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Ruft die Bewegungsgeschwindigkeit des GPS-Empfängers ab oder legt sie fest. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Ruft die Einheit ab oder legt sie fest, die verwendet wird, um die Bewegungsgeschwindigkeit des GPS-Empfängers auszudrücken. „K“, „M“ und „N“ stehen für Kilometer pro Stunde, Meilen pro Stunde und Knoten. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Ruft den Status des GPS-Empfängers ab oder setzt ihn, wenn das Bild aufgezeichnet wird. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Ruft die Uhrzeit als UTC (Coordinated Universal Time) ab oder legt sie fest. TimeStamp wird als drei RATIONAL-Werte ausgedrückt, die Stunde, Minute und Sekunde angeben. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Ruft die Referenz für die Angabe der Bewegungsrichtung des GPS-Empfängers ab oder legt sie fest. „T“ bezeichnet die wahre Richtung und „M“ die magnetische Richtung. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Ruft die Version von GPS IFD ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Fügt bekannte Metadateneigenschaften hinzu, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Entfernt alle im Paket gespeicherten TIFF-Tags. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestimmt, ob das Paket eine Metadateneigenschaft mit dem angegebenen Namen enthält. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Findet die Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Suche ist rekursiv, sodass sie auch alle verschachtelten Pakete betrifft. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Entfernt die Eigenschaft mit der angegebenen ID. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Entfernt Metadateneigenschaften, die das angegebene Prädikat erfüllen. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Entfernt beschreibbare Metadateneigenschaften aus dem Paket. Der Vorgang ist rekursiv, sodass er sich auch auf alle verschachtelten Pakete auswirkt. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Fügt das angegebene Tag hinzu oder ersetzt es. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Legt bekannte Metadateneigenschaften fest, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. Diese Methode ist eine Kombination aus[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Und[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Wenn eine vorhandene Eigenschaft das Prädikat erfüllt, wird ihr Wert aktualisiert. Wenn im Paket eine bekannte Eigenschaft fehlt, die das Prädikat erfüllt, wird sie dem Paket hinzugefügt. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Erstellt eine Liste aus dem Paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aktualisiert bekannte Metadateneigenschaften, die das angegebene Prädikat erfüllen. Die Operation ist rekursiv, sodass sie sich auch auf alle verschachtelten Pakete auswirkt. |

### Bemerkungen

**Erfahren Sie mehr**

* [Arbeiten mit EXIF-Metadaten](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Siehe auch

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* namensraum [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
