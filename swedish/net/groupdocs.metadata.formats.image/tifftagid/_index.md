---
title: TiffTagID
second_title: GroupDocs.Metadata for .NET API-referens
description: Definierar ID för TIFFtaggar.
type: docs
weight: 2100
url: /sv/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Definierar ID för TIFF-taggar.

```csharp
public enum TiffTagID : ushort
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| GpsVersionID | `0` | Indikerar versionen av GPSInfoIFD. |
| GpsLatitudeRef | `1` | Indikerar om latituden är nordlig eller sydlig latitud. |
| GpsLatitude | `2` | Indikerar latitud. |
| GpsLongitudeRef | `3` | Indikerar om longituden är östlig eller västlig longitud. |
| GpsLongitude | `4` | Indikerar longituden. |
| GpsAltitudeRef | `5` | Indikerar höjden som används som referenshöjd. |
| GpsAltitude | `6` | Indikerar höjden baserat på referensen i GPSAltitudeRef. |
| GpsTimeStamp | `7` | Indikerar tiden som UTC (Coordinated Universal Time). |
| GpsSatellites | `8` | indikerar GPS-satelliterna som används för mätningar. |
| GpsStatus | `9` | Indikerar GPS-mottagarens status när bilden spelas in. |
| GpsMeasureMode | `10` | Indikerar GPS-mätningsläget. |
| GpsDop | `11` | Indikerar GPS DOP (datagrad av precision). |
| GpsSpeedRef | `12` | Indikerar enheten som används för att uttrycka GPS-mottagarens rörelsehastighet |
| GpsSpeed | `13` | Indikerar hastigheten för GPS-mottagarens rörelse. |
| GpsTrackRef | `14` | Indikerar referensen för att ge GPS-mottagarens rörelseriktning. |
| GpsTrack | `15` | Indikerar riktningen för GPS-mottagarens rörelse. |
| GpsImgDirectionRef | `16` | Indikerar referensen för att ge bildens riktning när den tas. |
| GpsImgDirection | `17` | Indikerar bildens riktning när den togs. |
| GpsMapDatum | `18` | Indikerar geodetiska mätdata som används av GPS-mottagaren. |
| GpsDestLatitudeRef | `19` | Indikerar om latituden för destinationspunkten är nordlig eller sydlig latitud. |
| GpsDestLatitude | `20` | Indikerar latitud för destinationspunkten. |
| GpsDestLongitudeRef | `21` | Indikerar om longituden för destinationspunkten är östlig eller västlig longitud. |
| GpsDestLongitude | `22` | Indikerar longituden för destinationspunkten. |
| GpsDestBearingRef | `23` | Indikerar referensen som används för att ge bäringen till destinationspunkten. |
| GpsDestBearing | `24` | Indikerar bäringen till destinationspunkten. |
| GpsDestDistanceRef | `25` | Indikerar enheten som används för att uttrycka avståndet till destinationspunkten. |
| GpsDestDistance | `26` | Indikerar avståndet till destinationspunkten. |
| GpsProcessingMethod | `27` | En teckensträng som registrerar namnet på metoden som används för att hitta plats. |
| GpsAreaInformation | `28` | En teckensträng som registrerar namnet på GPS-området. |
| GpsDateStamp | `29` | En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| GpsDifferential | `30` | Indikerar om differentiell korrigering tillämpas på GPS-mottagaren. |
| GpsHPositioningError | `31` | Denna tagg indikerar horisontella positioneringsfel i meter. |
| NewSubfileType | `254` | En allmän indikation på vilken typ av data som finns i denna underfil. |
| SubfileType | `255` | En allmän indikation på vilken typ av data som finns i den här underfilen. Det här fältet är föråldrat. Fältet NewSubfileType ska användas istället |
| ImageWidth | `256` | Antalet kolumner i bilden, dvs antalet pixlar per skanningslinje. |
| ImageLength | `257` | Antalet rader (ibland beskrivet som skanningslinjer) i bilden. |
| BitsPerSample | `258` | Antal bitar per komponent. |
| Compression | `259` | Kompressionsschema som används på bilddata. |
| PhotometricInterpretation | `262` | Bilddatans färgrymd. |
| Threshholding | `263` | För svartvita TIFF-filer som representerar nyanser av grått, den teknik som används för att konvertera från grå till svarta och vita pixlar. |
| CellWidth | `264` | Bredden på raster- eller halvtonsmatrisen som används för att skapa en rasterad eller halvtonsfil med två nivåer. |
| CellLength | `265` | Längden på raster- eller halvtonsmatrisen som används för att skapa en rasterad eller halvtonsfil med två nivåer. |
| FillOrder | `266` | Den logiska ordningen för bitar inom en byte. |
| DocumentName | `269` | Namnet på dokumentet som denna bild skannades från. |
| ImageDescription | `270` | En sträng som beskriver motivet för bilden. |
| Make | `271` | Skannertillverkaren. |
| Model | `272` | Skannerns modellnamn eller nummer. |
| StripOffsets | `273` | För varje remsa, byteoffset för den remsan. |
| Orientation | `274` | Bildens orientering i förhållande till raderna och kolumnerna. |
| SamplesPerPixel | `277` | Antalet komponenter per pixel. |
| RowsPerStrip | `278` | Antal rader per remsa. |
| StripByteCounts | `279` | För varje remsa, antalet byte i remsan efter komprimering. |
| MinSampleValue | `280` | Minsta komponentvärde som används. |
| MaxSampleValue | `281` | Det maximala komponentvärdet som används. |
| XResolution | `282` | Antalet pixlar per ResolutionUnit i ImageWidth-riktningen. |
| YResolution | `283` | Antalet pixlar per ResolutionUnit i ImageLength-riktningen. |
| PlanarConfiguration | `284` | Hur komponenterna i varje pixel lagras. |
| PageName | `285` | Namnet på sidan från vilken bilden skannades. |
| XPosition | `286` | X position för bilden. |
| YPosition | `287` | Y-position för bilden. |
| FreeOffsets | `288` | För varje sträng av sammanhängande oanvända byte i en TIFF-fil, byteoffset för strängen. |
| FreeByteCounts | `289` | För varje sträng med sammanhängande oanvända byte i en TIFF-fil, antalet byte i strängen. |
| GrayResponseUnit | `290` | Precisionen för informationen i GrayResponseCurve. |
| GrayResponseCurve | `291` | För gråskaledata, den optiska densiteten för varje möjligt pixelvärde. |
| T4Options | `292` | T4-kodningsalternativ. |
| T6Options | `293` | T6-kodningsalternativ. |
| ResolutionUnit | `296` | Måttenheten för XResolution och YResolution. |
| PageNumber | `297` | Sidnumret på sidan från vilken bilden skannades. |
| TransferFunction | `301` | Beskriver en överföringsfunktion för bilden i tabellform. Pixelkomponenter kan vara gamma-kompenserade, kompanderade, icke-enhetligt kvantiserade eller kodade på något annat sätt. TransferFunction mappar pixelkomponenterna från en icke-linjär BitsPerSample (t.ex. 8-bitars) form till en 16-bitars linjär form utan en märkbar förlust av noggrannhet. |
| Software | `305` | Namn och versionsnummer för mjukvarupaketen som användes för att skapa bilden. |
| DateTime | `306` | Datum och tid för bildskapande. |
| Artist | `315` | Person som skapade bilden. |
| HostComputer | `316` | Datorn och/eller operativsystemet som används när bilden skapades. |
| Predictor | `317` | Det här avsnittet definierar en prediktor som avsevärt förbättrar komprimeringsförhållandena för vissa bilder. |
| WhitePoint | `318` | Kromaticiteten hos bildens vita punkt. |
| PrimaryChromaticities | `319` | Färgerna hos bildens primära färger. |
| ColorMap | `320` | En färgkarta för palettfärgbilder. |
| HalftoneHints | `321` | Syftet med fältet HalftoneHints är att förmedla till halvtonsfunktionen intervallet av grånivåer inom en kolorimetriskt specificerad bild som ska behålla tonal detalj. |
| TileWidth | `322` | Brickbredden i pixlar. Detta är antalet kolumner i varje bricka. |
| TileLength | `323` | Bricklängden (höjden) i pixlar. Detta är antalet rader i varje bricka. |
| TileOffsets | `324` | För varje bricka, byteoffset för den bricka, som komprimerad och lagrad på disk. Förskjutningen anges med avseende på början av TIFF-filen. Observera att detta innebär att varje bricka har en plats oberoende av placeringen av andra plattor. |
| TileByteCounts | `325` | För varje bricka, antalet (komprimerade) byte i den plattan. |
| InkSet | `332` | Uppsättningen bläck som används i en separerad (PhotometricInterpretation=5) bild. |
| InkNames | `333` | Namnet på varje bläck som används i en separerad (PhotometricInterpretation=5) bild, skriven som en lista över sammanlänkade, NUL-terminerade ASCII-strängar. |
| NumberOfInks | `334` | Antalet bläck. Vanligtvis lika med SamplesPerPixel, såvida det inte finns extra sampel. |
| DotRange | `336` | De komponentvärden som motsvarar en 0 % punkt och 100 % punkt. DotRange[0] motsvarar en 0 % prick och DotRange[1] motsvarar en 100 % dot. |
| ExtraSamples | `338` | Beskrivning av extra komponenter. |
| SampleFormat | `339` | Det här fältet anger hur man tolkar varje dataexempel i en pixel. |
| SMinSampleValue | `340` | Det här fältet anger det lägsta provvärdet. |
| SMaxSampleValue | `341` | Det här nya fältet anger det maximala provvärdet. |
| TransferRange | `342` | Utökar räckvidden för TransferFunction. |
| JpegProc | `512` | Detta fält indikerar JPEG-processen som används för att producera komprimerad data. |
| JpegInterchangeFormat | `513` | Det här fältet anger om en bitström av JPEG-utbytesformat finns i TIFF-filen. |
| JpegInterchangeFormatLength | `514` | Det här fältet anger längden i byte för JPEG-utbytesformatet bitstream |
| JpegRestartInterval | `515` | Det här fältet anger längden på omstartsintervallet som används i de komprimerade bilddata. |
| JpegLosslessPredictors | `517` | Det här fältet pekar på en lista med förlustfria prediktor-valvärden, ett per komponent. |
| JpegPointTransforms | `518` | Detta fält pekar på en lista med punkttransformeringsvärden, ett per komponent. |
| JpegQTables | `519` | Detta fält pekar på en lista med offset till kvantiseringstabellerna, en per komponent. |
| JpegDCTables | `520` | Det här fältet pekar på en lista med offset till DC Huffman-tabellerna eller lossless Huffman-tabellerna, en per komponent. |
| JpegACTables | `521` | Detta fält pekar på en lista med offset till Huffman AC-tabellerna, en per komponent. |
| YCbCrCoefficients | `529` | Matriskofficienterna för transformation från RGB till YCbCr bilddata. |
| YCbCrSubSampling | `530` | Samplingsförhållandet för krominanskomponenter i förhållande till luminanskomponenten. |
| YCbCrPositioning | `531` | Anger placeringen av delsamplade krominanskomponenter i förhållande till luminanssampel. |
| ReferenceBlackWhite | `532` | Anger ett par bilddatavärden (koder) för takhöjd och fotutrymme för varje pixelkomponent. |
| Copyright | `33432` | Upphovsrättsmeddelande. |
| UserComment | `37510` | Nyckelord eller kommentarer på bilden; kompletterar ImageDescription. |
| Xmp | `700` | Pekare till XMP-metadata. |
| ImageID | `32781` | OPI-relaterad. |
| Iptc | `33723` | IPTC (International Press Telecommunications Council) metadata. Ofta är datatypen felaktigt angiven som LONG. |
| Photoshop | `34377` | Samling av Photoshop 'Bildresursblock'. |
| ImageLayer | `34732` | Bildlager. |
| IccProfile | `34675` | Färgprofildata. |
| ExifIfd | `34665` | Pekare till insamling av all EXIF-metadata. EXIF använder fältnamn snarare än taggar för att indikera fältinnehållet. |
| GpsIfd | `34853` | Pekare till GPS-data. |
| Makernotes | `37500` | Pekare till makernotes-data. |
| InteroperabilityIfd | `40965` | Exif-relaterad interoperabilitet IFD. |
| CameraOwnerName | `42032` | Kameraägarens namn som ASCII-sträng. |
| BodySerialNumber | `42033` | Kamerahusets serienummer som ASCII-sträng. |
| CfaPattern | `41730` | indikerar det geometriska mönstret för färgfiltermatrisen (CFA) för bildsensorn när en färgområdessensor med ett chip används. Det gäller inte alla avkänningsmetoder. |
| ExifVersion | `36864` | Den version av EXIF-standarden som stöds. |
| ComponentsConfiguration | `37121` | Information som är specifik för den komprimerade datan. Kanalerna för varje komponent är ordnade i ordning från den 1:a komponenten till den 4:e. |
| FlashpixVersion | `40960` | Flashpix-formatversionen som stöds av en FPXR-fil. Om FPXR-funktionen stöder Flashpix-format Ver. 1.0, indikeras detta på samma sätt som ExifVersion genom att spela in "0100" som 4-byte ASCII. |
| ColorSpace | `40961` | Färgrymdsinformationstaggen (ColorSpace) registreras alltid som färgrymdsspecifikator. Normalt används sRGB (=1) för att definiera färgrymden baserat på PC-skärmens förhållanden och miljö. Om en annan färgrymd än sRGB används, ställs Okalibrerad (=FFFF.H) in. |
| PixelXDimension | `40962` | Information som är specifik för komprimerad data. När en komprimerad fil spelas in, ska den giltiga bredden på den meningsfulla bilden registreras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör. |
| PixelYDimension | `40963` | Information som är specifik för komprimerad data. När en komprimerad fil spelas in, ska den giltiga höjden på den meningsfulla bilden registreras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör. |
| SceneCaptureType | `41990` | Den här taggen anger vilken typ av scen som spelades in. Den kan också användas för att spela in i vilket läge bilden togs. |
| Gamma | `42240` | Indikerar värdet av koefficient gamma. |
| CompressedBitsPerPixel | `37122` | Information som är specifik för komprimerad data. Komprimeringsläget som används för en komprimerad bild indikeras i bitar per pixel. |
| RelatedSoundFile | `40964` | Denna tagg används för att spela in namnet på en ljudfil relaterad till bilddata. Den enda relationsinformation som registreras här är Exif-ljudfilens namn och tillägg (en ASCII-sträng bestående av 8 tecken + '.' + 3 tecken). |
| DateTimeOriginal | `36867` | Datum och tid då den ursprungliga bilddatan genererades. För en DSC registreras datum och tid då bilden togs. Formatet är "ÅÅÅÅ:MM:DD TT:MM:SS" med tiden i 24-timmarsformat och datum och tid separerade med ett tomt tecken. |
| DateTimeDigitized | `36868` | Datum och tid då bilden lagrades som digital data. Om till exempel en bild togs med DSC och samtidigt filen spelades in, kommer DateTimeOriginal och DateTimeDigitized att ha samma innehåll. Formatet är "ÅÅÅÅ:MM:DD TT:MM:SS" med tiden i 24-timmarsformat och datum och tid separerade med ett tomt tecken. |
| OffsetTime | `36880` | En tagg som används för att registrera offset från UTC (tidsskillnaden från Universal Time Coordinated inklusive sommartid) för tiden för DateTime-taggen. Formatet vid inspelning av offset är "±HH:MM". Delen av "±" ska registreras som "+" eller "-". |
| OffsetTimeOriginal | `36881` | En tagg som används för att registrera offset från UTC (tidsskillnaden från Universal Time Coordinated inklusive sommartid) för tiden för DateTimeOriginal tag. Formatet vid registrering av offset är "±HH:MM". Delen av "±" ska registreras som "+" eller "-". |
| OffsetTimeDigitized | `36882` | En tagg som används för att registrera offset från UTC (tidsskillnaden från Universal Time Coordinated inklusive sommartid) för tiden för DateTimeDigitized-taggen. Formatet vid inspelning av offset är "±HH:MM". Delen av "±" ska registreras som "+" eller "-". |
| SubsecTime | `37520` | En tagg som används för att registrera bråkdelar av sekunder för DateTime-taggen. |
| SubsecTimeOriginal | `37521` | En tagg som används för att registrera bråkdelar av sekunder för DateTimeOriginal-taggen. |
| SubsecTimeDigitized | `37522` | En tagg som används för att registrera bråkdelar av sekunder för DateTime Digitalized-taggen. |
| ExposureTime | `33434` | Exponeringstid, angiven i sekunder (sek). |
| FNumber | `33437` | F-numret. |
| ExposureProgram | `34850` | Klassen för programmet som används av kameran för att ställa in exponeringen när bilden tas. |
| SpectralSensitivity | `34852` | Indikerar den spektrala känsligheten för varje kanal i kameran som används. Taggvärdet är en ASCII-sträng som är kompatibel med standarden som utvecklats av ASTM Technical Committee. |
| PhotographicSensitivity | `34855` | Den här taggen indikerar känsligheten hos kameran eller inmatningsenheten när bilden togs. |
| Oecf | `34856` | Indikerar den optoelektriska konverteringsfunktionen (OECF) specificerad i ISO 14524. OECF är förhållandet mellan kamerans optiska ingång och bildvärdena. |
| SensitivityType | `34864` | SensitivityType-taggen anger vilken av parametrarna i ISO12232 som är PhotographicSensitivity-taggen. Även om det är en valfri tagg, bör den spelas in när en PhotographicSensitivity-tagg spelas in. |
| StandardOutputSensitivity | `34865` | Denna tagg indikerar standardvärdet för utmatningskänslighet för en kamera eller inmatningsenhet som definieras i ISO 12232. Vid inspelning av denna tagg ska taggarna PhotographicSensitivity och SensitivityType också registreras. |
| RecommendedExposureIndex | `34866` | Denna tagg indikerar det rekommenderade exponeringsindexvärdet för en kamera eller inmatningsenhet som definieras i ISO 12232. När denna tagg spelas in ska taggarna PhotographicSensitivity och SensitivityType också registreras. |
| IsoSpeed | `34867` | Denna tagg indikerar ISO-hastighetsvärdet för en kamera eller inmatningsenhet som är definierad i ISO 12232. När denna tagg spelas in ska taggarna PhotographicSensitivity och SensitivityType också registreras. |
| ISOSpeedLatitudeYyy | `34868` | Den här taggen indikerar ISO-hastigheten latitud yyy-värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | Den här taggen indikerar ISO-hastighetens latitud zzz-värde för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| ShutterSpeedValue | `37377` | Slutartid. Enheten har inställningen APEX (Additive System of Photographic Exposure). |
| ApertureValue | `37378` | Linsens bländare. Enheten är APEX-värdet. |
| BrightnessValue | `37379` | Värdet för ljusstyrka. Enheten är APEX-värdet. |
| ExposureBiasValue | `37380` | Exponeringsbias. Enheten är APEX-värdet. |
| MaxApertureValue | `37381` | Objektivets minsta F-nummer. Enheten är APEX-värdet. |
| SubjectDistance | `37382` | Avståndet till motivet, angivet i meter. |
| MeteringMode | `37383` | Mätläget. |
| LightSource | `37384` | Typ av ljuskälla. |
| Flash | `37385` | Den här taggen indikerar blixtens status när bilden togs. Bit 0 indikerar blixtavfyrningsstatus, bit 1 och 2 indikerar blixtreturstatus, bitar 3 och 4 indikerar blixtläge, bit 5 indikerar om blixtfunktionen är närvarande och bit 6 indikerar "röda ögon"-läge. |
| SubjectArea | `37396` | Den här taggen anger platsen och området för huvudmotivet i den övergripande scenen. |
| FocalLength | `37386` | Objektivets faktiska brännvidd, i mm. Konvertering görs inte till brännvidden för en 35 mm filmkamera. |
| FlashEnergy | `41483` | Indikerar strobeenergin vid den tidpunkt då bilden tas, mätt i Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Denna tagg registrerar kameran eller inmatningsenhetens rumsliga frekvenstabell och SFR-värden i riktningen för bildens bredd, bildhöjd och diagonal riktning, enligt ISO 12233. |
| FocalPlaneXResolution | `41486` | Indikerar antalet pixlar i bildens bredd (X) riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FocalPlaneYResolution | `41487` | Indikerar antalet pixlar i bildhöjdsriktningen (Y) per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FocalPlaneResolutionUnit | `41488` | Indikerar enheten för att mäta FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit. |
| SubjectLocation | `41492` | Indikerar platsen för huvudmotivet i scenen. Värdet på denna tagg representerar pixeln i mitten av huvudmotivet i förhållande till den vänstra kanten, före rotationsbearbetning enligt rotationstaggen. Det första värdet anger X-kolumnnumret och det andra anger Y-radnumret. |
| ExposureIndex | `41493` | Indikerar exponeringsindexet som valts på kameran eller inmatningsenheten vid den tidpunkt då bilden togs. |
| SensingMethod | `41495` | Indikerar bildsensortypen på kameran eller inmatningsenheten. |
| FileSource | `41728` | Indikerar bildkällan. Om en DSC spelade in bilden ska detta taggvärde alltid sättas till 3. |
| SceneType | `41729` | Indikerar typen av scen. Om en DSC spelade in bilden ska detta taggvärde alltid sättas till 1, vilket indikerar att bilden är direkt fotograferad. |
| CustomRendered | `41985` | Den här taggen indikerar användningen av speciell bearbetning av bilddata, såsom rendering anpassad till utdata. |
| ExposureMode | `41986` | Denna tagg indikerar exponeringsläget som ställdes in när bilden togs. I läget för automatisk variation, tar kameran en serie bilder av samma scen med olika exponeringsinställningar. |
| WhiteBalance | `41987` | Den här taggen anger vilket vitbalansläge som ställdes in när bilden togs. |
| DigitalZoomRatio | `41988` | Den här taggen anger det digitala zoomförhållandet när bilden togs. Om täljaren för det registrerade värdet är 0, indikerar detta att digital zoom inte användes. |
| FocalLengthIn35mmFilm | `41989` | Den här taggen indikerar motsvarande brännvidd om man antar en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength-taggen. |
| GainControl | `41991` | Denna tagg indikerar graden av total bildförstärkningsjustering. |
| Contrast | `41992` | Den här taggen indikerar riktningen för kontrastbehandling som användes av kameran när bilden togs. |
| Saturation | `41993` | Den här taggen indikerar riktningen för mättnadsbearbetning som användes av kameran när bilden togs. |
| Sharpness | `41994` | Den här taggen indikerar riktningen för skärpans bearbetning som användes av kameran när bilden togs. |
| DeviceSettingDescription | `41995` | Den här taggen indikerar information om fotograferingsförhållandena för en viss kameramodell. |
| SubjectDistanceRange | `41996` | Den här taggen anger avståndet till motivet. |
| CompositeImage | `42080` | Den här taggen anger om den inspelade bilden är en sammansatt bild* eller inte. |
| SourceImageNumberOfCompositeImage | `42081` | Den här taggen anger antalet källbilder (preliminärt inspelade bilder) som tagits för en sammansatt bild. |
| SourceExposureTimesOfCompositeImage | `42082` | För en sammansatt bild registrerar denna tagg parametrarna som relaterar exponeringstiden för exponeringarna för att generera nämnda sammansatta bild, såsom respektive exponeringstider för tagna källbilder (preliminärt inspelade bilder). |
| Temperature | `37888` | Temperatur som den omgivande situationen vid tagningen, till exempel rumstemperaturen där fotografen höll kameran. Enheten är °C. |
| Humidity | `37889` | Fuktighet som den omgivande situationen vid tagningen, till exempel luftfuktigheten i rummet där fotografen höll i kameran. Enheten är %. |
| Pressure | `37890` | Tryck som den omgivande situationen vid bilden, till exempel rumsatmosfären där fotografen höll kameran eller vattentrycket under havet. Enheten är hPa. |
| WaterDepth | `37891` | Vattendjup som den omgivande situationen vid bilden, till exempel kamerans vattendjup vid undervattensfotografering. Enheten är m. |
| Acceleration | `37892` | Acceleration (en skalär oavsett riktning) som den omgivande situationen vid tagningen, till exempel köraccelerationen för fordonet som fotografen åkte på vid tagningen. Enheten är mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Höjd/depression. vinkeln på kamerans orientering (optisk bildaxel) som den omgivande situationen vid bilden. Enheten är grader(°). |
| ImageUniqueID | `42016` | Denna tagg indikerar en identifierare som är unikt tilldelad varje bild. |
| LensSpecification | `42034` | Den här taggen noterar minsta brännvidd, maximal brännvidd, minsta F-nummer i minsta brännvidd, och minsta F-nummer i maximal brännvidd, som är specifikationsinformation för objektivet som användes vid fotografering. |
| LensMake | `42035` | Den här taggen registrerar linstillverkaren som en ASCII-sträng. |
| LensModel | `42036` | Den här taggen registrerar objektivets modellnamn och modellnummer som en ASCII-sträng. |
| LensSerialNumber | `42037` | Denna tagg registrerar serienumret på det utbytbara objektivet som användes vid fotografering som en ASCII-sträng. |

### Se även

* namnutrymme [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
