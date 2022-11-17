---
title: SonyMakerNotePackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta i metadati SONY MakerNote.
type: docs
weight: 2860
url: /it/net/groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/
---
## SonyMakerNotePackage class

Rappresenta i metadati SONY MakerNote.

```csharp
public sealed class SonyMakerNotePackage : MakerNotePackage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AFIlluminator](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/afilluminator) { get; } | Ottiene il tipo di illuminatore AF. |
| [Brightness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/brightness) { get; } | Ottiene la luminosità. |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colormode) { get; } | Ottiene la modalità colore. |
| [ColorTemperature](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colortemperature) { get; } | Ottiene la temperatura del colore. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/contrast) { get; } | Ottiene il contrasto. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CreativeStyle](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/creativestyle) { get; } | Ottiene lo stile creativo. |
| [ExposureMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/exposuremode) { get; } | Ottiene la modalità di esposizione. |
| [FlashLevel](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/flashlevel) { get; } | Ottiene il livello di flash. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/focusmode) { get; } | Ottiene la modalità focus. |
| [Header](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/header) { get; } | Ottiene l'intestazione MakerNote. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Ottiene il tag TIFF con l'id specificato. (2 indexers) |
| [JpegQuality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/jpegquality) { get; } | Ottiene la qualità JPEG. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [Macro](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/macro) { get; } | Ottiene la macro. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [MultiBurstImageHeight](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimageheight) { get; } | Ottiene l'altezza dell'immagine multi burst. |
| [MultiBurstImageWidth](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimagewidth) { get; } | Ottiene la larghezza dell'immagine multi burst. |
| [MultiBurstMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstmode) { get; } | Ottiene un valore che indica se la modalità multi burst è attiva. |
| [PictureEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/pictureeffect) { get; } | Ottiene l'effetto immagine. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/quality) { get; } | Ottiene la qualità dell'immagine. |
| [Rating](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/rating) { get; } | Ottiene la valutazione. |
| [ReleaseMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/releasemode) { get; } | Ottiene la modalità di rilascio. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/saturation) { get; } | Ottiene la saturazione. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sharpness) { get; } | Ottiene la nitidezza. |
| [SoftSkinEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/softskineffect) { get; } | Ottiene l'effetto pelle morbida. |
| [SonyModelID](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sonymodelid) { get; } | Ottiene l'identificatore del modello Sony. |
| [Teleconverter](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/teleconverter) { get; } | Ottiene il tipo di moltiplicatore di focale. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/whitebalance) { get; } | Ottiene il bilanciamento del bianco. |

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
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) e[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Crea un elenco dal pacchetto. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [MakerNotePackage](../makernotepackage)
* spazio dei nomi [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
