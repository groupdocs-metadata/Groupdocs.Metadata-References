---
title: ExifGpsPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati GPS in un pacchetto di metadati EXIF.
type: docs
weight: 2770
url: /it/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Rappresenta i metadati GPS in un pacchetto di metadati EXIF.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Inizializza una nuova istanza di[`ExifGpsPackage`](../exifgpspackage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | Ottiene o imposta l'altitudine in base al riferimento in[`AltitudeRef`](./altituderef) . L'unità di riferimento è metri. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Ottiene o imposta l'altitudine utilizzata come altitudine di riferimento. Se il riferimento è il livello del mare e l'altitudine è al di sopra del livello del mare, viene dato 0. Se l'altitudine è al di sotto del livello del mare, viene dato il valore 1 e l'altitudine è indicata come valore assoluto nel[`Altitude`](./altitude) etichetta. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | Ottiene o imposta la stringa di caratteri che registra il nome dell'area GPS. Il primo byte indica il codice carattere utilizzato, seguito dal nome dell'area GPS. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | Ottiene o imposta il GPS DOP (grado di precisione dei dati). Viene scritto un valore HDOP durante la misurazione bidimensionale e PDOP durante la misurazione tridimensionale. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | Ottiene o imposta le informazioni sulla data e l'ora di registrazione della stringa di caratteri relative all'ora UTC (Coordinated Universal Time). Il formato è AAAA:MM:GG. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Ottiene o imposta il rilevamento GPS rispetto al punto di destinazione. L'intervallo di valori è compreso tra 0,00 e 359,99. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Ottiene o imposta il riferimento GPS utilizzato per fornire il rilevamento al punto di destinazione. 'T' indica la direzione vera e 'M' è la direzione magnetica. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Ottiene o imposta la distanza GPS dal punto di destinazione. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Ottiene o imposta l'unità GPS utilizzata per esprimere la distanza dal punto di destinazione. 'K', 'M' e 'N' rappresentano chilometri, miglia e nodi. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. Il valore ASCII 'N' indica la latitudine nord e 'S' è la latitudine sud. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. ASCII 'E' indica longitudine est e 'W' è longitudine ovest. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Ottiene o imposta la direzione GPS dell'immagine al momento dell'acquisizione. L'intervallo di valori è compreso tra 0,00 e 359,99. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine quando viene acquisita. 'T' indica la direzione reale e 'M' è la direzione magnetica. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Ottiene il tag TIFF con l'id specificato. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | Ottiene o imposta la latitudine GPS. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Ottiene o imposta un valore GPS che indica se la latitudine è nord o sud. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | Ottiene o imposta la longitudine GPS. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Ottiene o imposta un valore GPS che indica se la longitudine è est o ovest. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | Ottiene o imposta i dati del rilievo geodetico utilizzati dal ricevitore GPS. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | Ottiene o imposta la modalità di misurazione GPS. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Ottiene o imposta una stringa di caratteri che registra il nome del metodo utilizzato per la ricerca della posizione. Il primo byte indica il codice del carattere utilizzato, seguito dal nome del metodo. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Ottiene o imposta i satelliti GPS utilizzati per le misurazioni. Questo tag può essere utilizzato per descrivere il numero di satelliti, il loro numero ID, angolo di elevazione, azimut, SNR e altre informazioni in notazione ASCII. Il formato non è specificato. Se il ricevitore GPS non è in grado di effettuare misurazioni, il valore del tag deve essere impostato su NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | Ottiene o imposta la velocità di movimento del ricevitore GPS. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | Ottiene o imposta l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS. 'K' 'M' e 'N' rappresentano chilometri all'ora, miglia all'ora e nodi. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Ottiene o imposta lo stato del ricevitore GPS quando l'immagine viene registrata. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Ottiene o imposta l'ora come UTC (Coordinated Universal Time). TimeStamp è espresso come tre valori RATIONAL che forniscono l'ora, i minuti e i secondi. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS. 'T' indica la direzione vera e 'M' è la direzione magnetica. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | Ottiene o imposta la versione di GPS IFD. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Rimuove tutti i tag TIFF memorizzati nel pacchetto. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Rimuove la proprietà con l'id specificato. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Aggiunge o sostituisce il tag specificato. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Guarda anche

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* spazio dei nomi [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
