---
title: IptcApplicationRecordDataSet
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Definisce i numeri del set di dati dei record dellapplicazione IPTC.
type: docs
weight: 2890
url: /it/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

Definisce i numeri del set di dati dei record dell'applicazione IPTC.

```csharp
public enum IptcApplicationRecordDataSet
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RecordVersion | `0` | Rappresenta la versione del record. Binario. Sempre 2 in JPEG. |
| ObjectTypeReference | `3` | Riferimento al tipo di oggetto. Schema utilizzato: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | Il riferimento all'attributo dell'oggetto. |
| ObjectName | `5` | Utilizzato come riferimento abbreviato per l'oggetto. |
| EditStatus | `7` | Stato dei dati oggetto, secondo la prassi del provider. |
| EditorialUpdate | `8` | Indica il tipo di aggiornamento che questo oggetto fornisce a un oggetto precedente. |
| Urgency | `10` | Specifica l'urgenza editoriale del contenuto e non necessariamente la priorità di gestione della busta (vedi 1:60, Priorità della busta). |
| SubjectReference | `12` | Il riferimento al soggetto. |
| Category | `15` | Identifica l'oggetto dei dati oggetto secondo il parere del provider. |
| SupplementalCategory | `20` | Le categorie supplementari perfezionano ulteriormente l'oggetto di un objectdata. In ogni DataSet può essere contenuta solo una singola categoria supplementare. Una categoria supplementare può includere una qualsiasi delle categorie riconosciute utilizzate in 2:15. |
| FixtureIdentifier | `22` | L'identificativo dell'impianto. |
| Keywords | `25` | Utilizzato per indicare parole specifiche per il recupero di informazioni. Ogni parola chiave utilizza un singolo set di dati di parole chiave. Più parole chiave utilizzano più set di dati delle parole chiave. |
| ContentLocationCode | `26` | Indica il codice di una nazione/località geografica cui fa riferimento il contenuto dell'oggetto. |
| ContentLocationName | `27` | Fornisce un nome completo e pubblicabile di un paese/località geografica a cui fa riferimento il contenuto dell'oggetto, secondo le linee guida del provider. |
| ReleaseDate | `30` | Indica nella forma CCYYMMDD la prima data in cui il provider intende utilizzare l'oggetto. Conforme allo standard ISO 8601. |
| ReleaseTime | `35` | Indica nella forma HHMMSS±HHMM la prima volta che il provider intende utilizzare l'oggetto. Conforme allo standard ISO 8601. |
| ExpirationDate | `37` | Indica nella forma CCYYMMDD l'ultima data in cui il fornitore o il proprietario intende utilizzare i dati dell'oggetto. Conforme allo standard ISO 8601. |
| SpecialInstructions | `40` | Altre istruzioni redazionali riguardanti l'uso dei dati oggetto, come embarghi e avvertimenti. |
| ActionAdvised | `42` | Indica il tipo di azione che questo oggetto fornisce a un oggetto precedente. |
| ReferenceService | `45` | Identifica il Service Identifier di una busta precedente a cui fa riferimento l'oggetto corrente. |
| ReferenceDate | `47` | Identifica la data di una busta precedente a cui fa riferimento l'oggetto corrente. |
| ReferenceNumber | `50` | Identifica il Numero Busta di una busta precedente a cui fa riferimento l'oggetto corrente. |
| DateCreated | `55` | Rappresentato nella forma CCYYMMDD per designare la data di creazione del contenuto intellettuale dei dati oggetto piuttosto che la data di creazione della rappresentazione fisica. |
| TimeCreated | `60` | Rappresentato nella forma HHMMSS±HHMM per indicare l'ora in cui è stato creato il contenuto intellettuale dei dati oggetto il materiale sorgente corrente piuttosto che la creazione della rappresentazione fisica. |
| DigitalCreationDate | `62` | Rappresentato nella forma CCYYMMDD per designare la data in cui è stata creata la rappresentazione digitale dei dati oggetto. |
| DigitalCreationTime | `63` | Rappresentato nella forma HHMMSS±HHMM per designare l'ora in cui è stata creata la rappresentazione digitale dei dati oggetto. |
| OriginatingProgram | `65` | Identifica il tipo di programma utilizzato per originare i dati oggetto. |
| ProgramVersion | `70` | Utilizzato per identificare la versione del programma menzionato in 2:65. DataSet 2:70 non è valido se 2:65 non è presente. |
| ObjectCycle | `75` | Composto da un carattere alfabetico. Dove: 'a' = mattina, 'p' = sera, 'b' = entrambi. |
| Byline | `80` | Contiene il nome del creatore dei dati oggetto, ad esempio scrittore, fotografo o artista grafico. |
| BylineTitle | `85` | Un titolo per riga è il titolo del creatore o dei creatori di dati oggetto. |
| City | `90` | Identifica la città di origine dei dati dell'oggetto secondo le linee guida stabilite dal provider. |
| SubLocation | `92` | Identifica la posizione all'interno di una città da cui provengono gli objectdata, secondo le linee guida stabilite dal provider. |
| ProvinceState | `95` | Identifica la Provincia/Stato di provenienza secondo le linee guida stabilite dal provider. |
| PrimaryLocationCode | `100` | Indica il codice del paese/località principale in cui è stata creata la proprietà intellettuale dei dati dell'oggetto, ad esempio è stata scattata una foto, si è verificato un evento. |
| PrimaryLocationName | `101` | Fornisce il nome completo, pubblicabile, del paese/luogo principale in cui è stata creata la proprietà intellettuale dei dati dell'oggetto, secondo le linee guida del provider. |
| OriginalTransmissionReference | `103` | Un codice che rappresenta la posizione della trasmissione originale secondo le pratiche del provider. |
| Headline | `105` | Una voce pubblicabile che fornisce una sintesi del contenuto dell'objectdata. |
| Credit | `110` | Identifica il fornitore dei dati oggetto, non necessariamente il proprietario/creatore. |
| Source | `115` | Il nome di una persona o parte che ha un ruolo nella catena di fornitura dei contenuti. Potrebbe trattarsi di un'agenzia, un membro di un'agenzia, un individuo o una combinazione. |
| CopyrightNotice | `116` | Contiene tutti gli avvisi di copyright necessari. |
| Contact | `118` | Identifica la persona o l'organizzazione che può fornire ulteriori informazioni di base sui dati dell'oggetto. |
| CaptionAbstract | `120` | Una descrizione testuale dei dati dell'oggetto, utilizzata in particolare quando l'oggetto non è testo. |
| WriterEditor | `122` | Identificazione del nome della persona coinvolta nella scrittura, modifica o correzione dei dati oggetto o didascalia/abstract. |
| RasterizedCaption | `125` | Larghezza immagine 460 pixel e altezza immagine 128 pixel. Direzione di scansione dal basso verso l'alto, da sinistra a destra. |
| ImageType | `130` | I caratteri numerici da 1 a 4 indicano il numero di componenti in un'immagine, in buste singole o multiple. |
| ImageOrientation | `131` | Indica il layout dell'area dell'immagine. |
| LanguageIdentifier | `135` | Descrive la principale lingua nazionale dell'oggetto, secondo i codici a 2 lettere della norma ISO 639:1988. |
| AudioType | `150` | Il tipo di audio. |
| AudioSamplingRate | `151` | Caratteri numerici della frequenza di campionamento, che rappresentano la frequenza di campionamento in hertz (Hz). |
| AudioSamplingResolution | `152` | Il numero di bit in ciascun campione audio. |
| AudioDuration | `153` | Durata Indica nella forma HHMMSS il tempo di esecuzione dei dati di un oggetto audio riprodotti alla velocità con cui sono stati registrati. |
| AudioOutcue | `154` | Identifica il contenuto della fine di un oggetto audiodata, secondo le linee guida stabilite dal provider. |
| ObjDataPreviewFileFormat | `200` | Un numero binario che rappresenta il formato file dell'anteprima ObjectData. |
| ObjDataPreviewFileFormatVer | `201` | Un numero binario che rappresenta la versione specifica del formato del file di anteprima ObjectData specificato in 2:200. |
| ObjDataPreviewData | `202` | L'anteprima dei dati dell'oggetto. |

### Guarda anche

* spazio dei nomi [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
