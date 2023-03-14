---
title: XmpCameraRawPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Rappresenta lo schema Camera Raw.
type: docs
weight: 3100
url: /it/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Rappresenta lo schema Camera Raw.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | Inizializza una nuova istanza di[`XmpCameraRawPackage`](../xmpcamerarawpackage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | Ottiene o imposta il valore AutoBrightness. Quando è vero,[`Brightness`](./brightness) viene regolato automaticamente. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | Ottiene o imposta il valore AutoContrast. Se vero, "Contrasto" viene regolato automaticamente. |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | Ottiene o imposta il valore AutoExposure. Se vero, "Esposizione" viene regolata automaticamente. |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | Ottiene o imposta il valore di AutoShadows. Quando è vero, "Shadows" viene regolato automaticamente. |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | Ottiene o imposta il valore BlueHue. Null se non definito. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | Ottiene o imposta BlueSaturation. Null se non definito. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | Ottiene o imposta il valore di luminosità. Null se non definito. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | Ottiene o imposta il valore CameraProfile. |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | Ottiene o imposta l'impostazione "Aberrazione cromatica, Fix Blue/Yellow Fringe". Null se non definito. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | Ottiene o imposta l'impostazione "Chromatic Aberration, Fix Red/Cyan Fringe". Null se non definito. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | Ottiene o imposta l'impostazione Riduzione disturbo colore. Intervallo da 0 a 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | Ottiene o imposta l'impostazione Contrasto. Intervallo da -50 a 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Ottiene il numero di proprietà dei metadati. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | Ottiene o imposta l'impostazione CropAngle. Quando HasCrop è vero, angolo del rettangolo di ritaglio. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | Ottiene o imposta l'impostazione CropBottom. Quando HasCrop è vero, parte inferiore del rettangolo di ritaglio. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | Ottiene o imposta l'altezza dell'immagine ritagliata risultante[`CropUnits`](./cropunits) unità. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | Ottiene o imposta l'impostazione CropLeft. Quando HasCrop è vero, a sinistra del rettangolo di ritaglio. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | Ottiene o imposta l'impostazione CropRight. Quando HasCrop è vero, a destra del rettangolo di ritaglio. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | Ottiene o imposta l'impostazione CropTop. Quando HasCrop è vero, parte superiore del rettangolo di ritaglio. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | Ottiene o imposta le unità per[`CropWidth`](./cropwidth) E[`CropHeight`](./cropheight) . |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | Ottiene o imposta la larghezza dell'immagine ritagliata risultante[`CropUnits`](./cropunits) unità. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | Ottiene o imposta l'impostazione Esposizione. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | Ottiene o imposta l'impostazione della tonalità verde. Intervallo da -100 a 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | Ottiene o imposta l'impostazione Saturazione verde. Intervallo da -100 a 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | Ottiene o imposta il valore HasCrop. Se vero, l'immagine ha un rettangolo di ritaglio. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | Ottiene o imposta il valore HasSettings. Quando vero, impostazioni raw della fotocamera non predefinite. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Ottiene il[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) con il nome specificato. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Ottiene una raccolta dei nomi delle proprietà dei metadati. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | Ottiene o imposta l'impostazione LuminanceSmoothing. Intervallo da 0 a 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Ottiene il tipo di metadati. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ottiene l'URI dello spazio dei nomi. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Ottiene il prefisso xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Ottiene una raccolta di descrittori che contengono informazioni sulle proprietà accessibili tramite il motore di ricerca GroupDocs.Metadata. |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | Ottiene o imposta il nome file per un file non elaborato (non un percorso completo). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | Ottiene o imposta l'impostazione della tonalità rossa. Intervallo da -100 a 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | Ottiene o imposta l'impostazione Saturazione rosso. Intervallo da -100 a 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | Ottiene o imposta l'impostazione Saturation. Intervallo da -100 a 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | Ottiene o imposta l'impostazione Ombre. Intervallo da 0 a 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | Ottiene o imposta l'impostazione ShadowTint. Intervallo da -100 a 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | Ottiene o imposta l'impostazione Sharpness. Intervallo da 0 a 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | Ottiene o imposta l'impostazione della temperatura. Intervallo da 2000 a 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | Ottiene o imposta l'impostazione Tinta. Intervallo da -150 a 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Ottiene o imposta la versione del plug-in Camera Raw. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | Ottiene o imposta l'impostazione Quantità vignettatura. Intervallo da -100 a 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | Ottiene o imposta l'impostazione Vignetting Midpoint. Intervallo da 0 a 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | Ottiene l'impostazione del bilanciamento del bianco. Utilizzo[`SetWhiteBalance`](./setwhitebalance) per impostare il valore del bilanciamento del bianco. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Ottiene lo spazio dei nomi XML. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiunge proprietà di metadati note che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Rimuove tutte le proprietà XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determina se il pacchetto contiene una proprietà di metadati con il nome specificato. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Trova le proprietà dei metadati che soddisfano il predicato specificato. La ricerca è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converte il valore XMP nella rappresentazione XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Rimuove la proprietà con il nome specificato. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Rimuove le proprietà dei metadati che soddisfano il predicato specificato. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Rimuove le proprietà dei metadati scrivibili dal pacchetto. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti annidati. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Imposta la proprietà booleana. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | InsiemiDateTime proprietà. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Imposta la proprietà double. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Imposta la proprietà numero intero. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | Aggiunge proprietà stringa. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Imposta il valore ereditato da[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Imposta il valore ereditato da[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Imposta il valore ereditato da[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Imposta le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. Questo metodo è una combinazione di[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) E[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Se una proprietà esistente soddisfa il predicato, il suo valore viene aggiornato. Se nel pacchetto manca una proprietà nota che soddisfa il predicato, viene aggiunta al pacchetto. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | Imposta il bilanciamento del bianco. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Aggiorna le proprietà dei metadati noti che soddisfano il predicato specificato. L'operazione è ricorsiva quindi interessa anche tutti i pacchetti nidificati. |

### Guarda anche

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* spazio dei nomi [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
