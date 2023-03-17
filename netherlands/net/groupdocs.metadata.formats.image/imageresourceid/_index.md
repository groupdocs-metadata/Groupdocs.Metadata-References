---
title: ImageResourceID
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Beeldbronnen standaard IDnummers. Niet alle bestandsindelingen gebruiken alle IDs. Sommige informatie kan worden opgeslagen in andere secties van het bestand.
type: docs
weight: 1750
url: /nl/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Beeldbronnen standaard ID-nummers. Niet alle bestandsindelingen gebruiken alle ID's. Sommige informatie kan worden opgeslagen in andere secties van het bestand.

```csharp
public enum ImageResourceID
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo-structuur. Zie Bijlage A in PDF-document Photoshop API Guide. |
| NamesOfAlphaChannels | `1006` | Namen van de alfakanalen als een reeks Pascal-strings. |
| Caption | `1008` | Het bijschrift als Pascal-tekenreeks. |
| BorderInformation | `1009` | Grensinformatie. Bevat een vast getal (2 bytes reëel, 2 bytes breuk) voor de grensbreedte, en 2 bytes voor grenseenheden (1 = inch, 2 = cm, 3 = punten, 4 = pica's, 5 = kolommen). |
| BackgroundColor | `1010` | Achtergrondkleur. [Bekijk meer.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Druk vlaggen af. Een reeks booleaanse waarden van één byte (zie dialoogvenster Pagina-instelling): labels, snijtekens, kleurenbalken, registratietekens, negatief, spiegelen, interpoleren, bijschrift, afdrukvlaggen. |
| Grayscale | `1012` | Informatie over grijstinten en meerkanaals halftonen. |
| ColorHalftoning | `1013` | Informatie over halftonen in kleur. |
| DuotoneHalftoning | `1014` | Informatie over duotone halftonen. |
| GrayscaleFunction | `1015` | Grijstinten en meerkanaals overdrachtsfunctie. |
| ColorTransferFunctions | `1016` | Functies voor kleuroverdracht. |
| DuotoneTransferFunctions | `1017` | Duotone-overdrachtsfuncties. |
| DuotoneImageInformation | `1018` | Duotone beeldinformatie. |
| EPSOptions | `1021` | EPS-opties. |
| QuickMaskInformation | `1022` | Quick Mask-informatie. 2 bytes met Quick Mask-kanaal-ID; 1-byte booleaanse waarde die aangeeft of het masker aanvankelijk leeg was. |
| LayerStateInformation | `1024` | Laagstatusinformatie. 2 bytes met de index van de doellaag (0 = onderste laag). |
| WorkingPath | `1025` | Werkpad (niet opgeslagen). Zie Zie Zie Padbronformaat. |
| LayersGroupInformation | `1026` | Lagen groeperen informatie. 2 bytes per laag met een groeps-ID voor de sleepgroepen. Lagen in een groep hebben dezelfde groeps-ID. |
| Iptc | `1028` | IPTC-NAA-record. Bevat de File Info... informatie. Zie de documentatie in de IPTC-map van de documentatiemap. |
| ImageModeForRawFormat | `1029` | Afbeeldingsmodus voor bestanden in onbewerkte indeling. |
| JpegQuality | `1030` | JPEG-kwaliteit. Privé. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Informatie over raster en hulplijnen. |
| ThumbnailResourcePhotoshop4 | `1033` | Miniatuurbron alleen voor Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Copyrightvlag. Booleaanse waarde die aangeeft of de afbeelding auteursrechtelijk beschermd is. Kan worden ingesteld via Property suite of door gebruiker in File Info... |
| UrlPhotoshop4 | `1035` | URL. Handvat van een tekststring met uniforme bronzoeker. Kan worden ingesteld via Property suite of door gebruiker in File Info... |
| ThumbnailResourcePhotoshop5 | `1036` | Miniatuurbron (vervangt bron 1033). Zie Zie Indeling miniatuurbron. |
| GlobalAnglePhotoshop5 | `1037` | Globale hoek. 4 bytes die een geheel getal tussen 0 en 359 bevatten, wat de globale belichtingshoek is voor de effectlaag. Indien niet aanwezig, verondersteld 30. te zijn |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC-profiel. De onbewerkte bytes van een profiel in ICC-indeling (International Color Consortium). Zie ICC1v42_2006-05.pdf in de map Documentation en icProfileHeader.h in Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Watermerk. Eén byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC niet-gelabeld profiel. 1 byte die elke veronderstelde profielverwerking uitschakelt bij het openen van het bestand. 1 = opzettelijk niet getagd. |
| TransparencyIndexPhotoshop6 | `1047` | Transparantie-index. 2 bytes voor de index van transparante kleur, indien aanwezig. |
| GlobalAltitudePhotoshop6 | `1049` | Wereldwijde hoogte. 4 byte invoer voor hoogte. |
| SlicesPhotoshop6 | `1050` | Plakjes (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | Workflow-URL. Unicode-reeks. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Alfa-ID's. 4 bytes lang, gevolgd door elk 4 bytes voor elke alfa-ID. |
| UrlListPhotoshop6 | `1054` | URL InterneLijst. Aantal URL's van 4 bytes, gevolgd door een lengte van 4 bytes, een ID van 4 bytes en een Unicode-tekenreeks voor elk aantal. |
| VersionInfoPhotoshop6 | `1057` | Versie-info. 4 bytes versie, 1 byte hasRealMergedData , Unicode string: naam schrijver, Unicode string: naam lezer, 4 bytes bestandsversie. |
| ExifData1Photoshop7 | `1058` | EXIF-gegevens 1,[Bekijk meer](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ EXIF-gegevens 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP-metagegevens. Bestandsinfo als XML-beschrijving,[Bekijk meer](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Samenvatting van ondertiteling. 16 bytes: RSA-gegevensbeveiliging, MD5-algoritme voor berichtsamenvatting. |
| PrintScalePhotoshop7 | `1062` | Afdrukschaal. 2 bytes stijl (0 = gecentreerd, 1 = maat passend, 2 = door gebruiker gedefinieerd). 4 bytes x locatie (zwevende komma). 4 bytes y locatie (zwevende komma). 4 bytes schaal (zwevende komma). |
| PixelAspectRatio | `1064` | Pixel-beeldverhouding. 4 bytes (versie = 1 of 2), 8 bytes dubbel, x/y van een pixel. Versie 2, waarin wordt geprobeerd de waarden voor NTSC en PAL te corrigeren, voorheen afwijkend met een factor van ongeveer. 5%. |
| LayerComps | `1065` | Laagsamenstellingen. 4 bytes (descriptorversie = 16), descriptor. |
| LayerSelectionIds | `1069` | Laagselectie-ID('s). 2 bytes tellen, het volgende wordt herhaald voor elke telling: 4 bytes laag ID. |
| PrintInfoCS2 | `1071` | Afdrukinfo (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Lagengroep(en) ingeschakeld ID. 1 byte voor elke laag in het document, herhaald op basis van de lengte van de bron. OPMERKING: Laaggroepen hebben begin- en eindmarkeringen (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Resource voor kleurmonsters. Zie ook ID 1038 voor oud formaat. |
| MeasurementScaleCS3 | `1074` | Meetschaal. 4 bytes (descriptorversie = 16), descriptor. |
| TimelineInformationCS3 | `1075` | Tijdlijninformatie. 4 bytes (descriptorversie = 16), descriptor. |
| SheetDisclosureCS3 | `1076` | Blad openbaarmaking. 4 bytes (descriptorversie = 16), descriptor. |
| PrintInformationCS5 | `1082` | Afdrukinformatie (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Afdrukstijl (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Variabele OS-specifieke informatie voor Macintosh. NSPrintInfo. Het wordt aanbevolen deze gegevens niet te interpreteren of te gebruiken. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Variabele OS-specifieke informatie voor Windows. DEVMODE. Het wordt aanbevolen deze gegevens niet te interpreteren of te gebruiken. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Bestandspad automatisch opslaan. Unicode-reeks. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Formaat voor automatisch opslaan. Unicode-reeks. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Status padselectie. (Photoshop CC). |
| ImageReadyVariables | `7000` | Image Ready-variabelen. XML-weergave van definitie van variabelen. |
| ImageReadyDatasets | `7001` | Image Ready-gegevenssets. |
| PrintFlagsInformation | `10000` | Informatie over vlaggen afdrukken. 2 bytes versie ( = 1), 1 byte snijtekens midden, 1 byte ( = 0), 4 bytes afloopbreedtewaarde, 2 bytes afloopbreedteschaal. |

### Zie ook

* naamruimte [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
