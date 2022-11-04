---
title: ImageResourceID
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: StandardIDNummern für Bildressourcen. Nicht alle Dateiformate verwenden alle IDs. Einige Informationen können in anderen Abschnitten der Datei gespeichert werden.
type: docs
weight: 1750
url: /de/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Standard-ID-Nummern für Bildressourcen. Nicht alle Dateiformate verwenden alle IDs. Einige Informationen können in anderen Abschnitten der Datei gespeichert werden.

```csharp
public enum ImageResourceID
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo-Struktur. Siehe Anhang A im PDF-Dokument des Photoshop-API-Leitfadens. |
| NamesOfAlphaChannels | `1006` | Namen der Alphakanäle als eine Reihe von Pascal-Strings. |
| Caption | `1008` | Die Beschriftung als Pascal-String. |
| BorderInformation | `1009` | Grenzinformationen. Enthält eine feste Zahl (2 Bytes Real, 2 Bytes Bruch) für die Rahmenbreite, und 2 Bytes für Rahmeneinheiten (1 = Zoll, 2 = cm, 3 = Punkte, 4 = Pica, 5 = Spalten). |
| BackgroundColor | `1010` | Hintergrundfarbe. [Mehr sehen.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Flags drucken. Eine Reihe von booleschen Ein-Byte-Werten (siehe Dialogfeld „Seite einrichten“): Etiketten, Schnittmarken, Farbbalken, Passmarken, Negativ, Spiegeln, Interpolieren, Beschriftung, Druckmarkierungen. |
| Grayscale | `1012` | Graustufen- und Mehrkanal-Halbtoninformationen. |
| ColorHalftoning | `1013` | Farbrasterinformationen. |
| DuotoneHalftoning | `1014` | Duplex-Halbtoninformationen. |
| GrayscaleFunction | `1015` | Graustufen- und Mehrkanal-Übertragungsfunktion. |
| ColorTransferFunctions | `1016` | Farbübertragungsfunktionen. |
| DuotoneTransferFunctions | `1017` | Duplex-Übertragungsfunktionen. |
| DuotoneImageInformation | `1018` | Duotone-Bildinformationen. |
| EPSOptions | `1021` | EPS-Optionen. |
| QuickMaskInformation | `1022` | Schnelle Maskeninformationen. 2 Byte mit Quick Mask-Kanal-ID; 1-Byte boolesch, der angibt, ob die Maske anfänglich leer war. |
| LayerStateInformation | `1024` | Schichtzustandsinformationen. 2 Bytes enthalten den Index der Zielebene (0 = unterste Ebene). |
| WorkingPath | `1025` | Arbeitspfad (nicht gespeichert). Siehe Siehe Pfadressourcenformat. |
| LayersGroupInformation | `1026` | Layer-Gruppeninformationen. 2 Bytes pro Layer, die eine Gruppen-ID für die Schleppgruppen enthalten. Ebenen in einer Gruppe haben dieselbe Gruppen-ID. |
| Iptc | `1028` | IPTC-NAA-Eintrag. Enthält die Dateiinfo...-Informationen. Siehe die Dokumentation im IPTC-Ordner des Dokumentationsordners. |
| ImageModeForRawFormat | `1029` | Bildmodus für Rohformatdateien. |
| JpegQuality | `1030` | JPEG-Qualität. Privat. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Raster- und Führungsinformationen. |
| ThumbnailResourcePhotoshop4 | `1033` | Thumbnail-Ressource nur für Photoshop 4.0. |
| CopyrightFlagPhotoshop4 | `1034` | Copyright-Flag. Boolescher Wert, der angibt, ob das Bild urheberrechtlich geschützt ist. Kann über die Property Suite oder vom Benutzer in File Info... festgelegt werden |
| UrlPhotoshop4 | `1035` | -URL. Handle einer Textzeichenfolge mit Uniform Resource Locator. Kann über die Property Suite oder vom Benutzer in File Info... festgelegt werden |
| ThumbnailResourcePhotoshop5 | `1036` | Thumbnail-Ressource (ersetzt Ressource 1033). Siehe Ressourcenformat für Miniaturansichten. |
| GlobalAnglePhotoshop5 | `1037` | Globaler Winkel. 4 Bytes, die eine Ganzzahl zwischen 0 und 359 enthalten, die der globale Beleuchtungswinkel für die Effektebene ist. Wenn nicht vorhanden, angenommen 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC-Profil. Die Rohbytes eines Profils im ICC-Format (International Color Consortium). Siehe ICC1v42_2006-05.pdf im Documentation-Ordner und icProfileHeader.h in Sample Code\Common\Includes. |
| WatermarkPhotoshop5 | `1040` | Wasserzeichen. Ein Byte. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC-Profil ohne Tags. 1 Byte, das jede angenommene Profilbehandlung beim Öffnen der Datei deaktiviert. 1 = absichtlich nicht getaggt. |
| TransparencyIndexPhotoshop6 | `1047` | Transparenzindex. 2 Bytes für den Index der transparenten Farbe, falls vorhanden. |
| GlobalAltitudePhotoshop6 | `1049` | Globale Höhe. 4 Byte Eintrag für Höhe. |
| SlicesPhotoshop6 | `1050` | Slices (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | Workflow-URL. Unicode-String. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Alpha-Identifikatoren. 4 Bytes Länge, gefolgt von jeweils 4 Bytes für jede Alpha-Kennung. |
| UrlListPhotoshop6 | `1054` | URL InternalList. 4 Byte URLs, gefolgt von 4 Byte Länge, 4 Byte ID und Unicode-String für jede Zählung. |
| VersionInfoPhotoshop6 | `1057` | Versionsinformationen. 4 Bytes Version, 1 Byte hasRealMergedData , Unicode-String: Schreibername, Unicode-String: Lesername, 4 Bytes Dateiversion. |
| ExifData1Photoshop7 | `1058` | EXIF-Daten 1,[Mehr sehen](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ EXIF-Daten 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP-Metadaten. Dateiinfo als XML-Beschreibung,[Mehr sehen](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Untertitelzusammenfassung. 16 Byte: RSA Data Security, MD5 Message-Digest-Algorithmus. |
| PrintScalePhotoshop7 | `1062` | Skala drucken. 2 Bytes Stil (0 = zentriert, 1 = passende Größe, 2 = benutzerdefiniert). 4 Bytes x Ort (Gleitkomma). 4 Bytes y-Position (Gleitkomma). 4-Byte-Skalierung (Fließkomma). |
| PixelAspectRatio | `1064` | Pixel-Seitenverhältnis. 4 Bytes (Version = 1 oder 2), 8 Bytes doppelt, x / y eines Pixels. Version 2, Versuch Werte für NTSC und PAL zu korrigieren, vorher um Faktor ca. 5 %. |
| LayerComps | `1065` | Layer-Komp. 4 Bytes (Deskriptorversion = 16), Deskriptor. |
| LayerSelectionIds | `1069` | Ebenenauswahl-ID(s). 2 Bytes Zählung, Folgendes wird für jede Zählung wiederholt: 4 Bytes Schicht-ID. |
| PrintInfoCS2 | `1071` | Druckinfo (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Layer-Gruppe(n) Aktivierte ID. 1 Byte für jede Ebene im Dokument, wiederholt durch die Länge der Ressource. HINWEIS: Ebenengruppen haben Start- und Endmarkierungen (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Ressource für Farbmuster. Siehe auch ID 1038 für altes Format. |
| MeasurementScaleCS3 | `1074` | Messskala. 4 Bytes (Deskriptorversion = 16), Deskriptor. |
| TimelineInformationCS3 | `1075` | Timeline-Informationen. 4 Bytes (Deskriptorversion = 16), Deskriptor. |
| SheetDisclosureCS3 | `1076` | Blatt Offenlegung. 4 Bytes (Deskriptorversion = 16), Deskriptor. |
| PrintInformationCS5 | `1082` | Druckinformationen (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Druckstil (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Variable betriebssystemspezifische Informationen für Macintosh. NSPrintInfo. Es wird empfohlen, diese Daten nicht zu interpretieren oder zu verwenden. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Variable betriebssystemspezifische Informationen für Windows. ENTWICKLUNGSMODUS. Es wird empfohlen, diese Daten nicht zu interpretieren oder zu verwenden. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Dateipfad automatisch speichern. Unicode-String. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Automatisch gespeichertes Format. Unicode-String. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Zustand der Pfadauswahl. (Photoshop CC). |
| ImageReadyVariables | `7000` | Image Ready-Variablen. XML-Darstellung der Variablendefinition. |
| ImageReadyDatasets | `7001` | Bildfertige Datensätze. |
| PrintFlagsInformation | `10000` | Flaggeninformationen drucken. 2 Byte Version ( = 1), 1 Byte Schnittmarken in der Mitte, 1 Byte ( = 0), 4 Byte Beschnittbreitenwert, 2 Byte Beschnittbreitenskalierung. |

### Siehe auch

* namensraum [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
