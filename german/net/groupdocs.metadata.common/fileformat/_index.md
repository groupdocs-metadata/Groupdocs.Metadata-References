---
title: FileFormat
second_title: GroupDocs.Metadata für .NET-API-Referenz
description: Repräsentiert das erkannte Format einer geladenen Datei.
type: docs
weight: 40
url: /de/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

Repräsentiert das erkannte Format einer geladenen Datei.

```csharp
public enum FileFormat
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Unknown | `0` | Der Dateityp wird nicht erkannt. |
| Presentation | `1` | Eine Präsentationsdatei. Audio und eingebettete Objekte. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/presentation/) . |
| Spreadsheet | `2` | Eine Tabellenkalkulationsdatei. Eine Tabellenkalkulationsdatei enthält Daten in Form von Zeilen und Spalten. Sie können solche Dateien mit Tabellenkalkulationssoftwareanwendungen wie Microsoft Excel öffnen, anzeigen und bearbeiten, das jetzt sowohl für Windows- als auch für MacOS-Betriebssysteme verfügbar ist. Ebenso ist Google Sheets ein kostenloses Tool zum Erstellen und Bearbeiten von Online-Tabellen, das von jedem Webbrowser aus funktioniert. Weitere Informationen zu diesem Dateiformat[Hier](https://wiki.fileformat.com/spreadsheet/) . |
| WordProcessing | `3` | Eine Textverarbeitungsdatei. Eine Textverarbeitungsdatei enthält Benutzerinformationen im Nur-Text- oder Rich-Text-Format. Ein Nur-Text-Dateiformat enthält unformatierten Text und es können keine Schriftart- oder Seiteneinstellungen usw. angewendet werden. Im Gegensatz dazu ermöglicht ein Rich-Text-Dateiformat Formatierungsoptionen wie das Festlegen von Schriftarten, Stilen (fett, kursiv, unterstrichen usw.), Seitenränder, Überschriften, Aufzählungszeichen und Zahlen sowie mehrere andere Formatierungsfunktionen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/word-processing/) . |
| Diagram | `4` | Eine Diagrammdatei. |
| Note | `5` | Eine elektronische Notizdatei. Mit Notizprogrammen wie Microsoft OneNote können Sie Notizdateien erstellen, öffnen und bearbeiten, die Abschnitte und Seiten zum Speichern von Notizen enthalten. Ein Notizdokument kann so einfach wie ein Textdokument sein, aber auch detaillierter bestehend aus digitalen Bildern, Audio-/Videoclips und handgezeichneten Skizzen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/note-taking/) . |
| ProjectManagement | `6` | Ein Projektmanagementformat. Haben Sie sich jemals gefragt, was eine MPP-Datei ist oder wie man sie öffnet? MPP und andere ähnliche Dateien sind Projektdateiformate, die von Projektmanagementsoftware wie Microsoft Project erstellt werden. Ein Projekt Datei ist eine Sammlung von Aufgaben, Ressourcen und deren Planung, um ein messbares Ergebnis in Form eines Formulars oder eines Produkts oder einer Dienstleistung zu erzielen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/project-management/) . |
| Pdf | `7` | Eine PDF-Datei. Portable Document Format (PDF) ist ein Dokumententyp, der von Adobe in den 1990er Jahren erstellt wurde. Der Zweck dieses -Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einzuführen, einem Format, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/view/pdf/) . |
| Tiff | `8` | Ein TIFF-Bild. TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten bestimmt sind, die diesem Dateiformatstandard entsprechen. Weitere Informationen zu diesem Dateiformat [Hier](https://wiki.fileformat.com/image/tiff/) . |
| Jpeg | `9` | Ein JPEG-Bild. JPEG ist ein Bildformat, das mit der Methode der verlustbehafteten Komprimierung gespeichert wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/jpeg/) . |
| Psd | `10` | Ein PSD-Bild . Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/psd/) . |
| Jpeg2000 | `11` | Ein JPEG2000-Bild. JPEG 2000 (JPX) ist ein Bildcodierungssystem und ein hochmoderner Bildkomprimierungsstandard. Entworfen, mit Wavelet-Technologie JPEG 2000 kann verlustfreie Inhalte in jeder Qualität auf einmal codieren. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/jp2/) . |
| Gif | `12` | Ein GIF-Bild. Ein GIF oder Graphical Interchange Format ist eine Art stark komprimiertes Bild. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/gif/) . |
| Png | `13` | Ein PNG-Bild. PNG, Portable Network Graphics, bezieht sich auf ein Rasterbild-Dateiformat, das verlustfreie Komprimierung verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/png/) . |
| Bmp | `14` | Ein BMP-Bild. Dateien mit der Erweiterung .BMP stellen Bitmap-Bilddateien dar, die zum Speichern digitaler Bitmap-Bilder verwendet werden. Diese Bilder sind unabhängig vom Grafikadapter und werden auch als Device Independent Bitmap (DIB)-Datei -Format bezeichnet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/bmp/) . |
| Dicom | `15` | Ein DICOM-Bild. DICOM ist die Abkürzung für Digital Imaging and Communications in Medicine und bezieht sich auf das Gebiet der medizinischen Informatik. DICOM ist die Kombination aus Dateiformatdefinition und einem Netzwerkkommunikationsprotokoll. Erfahren Sie mehr über dieses Dateiformat[ Hier](https://wiki.fileformat.com/image/dicom/) . |
| WebP | `16` | Ein WEBP-Bild. WebP, eingeführt von Google, ist ein modernes Dateiformat für Raster-Webbilder, das auf verlustfreier und verlustbehafteter Komprimierung basiert. Es bietet die gleiche Bildqualität, während die Bildgröße erheblich reduziert wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/webp/) . |
| Emf | `17` | Ein EMF-Bild. Enhanced Metafile Format (EMF) speichert grafische Bilder geräteunabhängig. Metadateien von EMF bestehen aus Aufzeichnungen variabler Länge in chronologischer Reihenfolge, die das gespeicherte Bild nach dem Parsen auf jedem Ausgabegerät wiedergeben können. Erfahren Sie mehr darüber Datei Format[Hier](https://wiki.fileformat.com/image/emf/) . |
| Wmf | `18` | Ein WMF-Bild. Dateien mit der Erweiterung WMF stellen Microsoft Windows Metafile (WMF) zum Speichern von Bilddaten im Vektor- und Bitmap-Format dar. Um genauer zu sein, gehört WMF zur Kategorie der Vektordateiformate der Grafikdateiformate, das Gerät Independent. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/wmf/) . |
| DjVu | `19` | Eine DjVu-Datei. Es wurde von AT&amp;T Labs entwickelt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/image/djvu/) . |
| Wav | `20` | Eine WAV-Audiodatei. WAV, bekannt als WAVE (Waveform Audio File Format), ist eine Teilmenge der RIFF-Spezifikation (Resource Interchange File Format) von Microsoft zum Speichern digitaler Audiodateien. Das Format wendet keine Komprimierung auf den Bitstrom an und speichert die Audioaufnahmen mit unterschiedlichen Abtastraten und Bitraten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/audio/wav/) . |
| Mp3 | `21` | Eine MP3-Audiodatei. Dateien mit der Erweiterung MP3 sind digital codierte Dateiformate für Audiodateien, die formal auf MPEG-1 Audio Layer III oder MPEG-2 Audio Layer III basieren. Es wurde von der Moving Picture Experts Group entwickelt ( MPEG), das Layer-3-Audiokomprimierung verwendet. Weitere Informationen zu diesem Dateiformat[Hier](https://wiki.fileformat.com/audio/mp3/) . |
| Avi | `22` | Ein AVI-Video. Das AVI-Dateiformat ist ein Audio-Video-Multimedia-Containerdateiformat, das von Microsoft eingeführt wurde. Es enthält die Audio- und Videodaten, die mit mehreren Codecs (Coder/Decoder) wie Xvid und DivX erstellt und komprimiert wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/video/avi/) . |
| Flv | `23` | Ein FLV-Video. |
| Asf | `24` | Ein ASF-Video. Das Advanced Systems Format (ASF) ist ein digitaler Multimedia-Container, der hauptsächlich zum Speichern und Übertragen von Medienströmen entwickelt wurde. Microsoft Windows Media Video (WMV) ist das komprimierte Videoformat und Microsoft Windows Media Audio (WMA) ist das komprimiertes Audioformat zusammen mit zusätzlichen Metadaten im von Microsoft entwickelten ASF-Container. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/video/wmv/) . |
| Mov | `25` | Ein QuickTime-Video. Das Mov- oder QuickTime-Dateiformat ist ein von Apple entwickelter Multimedia-Container: enthält einen oder mehrere Tracks, jeder Track enthält einen bestimmten Datentyp, z. B. Video, Audio, Text usw. Das Mov-Format ist mit beiden kompatibel Windows- und Macintosh-Systeme. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/video/mov/) . |
| Matroska | `26` | Ein mit dem Matroska-Multimedia-Container codiertes Video. |
| Zip | `27` | Ein ZIP-Archiv Februar 1989 von Phil Katz für die Archivierung von Dateien und Ordnern. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/compression/zip/) . |
| VCard | `28` | Eine VCard-Datei. VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen gängigen Informationsaustauschanwendungen verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/vcf/) . |
| Epub | `29` | Ein elektronisches EPUB-Buch. Dateien mit der Erweiterung .EPUB sind ein E-Book-Dateiformat, das ein digitales Standardveröffentlichungsformat für Verleger und Verbraucher bietet. Das Format ist inzwischen so weit verbreitet, dass es von vielen E-Readern und unterstützt wird Softwareanwendungen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/ebook/epub/) . |
| OpenType | `30` | Eine OpenType-Schriftart. |
| Dxf | `31` | Eine DXF-Zeichnung (Drawing Exchange Format). DXF, Drawing Interchange Format oder Drawing Exchange Format, ist eine getaggte Datendarstellung einer AutoCAD-Zeichnungsdatei. Jedes Element in der Datei hat eine Präfix-Ganzzahl, die als Gruppencode bezeichnet wird. Lernen mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dxf/) . |
| Dwg | `32` | Eine DWG-Zeichnung. Dateien mit der Erweiterung DWG stellen proprietäre Binärdateien dar, die zum Speichern von 2D- und 3D-Konstruktionsdaten verwendet werden. Wie DXF, bei denen es sich um ASCII-Dateien handelt, stellt DWG das binäre Dateiformat für CAD-Zeichnungen (Computer Aided Design) dar. Weitere Informationen über dieses Dateiformat[Hier](https://wiki.fileformat.com/cad/dwg/) . |
| Eml | `33` | Eine EML-E-Mail-Nachricht. Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Fast alle E-Mail-Clients unterstützen dieses Dateiformat aufgrund seiner Konformität mit RFC-822 Internet Message Format Standard. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/eml/) . |
| Msg | `34` | Eine MSG-E-Mail-Nachricht. MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange zum Speichern von E-Mail-Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. Solche Nachrichten können ein oder mehrere E-Mail-Felder mit Absender, Empfänger, Betreff, Datum, und Nachrichtentext oder Kontaktinformationen, Termindetails und eine oder mehrere Aufgabenspezifikationen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://wiki.fileformat.com/email/msg/) . |
| Torrent | `35` | Eine Torrent-Datei, die Metadaten über zu verteilende Dateien und Ordner enthält. |
| Heif | `36` | Ein HEIF/HEIC-Bild. |

### Siehe auch

* namensraum [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* Montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
