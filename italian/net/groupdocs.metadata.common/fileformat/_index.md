---
title: FileFormat
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta il formato riconosciuto di un file caricato.
type: docs
weight: 40
url: /it/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

Rappresenta il formato riconosciuto di un file caricato.

```csharp
public enum FileFormat
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Unknown | `0` | Il tipo di file non è riconosciuto. |
| Presentation | `1` | Un file di presentazione. È necessario avere familiarità con i file di estensione PPTX e PPT mentre si lavora con Microsoft PowerPoint. Si tratta di formati di file di presentazione che memorizzano raccolte di record per accogliere dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/) . |
| Spreadsheet | `2` | Un file di foglio di calcolo. Un file di foglio di calcolo contiene dati sotto forma di righe e colonne. È possibile aprire, visualizzare e modificare tali file utilizzando applicazioni software per fogli di calcolo come Microsoft Excel, ora disponibile sia per il sistema operativo Windows che per MacOS. Allo stesso modo, Fogli Google è uno strumento online gratuito per la creazione e la modifica di fogli di lavoro che funziona da qualsiasi browser web. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/spreadsheet/) . |
| WordProcessing | `3` | Un file di elaborazione testi. Un file di elaborazione testi contiene informazioni utente in formato testo normale o RTF. Un formato di file di testo normale contiene testo non formattato e non è possibile applicare impostazioni di carattere o pagina ecc. Al contrario, un formato di file di testo ricco consente opzioni di formattazione come l'impostazione del tipo di carattere, stili (grassetto, corsivo, sottolineato, ecc.), margini della pagina, intestazioni, elenchi puntati e numeri e molte altre funzioni di formattazione. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/word-processing/) . |
| Diagram | `4` | Un file di diagramma. |
| Note | `5` | Un file di note elettroniche. Programmi per prendere appunti come Microsoft OneNote ti consentono di creare, aprire e modificare file di note che contengono sezioni e pagine per la memorizzazione di note. Un documento di note può essere semplice come un documento di testo e anche più dettagliato costituito da immagini digitali, clip audio/video e disegni di schizzi a mano. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/note-taking/) . |
| ProjectManagement | `6` | Un formato di gestione del progetto. Ti sei mai imbattuto e ti sei mai chiesto cos'è un file MPP o come aprirlo? MPP e altri file simili sono formati di file di progetto creati da software di gestione del progetto come Microsoft Project. Un progetto file è una raccolta di attività, risorse e la relativa pianificazione per ottenere un output misurabile sotto forma di prodotto o servizio. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/project-management/) . |
| Pdf | `7` | Un file PDF. Il Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era quello di introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/view/pdf/) . |
| Tiff | `8` | Un'immagine TIFF. TIFF o TIF, Tagged Image File Format, rappresenta le immagini raster destinate all'utilizzo su una varietà di dispositivi conformi a questo standard di formato file. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/tiff/) . |
| Jpeg | `9` | Un'immagine JPEG. JPEG è un tipo di formato di immagine che viene salvato utilizzando il metodo di compressione con perdita. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jpeg/) . |
| Psd | `10` | Un'immagine PSD. PSD, Photoshop Document, rappresenta il formato di file nativo di Adobe Photoshop utilizzato per la progettazione e lo sviluppo della grafica. I file PSD possono includere livelli immagine, livelli di regolazione, maschere di livello, annotazioni, informazioni sui file, parole chiave e altri elementi specifici di Photoshop . Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/psd/) . |
| Jpeg2000 | `11` | Un'immagine Jpeg2000. JPEG 2000 (JPX) è un sistema di codifica delle immagini e uno standard di compressione delle immagini all'avanguardia. Progettato, utilizzando la tecnologia wavelet JPEG 2000 può codificare contenuti senza perdita di qualsiasi qualità contemporaneamente. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jp2/) . |
| Gif | `12` | Un'immagine GIF. Un GIF o formato di interscambio grafico è un tipo di immagine altamente compressa. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/gif/) . |
| Png | `13` | Un'immagine PNG. PNG, Portable Network Graphics, si riferisce a un tipo di formato di file di immagine raster che utilizza la compressione senza perdita di dati. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/png/) . |
| Bmp | `14` | Un'immagine BMP. I file con estensione .BMP rappresentano i file di immagine bitmap che vengono utilizzati per memorizzare immagini digitali bitmap. Queste immagini sono indipendenti dall'adattatore grafico e sono anche chiamate formato file indipendente dal dispositivo bitmap (DIB). Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/bmp/) . |
| Dicom | `15` | Un'immagine DICOM. DICOM è l'acronimo di Digital Imaging and Communications in Medicine e appartiene al campo dell'informatica medica. DICOM è la combinazione della definizione del formato file e di un protocollo di comunicazione di rete. Ulteriori informazioni su questo formato file[ qui](https://wiki.fileformat.com/image/dicom/) . |
| WebP | `16` | Un'immagine WEBP. WebP, introdotto da Google, è un moderno formato di file immagine web raster basato sulla compressione lossless e lossy. Fornisce la stessa qualità dell'immagine riducendo considerevolmente le dimensioni dell'immagine. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/webp/) . |
| Emf | `17` | Un'immagine EMF. Il formato metafile avanzato (EMF) memorizza le immagini grafiche in modo indipendente dal dispositivo. I metafile di EMF comprendono record di lunghezza variabile in ordine cronologico che possono eseguire il rendering dell'immagine memorizzata dopo l'analisi su qualsiasi dispositivo di output. Ulteriori informazioni su questo formato del file[qui](https://wiki.fileformat.com/image/emf/) . |
| Wmf | `18` | Un'immagine WMF. I file con estensione WMF rappresentano Microsoft Windows Metafile (WMF) per la memorizzazione di dati di immagini in formato vettoriale e bitmap. Per essere più precisi, WMF appartiene alla categoria di formati di file vettoriali dei formati di file grafici che è dispositivo independent. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/wmf/) . |
| DjVu | `19` | Un file DjVu. DjVu è un formato di file grafico destinato a documenti e libri digitalizzati, in particolare quelli che contengono la combinazione di testo, disegni, immagini e fotografie. È stato sviluppato da AT&amp;T Labs. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/djvu/) . |
| Wav | `20` | Un file audio WAV. WAV, noto per WAVE (Waveform Audio File Format), è un sottoinsieme delle specifiche RIFF (Resource Interchange File Format) di Microsoft per la memorizzazione di file audio digitali. Il formato non applica alcuna compressione al bitstream e memorizza le registrazioni audio con diverse frequenze di campionamento e bitrate. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/audio/wav/) . |
| Mp3 | `21` | Un file audio Mp3. I file con estensione MP3 sono formati di file codificati digitalmente per file audio formalmente basati su MPEG-1 Audio Layer III o MPEG-2 Audio Layer III. È stato sviluppato dal Moving Picture Experts Group ( MPEG) che utilizza la compressione audio Layer 3. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/audio/mp3/) . |
| Avi | `22` | Un video AVI. Il formato di file AVI è un formato di file contenitore multimediale audio video introdotto da Microsoft. Contiene i dati audio e video creati e compressi utilizzando diversi codec (codificatori/decodificatori) come Xvid e DivX. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/video/avi/) . |
| Flv | `23` | Un video FLV. |
| Asf | `24` | Un video ASF. L'Advanced Systems Format (ASF) è un contenitore multimediale digitale progettato principalmente per l'archiviazione e la trasmissione di flussi multimediali. Microsoft Windows Media Video (WMV) è il formato video compresso e Microsoft Windows Media Audio (WMA) è il formato audio compresso insieme a metadati aggiuntivi nel contenitore ASF sviluppato da Microsoft. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/video/wmv/) . |
| Mov | `25` | Un video QuickTime. Il formato Mov o QuickTime File è un contenitore multimediale sviluppato da Apple: contiene una o più tracce, ogni traccia contiene un particolare tipo di dati, ad esempio video, audio, testo ecc. Il formato Mov è compatibile sia in Sistemi Windows e Macintosh. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/video/mov/) . |
| Matroska | `26` | Un video codificato con il contenitore multimediale Matroska. |
| Zip | `27` | Un archivio ZIP. L'estensione file ZIP rappresenta archivi che possono contenere uno o più file o directory. L'archivio può avere la compressione applicata ai file inclusi per ridurre le dimensioni del file ZIP. Il formato file ZIP è stato reso pubblico nel Febbraio 1989 di Phil Katz per aver ottenuto l'archiviazione di file e cartelle. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/compression/zip/) . |
| VCard | `28` | Un file VCard. VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione delle informazioni di contatto. Il formato è ampiamente utilizzato per lo scambio di dati tra le applicazioni di scambio di informazioni più diffuse. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/email/vcf/) . |
| Epub | `29` | Un libro elettronico EPUB. I file con estensione .EPUB sono un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è ormai così comune che è supportato da molti e-reader e applicazioni software. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/ebook/epub/) . |
| OpenType | `30` | Un carattere OpenType. |
| Dxf | `31` | Un disegno DXF (Drawing Exchange Format). DXF, Drawing Interchange Format o Drawing Exchange Format, è una rappresentazione dei dati con tag del file di disegno di AutoCAD. Ogni elemento nel file ha un numero intero prefisso chiamato codice di gruppo. Scopri ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dxf/) . |
| Dwg | `32` | Un disegno DWG. I file con estensione DWG rappresentano file binari proprietari utilizzati per contenere dati di progettazione 2D e 3D. Come i DXF, che sono file ASCII, i DWG rappresentano il formato di file binario per i disegni CAD (Computer Aided Design). Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/cad/dwg/) . |
| Eml | `33` | Un messaggio di posta elettronica EML. Il formato di file EML rappresenta i messaggi di posta elettronica salvati utilizzando Outlook e altre applicazioni pertinenti. Quasi tutti i client di posta elettronica supportano questo formato di file per la sua conformità con RFC-822 Internet Message Format Standard. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/email/eml/) . |
| Msg | `34` | Un messaggio di posta elettronica MSG. MSG è un formato di file utilizzato da Microsoft Outlook ed Exchange per archiviare messaggi di posta elettronica, contatti, appuntamenti o altre attività. Tali messaggi possono contenere uno o più campi di posta elettronica, con il mittente, il destinatario, l'oggetto, data, e corpo del messaggio o informazioni di contatto, dettagli dell'appuntamento e una o più specifiche dell'attività. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/email/msg/) . |
| Torrent | `35` | Un file torrent che contiene metadati su file e cartelle da distribuire. |
| Heif | `36` | Un'immagine HEIF/HEIC. |

### Guarda anche

* spazio dei nomi [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->