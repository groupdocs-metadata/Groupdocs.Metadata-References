---
title: ImageResourceID
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Numeri ID standard delle risorse immagine. Non tutti i formati di file utilizzano tutti gli ID. Alcune informazioni possono essere memorizzate in altre sezioni del file.
type: docs
weight: 1750
url: /it/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Numeri ID standard delle risorse immagine. Non tutti i formati di file utilizzano tutti gli ID. Alcune informazioni possono essere memorizzate in altre sezioni del file.

```csharp
public enum ImageResourceID
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ResolutionInfo | `1005` | Struttura ResolutionInfo. Consulta l'Appendice A nel documento PDF Guida API di Photoshop. |
| NamesOfAlphaChannels | `1006` | Nomi dei canali alfa come una serie di stringhe Pascal. |
| Caption | `1008` | La didascalia come stringa Pascal. |
| BorderInformation | `1009` | Informazioni sul confine. Contiene un numero fisso (2 byte reali, 2 byte frazione) per la larghezza del bordo, e 2 byte per le unità del bordo (1 = pollici, 2 = cm, 3 = punti, 4 = pica, 5 = colonne). |
| BackgroundColor | `1010` | Colore di sfondo. [Vedi altro.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Stampa flag. Una serie di valori booleani a un byte (vedere la finestra di dialogo Imposta pagina): etichette, indicatori di ritaglio, barre dei colori, indicatori di registro, negativo, capovolgi, interpola, didascalia, flag di stampa. |
| Grayscale | `1012` | Informazioni sulla scala di grigi e sui mezzitoni multicanale. |
| ColorHalftoning | `1013` | Informazioni sui mezzitoni colore. |
| DuotoneHalftoning | `1014` | Informazioni sui mezzitoni a due tonalità. |
| GrayscaleFunction | `1015` | Scala di grigi e funzione di trasferimento multicanale. |
| ColorTransferFunctions | `1016` | Funzioni di trasferimento del colore. |
| DuotoneTransferFunctions | `1017` | Funzioni di trasferimento a due tonalità. |
| DuotoneImageInformation | `1018` | Informazioni sull'immagine a due tonalità. |
| EPSOptions | `1021` | Opzioni EPS. |
| QuickMaskInformation | `1022` | Informazioni sulla maschera veloce. 2 byte contenenti l'ID del canale maschera veloce; Valore booleano di 1 byte che indica se la maschera era inizialmente vuota. |
| LayerStateInformation | `1024` | Informazioni sullo stato del layer. 2 byte contenenti l'indice del livello di destinazione (0 = livello inferiore). |
| WorkingPath | `1025` | Percorso di lavoro (non salvato). Vedere Vedere Formato risorsa percorso. |
| LayersGroupInformation | `1026` | Informazioni sul gruppo di livelli. 2 byte per layer contenente un ID gruppo per i gruppi di trascinamento. I livelli in un gruppo hanno lo stesso ID gruppo. |
| Iptc | `1028` | Registro IPTC-NAA. Contiene le informazioni File Info.... Consulta la documentazione nella cartella IPTC della cartella Documentazione. |
| ImageModeForRawFormat | `1029` | Modalità immagine per file in formato raw. |
| JpegQuality | `1030` | Qualità JPEG. Privato. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Informazioni su griglia e guide. |
| ThumbnailResourcePhotoshop4 | `1033` | Risorsa miniature solo per Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Indicatore di copyright. Valore booleano che indica se l'immagine è protetta da copyright. Può essere impostato tramite la suite Proprietà o dall'utente in Info file... |
| UrlPhotoshop4 | `1035` | URL. Handle di una stringa di testo con localizzatore di risorse uniforme. Può essere impostato tramite la suite Proprietà o dall'utente in Info file... |
| ThumbnailResourcePhotoshop5 | `1036` | Risorsa miniatura (sostituisce la risorsa 1033). Vedere Vedere Formato risorsa miniatura. |
| GlobalAnglePhotoshop5 | `1037` | Angolo globale. 4 byte che contengono un numero intero compreso tra 0 e 359, ovvero l'angolo di illuminazione globale per il livello degli effetti. Se non presente, si assume che sia 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) Profilo ICC. I byte grezzi di un profilo in formato ICC (International Color Consortium). Vedere ICC1v42_2006-05.pdf nella cartella Documentation e icProfileHeader.h in Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Filigrana. Un byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | Profilo senza tag ICC. 1 byte che disabilita qualsiasi presunta gestione del profilo all'apertura del file. 1 = intenzionalmente senza tag. |
| TransparencyIndexPhotoshop6 | `1047` | Indice di trasparenza. 2 byte per l'indice di colore trasparente, se presente. |
| GlobalAltitudePhotoshop6 | `1049` | Altitudine globale. Immissione di 4 byte per l'altitudine. |
| SlicesPhotoshop6 | `1050` | Fette (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | URL del flusso di lavoro. Stringa Unicode. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Identificatori Alfa. 4 byte di lunghezza, seguiti da 4 byte ciascuno per ogni identificatore alfa. |
| UrlListPhotoshop6 | `1054` | URL InternalList. Conteggio di 4 byte di URL, seguito da 4 byte di lunghezza, ID di 4 byte e stringa Unicode per ciascun conteggio. |
| VersionInfoPhotoshop6 | `1057` | Informazioni sulla versione. Versione a 4 byte, hasRealMergedData a 1 byte, stringa Unicode: nome del writer, stringa Unicode: nome del lettore, versione del file a 4 byte. |
| ExifData1Photoshop7 | `1058` | dati EXIF 1,[Vedi altro](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ Dati EXIF 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | Metadati XMP. Informazioni sul file come descrizione XML,[Vedi altro](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Caption digest. 16 byte: RSA Data Security, algoritmo MD5 message-digest. |
| PrintScalePhotoshop7 | `1062` | Stampa scala. Stile a 2 byte (0 = centrato, 1 = dimensione adatta, 2 = definito dall'utente). 4 byte x posizione (virgola mobile). 4 byte y posizione (virgola mobile). Scala 4 byte (virgola mobile). |
| PixelAspectRatio | `1064` | Proporzioni pixel. 4 byte (versione = 1 o 2), 8 byte doppi, x/y di un pixel. Versione 2, tentativo di correggere i valori per NTSC e PAL, precedentemente disattivati di un fattore di ca. 5%. |
| LayerComps | `1065` | Comp. livelli. 4 byte (versione descrittore = 16), Descriptor. |
| LayerSelectionIds | `1069` | ID selezione layer. Conteggio di 2 byte, per ogni conteggio viene ripetuto quanto segue: ID layer di 4 byte. |
| PrintInfoCS2 | `1071` | Stampa informazioni (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | ID abilitato gruppo(i) layer. 1 byte per ogni livello nel documento, ripetuto per lunghezza della risorsa. NOTA: i gruppi di livelli hanno indicatori di inizio e fine (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Risorsa campionatori di colore. Vedi anche l'ID 1038 per il vecchio formato. |
| MeasurementScaleCS3 | `1074` | Scala di misurazione. 4 byte (versione descrittore = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Informazioni sulla sequenza temporale. 4 byte (versione descrittore = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Foglio Divulgazione. 4 byte (versione descrittore = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Stampa informazioni (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Stile di stampa (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Informazioni specifiche del sistema operativo variabile per Macintosh. NSPrintInfo. Si consiglia di non interpretare o utilizzare questi dati. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Informazioni specifiche del sistema operativo variabile per Windows. DEVMODE. Si consiglia di non interpretare o utilizzare questi dati. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Percorso file salvataggio automatico. Stringa Unicode. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Formato di salvataggio automatico. Stringa Unicode. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Stato selezione percorso. (Photoshop CC). |
| ImageReadyVariables | `7000` | Variabili Image Ready. Rappresentazione XML della definizione delle variabili. |
| ImageReadyDatasets | `7001` | Set di dati Image Ready. |
| PrintFlagsInformation | `10000` | Stampa le informazioni sui flag. versione a 2 byte (= 1), segni di taglio al centro a 1 byte, 1 byte ( = 0), valore della larghezza al vivo a 4 byte, scala della larghezza al vivo a 2 byte. |

### Guarda anche

* spazio dei nomi [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
