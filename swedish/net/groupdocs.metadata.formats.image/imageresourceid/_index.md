---
title: ImageResourceID
second_title: GroupDocs.Metadata for .NET API-referens
description: StandardIDnummer för bildresurser. Alla filformat använder inte alla ID. Viss information kan lagras i andra delar av filen.
type: docs
weight: 1750
url: /sv/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Standard-ID-nummer för bildresurser. Alla filformat använder inte alla ID. Viss information kan lagras i andra delar av filen.

```csharp
public enum ImageResourceID
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo-struktur. Se bilaga A i Photoshop API Guide PDF-dokument. |
| NamesOfAlphaChannels | `1006` | Namn på alfakanalerna som en serie av Pascal-strängar. |
| Caption | `1008` | Bildtexten som en Pascal-sträng. |
| BorderInformation | `1009` | Kantinformation. Innehåller ett fast tal (2 byte reell, 2 byte fraktion) för kantbredden, och 2 byte för kantenheter (1 = tum, 2 = cm, 3 = poäng, 4 = picas, 5 = kolumner). |
| BackgroundColor | `1010` | Bakgrundsfärg. [Se mer.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Skriv ut flaggor. En serie booleska värden på en byte (se dialogrutan Utskriftsformat): etiketter, skärmärken, färgfält, registreringsmärken, negativ, vänd, interpolera, bildtext, skriv ut flaggor. |
| Grayscale | `1012` | Gråskala och flerkanalig halvtonsinformation. |
| ColorHalftoning | `1013` | Färghalvtonsinformation. |
| DuotoneHalftoning | `1014` | Duotone halvtonsinformation. |
| GrayscaleFunction | `1015` | Gråskala och flerkanalsöverföringsfunktion. |
| ColorTransferFunctions | `1016` | Färgöverföringsfunktioner. |
| DuotoneTransferFunctions | `1017` | Duotone överföringsfunktioner. |
| DuotoneImageInformation | `1018` | Duotone bildinformation. |
| EPSOptions | `1021` | EPS-alternativ. |
| QuickMaskInformation | `1022` | Snabbmask information. 2 byte som innehåller Quick Mask-kanal-ID; 1-byte boolean som indikerar om masken från början var tom. |
| LayerStateInformation | `1024` | Lagerstatusinformation. 2 byte som innehåller indexet för målskiktet (0 = bottenskiktet). |
| WorkingPath | `1025` | Arbetsväg (ej sparad). Se Se sökvägsresursformat. |
| LayersGroupInformation | `1026` | Lagergruppinformation. 2 byte per lager som innehåller ett grupp-ID för draggrupperna. Lager i en grupp har samma grupp-ID. |
| Iptc | `1028` | IPTC-NAA-post. Innehåller filinformation... information. Se dokumentationen i mappen IPTC i mappen Documentation. |
| ImageModeForRawFormat | `1029` | Bildläge för filer i råformat. |
| JpegQuality | `1030` | JPEG-kvalitet. Privat. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Rutnät och guider information. |
| ThumbnailResourcePhotoshop4 | `1033` | Miniatyrresurs endast för Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Upphovsrättsflagga. Boolean som anger om bilden är upphovsrättsskyddad. Kan ställas in via Property Suite eller av användare i File Info... |
| UrlPhotoshop4 | `1035` | URL. Handtag för en textsträng med enhetlig resurslokalisering. Kan ställas in via Property Suite eller av användare i File Info... |
| ThumbnailResourcePhotoshop5 | `1036` | Miniatyrresurs (ersätter resurs 1033). Se Se miniatyrbildsresursformat. |
| GlobalAnglePhotoshop5 | `1037` | Global vinkel. 4 byte som innehåller ett heltal mellan 0 och 359, vilket är den globala ljusvinkeln för effektskiktet. Om det inte finns, antas det vara 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC-profil. De obearbetade byten för en profil i ICC-format (International Color Consortium). Se ICC1v42_2006-05.pdf i mappen Documentation och icProfileHeader.h i Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Vattenstämpel. En byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC otaggad profil. 1 byte som inaktiverar all antagen profilhantering när filen öppnas. 1 = avsiktligt otaggat. |
| TransparencyIndexPhotoshop6 | `1047` | Transparensindex. 2 byte för indexet för transparent färg, om någon. |
| GlobalAltitudePhotoshop6 | `1049` | Global Altitude. 4 byte post för höjd. |
| SlicesPhotoshop6 | `1050` | Skivor (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | Arbetsflödes-URL. Unicode-sträng. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Alfa-identifierare. 4 byte lång, följt av 4 byte vardera för varje alfa-identifierare. |
| UrlListPhotoshop6 | `1054` | URL InternalList. 4 byte antal webbadresser, följt av 4 byte långa, 4 byte ID och Unicode-sträng för varje count. |
| VersionInfoPhotoshop6 | `1057` | Versionsinformation. 4 byte version, 1 byte hasRealMergedData , Unicode-sträng: författarens namn, Unicode-sträng: läsarens namn, 4 bytes filversion. |
| ExifData1Photoshop7 | `1058` | EXIF-data 1,[se mer](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ EXIF-data 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP-metadata. Filinformation som XML-beskrivning,[se mer](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Bildtextsammandrag. 16 byte: RSA Data Security, MD5 meddelandesammandragningsalgoritm. |
| PrintScalePhotoshop7 | `1062` | Skriv ut skala. 2 byte stil (0 = centrerad, 1 = storlek som passar, 2 = användardefinierad). 4 byte x plats (flytande komma). 4 byte y plats (flytande komma). 4 byte skala (flytande komma). |
| PixelAspectRatio | `1064` | Pixelbildförhållande. 4 byte (version = 1 eller 2), 8 byte dubbel, x/y av en pixel. Version 2, försök att korrigera värden för NTSC och PAL, tidigare avstängd med en faktor på ca. 5 % |
| LayerComps | `1065` | Lagerkomp. 4 byte (deskriptorversion = 16), Descriptor. |
| LayerSelectionIds | `1069` | Lagerurvals-ID(n). 2 byte antal, följande upprepas för varje antal: 4 byte lager-ID. |
| PrintInfoCS2 | `1071` | Utskriftsinformation (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Lagergrupp(er) aktiverat ID. 1 byte för varje lager i dokumentet, upprepad efter resursens längd. OBS: Lagergrupper har start- och slutmarkörer (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Resurs för färgprovtagare. Se även ID 1038 för gammalt format. |
| MeasurementScaleCS3 | `1074` | Måttskala. 4 byte (deskriptorversion = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Tidslinjeinformation. 4 byte (deskriptorversion = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Upplysningsblad. 4 byte (deskriptorversion = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Utskriftsinformation (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Utskriftsstil (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Variabel OS-specifik information för Macintosh. NSPrintInfo. Det rekommenderas att du inte tolkar eller använder denna data. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Variabel OS-specifik information för Windows. DEVMODE. Det rekommenderas att du inte tolkar eller använder denna data. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Autospara filsökväg. Unicode-sträng. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Autospara format. Unicode-sträng. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Sökvägsvalstillstånd. (Photoshop CC). |
| ImageReadyVariables | `7000` | Image Ready variabler. XML-representation av variabeldefinition. |
| ImageReadyDatasets | `7001` | Bildklara datamängder. |
| PrintFlagsInformation | `10000` | Skriv ut flagginformation. 2 byte version ( = 1), 1 byte mittskärmärken, 1 byte ( = 0), 4 byte bleed width värde, 2 byte bleed width skala. |

### Se även

* namnutrymme [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
