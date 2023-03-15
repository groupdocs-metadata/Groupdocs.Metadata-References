---
title: TiffTagID
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Definieert ids van TIFFtags.
type: docs
weight: 2100
url: /nl/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Definieert id's van TIFF-tags.

```csharp
public enum TiffTagID : ushort
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| GpsVersionID | `0` | Geeft de versie aan van GPSInfoIFD. |
| GpsLatitudeRef | `1` | Geeft aan of de breedtegraad noord- of zuiderbreedte is. |
| GpsLatitude | `2` | Geeft de breedtegraad aan. |
| GpsLongitudeRef | `3` | Geeft aan of de lengtegraad oost- of westlengte is. |
| GpsLongitude | `4` | Geeft de lengtegraad aan. |
| GpsAltitudeRef | `5` | Geeft de hoogte aan die als referentiehoogte wordt gebruikt. |
| GpsAltitude | `6` | Geeft de hoogte aan op basis van de referentie in GPSAltitudeRef. |
| GpsTimeStamp | `7` | Geeft de tijd aan als UTC (Coordinated Universal Time). |
| GpsSatellites | `8` | geeft de GPS-satellieten aan die voor metingen worden gebruikt. |
| GpsStatus | `9` | Geeft de status van de GPS-ontvanger aan wanneer het beeld wordt opgenomen. |
| GpsMeasureMode | `10` | Geeft de GPS-meetmodus aan. |
| GpsDop | `11` | Geeft de GPS DOP (gegevensgraad van precisie) aan. |
| GpsSpeedRef | `12` | Geeft de eenheid aan die wordt gebruikt om de bewegingssnelheid van de GPS-ontvanger uit te drukken |
| GpsSpeed | `13` | Geeft de snelheid van de beweging van de GPS-ontvanger aan. |
| GpsTrackRef | `14` | Geeft de referentie aan voor het aangeven van de richting van de beweging van de GPS-ontvanger. |
| GpsTrack | `15` | Geeft de bewegingsrichting van de GPS-ontvanger aan. |
| GpsImgDirectionRef | `16` | Geeft de referentie aan voor het aangeven van de richting van het beeld wanneer het wordt vastgelegd. |
| GpsImgDirection | `17` | Geeft de richting van het beeld aan toen het werd vastgelegd. |
| GpsMapDatum | `18` | Geeft de geodetische onderzoeksgegevens aan die door de GPS-ontvanger worden gebruikt. |
| GpsDestLatitudeRef | `19` | Geeft aan of de breedtegraad van het bestemmingspunt noord- of zuiderbreedte is. |
| GpsDestLatitude | `20` | Geeft de breedtegraad van het bestemmingspunt aan. |
| GpsDestLongitudeRef | `21` | Geeft aan of de lengtegraad van het bestemmingspunt oost- of westlengte is. |
| GpsDestLongitude | `22` | Geeft de lengtegraad van het bestemmingspunt aan. |
| GpsDestBearingRef | `23` | Geeft de referentie aan die wordt gebruikt voor het geven van de peiling naar het bestemmingspunt. |
| GpsDestBearing | `24` | Geeft de peiling naar het bestemmingspunt aan. |
| GpsDestDistanceRef | `25` | Geeft de eenheid aan die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken. |
| GpsDestDistance | `26` | Geeft de afstand tot het bestemmingspunt aan. |
| GpsProcessingMethod | `27` | Een tekenreeks die de naam vastlegt van de methode die wordt gebruikt voor het vinden van een locatie. |
| GpsAreaInformation | `28` | Een tekenreeks die de naam van het GPS-gebied vastlegt. |
| GpsDateStamp | `29` | Een tekenreeks die datum- en tijdinformatie vastlegt ten opzichte van UTC (Coordinated Universal Time). |
| GpsDifferential | `30` | Geeft aan of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| GpsHPositioningError | `31` | Deze tag geeft horizontale positioneringsfouten in meters aan. |
| NewSubfileType | `254` | Een algemene indicatie van het soort gegevens in dit subbestand. |
| SubfileType | `255` | Een algemene indicatie van het soort gegevens in dit subbestand. Dit veld is verouderd. Het veld NewSubfileType moet in plaats daarvan worden gebruikt |
| ImageWidth | `256` | Het aantal kolommen in de afbeelding, dwz het aantal pixels per scanlijn. |
| ImageLength | `257` | Het aantal rijen (soms omschreven als scanlijnen) in de afbeelding. |
| BitsPerSample | `258` | Aantal bits per component. |
| Compression | `259` | Compressieschema gebruikt op de afbeeldingsgegevens. |
| PhotometricInterpretation | `262` | De kleurruimte van de beeldgegevens. |
| Threshholding | `263` | Voor zwart-wit TIFF-bestanden die grijstinten vertegenwoordigen, de techniek die wordt gebruikt om grijze naar zwart-witte pixels te converteren. |
| CellWidth | `264` | De breedte van de dithering- of halftoonmatrix die wordt gebruikt om een geditherd of halftoon bi-level bestand te maken. |
| CellLength | `265` | De lengte van de raster- of halftoonmatrix die wordt gebruikt om een raster- of halftoon bi-level bestand te maken. |
| FillOrder | `266` | De logische volgorde van bits binnen een byte. |
| DocumentName | `269` | De naam van het document waaruit deze afbeelding is gescand. |
| ImageDescription | `270` | Een tekenreeks die het onderwerp van de afbeelding beschrijft. |
| Make | `271` | De scannerfabrikant. |
| Model | `272` | De naam of het nummer van het scannermodel. |
| StripOffsets | `273` | Voor elke strip, de byte-offset van die strip. |
| Orientation | `274` | De oriëntatie van de afbeelding ten opzichte van de rijen en kolommen. |
| SamplesPerPixel | `277` | Het aantal componenten per pixel. |
| RowsPerStrip | `278` | Het aantal rijen per strip. |
| StripByteCounts | `279` | Voor elke strip het aantal bytes in de strip na compressie. |
| MinSampleValue | `280` | De minimaal gebruikte componentwaarde. |
| MaxSampleValue | `281` | De maximaal gebruikte componentwaarde. |
| XResolution | `282` | Het aantal pixels per ResolutionUnit in de richting ImageWidth. |
| YResolution | `283` | Het aantal pixels per ResolutionUnit in de richting ImageLength. |
| PlanarConfiguration | `284` | Hoe de componenten van elke pixel worden opgeslagen. |
| PageName | `285` | De naam van de pagina waarvan deze afbeelding is gescand. |
| XPosition | `286` | X-positie van de afbeelding. |
| YPosition | `287` | Y-positie van de afbeelding. |
| FreeOffsets | `288` | Voor elke reeks aaneengesloten ongebruikte bytes in een TIFF-bestand, de byte-offset van de reeks. |
| FreeByteCounts | `289` | Voor elke reeks aaneengesloten ongebruikte bytes in een TIFF-bestand, het aantal bytes in de reeks. |
| GrayResponseUnit | `290` | De precisie van de informatie in de GrayResponseCurve. |
| GrayResponseCurve | `291` | Voor grijswaardengegevens, de optische densiteit van elke mogelijke pixelwaarde. |
| T4Options | `292` | T4-coderingsopties. |
| T6Options | `293` | T6-coderingsopties. |
| ResolutionUnit | `296` | De meeteenheid voor XResolution en YResolution. |
| PageNumber | `297` | Het paginanummer van de pagina waarvan deze afbeelding is gescand. |
| TransferFunction | `301` | Beschrijft een overdrachtsfunctie voor de afbeelding in tabelvorm. Pixelcomponenten kunnen gamma-gecompenseerd, gecompandeerd, niet-uniform gekwantiseerd of op een andere manier gecodeerd zijn. De TransferFunction brengt de pixelcomponenten in kaart van een niet-lineaire BitsPerSample (bijv. 8-bits) vorm naar een 16-bits lineaire vorm zonder waarneembaar verlies van nauwkeurigheid. |
| Software | `305` | Naam en versienummer van de softwarepakketten die zijn gebruikt om de afbeelding te maken. |
| DateTime | `306` | Datum en tijd waarop de afbeelding is gemaakt. |
| Artist | `315` | Persoon die de afbeelding heeft gemaakt. |
| HostComputer | `316` | De computer en/of het besturingssysteem dat werd gebruikt op het moment dat de afbeelding werd gemaakt. |
| Predictor | `317` | Deze sectie definieert een Predictor die de compressieverhoudingen voor sommige afbeeldingen aanzienlijk verbetert. |
| WhitePoint | `318` | De kleurkwaliteit van het witpunt van de afbeelding. |
| PrimaryChromaticities | `319` | De kleurkwaliteiten van de voorverkiezingen van de afbeelding. |
| ColorMap | `320` | Een kleurenkaart voor kleurenpaletafbeeldingen. |
| HalftoneHints | `321` | Het doel van het veld HalftoneHints is om aan de halftoonfunctie het bereik van grijsniveaus over te brengen binnen een colorimetrisch gespecificeerde afbeelding die toondetails moet behouden. |
| TileWidth | `322` | De tegelbreedte in pixels. Dit is het aantal kolommen in elke tegel. |
| TileLength | `323` | De tegellengte (hoogte) in pixels. Dit is het aantal rijen in elke tegel. |
| TileOffsets | `324` | Voor elke tegel, de byte-offset van die tegel, zoals gecomprimeerd en opgeslagen op schijf. De offset wordt gespecificeerd ten opzichte van het begin van het TIFF-bestand. Merk op dat dit impliceert dat elke tegel een locatie heeft die onafhankelijk is van de locaties van andere tegels. |
| TileByteCounts | `325` | Voor elke tegel, het aantal (gecomprimeerde) bytes in die tegel. |
| InkSet | `332` | De set inkten die wordt gebruikt in een afzonderlijke (PhotometricInterpretation=5) afbeelding. |
| InkNames | `333` | De naam van elke inkt die wordt gebruikt in een gescheiden (PhotometricInterpretation=5) afbeelding, geschreven als een lijst van aaneengeschakelde ASCII-tekenreeksen met NUL-eindtermen. |
| NumberOfInks | `334` | Het aantal inkten. Meestal gelijk aan SamplesPerPixel, tenzij er extra samples zijn. |
| DotRange | `336` | De componentwaarden die overeenkomen met een punt van 0% en een punt van 100%. DotRange[0] komt overeen met een punt van 0% en DotRange[1] komt overeen met een punt van 100%. |
| ExtraSamples | `338` | Beschrijving van extra componenten. |
| SampleFormat | `339` | Dit veld geeft aan hoe elk gegevensmonster in een pixel moet worden geïnterpreteerd. |
| SMinSampleValue | `340` | Dit veld specificeert de minimale steekproefwaarde. |
| SMaxSampleValue | `341` | Dit nieuwe veld specificeert de maximale steekproefwaarde. |
| TransferRange | `342` | Breidt het bereik van de TransferFunction uit. |
| JpegProc | `512` | Dit veld geeft het JPEG-proces aan dat is gebruikt om de gecomprimeerde gegevens te produceren. |
| JpegInterchangeFormat | `513` | Dit veld geeft aan of er een bitstream in JPEG-uitwisselingsformaat aanwezig is in het TIFF-bestand. |
| JpegInterchangeFormatLength | `514` | Dit veld geeft de lengte in bytes aan van het JPEG-uitwisselingsformaat bitstream |
| JpegRestartInterval | `515` | Dit veld geeft de lengte aan van het herstartinterval dat wordt gebruikt in de gecomprimeerde beeldgegevens. |
| JpegLosslessPredictors | `517` | Dit veld verwijst naar een lijst met lossless predictorselectiewaarden, één per component. |
| JpegPointTransforms | `518` | Dit veld verwijst naar een lijst met punttransformatiewaarden, één per component. |
| JpegQTables | `519` | Dit veld verwijst naar een lijst met offsets ten opzichte van de kwantiseringstabellen, één per component. |
| JpegDCTables | `520` | Dit veld verwijst naar een lijst met offsets naar de DC Huffman-tabellen of de lossless Huffman-tabellen, één per component. |
| JpegACTables | `521` | Dit veld verwijst naar een lijst met offsets naar de Huffman AC-tabellen, één per component. |
| YCbCrCoefficients | `529` | De matrixcoëfficiënten voor transformatie van RGB- naar YCbCr-beeldgegevens. |
| YCbCrSubSampling | `530` | De bemonsteringsratio van chrominantiecomponenten in verhouding tot de luminantiecomponent. |
| YCbCrPositioning | `531` | Specificeert de positionering van gesubsamplede chrominantiecomponenten ten opzichte van luminantiemonsters. |
| ReferenceBlackWhite | `532` | Specificeert een paar hoofdruimte- en voetruimte-beeldgegevenswaarden (codes) voor elke pixelcomponent. |
| Copyright | `33432` | Copyrightvermelding. |
| UserComment | `37510` | Trefwoorden of opmerkingen over de afbeelding; vormt een aanvulling op ImageDescription. |
| Xmp | `700` | Pointer naar de XMP-metadata. |
| ImageID | `32781` | OPI-gerelateerd. |
| Iptc | `33723` | IPTC (International Press Telecommunications Council) metadata. Vaak wordt het gegevenstype onjuist gespecificeerd als LONG. |
| Photoshop | `34377` | Verzameling van Photoshop 'Image Resource Blocks'. |
| ImageLayer | `34732` | Afbeeldingslaag. |
| IccProfile | `34675` | Kleurprofielgegevens. |
| ExifIfd | `34665` | Pointer naar verzameling van alle EXIF-metadata. EXIF gebruikt veldnamen in plaats van tags om de veldinhoud aan te geven. |
| GpsIfd | `34853` | Aanwijzer naar GPS-gegevens. |
| Makernotes | `37500` | Pointer naar makernotes-gegevens. |
| InteroperabilityIfd | `40965` | Exif-gerelateerde interoperabiliteit IFD. |
| CameraOwnerName | `42032` | Naam camera-eigenaar als ASCII-tekenreeks. |
| BodySerialNumber | `42033` | Serienummer camerabody als ASCII-tekenreeks. |
| CfaPattern | `41730` | geeft het geometrische patroon van de kleurfilterarray (CFA) van de beeldsensor aan wanneer een één-chip kleurgebiedsensor wordt gebruikt. Het is niet van toepassing op alle detectiemethoden. |
| ExifVersion | `36864` | De ondersteunde versie van de EXIF-standaard. |
| ComponentsConfiguration | `37121` | Informatie die specifiek is voor de gecomprimeerde gegevens. De kanalen van elke component zijn gerangschikt van de 1e component tot de 4e. |
| FlashpixVersion | `40960` | De versie in Flashpix-indeling die wordt ondersteund door een FPXR-bestand. Als de FPXR-functie het Flashpix-formaat Ver. 1.0, wordt dit op dezelfde manier aangegeven als ExifVersion door "0100" op te nemen als 4-byte ASCII. |
| ColorSpace | `40961` | De kleurruimte-informatietag (ColorSpace) wordt altijd vastgelegd als de kleurruimtespecificatie. Normaal gesproken wordt sRGB (=1) gebruikt om de kleurruimte te definiëren op basis van de condities en omgeving van de pc-monitor. Als een andere kleurruimte dan sRGB wordt gebruikt, wordt Uncalibrated (=FFFF.H) ingesteld. |
| PixelXDimension | `40962` | Informatie specifiek voor gecomprimeerde gegevens. Wanneer een gecomprimeerd bestand wordt opgenomen, wordt de geldige breedte van de betekenisvolle afbeelding in deze tag vastgelegd, ongeacht of er opvulgegevens of een herstartmarkering zijn. |
| PixelYDimension | `40963` | Informatie specifiek voor gecomprimeerde gegevens. Wanneer een gecomprimeerd bestand wordt opgenomen, wordt de geldige hoogte van de betekenisvolle afbeelding in deze tag vastgelegd, ongeacht of er opvulgegevens of een herstartmarkering zijn. |
| SceneCaptureType | `41990` | Deze tag geeft het type scène aan dat is opgenomen. Het kan ook worden gebruikt om de modus vast te leggen waarin de foto is gemaakt. |
| Gamma | `42240` | Geeft de waarde van coëfficiënt gamma aan. |
| CompressedBitsPerPixel | `37122` | Informatie specifiek voor gecomprimeerde gegevens. De compressiemodus die voor een gecomprimeerde afbeelding wordt gebruikt, wordt aangegeven in eenheidsbits per pixel. |
| RelatedSoundFile | `40964` | Deze tag wordt gebruikt om de naam van een audiobestand met betrekking tot de afbeeldingsgegevens vast te leggen. De enige relationele informatie die hier wordt vastgelegd, is de naam van het Exif-audiobestand en de extensie (een ASCII-tekenreeks bestaande uit 8 tekens + '.' + 3 tekens). |
| DateTimeOriginal | `36867` | De datum en tijd waarop de oorspronkelijke afbeeldingsgegevens zijn gegenereerd. Bij een DSC worden de datum en tijd van de opname vastgelegd. Het formaat is "JJJJ:MM:DD UU:MM:SS" met de tijd weergegeven in 24-uurs formaat, en de datum en tijd gescheiden door één leeg teken. |
| DateTimeDigitized | `36868` | De datum en tijd waarop de afbeelding is opgeslagen als digitale gegevens. Als er bijvoorbeeld een afbeelding is vastgelegd met DSC en tegelijkertijd het bestand is opgenomen, dan hebben DateTimeOriginal en DateTimeDigitized dezelfde inhoud. Het formaat is "JJJJ:MM:DD UU:MM:SS" met de tijd weergegeven in 24-uurs formaat, en de datum en tijd gescheiden door één leeg teken. |
| OffsetTime | `36880` | Een tag die wordt gebruikt om de afwijking van UTC (het tijdsverschil met Universal Time Coordinated inclusief zomertijd) van de tijd van de DateTime-tag vast te leggen. Het formaat bij het opnemen van de offset is "±UU:MM". Het deel van "±" wordt geregistreerd als "+" of "-". |
| OffsetTimeOriginal | `36881` | Een tag die wordt gebruikt om de offset vanaf UTC (het tijdsverschil met Universal Time Coordinated inclusief zomertijd) van de tijd van de DateTimeOriginal-tag vast te leggen. Het formaat bij het opnemen van de offset is "±UU:MM". Het deel van "±" wordt geregistreerd als "+" of "-". |
| OffsetTimeDigitized | `36882` | Een tag die wordt gebruikt om de afwijking van UTC (het tijdsverschil met Universal Time Coordinated inclusief zomertijd) van de tijd van de DateTimeDigitized-tag vast te leggen. Het formaat bij het opnemen van de offset is "±UU:MM". Het deel van "±" wordt geregistreerd als "+" of "-". |
| SubsecTime | `37520` | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTime-tag. |
| SubsecTimeOriginal | `37521` | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTimeOriginal-tag. |
| SubsecTimeDigitized | `37522` | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTimeDigitized-tag. |
| ExposureTime | `33434` | Belichtingstijd, gegeven in seconden (sec). |
| FNumber | `33437` | Het F-nummer. |
| ExposureProgram | `34850` | De klasse van het programma dat door de camera wordt gebruikt om de belichting in te stellen wanneer de foto wordt gemaakt. |
| SpectralSensitivity | `34852` | Geeft de spectrale gevoeligheid aan van elk kanaal van de gebruikte camera. De tagwaarde is een ASCII-tekenreeks die compatibel is met de standaard ontwikkeld door de ASTM Technische commissie. |
| PhotographicSensitivity | `34855` | Deze tag geeft de gevoeligheid van de camera of het invoerapparaat aan toen de foto werd gemaakt. |
| Oecf | `34856` | Geeft de opto-elektrische conversiefunctie (OECF) aan die is gespecificeerd in ISO 14524. OECF is de relatie tussen de optische invoer van de camera en de beeldwaarden. |
| SensitivityType | `34864` | De SensitivityType-tag geeft aan welke van de parameters van ISO12232 de PhotographicSensitivity-tag is. Hoewel het een optionele tag is, moet deze worden opgenomen wanneer een PhotographicSensitivity-tag wordt opgenomen. |
| StandardOutputSensitivity | `34865` | Deze tag geeft de standaard uitvoergevoeligheidswaarde aan van een camera of invoerapparaat gedefinieerd in ISO 12232. Bij het opnemen van deze tag worden ook de tags PhotographicSensitivity en SensitivityType opgenomen. |
| RecommendedExposureIndex | `34866` | Deze tag geeft de aanbevolen belichtingsindexwaarde aan van een camera of invoerapparaat gedefinieerd in ISO 12232. Bij het opnemen van deze tag worden ook de tags PhotographicSensitivity en SensitivityType opgenomen. |
| IsoSpeed | `34867` | Deze tag geeft de ISO-snelheidswaarde aan van een camera of invoerapparaat die is gedefinieerd in ISO 12232. Bij het opnemen van deze tag worden ook de tags PhotographicSensitivity en SensitivityType opgenomen. |
| ISOSpeedLatitudeYyy | `34868` | Deze tag geeft de ISO-speelruimte yyy-waarde van een camera of invoerapparaat aan die is gedefinieerd in ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | Deze tag geeft de ISO-snelheid latitude zzz-waarde van een camera of invoerapparaat aan die is gedefinieerd in ISO 12232. |
| ShutterSpeedValue | `37377` | Sluitertijd. De eenheid is de APEX-instelling (Additive System of Photographic Exposure). |
| ApertureValue | `37378` | De lensopening. De eenheid is de APEX-waarde. |
| BrightnessValue | `37379` | De waarde van helderheid. De eenheid is de APEX-waarde. |
| ExposureBiasValue | `37380` | De belichtingsbias. De eenheid is de APEX-waarde. |
| MaxApertureValue | `37381` | Het kleinste F-getal van de lens. De eenheid is de APEX-waarde. |
| SubjectDistance | `37382` | De afstand tot het onderwerp, gegeven in meters. |
| MeteringMode | `37383` | De meetmodus. |
| LightSource | `37384` | Het soort lichtbron. |
| Flash | `37385` | Deze tag geeft de status van de flitser aan toen de foto werd gemaakt. Bit 0 geeft de flitsstatus aan, bits 1 en 2 geven de flitsterugkeerstatus aan, bits 3 en 4 geven de flitsmodus aan, bit 5 geeft aan of de flitsfunctie aanwezig is en bit 6 geeft de "rode ogen"-modus aan. |
| SubjectArea | `37396` | Deze tag geeft de locatie en het gebied van het hoofdonderwerp in de algehele scène aan. |
| FocalLength | `37386` | De werkelijke brandpuntsafstand van de lens, in mm. Conversie vindt niet plaats naar de brandpuntsafstand van een 35 mm filmcamera. |
| FlashEnergy | `41483` | Geeft de stroboscoopenergie aan op het moment dat het beeld wordt vastgelegd, zoals gemeten in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Deze tag registreert de ruimtelijke frequentietabel van de camera of het invoerapparaat en SFR-waarden in de richting van beeldbreedte, beeldhoogte en diagonale richting, zoals gespecificeerd in ISO 12233. |
| FocalPlaneXResolution | `41486` | Geeft het aantal pixels aan in de beeldbreedterichting (X) per FocalPlaneResolutionUnit op het brandvlak van de camera. |
| FocalPlaneYResolution | `41487` | Geeft het aantal pixels aan in de richting van de beeldhoogte (Y) per FocalPlaneResolutionUnit op het brandvlak van de camera. |
| FocalPlaneResolutionUnit | `41488` | Geeft de eenheid aan voor het meten van FocalPlaneXResolution en FocalPlaneYResolution. Deze waarde is gelijk aan de ResolutionUnit. |
| SubjectLocation | `41492` | Geeft de locatie van het hoofdonderwerp in de scène aan. De waarde van deze tag vertegenwoordigt de pixel in het midden van het hoofdonderwerp ten opzichte van de linkerrand, voorafgaand aan de rotatieverwerking volgens de Rotation-tag. De eerste waarde geeft het X-kolomnummer aan en de tweede waarde geeft het Y-rijnummer aan. |
| ExposureIndex | `41493` | Geeft de belichtingsindex aan die is geselecteerd op de camera of het invoerapparaat op het moment dat de foto wordt gemaakt. |
| SensingMethod | `41495` | Geeft het type beeldsensor op de camera of het invoerapparaat aan. |
| FileSource | `41728` | Geeft de afbeeldingsbron aan. Als een DSC het beeld heeft opgenomen, moet deze tagwaarde altijd worden ingesteld op 3. |
| SceneType | `41729` | Geeft het type scène aan. Als een DSC het beeld heeft opgenomen, moet deze tagwaarde altijd op 1 worden gezet, wat aangeeft dat het beeld direct is gefotografeerd. |
| CustomRendered | `41985` | Deze tag geeft het gebruik van speciale verwerking van beeldgegevens aan, zoals renderen gericht op uitvoer. |
| ExposureMode | `41986` | Deze tag geeft de belichtingsmodus aan die was ingesteld toen de foto werd gemaakt. In de auto-bracketing-modus maakt de camera een reeks frames van dezelfde scène met verschillende belichtingsinstellingen. |
| WhiteBalance | `41987` | Deze tag geeft de witbalansmodus aan die was ingesteld toen de foto werd gemaakt. |
| DigitalZoomRatio | `41988` | Deze tag geeft de digitale zoomverhouding aan toen de foto werd gemaakt. Als de teller van de geregistreerde waarde 0 is, betekent dit dat er geen digitale zoom is gebruikt. |
| FocalLengthIn35mmFilm | `41989` | Deze tag geeft de equivalente brandpuntsafstand aan, uitgaande van een 35 mm filmcamera, in mm. Een waarde van 0 betekent dat de brandpuntsafstand onbekend is. Merk op dat deze tag verschilt van de FocalLength-tag. |
| GainControl | `41991` | Deze tag geeft de mate van algehele aanpassing van de beeldversterking aan. |
| Contrast | `41992` | Deze tag geeft de richting aan van de contrastverwerking die door de camera werd toegepast toen de foto werd gemaakt. |
| Saturation | `41993` | Deze tag geeft de richting aan van de verzadigingsverwerking die door de camera is toegepast toen de foto werd gemaakt. |
| Sharpness | `41994` | Deze tag geeft de richting aan van de scherpteverwerking die door de camera is toegepast toen de foto werd gemaakt. |
| DeviceSettingDescription | `41995` | Deze tag geeft informatie over de opnameomstandigheden van een bepaald cameramodel. |
| SubjectDistanceRange | `41996` | Deze tag geeft de afstand tot het onderwerp aan. |
| CompositeImage | `42080` | Deze tag geeft aan of het opgenomen beeld een samengesteld beeld* is of niet. |
| SourceImageNumberOfCompositeImage | `42081` | Deze tag geeft het aantal bronbeelden (voorlopig opgenomen beelden) aan dat is vastgelegd voor een samengesteld beeld. |
| SourceExposureTimesOfCompositeImage | `42082` | Voor een samengesteld beeld registreert deze tag de parameters met betrekking tot de belichtingstijd van de belichtingen voor het genereren van het genoemde samengestelde beeld, , zoals respectieve belichtingstijden van vastgelegde bronbeelden (voorlopig opgenomen beelden). |
| Temperature | `37888` | Temperatuur als de omgevingssituatie bij de opname, bijvoorbeeld de kamertemperatuur waar de fotograaf de camera vasthield. De eenheid is °C. |
| Humidity | `37889` | Vochtigheid als de omgevingssituatie bij de opname, bijvoorbeeld de luchtvochtigheid in de kamer waar de fotograaf de camera vasthield. De eenheid is %. |
| Pressure | `37890` | Druk als de omgevingssituatie bij de opname, bijvoorbeeld de kameratmosfeer waar de fotograaf de camera vasthield of de waterdruk onder de zee. De eenheid is hPa. |
| WaterDepth | `37891` | Waterdiepte als de omgevingssituatie bij de opname, bijvoorbeeld de waterdiepte van de camera bij onderwaterfotografie. De eenheid is m. |
| Acceleration | `37892` | Versnelling (een scalair ongeacht de richting) als de omgevingssituatie bij de opname, bijvoorbeeld de rijversnelling van het voertuig waarop de fotograaf tijdens de opname reed. De eenheid is mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Hoogte/depressie. hoek van de oriëntatie van de camera (beeldvormende optische as) als de omgevingssituatie bij de opname. De eenheid is graden(°). |
| ImageUniqueID | `42016` | Deze tag geeft een identificatie aan die uniek is toegewezen aan elke afbeelding. |
| LensSpecification | `42034` | Deze tag vermeldt de minimale brandpuntsafstand, maximale brandpuntsafstand, minimum F-getal in de minimale brandpuntsafstand, en minimum F-getal in de maximale brandpuntsafstand, die specificatie-informatie zijn voor de lens die werd gebruikt in fotografie. |
| LensMake | `42035` | Deze tag registreert de fabrikant van de lens als een ASCII-tekenreeks. |
| LensModel | `42036` | Deze tag registreert de modelnaam en het modelnummer van de lens als een ASCII-tekenreeks. |
| LensSerialNumber | `42037` | Deze tag registreert het serienummer van de verwisselbare lens die in de fotografie werd gebruikt als een ASCII-tekenreeks. |

### Zie ook

* naamruimte [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
