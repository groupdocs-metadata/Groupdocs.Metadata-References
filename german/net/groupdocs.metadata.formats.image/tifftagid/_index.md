---
title: TiffTagID
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Definiert IDs von TIFFTags.
type: docs
weight: 2100
url: /de/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Definiert IDs von TIFF-Tags.

```csharp
public enum TiffTagID : ushort
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| GpsVersionID | `0` | Zeigt die Version von GPSInfoIFD an. |
| GpsLatitudeRef | `1` | Gibt an, ob der Breitengrad der nördliche oder der südliche Breitengrad ist. |
| GpsLatitude | `2` | Gibt den Breitengrad an. |
| GpsLongitudeRef | `3` | Gibt an, ob der Längengrad östlicher oder westlicher Längengrad ist. |
| GpsLongitude | `4` | Gibt den Längengrad an. |
| GpsAltitudeRef | `5` | Zeigt die als Referenzhöhe verwendete Höhe an. |
| GpsAltitude | `6` | Gibt die Höhe basierend auf der Referenz in GPSAltitudeRef. an |
| GpsTimeStamp | `7` | Zeigt die Zeit als UTC (Koordinierte Weltzeit) an. |
| GpsSatellites | `8` | gibt die für Messungen verwendeten GPS-Satelliten an. |
| GpsStatus | `9` | Zeigt den Status des GPS-Empfängers an, wenn das Bild aufgezeichnet wird. |
| GpsMeasureMode | `10` | Zeigt den GPS-Messmodus an. |
| GpsDop | `11` | Gibt den GPS-DOP (Datengenauigkeitsgrad) an. |
| GpsSpeedRef | `12` | Gibt die Einheit an, die verwendet wird, um die Bewegungsgeschwindigkeit des GPS-Empfängers auszudrücken |
| GpsSpeed | `13` | Zeigt die Bewegungsgeschwindigkeit des GPS-Empfängers an. |
| GpsTrackRef | `14` | Gibt die Referenz an, um die Bewegungsrichtung des GPS-Empfängers anzugeben. |
| GpsTrack | `15` | Zeigt die Bewegungsrichtung des GPS-Empfängers an. |
| GpsImgDirectionRef | `16` | Gibt die Referenz an, um die Richtung des Bildes anzugeben, wenn es aufgenommen wird. |
| GpsImgDirection | `17` | Gibt die Richtung des Bildes an, als es aufgenommen wurde. |
| GpsMapDatum | `18` | Zeigt die vom GPS-Empfänger verwendeten geodätischen Vermessungsdaten an. |
| GpsDestLatitudeRef | `19` | Gibt an, ob der Breitengrad des Zielpunkts der nördliche oder der südliche Breitengrad ist. |
| GpsDestLatitude | `20` | Gibt den Breitengrad des Zielpunkts an. |
| GpsDestLongitudeRef | `21` | Gibt an, ob der Längengrad des Zielpunkts östlicher oder westlicher Längengrad ist. |
| GpsDestLongitude | `22` | Gibt den Längengrad des Zielpunkts an. |
| GpsDestBearingRef | `23` | Gibt die Referenz an, die für die Peilung zum Zielpunkt verwendet wird. |
| GpsDestBearing | `24` | Zeigt die Peilung zum Zielpunkt an. |
| GpsDestDistanceRef | `25` | Gibt die Einheit an, die verwendet wird, um die Entfernung zum Zielpunkt auszudrücken. |
| GpsDestDistance | `26` | Gibt die Entfernung zum Zielpunkt an. |
| GpsProcessingMethod | `27` | Eine Zeichenfolge, die den Namen der Methode enthält, die für die Standortbestimmung verwendet wird. |
| GpsAreaInformation | `28` | Eine Zeichenfolge, die den Namen des GPS-Bereichs aufzeichnet. |
| GpsDateStamp | `29` | Eine Zeichenkette, die Datums- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. |
| GpsDifferential | `30` | Gibt an, ob eine differentielle Korrektur auf den GPS-Empfänger angewendet wird. |
| GpsHPositioningError | `31` | Dieses Tag zeigt horizontale Positionierungsfehler in Metern an. |
| NewSubfileType | `254` | Ein allgemeiner Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten. |
| SubfileType | `255` | Ein allgemeiner Hinweis auf die Art der in dieser Unterdatei enthaltenen Daten. Dieses Feld ist veraltet. Das Feld NewSubfileType sollte stattdessen verwendet werden |
| ImageWidth | `256` | Die Anzahl der Spalten im Bild, dh die Anzahl der Pixel pro Abtastzeile. |
| ImageLength | `257` | Die Anzahl der Zeilen (manchmal als Scanlinien bezeichnet) im Bild. |
| BitsPerSample | `258` | Anzahl Bits pro Komponente. |
| Compression | `259` | Komprimierungsschema, das für die Bilddaten verwendet wird. |
| PhotometricInterpretation | `262` | Der Farbraum der Bilddaten. |
| Threshholding | `263` | Für Schwarz-Weiß-TIFF-Dateien, die Graustufen darstellen, die Technik, die zum Konvertieren von grauen in Schwarz-Weiß-Pixel verwendet wird. |
| CellWidth | `264` | Die Breite der Dithering- oder Halbtonmatrix, die verwendet wird, um eine geditherte oder gerasterte Bi-Level-Datei zu erstellen. |
| CellLength | `265` | Die Länge der Dithering- oder Halbtonmatrix, die verwendet wird, um eine geditherte oder gerasterte Bi-Level-Datei zu erstellen. |
| FillOrder | `266` | Die logische Reihenfolge der Bits innerhalb eines Bytes. |
| DocumentName | `269` | Der Name des Dokuments, von dem dieses Bild gescannt wurde. |
| ImageDescription | `270` | Eine Zeichenfolge, die das Thema des Bildes beschreibt. |
| Make | `271` | Der Scannerhersteller. |
| Model | `272` | Name oder Nummer des Scannermodells. |
| StripOffsets | `273` | Für jeden Streifen der Byte-Offset dieses Streifens. |
| Orientation | `274` | Die Ausrichtung des Bildes in Bezug auf die Zeilen und Spalten. |
| SamplesPerPixel | `277` | Die Anzahl der Komponenten pro Pixel. |
| RowsPerStrip | `278` | Die Anzahl der Reihen pro Streifen. |
| StripByteCounts | `279` | Für jeden Streifen die Anzahl der Bytes im Streifen nach der Komprimierung. |
| MinSampleValue | `280` | Der minimal verwendete Komponentenwert. |
| MaxSampleValue | `281` | Der maximal verwendete Komponentenwert. |
| XResolution | `282` | Die Anzahl der Pixel pro Auflösungseinheit in Richtung der Bildbreite. |
| YResolution | `283` | Die Anzahl der Pixel pro Auflösungseinheit in Richtung der Bildlänge. |
| PlanarConfiguration | `284` | Wie die Komponenten jedes Pixels gespeichert werden. |
| PageName | `285` | Der Name der Seite, von der dieses Bild gescannt wurde. |
| XPosition | `286` | X-Position des Bildes. |
| YPosition | `287` | Y-Position des Bildes. |
| FreeOffsets | `288` | Für jede Zeichenfolge zusammenhängender unbenutzter Bytes in einer TIFF-Datei der Byte-Offset der Zeichenfolge. |
| FreeByteCounts | `289` | Für jede Zeichenfolge zusammenhängender unbenutzter Bytes in einer TIFF-Datei die Anzahl der Bytes in der Zeichenfolge. |
| GrayResponseUnit | `290` | Die Genauigkeit der in der GrayResponseCurve enthaltenen Informationen. |
| GrayResponseCurve | `291` | Für Graustufendaten die optische Dichte jedes möglichen Pixelwerts. |
| T4Options | `292` | T4-Codierungsoptionen. |
| T6Options | `293` | T6-Codierungsoptionen. |
| ResolutionUnit | `296` | Die Maßeinheit für XResolution und YResolution. |
| PageNumber | `297` | Die Seitennummer der Seite, von der dieses Bild gescannt wurde. |
| TransferFunction | `301` | Beschreibt eine Übertragungsfunktion für das Bild in tabellarischer Form. Pixelkomponenten können gammakompensiert, kompandiert, ungleichmäßig quantisiert oder auf irgendeine andere Weise codiert werden. Die TransferFunction bildet die Pixelkomponenten von einer nicht-linearen BitsPerSample (z. B. 8-Bit)-Form in eine 16-Bit-lineare Form ohne wahrnehmbaren Genauigkeitsverlust ab. |
| Software | `305` | Name und Versionsnummer des Softwarepakets/der Softwarepakete, die zum Erstellen des Images verwendet wurden. |
| DateTime | `306` | Datum und Uhrzeit der Image-Erstellung. |
| Artist | `315` | Person, die das Bild erstellt hat. |
| HostComputer | `316` | Der zum Zeitpunkt der Image-Erstellung verwendete Computer und/oder das verwendete Betriebssystem. |
| Predictor | `317` | Dieser Abschnitt definiert einen Prädiktor, der die Komprimierungsverhältnisse für einige Bilder erheblich verbessert. |
| WhitePoint | `318` | Die Farbart des Weißpunkts des Bildes. |
| PrimaryChromaticities | `319` | Die Chromatizitäten der Primärfarben des Bildes. |
| ColorMap | `320` | Eine Farbkarte für Palettenfarbbilder. |
| HalftoneHints | `321` | Der Zweck des Felds HalftoneHints besteht darin, der Halbtonfunktion den -Bereich von Graustufen innerhalb eines farbmetrisch spezifizierten Bildes zu übermitteln, das tonale Details beibehalten soll. |
| TileWidth | `322` | Die Kachelbreite in Pixel. Dies ist die Anzahl der Spalten in jeder Kachel. |
| TileLength | `323` | Die Kachellänge (Höhe) in Pixel. Dies ist die Anzahl der Zeilen in jeder Kachel. |
| TileOffsets | `324` | Für jede Kachel der Byte-Offset dieser Kachel, komprimiert und auf der Festplatte gespeichert. Der Offset wird in Bezug auf den Anfang der TIFF-Datei angegeben. Beachten Sie, dass dies impliziert, dass jede Kachel einen Ort hat, der unabhängig von den Positionen anderer Kacheln ist. |
| TileByteCounts | `325` | Für jede Kachel die Anzahl der (komprimierten) Bytes in dieser Kachel. |
| InkSet | `332` | Der Tintensatz, der in einem separierten (PhotometricInterpretation=5) Bild verwendet wird. |
| InkNames | `333` | Der Name jeder Tinte, die in einem separierten (PhotometricInterpretation=5) Bild verwendet wird, , geschrieben als eine Liste von verketteten, NUL-terminierten ASCII-Strings. |
| NumberOfInks | `334` | Die Anzahl der Tinten. Normalerweise gleich SamplesPerPixel, es sei denn, es gibt zusätzliche Samples. |
| DotRange | `336` | Die Komponentenwerte, die einem 0 %-Punkt und einem 100 %-Punkt entsprechen. DotRange[0] entspricht einem 0 %-Punkt und DotRange[1] entspricht einem 100 %-Punkt. |
| ExtraSamples | `338` | Beschreibung zusätzlicher Komponenten. |
| SampleFormat | `339` | Dieses Feld gibt an, wie jede Datenprobe in einem Pixel zu interpretieren ist. |
| SMinSampleValue | `340` | Dieses Feld gibt den minimalen Abtastwert an. |
| SMaxSampleValue | `341` | Dieses neue Feld gibt den maximalen Probenwert an. |
| TransferRange | `342` | Erweitert den Bereich der TransferFunction. |
| JpegProc | `512` | Dieses Feld gibt den JPEG-Prozess an, der verwendet wird, um die komprimierten Daten zu erzeugen. |
| JpegInterchangeFormat | `513` | Dieses Feld gibt an, ob ein Bitstrom im JPEG-Austauschformat in der TIFF-Datei vorhanden ist. |
| JpegInterchangeFormatLength | `514` | Dieses Feld gibt die Länge in Bytes des JPEG-Austauschformats bitstream an. |
| JpegRestartInterval | `515` | Dieses Feld gibt die Länge des Neustartintervalls an, das in den komprimierten Bilddaten verwendet wird. |
| JpegLosslessPredictors | `517` | Dieses Feld verweist auf eine Liste von Auswahlwerten für verlustfreie Prädiktoren, einen pro Komponente. |
| JpegPointTransforms | `518` | Dieses Feld zeigt auf eine Liste von Punkttransformationswerten, einen pro Komponente. |
| JpegQTables | `519` | Dieses Feld zeigt auf eine Liste von Offsets zu den Quantisierungstabellen, einen pro Komponente. |
| JpegDCTables | `520` | Dieses Feld zeigt auf eine Liste von Offsets zu den DC-Huffman-Tabellen oder den lossless -Huffman-Tabellen, eine pro Komponente. |
| JpegACTables | `521` | Dieses Feld zeigt auf eine Liste von Offsets zu den Huffman-AC-Tabellen, einen pro Komponente. |
| YCbCrCoefficients | `529` | Die Matrixkoeffizienten für die Transformation von RGB- zu YCbCr-Bilddaten. |
| YCbCrSubSampling | `530` | Das Abtastverhältnis von Chrominanzkomponenten in Bezug auf die Luminanzkomponente. |
| YCbCrPositioning | `531` | Gibt die Positionierung von unterabgetasteten Chrominanzkomponenten relativ zu Luminanzabtastungen an. |
| ReferenceBlackWhite | `532` | Gibt ein Paar von Headroom- und Footroom-Bilddatenwerten (Codes) für jede Pixelkomponente an. |
| Copyright | `33432` | Urheberrechtshinweis. |
| UserComment | `37510` | Schlüsselwörter oder Kommentare zum Bild; ergänzt ImageDescription. |
| Xmp | `700` | Zeiger auf die XMP-Metadaten. |
| ImageID | `32781` | OPI-bezogen. |
| Iptc | `33723` | Metadaten des IPTC (International Press Telecommunications Council). Häufig wird der Datentyp fälschlicherweise als LONG angegeben. |
| Photoshop | `34377` | Sammlung von Photoshop-„Bildressourcenblöcken“. |
| ImageLayer | `34732` | Bildebene. |
| IccProfile | `34675` | Farbprofildaten. |
| ExifIfd | `34665` | Zeiger auf Sammlung aller EXIF-Metadaten. EXIF verwendet Feldnamen anstelle von Tags, um den Feldinhalt anzugeben. |
| GpsIfd | `34853` | Zeiger auf GPS-Daten. |
| Makernotes | `37500` | Zeiger auf Makernotes-Daten. |
| InteroperabilityIfd | `40965` | Exif-bezogene Interoperabilität IFD. |
| CameraOwnerName | `42032` | Name des Kamerabesitzers als ASCII-String. |
| BodySerialNumber | `42033` | Seriennummer des Kameragehäuses als ASCII-String. |
| CfaPattern | `41730` | gibt das geometrische Muster des Farbfilterarrays (CFA) des Bildsensors an, wenn ein Ein-Chip-Farbbereichssensor verwendet wird. Es gilt nicht für alle Erfassungsmethoden. |
| ExifVersion | `36864` | Die Version des unterstützten EXIF-Standards. |
| ComponentsConfiguration | `37121` | Spezifische Informationen zu den komprimierten Daten. Die Kanäle jeder Komponente sind in der Reihenfolge von der 1. bis zur 4. Komponente angeordnet. |
| FlashpixVersion | `40960` | Die Flashpix-Formatversion, die von einer FPXR-Datei unterstützt wird. Wenn die FPXR-Funktion das Flashpix-Format Ver. 1.0 wird dies ähnlich wie bei ExifVersion angezeigt, indem "0100" als 4-Byte-ASCII aufgezeichnet wird. |
| ColorSpace | `40961` | Das Farbrauminformations-Tag (ColorSpace) wird immer als Farbraumbezeichner aufgezeichnet. Normalerweise wird sRGB (=1) verwendet, um den Farbraum basierend auf den Bedingungen und der Umgebung des PC-Monitors zu definieren. Wird ein anderer Farbraum als sRGB verwendet, ist Unkalibriert (=FFFF.H) eingestellt. |
| PixelXDimension | `40962` | Spezifische Informationen zu komprimierten Daten. Wenn eine komprimierte Datei aufgezeichnet wird, muss die gültige Breite des aussagekräftigen Bildes in diesem Tag aufgezeichnet werden, unabhängig davon, ob Fülldaten oder eine Neustartmarkierung vorhanden sind. |
| PixelYDimension | `40963` | Spezifische Informationen zu komprimierten Daten. Wenn eine komprimierte Datei aufgezeichnet wird, muss die gültige Höhe des aussagekräftigen Bildes in diesem Tag aufgezeichnet werden, unabhängig davon, ob Fülldaten oder eine Neustartmarkierung vorhanden sind. |
| SceneCaptureType | `41990` | Dieses Tag zeigt die Art der aufgenommenen Szene an. Es kann auch verwendet werden, um den Modus aufzuzeichnen, in dem das Bild aufgenommen wurde. |
| Gamma | `42240` | Gibt den Wert des Gamma-Koeffizienten an. |
| CompressedBitsPerPixel | `37122` | Spezifische Informationen zu komprimierten Daten. Der für ein komprimiertes Bild verwendete Komprimierungsmodus wird in Bits pro Pixel angegeben. |
| RelatedSoundFile | `40964` | Dieses Tag wird verwendet, um den Namen einer Audiodatei aufzuzeichnen, die sich auf die Bilddaten bezieht. Die einzige hier aufgezeichnete relationale Information ist der Name der Exif-Audiodatei und die Erweiterung (eine ASCII-Zeichenfolge bestehend aus 8 Zeichen + '.' + 3 Zeichen). |
| DateTimeOriginal | `36867` | Datum und Uhrzeit der Generierung der Originalbilddaten. Bei einem DSC werden Datum und Uhrzeit der Aufnahme aufgezeichnet. Das Format ist „JJJJ:MM:TT HH:MM:SS“, wobei die Uhrzeit im 24-Stunden-Format angezeigt wird und Datum und Uhrzeit durch ein Leerzeichen getrennt sind. |
| DateTimeDigitized | `36868` | Das Datum und die Uhrzeit, wann das Bild als digitale Daten gespeichert wurde. Wenn zum Beispiel ein Bild mit DSC aufgenommen wurde und gleichzeitig die Datei aufgenommen wurde, dann haben DateTimeOriginal und DateTimeDigitized den gleichen Inhalt. Das Format ist „JJJJ:MM:TT HH:MM:SS“, wobei die Uhrzeit im 24-Stunden-Format angezeigt wird und Datum und Uhrzeit durch ein Leerzeichen getrennt sind. |
| OffsetTime | `36880` | Ein Tag, das verwendet wird, um den Offset von UTC (der Zeitdifferenz von der koordinierten Weltzeit einschließlich Sommerzeit) der Zeit des DateTime-Tags aufzuzeichnen. Das Format beim Aufzeichnen des Offsets ist „±HH:MM“. Der Teil von „±“ muss als „+“ oder „-“ aufgezeichnet werden. |
| OffsetTimeOriginal | `36881` | Ein Tag, das verwendet wird, um den Offset von UTC (der Zeitdifferenz von der koordinierten Weltzeit einschließlich Sommerzeit) der Zeit des DateTimeOriginal-Tags aufzuzeichnen. Das Format beim Aufzeichnen des Offsets ist „±HH:MM“. Der Teil von „±“ muss als „+“ oder „-“ aufgezeichnet werden. |
| OffsetTimeDigitized | `36882` | Ein Tag, das verwendet wird, um den Offset von UTC (der Zeitdifferenz von der koordinierten Weltzeit einschließlich Sommerzeit) der Zeit des DateTimeDigitized-Tags aufzuzeichnen. Das Format beim Aufzeichnen des Offsets ist „±HH:MM“. Der Teil von „±“ muss als „+“ oder „-“ aufgezeichnet werden. |
| SubsecTime | `37520` | Ein Tag zum Aufzeichnen von Sekundenbruchteilen für das DateTime-Tag. |
| SubsecTimeOriginal | `37521` | Ein Tag zum Aufzeichnen von Bruchteilen von Sekunden für das DateTimeOriginal-Tag. |
| SubsecTimeDigitized | `37522` | Ein Tag zum Aufzeichnen von Bruchteilen von Sekunden für das DateTimeDigitalized-Tag. |
| ExposureTime | `33434` | Belichtungszeit, angegeben in Sekunden (sec). |
| FNumber | `33437` | Die F-Nummer. |
| ExposureProgram | `34850` | Die Klasse des Programms, das von der Kamera verwendet wird, um die Belichtung einzustellen, wenn das Bild aufgenommen wird. |
| SpectralSensitivity | `34852` | Gibt die spektrale Empfindlichkeit jedes Kanals der verwendeten Kamera an. Der Tag-Wert ist eine ASCII-Zeichenfolge, die mit dem vom ASTM Technical Committee entwickelten Standard kompatibel ist. |
| PhotographicSensitivity | `34855` | Dieses Tag gibt die Empfindlichkeit der Kamera oder des Eingabegeräts an, als das Bild aufgenommen wurde. |
| Oecf | `34856` | Gibt die in ISO 14524 spezifizierte Opto-Electric Conversion Function (OECF) an. OECF ist die Beziehung zwischen dem optischen Kameraeingang und den Bildwerten. |
| SensitivityType | `34864` | Das SensitivityType-Tag gibt an, welcher der Parameter von ISO12232 das PhotographicSensitivity-Tag ist. Obwohl es sich um ein optionales Tag handelt, sollte es aufgezeichnet werden, wenn ein PhotographicSensitivity-Tag aufgezeichnet wird. |
| StandardOutputSensitivity | `34865` | Dieses Tag gibt den in ISO 12232 definierten Standardausgabeempfindlichkeitswert einer Kamera oder eines Eingabegeräts an. Beim Aufzeichnen dieses Tags müssen auch die Tags PhotographicSensitivity und SensitivityType aufgezeichnet werden. |
| RecommendedExposureIndex | `34866` | Dieses Tag gibt den empfohlenen Belichtungsindexwert einer Kamera oder eines Eingabegeräts an, der in ISO 12232 definiert ist. Beim Aufzeichnen dieses Tags müssen auch die Tags PhotographicSensitivity und SensitivityType aufgezeichnet werden. |
| IsoSpeed | `34867` | Dieses Tag gibt den ISO-Empfindlichkeitswert einer Kamera oder eines Eingabegeräts an, das in ISO 12232 definiert ist. Beim Aufzeichnen dieses Tags müssen auch die Tags PhotographicSensitivity und SensitivityType aufgezeichnet werden. |
| ISOSpeedLatitudeYyy | `34868` | Dieses Tag gibt den ISO-Geschwindigkeitsbreitenwert yyy einer Kamera oder eines Eingabegeräts an, das in ISO 12232 definiert ist. |
| ISOSpeedLatitudeZzz | `34869` | Dieses Tag gibt den zzz-Wert der ISO-Geschwindigkeitsbreite einer Kamera oder eines Eingabegeräts an, das in ISO 12232 definiert ist. |
| ShutterSpeedValue | `37377` | Verschlusszeit. Die Einheit ist die Einstellung APEX (Additive System of Photographic Exposure). |
| ApertureValue | `37378` | Die Objektivöffnung. Die Einheit ist der APEX-Wert. |
| BrightnessValue | `37379` | Der Helligkeitswert. Die Einheit ist der APEX-Wert. |
| ExposureBiasValue | `37380` | Die Belichtungsabweichung. Die Einheit ist der APEX-Wert. |
| MaxApertureValue | `37381` | Die kleinste Blendenzahl des Objektivs. Die Einheit ist der APEX-Wert. |
| SubjectDistance | `37382` | Die Entfernung zum Motiv, angegeben in Metern. |
| MeteringMode | `37383` | Der Messmodus. |
| LightSource | `37384` | Art der Lichtquelle. |
| Flash | `37385` | Dieses Tag zeigt den Status des Blitzes an, als das Bild aufgenommen wurde. Bit 0 zeigt den Blitzauslösestatus an, Bit 1 und 2 zeigen den Blitzrückgabestatus an, Bit 3 und 4 zeigen den Blitzmodus an, Bit 5 zeigt an, ob die Blitzfunktion vorhanden ist, und Bit 6 zeigt den „Rote-Augen“-Modus an. |
| SubjectArea | `37396` | Dieses Tag gibt die Position und den Bereich des Hauptmotivs in der Gesamtszene an. |
| FocalLength | `37386` | Die tatsächliche Brennweite des Objektivs in mm. Es erfolgt keine Umrechnung auf die Brennweite einer 35-mm-Filmkamera. |
| FlashEnergy | `41483` | Gibt die Blitzenergie zum Zeitpunkt der Bildaufnahme an, gemessen in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Dieses Tag zeichnet die Ortsfrequenztabelle der Kamera oder des Eingabegeräts und SFR-Werte in Richtung der Bildbreite, Bildhöhe und Diagonalrichtung auf, wie in ISO 12233 angegeben. |
| FocalPlaneXResolution | `41486` | Gibt die Anzahl der Pixel in Richtung der Bildbreite (X) pro FocalPlaneResolutionUnit auf der Brennebene der Kamera an. |
| FocalPlaneYResolution | `41487` | Gibt die Anzahl der Pixel in Richtung der Bildhöhe (Y) pro FocalPlaneResolutionUnit auf der Brennebene der Kamera an. |
| FocalPlaneResolutionUnit | `41488` | Gibt die Einheit zum Messen von FocalPlaneXResolution und FocalPlaneYResolution an. Dieser Wert ist derselbe wie die Resolution Unit. |
| SubjectLocation | `41492` | Zeigt die Position des Hauptmotivs in der Szene an. Der Wert dieses Tags repräsentiert das Pixel in der Mitte des Hauptmotivs relativ zum linken Rand vor der Rotationsverarbeitung gemäß dem Rotation-Tag. Der erste Wert gibt die X-Spaltennummer und der zweite die Y-Zeilennummer an. |
| ExposureIndex | `41493` | Gibt den Belichtungsindex an, der zum Zeitpunkt der Aufnahme des Bildes auf der Kamera oder dem Eingabegerät ausgewählt wurde. |
| SensingMethod | `41495` | Gibt den Bildsensortyp der Kamera oder des Eingabegeräts an. |
| FileSource | `41728` | Gibt die Bildquelle an. Wenn ein DSC das Bild aufgezeichnet hat, muss dieser Tag-Wert immer auf 3. gesetzt werden. |
| SceneType | `41729` | Gibt den Szenentyp an. Wenn ein DSC das Bild aufgenommen hat, muss dieser Tag-Wert immer auf 1 gesetzt werden, was anzeigt, dass das Bild direkt fotografiert wurde. |
| CustomRendered | `41985` | Dieses Tag weist auf die Verwendung einer speziellen Verarbeitung von Bilddaten hin, z. B. auf die Ausgabe ausgerichtetes Rendern. |
| ExposureMode | `41986` | Dieses Tag zeigt den bei der Aufnahme des Bildes eingestellten Belichtungsmodus an. Im automatischen Belichtungsreihenmodus nimmt die Kamera eine Reihe von Einzelbildern derselben Szene mit unterschiedlichen Belichtungseinstellungen auf. |
| WhiteBalance | `41987` | Dieses Tag zeigt den Weißabgleichmodus an, der bei der Aufnahme des Bildes eingestellt war. |
| DigitalZoomRatio | `41988` | Dieses Tag gibt das digitale Zoomverhältnis an, als das Bild aufgenommen wurde. Wenn der Zähler des aufgezeichneten Werts 0 ist, bedeutet dies, dass der Digitalzoom nicht verwendet wurde. |
| FocalLengthIn35mmFilm | `41989` | Dieses Tag gibt die äquivalente Brennweite in mm an, wenn man von einer 35-mm-Filmkamera ausgeht. Ein Wert von 0 bedeutet, dass die Brennweite unbekannt ist. Beachten Sie, dass sich dieses Tag vom FocalLength-Tag unterscheidet. |
| GainControl | `41991` | Dieses Tag gibt den Grad der Gesamtanpassung der Bildverstärkung an. |
| Contrast | `41992` | Dieses Tag gibt die Richtung der Kontrastverarbeitung an, die von der Kamera angewendet wurde, als das Bild aufgenommen wurde. |
| Saturation | `41993` | Dieses Tag gibt die Richtung der Sättigungsverarbeitung an, die von der Kamera angewendet wurde, als das Bild aufgenommen wurde. |
| Sharpness | `41994` | Dieses Tag gibt die Richtung der Schärfeverarbeitung an, die von der Kamera angewendet wurde, als das Bild aufgenommen wurde. |
| DeviceSettingDescription | `41995` | Dieses Tag zeigt Informationen zu den Aufnahmebedingungen eines bestimmten Kameramodells an. |
| SubjectDistanceRange | `41996` | Dieses Tag zeigt die Entfernung zum Motiv an. |
| CompositeImage | `42080` | Dieses Tag gibt an, ob das aufgezeichnete Bild ein zusammengesetztes Bild* ist oder nicht. |
| SourceImageNumberOfCompositeImage | `42081` | Dieses Tag gibt die Anzahl der Quellbilder (vorläufig aufgezeichnete Bilder) an, die für ein zusammengesetztes Bild erfasst wurden. |
| SourceExposureTimesOfCompositeImage | `42082` | Für ein zusammengesetztes Bild zeichnet dieses Tag die Parameter auf, die sich auf die Belichtungszeit der Aufnahmen zum Erzeugen des zusammengesetzten Bildes beziehen, wie z. |
| Temperature | `37888` | Temperatur als Umgebungssituation bei der Aufnahme, zum Beispiel die Raumtemperatur, in der der Fotograf die Kamera hielt. Die Einheit ist °C. |
| Humidity | `37889` | Luftfeuchtigkeit als Umgebungssituation bei der Aufnahme, zum Beispiel die Raumfeuchtigkeit, in der der Fotograf die Kamera hielt. Die Einheit ist %. |
| Pressure | `37890` | Druck als Umgebungssituation bei der Aufnahme, beispielsweise die Raumatmosphäre, in der der Fotograf die Kamera hielt oder der Wasserdruck unter dem Meer. Die Einheit ist hPa. |
| WaterDepth | `37891` | Wassertiefe als Umgebungssituation bei der Aufnahme, zB die Wassertiefe der Kamera bei der Unterwasserfotografie. Die Einheit ist m. |
| Acceleration | `37892` | Beschleunigung (ein richtungsunabhängiger Skalar) als Umgebungssituation bei der Aufnahme, zB die Fahrbeschleunigung des Fahrzeugs, auf dem der Fotograf bei der Aufnahme fuhr. Die Einheit ist mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Erhebung/Senkung. Winkel der Ausrichtung der Kamera (bildgebende optische Achse) als Umgebungssituation bei der Aufnahme. Die Einheit ist Grad (°). |
| ImageUniqueID | `42016` | Dieses Tag zeigt eine eindeutig jedem Bild zugewiesene Kennung an. |
| LensSpecification | `42034` | Dieses Tag notiert minimale Brennweite, maximale Brennweite, minimale F-Zahl in der minimalen Brennweite, und minimale F-Zahl in der maximalen Brennweite, die Spezifikationsinformationen für das Objektiv sind, das in der Fotografie verwendet wurde. |
| LensMake | `42035` | Dieses Tag zeichnet den Objektivhersteller als ASCII-String auf. |
| LensModel | `42036` | Dieses Tag zeichnet den Modellnamen und die Modellnummer des Objektivs als ASCII-Zeichenfolge auf. |
| LensSerialNumber | `42037` | Dieses Tag speichert die Seriennummer des Wechselobjektivs, das in der Fotografie verwendet wurde, als ASCII-String. |

### Siehe auch

* namensraum [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
