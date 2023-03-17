---
title: TiffTagID
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Definisce gli ID dei tag TIFF.
type: docs
weight: 2100
url: /it/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

Definisce gli ID dei tag TIFF.

```csharp
public enum TiffTagID : ushort
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| GpsVersionID | `0` | Indica la versione di GPSInfoIFD. |
| GpsLatitudeRef | `1` | Indica se la latitudine è nord o sud. |
| GpsLatitude | `2` | Indica la latitudine. |
| GpsLongitudeRef | `3` | Indica se la longitudine è est o ovest. |
| GpsLongitude | `4` | Indica la longitudine. |
| GpsAltitudeRef | `5` | Indica la quota utilizzata come quota di riferimento. |
| GpsAltitude | `6` | Indica l'altitudine in base al riferimento in GPSAltitudeRef. |
| GpsTimeStamp | `7` | Indica l'ora come UTC (Coordinated Universal Time). |
| GpsSatellites | `8` | indica i satelliti GPS utilizzati per le misure. |
| GpsStatus | `9` | Indica lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| GpsMeasureMode | `10` | Indica la modalità di misurazione GPS. |
| GpsDop | `11` | Indica il GPS DOP (grado di precisione dei dati). |
| GpsSpeedRef | `12` | Indica l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS |
| GpsSpeed | `13` | Indica la velocità di movimento del ricevitore GPS. |
| GpsTrackRef | `14` | Indica il riferimento per dare la direzione del movimento del ricevitore GPS. |
| GpsTrack | `15` | Indica la direzione del movimento del ricevitore GPS. |
| GpsImgDirectionRef | `16` | Indica il riferimento per dare la direzione dell'immagine quando viene catturata. |
| GpsImgDirection | `17` | Indica la direzione dell'immagine quando è stata catturata. |
| GpsMapDatum | `18` | Indica i dati del rilievo geodetico utilizzati dal ricevitore GPS. |
| GpsDestLatitudeRef | `19` | Indica se la latitudine del punto di destinazione è nord o sud. |
| GpsDestLatitude | `20` | Indica la latitudine del punto di destinazione. |
| GpsDestLongitudeRef | `21` | Indica se la longitudine del punto di destinazione è est o ovest. |
| GpsDestLongitude | `22` | Indica la longitudine del punto di destinazione. |
| GpsDestBearingRef | `23` | Indica il riferimento utilizzato per dare il rilevamento al punto di destinazione. |
| GpsDestBearing | `24` | Indica il rilevamento verso il punto di destinazione. |
| GpsDestDistanceRef | `25` | Indica l'unità utilizzata per esprimere la distanza dal punto di destinazione. |
| GpsDestDistance | `26` | Indica la distanza dal punto di destinazione. |
| GpsProcessingMethod | `27` | Una stringa di caratteri che registra il nome del metodo utilizzato per la ricerca della posizione. |
| GpsAreaInformation | `28` | Una stringa di caratteri che registra il nome dell'area GPS. |
| GpsDateStamp | `29` | Una stringa di caratteri che registra informazioni su data e ora relative all'UTC (Coordinated Universal Time). |
| GpsDifferential | `30` | Indica se la correzione differenziale è applicata al ricevitore GPS. |
| GpsHPositioningError | `31` | Questo tag indica gli errori di posizionamento orizzontale in metri. |
| NewSubfileType | `254` | Un'indicazione generale del tipo di dati contenuti in questo sub-file. |
| SubfileType | `255` | Un'indicazione generale del tipo di dati contenuti in questo sottofile. Questo campo è deprecato. Dovrebbe essere utilizzato invece il campo NewSubfileType |
| ImageWidth | `256` | Il numero di colonne nell'immagine, ovvero il numero di pixel per linea di scansione. |
| ImageLength | `257` | Il numero di righe (a volte descritte come linee di scansione) nell'immagine. |
| BitsPerSample | `258` | Numero di bit per componente. |
| Compression | `259` | Schema di compressione utilizzato sui dati dell'immagine. |
| PhotometricInterpretation | `262` | Lo spazio colore dei dati dell'immagine. |
| Threshholding | `263` | Per i file TIFF in bianco e nero che rappresentano sfumature di grigio, la tecnica utilizzata per convertire i pixel dal grigio al bianco e nero. |
| CellWidth | `264` | La larghezza della matrice di dithering o mezzitoni utilizzata per creare un file a due livelli con retino o mezzitoni. |
| CellLength | `265` | La lunghezza della matrice di dithering o mezzitoni utilizzata per creare un file a due livelli con retino o mezzitoni. |
| FillOrder | `266` | L'ordine logico dei bit all'interno di un byte. |
| DocumentName | `269` | Il nome del documento da cui è stata acquisita questa immagine. |
| ImageDescription | `270` | Una stringa che descrive il soggetto dell'immagine. |
| Make | `271` | Il produttore dello scanner. |
| Model | `272` | Il nome o il numero del modello dello scanner. |
| StripOffsets | `273` | Per ogni striscia, l'offset di byte di quella striscia. |
| Orientation | `274` | L'orientamento dell'immagine rispetto alle righe e alle colonne. |
| SamplesPerPixel | `277` | Il numero di componenti per pixel. |
| RowsPerStrip | `278` | Il numero di righe per striscia. |
| StripByteCounts | `279` | Per ogni striscia, il numero di byte nella striscia dopo la compressione. |
| MinSampleValue | `280` | Il valore minimo del componente utilizzato. |
| MaxSampleValue | `281` | Il valore massimo del componente utilizzato. |
| XResolution | `282` | Il numero di pixel per ResolutionUnit nella direzione ImageWidth. |
| YResolution | `283` | Il numero di pixel per ResolutionUnit nella direzione ImageLength. |
| PlanarConfiguration | `284` | Come vengono memorizzati i componenti di ciascun pixel. |
| PageName | `285` | Il nome della pagina da cui è stata scansionata l'immagine. |
| XPosition | `286` | Posizione X dell'immagine. |
| YPosition | `287` | Posizione Y dell'immagine. |
| FreeOffsets | `288` | Per ogni stringa di byte contigui inutilizzati in un file TIFF, l'offset di byte della stringa. |
| FreeByteCounts | `289` | Per ogni stringa di byte contigui inutilizzati in un file TIFF, il numero di byte nella stringa. |
| GrayResponseUnit | `290` | La precisione delle informazioni contenute nella GrayResponseCurve. |
| GrayResponseCurve | `291` | Per i dati in scala di grigi, la densità ottica di ogni possibile valore di pixel. |
| T4Options | `292` | Opzioni di codifica T4. |
| T6Options | `293` | Opzioni di codifica T6. |
| ResolutionUnit | `296` | L'unità di misura per XResolution e YResolution. |
| PageNumber | `297` | Il numero di pagina della pagina da cui è stata acquisita l'immagine. |
| TransferFunction | `301` | Descrive una funzione di trasferimento per l'immagine in stile tabulare. I componenti dei pixel possono essere compensati in gamma, compressi, quantizzati in modo non uniforme o codificati in qualche altro modo. TransferFunction mappa i componenti dei pixel da una forma non lineare BitsPerSample (ad es. 8 bit) a una forma lineare a 16 bit senza una perdita percettibile di accuratezza. |
| Software | `305` | Nome e numero di versione dei pacchetti software utilizzati per creare l'immagine. |
| DateTime | `306` | Data e ora di creazione dell'immagine. |
| Artist | `315` | Persona che ha creato l'immagine. |
| HostComputer | `316` | Il computer e/o il sistema operativo in uso al momento della creazione dell'immagine. |
| Predictor | `317` | Questa sezione definisce un predittore che migliora notevolmente i rapporti di compressione per alcune immagini. |
| WhitePoint | `318` | La cromaticità del punto bianco dell'immagine. |
| PrimaryChromaticities | `319` | Le cromaticità dei primari dell'immagine. |
| ColorMap | `320` | Una mappa dei colori per le immagini a colori della tavolozza. |
| HalftoneHints | `321` | Lo scopo del campo HalftoneHints è quello di trasmettere alla funzione mezzitoni l'intervallo dei livelli di grigio all'interno di un'immagine specificata colorimetricamente che dovrebbe mantenere i dettagli tonali. |
| TileWidth | `322` | La larghezza del riquadro in pixel. Questo è il numero di colonne in ogni riquadro. |
| TileLength | `323` | La lunghezza (altezza) del riquadro in pixel. Questo è il numero di righe in ogni riquadro. |
| TileOffsets | `324` | Per ogni tile, l'offset in byte di tale tile, come compresso e archiviato su disco. L'offset è specificato rispetto all'inizio del file TIFF. Nota che ciò implica che ogni tessera ha una posizione indipendente dalle posizioni delle altre tessere. |
| TileByteCounts | `325` | Per ogni tile, il numero di byte (compressi) in quel tile. |
| InkSet | `332` | Il set di inchiostri utilizzato in un'immagine separata (PhotometricInterpretation=5). |
| InkNames | `333` | Il nome di ciascun inchiostro utilizzato in un'immagine separata (PhotometricInterpretation=5), scritto come un elenco di stringhe ASCII concatenate con terminazione NUL. |
| NumberOfInks | `334` | Il numero di inchiostri. Di solito uguale a SamplesPerPixel, a meno che non ci siano campioni extra. |
| DotRange | `336` | I valori dei componenti che corrispondono a un punto 0% e a un punto 100%. DotRange[0] corrisponde a un punto 0% e DotRange[1] corrisponde a un punto 100%. |
| ExtraSamples | `338` | Descrizione dei componenti extra. |
| SampleFormat | `339` | Questo campo specifica come interpretare ciascun campione di dati in un pixel. |
| SMinSampleValue | `340` | Questo campo specifica il valore minimo del campione. |
| SMaxSampleValue | `341` | Questo nuovo campo specifica il valore massimo del campione. |
| TransferRange | `342` | Espande l'intervallo di TransferFunction. |
| JpegProc | `512` | Questo campo indica il processo JPEG utilizzato per produrre i dati compressi. |
| JpegInterchangeFormat | `513` | Questo campo indica se nel file TIFF è presente un bitstream in formato di interscambio JPEG. |
| JpegInterchangeFormatLength | `514` | Questo campo indica la lunghezza in byte del formato di interscambio JPEG bitstream |
| JpegRestartInterval | `515` | Questo campo indica la lunghezza dell'intervallo di riavvio utilizzato nei dati immagine compressi. |
| JpegLosslessPredictors | `517` | Questo campo punta a un elenco di valori di selezione dei predittori senza perdite, uno per componente. |
| JpegPointTransforms | `518` | Questo campo punta a un elenco di valori di trasformazione punto, uno per componente. |
| JpegQTables | `519` | Questo campo punta a un elenco di offset alle tabelle di quantizzazione, uno per componente. |
| JpegDCTables | `520` | Questo campo punta a un elenco di offset alle tabelle DC Huffman o alle tabelle lossless Huffman, una per componente. |
| JpegACTables | `521` | Questo campo punta a un elenco di offset delle tabelle Huffman AC, uno per componente. |
| YCbCrCoefficients | `529` | I coefficienti di matrice per la trasformazione da dati immagine RGB a YCbCr. |
| YCbCrSubSampling | `530` | Il rapporto di campionamento delle componenti di crominanza in relazione alla componente di luminanza. |
| YCbCrPositioning | `531` | Specifica il posizionamento dei componenti di crominanza sottocampionati rispetto ai campioni di luminanza. |
| ReferenceBlackWhite | `532` | Specifica una coppia di valori (codici) dei dati dell'immagine headroom e footroom per ciascun componente pixel. |
| Copyright | `33432` | Avviso sul copyright. |
| UserComment | `37510` | Parole chiave o commenti sull'immagine; integra ImageDescription. |
| Xmp | `700` | Puntatore ai metadati XMP. |
| ImageID | `32781` | Relativo all'OPI. |
| Iptc | `33723` | Metadati IPTC (International Press Telecommunications Council). Spesso, il tipo di dati viene erroneamente specificato come LONG. |
| Photoshop | `34377` | Raccolta di "Image Resource Blocks" di Photoshop. |
| ImageLayer | `34732` | Livello immagine. |
| IccProfile | `34675` | Dati profilo colore. |
| ExifIfd | `34665` | Puntatore alla raccolta di tutti i metadati EXIF. EXIF utilizza nomi di campo anziché tag per indicare il contenuto del campo. |
| GpsIfd | `34853` | Puntatore ai dati GPS. |
| Makernotes | `37500` | Puntatore ai dati delle note del creatore. |
| InteroperabilityIfd | `40965` | Interoperabilità correlata a Exif IFD. |
| CameraOwnerName | `42032` | Nome del proprietario della telecamera come stringa ASCII. |
| BodySerialNumber | `42033` | Numero di serie del corpo della fotocamera come stringa ASCII. |
| CfaPattern | `41730` | indica il motivo geometrico CFA (color filter array) del sensore di immagine quando viene utilizzato un sensore di area colore a un chip. Non si applica a tutti i metodi di rilevamento. |
| ExifVersion | `36864` | La versione dello standard EXIF supportata. |
| ComponentsConfiguration | `37121` | Informazioni specifiche per i dati compressi. I canali di ogni componente sono disposti in ordine dal 1° al 4° componente. |
| FlashpixVersion | `40960` | La versione del formato Flashpix supportata da un file FPXR. Se la funzione FPXR supporta il formato Flashpix ver. 1.0, questo è indicato in modo simile a ExifVersion registrando "0100" come ASCII a 4 byte. |
| ColorSpace | `40961` | Il tag delle informazioni sullo spazio colore (ColorSpace) viene sempre registrato come identificatore dello spazio colore. Normalmente sRGB (=1) viene utilizzato per definire lo spazio colore in base alle condizioni e all'ambiente del monitor del PC. Se viene utilizzato uno spazio colore diverso da sRGB, viene impostato Uncalibrated (=FFFF.H). |
| PixelXDimension | `40962` | Informazioni specifiche per i dati compressi. Quando viene registrato un file compresso, la larghezza valida dell'immagine significativa deve essere registrata in questo tag, indipendentemente dal fatto che siano presenti o meno dati di riempimento o un indicatore di riavvio. |
| PixelYDimension | `40963` | Informazioni specifiche per i dati compressi. Quando viene registrato un file compresso, l'altezza valida dell'immagine significativa deve essere registrata in questo tag, indipendentemente dal fatto che siano presenti o meno dati di riempimento o un indicatore di riavvio. |
| SceneCaptureType | `41990` | Questo tag indica il tipo di scena che è stata girata. Può anche essere utilizzato per registrare la modalità in cui è stata scattata l'immagine. |
| Gamma | `42240` | Indica il valore del coefficiente gamma. |
| CompressedBitsPerPixel | `37122` | Informazioni specifiche per i dati compressi. La modalità di compressione utilizzata per un'immagine compressa è indicata in unità di bit per pixel. |
| RelatedSoundFile | `40964` | Questo tag viene utilizzato per registrare il nome di un file audio correlato ai dati dell'immagine. Le uniche informazioni relazionali registrate qui sono il nome del file audio Exif e l'estensione (una stringa ASCII composta da 8 caratteri + '.' + 3 caratteri). |
| DateTimeOriginal | `36867` | La data e l'ora in cui sono stati generati i dati dell'immagine originale. Per un DSC vengono registrate la data e l'ora in cui è stata scattata la foto. Il formato è "AAAA:MM:GG HH:MM:SS" con l'ora visualizzata nel formato 24 ore e la data e l'ora separate da un carattere vuoto. |
| DateTimeDigitized | `36868` | La data e l'ora in cui l'immagine è stata memorizzata come dati digitali. Se, ad esempio, un'immagine è stata catturata da DSC e contemporaneamente è stato registrato il file, allora DateTimeOriginal e DateTimeDigitized avranno gli stessi contenuti. Il formato è "AAAA:MM:GG HH:MM:SS" con l'ora visualizzata nel formato 24 ore e la data e l'ora separate da un carattere vuoto. |
| OffsetTime | `36880` | Un tag utilizzato per registrare l'offset dall'ora UTC (la differenza di tempo rispetto all'ora universale coordinata, inclusa l'ora legale) dell'ora del tag DateTime. Il formato durante la registrazione dell'offset è "±HH:MM". La parte di "±" deve essere registrata come "+" o "-". |
| OffsetTimeOriginal | `36881` | Un tag utilizzato per registrare l'offset dall'UTC (la differenza di orario dall'ora universale coordinata, inclusa l'ora legale) dell'ora del tag DateTimeOriginal. Il formato durante la registrazione dell'offset è "±HH:MM". La parte di "±" deve essere registrata come "+" o "-". |
| OffsetTimeDigitized | `36882` | Un tag utilizzato per registrare l'offset dall'ora UTC (la differenza di orario rispetto all'ora universale coordinata, inclusa l'ora legale) dell'ora del tag DateTimeDigitized. Il formato durante la registrazione dell'offset è "±HH:MM". La parte di "±" deve essere registrata come "+" o "-". |
| SubsecTime | `37520` | Un tag utilizzato per registrare frazioni di secondo per il tag DateTime. |
| SubsecTimeOriginal | `37521` | Un tag utilizzato per registrare frazioni di secondo per il tag DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Un tag utilizzato per registrare frazioni di secondo per il tag DateTimeDigitized. |
| ExposureTime | `33434` | Tempo di esposizione, espresso in secondi (sec). |
| FNumber | `33437` | Il numero F. |
| ExposureProgram | `34850` | La classe del programma utilizzato dalla fotocamera per impostare l'esposizione quando viene scattata la foto. |
| SpectralSensitivity | `34852` | Indica la sensibilità spettrale di ogni canale della telecamera utilizzata. Il valore del tag è una stringa ASCII compatibile con lo standard sviluppato dal comitato tecnico ASTM. |
| PhotographicSensitivity | `34855` | Questo tag indica la sensibilità della fotocamera o del dispositivo di input quando è stata scattata l'immagine. |
| Oecf | `34856` | Indica la funzione di conversione opto-elettrica (OECF) specificata in ISO 14524. OECF è la relazione tra l'ingresso ottico della telecamera e i valori dell'immagine. |
| SensitivityType | `34864` | Il tag SensitivityType indica quale dei parametri di ISO12232 è il tag PhotographicSensitivity. Sebbene sia un tag facoltativo, dovrebbe essere registrato quando viene registrato un tag PhotographicSensitivity. |
| StandardOutputSensitivity | `34865` | Questo tag indica il valore standard della sensibilità di output di una fotocamera o di un dispositivo di input definito in ISO 12232. Quando si registra questo tag, devono essere registrati anche i tag PhotographicSensitivity e SensitivityType. |
| RecommendedExposureIndex | `34866` | Questo tag indica il valore dell'indice di esposizione consigliato di una fotocamera o di un dispositivo di input definito in ISO 12232. Quando si registra questo tag, devono essere registrati anche i tag PhotographicSensitivity e SensitivityType. |
| IsoSpeed | `34867` | Questo tag indica il valore della velocità ISO di una fotocamera o di un dispositivo di input definito in ISO 12232. Quando si registra questo tag, devono essere registrati anche i tag PhotographicSensitivity e SensitivityType. |
| ISOSpeedLatitudeYyy | `34868` | Questo tag indica il valore yyy della latitudine della velocità ISO di una fotocamera o di un dispositivo di input definito in ISO 12232. |
| ISOSpeedLatitudeZzz | `34869` | Questo tag indica il valore zzz della latitudine della velocità ISO di una fotocamera o di un dispositivo di input definito in ISO 12232. |
| ShutterSpeedValue | `37377` | Velocità dell'otturatore. L'unità è l'impostazione APEX (Additive System of Photographic Exposure). |
| ApertureValue | `37378` | L'apertura dell'obiettivo. L'unità è il valore APEX. |
| BrightnessValue | `37379` | Il valore della luminosità. L'unità è il valore APEX. |
| ExposureBiasValue | `37380` | La distorsione dell'esposizione. L'unità è il valore APEX. |
| MaxApertureValue | `37381` | Il numero F più piccolo dell'obiettivo. L'unità è il valore APEX. |
| SubjectDistance | `37382` | La distanza dal soggetto, espressa in metri. |
| MeteringMode | `37383` | La modalità di misurazione. |
| LightSource | `37384` | Il tipo di sorgente luminosa. |
| Flash | `37385` | Questo tag indica lo stato del flash quando è stata scattata l'immagine. Il bit 0 indica lo stato di attivazione del flash, i bit 1 e 2 indicano lo stato di ritorno del flash, i bit 3 e 4 indicano la modalità del flash, il bit 5 indica se la funzione flash è presente e il bit 6 indica la modalità "occhi rossi". |
| SubjectArea | `37396` | Questo tag indica la posizione e l'area del soggetto principale nella scena complessiva. |
| FocalLength | `37386` | L'effettiva lunghezza focale dell'obiettivo, in mm. La conversione non viene effettuata alla lunghezza focale di una fotocamera con pellicola da 35 mm. |
| FlashEnergy | `41483` | Indica l'energia stroboscopica al momento dell'acquisizione dell'immagine, misurata in secondi di potenza della candela del raggio (BCPS). |
| SpatialFrequencyResponse | `41484` | Questo tag registra la tabella delle frequenze spaziali della fotocamera o del dispositivo di input e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione diagonale, come specificato in ISO 12233. |
| FocalPlaneXResolution | `41486` | Indica il numero di pixel nella direzione della larghezza dell'immagine (X) per FocalPlaneResolutionUnit sul piano focale della telecamera. |
| FocalPlaneYResolution | `41487` | Indica il numero di pixel nella direzione dell'altezza dell'immagine (Y) per FocalPlaneResolutionUnit sul piano focale della telecamera. |
| FocalPlaneResolutionUnit | `41488` | Indica l'unità di misura FocalPlaneXResolution e FocalPlaneYResolution. Questo valore è lo stesso di ResolutionUnit. |
| SubjectLocation | `41492` | Indica la posizione del soggetto principale nella scena. Il valore di questo tag rappresenta il pixel al centro del soggetto principale rispetto al bordo sinistro, prima dell'elaborazione della rotazione secondo il tag Rotazione. Il primo valore indica il numero della colonna X e il secondo indica il numero della riga Y. |
| ExposureIndex | `41493` | Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento dell'acquisizione dell'immagine. |
| SensingMethod | `41495` | Indica il tipo di sensore di immagine sulla fotocamera o sul dispositivo di input. |
| FileSource | `41728` | Indica la sorgente dell'immagine. Se un DSC ha registrato l'immagine, questo valore di tag deve essere sempre impostato su 3. |
| SceneType | `41729` | Indica il tipo di scena. Se un DSC ha registrato l'immagine, questo valore di tag deve essere sempre impostato su 1, a indicare che l'immagine è stata fotografata direttamente. |
| CustomRendered | `41985` | Questo tag indica l'uso di un'elaborazione speciale sui dati dell'immagine, come il rendering orientato all'output. |
| ExposureMode | `41986` | Questo tag indica la modalità di esposizione impostata al momento dello scatto dell'immagine. In modalità bracketing automatico, la fotocamera scatta una serie di fotogrammi della stessa scena con diverse impostazioni di esposizione. |
| WhiteBalance | `41987` | Questo tag indica la modalità di bilanciamento del bianco impostata al momento dello scatto dell'immagine. |
| DigitalZoomRatio | `41988` | Questo tag indica il rapporto di zoom digitale quando l'immagine è stata scattata. Se il numeratore del valore registrato è 0, ciò indica che non è stato utilizzato lo zoom digitale. |
| FocalLengthIn35mmFilm | `41989` | Questo tag indica la lunghezza focale equivalente assumendo una fotocamera con pellicola da 35 mm, in mm. Un valore pari a 0 indica che la lunghezza focale è sconosciuta. Tieni presente che questo tag differisce dal tag FocalLength. |
| GainControl | `41991` | Questo tag indica il grado di regolazione complessiva del guadagno dell'immagine. |
| Contrast | `41992` | Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera quando è stata scattata l'immagine. |
| Saturation | `41993` | Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera quando è stata scattata l'immagine. |
| Sharpness | `41994` | Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera quando è stata scattata l'immagine. |
| DeviceSettingDescription | `41995` | Questo tag indica le informazioni sulle condizioni di scatto delle foto di un particolare modello di fotocamera. |
| SubjectDistanceRange | `41996` | Questo tag indica la distanza dal soggetto. |
| CompositeImage | `42080` | Questo tag indica se l'immagine registrata è un'immagine composita* o meno. |
| SourceImageNumberOfCompositeImage | `42081` | Questo tag indica il numero di immagini sorgente (immagini provvisoriamente registrate) acquisite per un'immagine composita. |
| SourceExposureTimesOfCompositeImage | `42082` | Per un'immagine composita, questo tag registra i parametri relativi al tempo di esposizione delle esposizioni per generare detta immagine composita, come i rispettivi tempi di esposizione delle immagini sorgente catturate (immagini provvisoriamente registrate). |
| Temperature | `37888` | Temperatura come situazione ambientale al momento dello scatto, ad esempio la temperatura della stanza in cui il fotografo teneva la fotocamera. L'unità è °C. |
| Humidity | `37889` | Umidità come situazione ambientale durante lo scatto, ad esempio l'umidità della stanza in cui il fotografo teneva la fotocamera. L'unità è %. |
| Pressure | `37890` | Pressione come situazione ambientale al momento dello scatto, ad esempio l'atmosfera della stanza in cui il fotografo teneva la macchina fotografica o la pressione dell'acqua sotto il mare. L'unità è hPa. |
| WaterDepth | `37891` | Profondità dell'acqua come situazione ambientale allo scatto, ad esempio la profondità dell'acqua della fotocamera durante la fotografia subacquea. L'unità è m. |
| Acceleration | `37892` | Accelerazione (uno scalare indipendentemente dalla direzione) come situazione ambientale al momento dello scatto, ad esempio l'accelerazione di guida del veicolo su cui viaggiava il fotografo al momento dello scatto. L'unità è mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | Elevazione/depressione. angolo dell'orientamento della fotocamera (asse ottico dell'immagine) come situazione ambientale durante lo scatto. L'unità è gradi(°). |
| ImageUniqueID | `42016` | Questo tag indica un identificatore assegnato univocamente a ciascuna immagine. |
| LensSpecification | `42034` | Questo tag indica la lunghezza focale minima, la lunghezza focale massima, il numero F minimo nella lunghezza focale minima, e il numero F minimo nella lunghezza focale massima, che sono informazioni specifiche per l'obiettivo utilizzato nella fotografia. |
| LensMake | `42035` | Questo tag registra il produttore dell'obiettivo come una stringa ASCII. |
| LensModel | `42036` | Questo tag registra il nome e il numero del modello dell'obiettivo come una stringa ASCII. |
| LensSerialNumber | `42037` | Questo tag registra il numero di serie dell'obiettivo intercambiabile utilizzato in fotografia come stringa ASCII. |

### Guarda anche

* spazio dei nomi [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
