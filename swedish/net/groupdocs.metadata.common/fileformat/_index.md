---
title: FileFormat
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar det igenkända formatet för en laddad fil.
type: docs
weight: 40
url: /sv/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

Representerar det igenkända formatet för en laddad fil.

```csharp
public enum FileFormat
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Unknown | `0` | Filtypen känns inte igen. |
| Presentation | `1` | En presentationsfil. Du måste vara bekant med PPTX- och PPT-tilläggsfiler när du arbetar med Microsoft PowerPoint. Dessa är presentationsfilformat som lagrar samling av poster för att ta emot presentationsdata som bilder, former, text, animationer, video, ljud och inbäddade objekt. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/) . |
| Spreadsheet | `2` | En kalkylarksfil. En kalkylarksfil innehåller data i form av rader och kolumner. Du kan öppna, visa och redigera sådana filer med hjälp av kalkylarksprogram som Microsoft Excel som nu är tillgängligt för både Windows och MacOS operativsystem. På samma sätt är Google Sheets ett gratis onlineverktyg för att skapa och redigera kalkylark som fungerar från alla webbläsare. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/) . |
| WordProcessing | `3` | En ordbehandlingsfil. En ordbehandlingsfil innehåller användarinformation i vanlig text eller RTF-format. En vanlig textfil format innehåller oformaterad text och inga teckensnitt eller sidinställningar etc. kan tillämpas. Däremot tillåter ett filformat med rik text formateringsalternativ som att ställa in typsnittstyp, stilar (fet, kursiv, understruken, etc.), sidmarginaler, rubriker, punkter och siffror och flera andra formateringsfunktioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/) . |
| Diagram | `4` | En diagramfil. |
| Note | `5` | En elektronisk anteckningsfil. Anteckningsprogram som Microsoft OneNote låter dig skapa, öppna och redigera anteckningsfiler som innehåller avsnitt och sidor för lagring av anteckningar. Ett anteckningsdokument kan vara lika enkelt som ett textdokument och mer detaljerat bestående av digitala bilder, ljud/videoklipp och handskisser. Lär dig mer om detta filformat[här](https://wiki.fileformat.com/note-taking/) . |
| ProjectManagement | `6` | Ett projektledningsformat. Har du någonsin stött på och undrat vad en MPP-fil är eller hur man öppnar den? MPP och andra liknande filer är Project-filformat som skapas av Project Management-programvara som Microsoft Project. Ett projekt fil är en samling av uppgifter, resurser och deras schemaläggning för att få en mätbar utdata i formen eller en produkt eller en tjänst. Läs mer om detta filformat[här](https://wiki.fileformat.com/project-management/) . |
| Pdf | `7` | En PDF-fil. Portable Document Format (PDF) är en typ av dokument som skapades av Adobe redan på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. Läs mer om detta filformat[här](https://wiki.fileformat.com/view/pdf/) . |
| Tiff | `8` | En TIFF-bild. TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd av enheter som överensstämmer med denna filformatstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff/) . |
| Jpeg | `9` | En JPEG-bild. JPEG är en typ av bildformat som sparas med metoden för förlustkomprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg/) . |
| Psd | `10` | En PSD-bild. PSD, Photoshop Document, representerar Adobe Photoshops ursprungliga filformat som används för grafisk design och utveckling. PSD-filer kan innehålla bildlager, justeringslager, lagermasker, anteckningar, filinformation, nyckelord och andra Photoshop-specifika element . Läs mer om detta filformat[här](https://wiki.fileformat.com/image/psd/) . |
| Jpeg2000 | `11` | En Jpeg2000-bild. JPEG 2000 (JPX) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad, med hjälp av wavelet-teknik JPEG 2000 kan koda förlustfritt innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jp2/) . |
| Gif | `12` | En GIF-bild. En GIF eller Graphical Interchange Format är en typ av mycket komprimerad bild. Läs mer om det här filformatet[här](https://wiki.fileformat.com/image/gif/) . |
| Png | `13` | En PNG-bild. PNG, Portable Network Graphics, hänvisar till en typ av rasterbildsfilformat som använder förlustfri komprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/png/) . |
| Bmp | `14` | En BMP-bild. Filer med filtillägget .BMP representerar bitmappsbildfiler som används för att lagra digitala bitmappsbilder. Dessa bilder är oberoende av grafikkortet och kallas även enhetsoberoende bitmappsformat (DIB) file . Läs mer om detta filformat[här](https://wiki.fileformat.com/image/bmp/) . |
| Dicom | `15` | En DICOM-bild. DICOM är förkortningen för Digital Imaging and Communications in Medicine och hänför sig till området medicinsk informatik. DICOM är kombinationen av filformatsdefinition och ett nätverkskommunikationsprotokoll. Läs mer om detta filformat[ här](https://wiki.fileformat.com/image/dicom/) . |
| WebP | `16` | En WEBP-bild. WebP, introducerad av Google, är ett modernt rasterwebbbildsfilformat som är baserat på förlustfri och förlustfri komprimering. Den ger samma bildkvalitet samtidigt som den minskar bildstorleken avsevärt. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/webp/) . |
| Emf | `17` | En EMF-bild. Enhanced metafile format (EMF) lagrar grafiska bilder enhetsoberoende. Metafiler av EMF består av poster med variabel längd i kronologisk ordning som kan återge den lagrade bilden efter analys på valfri utenhet. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/emf/) . |
| Wmf | `18` | En WMF-bild. Filer med WMF-tillägget representerar Microsoft Windows Metafile (WMF) för lagring av vektor- och bitmappsbilddata. För att vara mer exakt tillhör WMF kategorin vektorfilformat för grafikfilformat som är enhet independent. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/wmf/) . |
| DjVu | `19` | En DjVu-fil. DjVu är ett grafikfilformat avsett för skannade dokument och böcker, särskilt de som innehåller en kombination av text, teckningar, bilder och fotografier. Det har utvecklats av AT&amp;T Labs. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/djvu/) . |
| Wav | `20` | En WAV-ljudfil. WAV, känd för WAVE (Waveform Audio File Format), är en delmängd av Microsofts RIFF-specifikation (Resource Interchange File Format) för lagring av digitala ljudfiler. Formatet tillämpar ingen komprimering på bitströmmen och lagrar ljudinspelningarna med olika samplingshastigheter och bithastigheter. Läs mer om detta filformat[här](https://wiki.fileformat.com/audio/wav/) . |
| Mp3 | `21` | En mp3-ljudfil. Filer med MP3-tillägg är digitalt kodade filformat för ljudfiler som formellt är baserade på MPEG-1 Audio Layer III eller MPEG-2 Audio Layer III. Det utvecklades av Moving Picture Experts Group ( MPEG) som använder Layer 3-ljudkomprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/audio/mp3/) . |
| Avi | `22` | En AVI-video. AVI-filformatet är ett audiovideo-multimediacontainerfilformat som introducerades av Microsoft. Det innehåller ljud- och videodata som skapats och komprimerats med hjälp av flera codecs (kodrar/avkodare) som Xvid och DivX. Läs mer om detta filformat[här](https://wiki.fileformat.com/video/avi/) . |
| Flv | `23` | En FLV-video. |
| Asf | `24` | En ASF-video. Advanced Systems Format (ASF) är en digital multimediabehållare designad främst för att lagra och överföra mediaströmmar. Microsoft Windows Media Video (WMV) är det komprimerade videoformatet och Microsoft Windows Media Audio (WMA) är komprimerat ljud format tillsammans med ytterligare metadata i ASF-behållaren utvecklad av Microsoft. Läs mer om detta filformat[här](https://wiki.fileformat.com/video/wmv/) . |
| Mov | `25` | En QuickTime-video. Mov- eller QuickTime-filformat är en multimediabehållare som utvecklats av Apple: innehåller ett eller flera spår, varje spår innehåller en viss typ av data, dvs. video, ljud, text etc. Mov-formatet är kompatibelt både i Windows- och Macintosh-system. Läs mer om detta filformat[här](https://wiki.fileformat.com/video/mov/) . |
| Matroska | `26` | En video kodad med Matroska multimediabehållare. |
| Zip | `27` | Ett ZIP-arkiv. ZIP-filtillägget representerar arkiv som kan innehålla en eller flera filer eller kataloger. Arkivet kan ha komprimering på de inkluderade filerna för att minska ZIP-filstorleken. ZIP-filformatet gjordes offentligt tillbaka i Februari 1989 av Phil Katz för att uppnå arkivering av filer och mappar. Lär dig mer om detta filformat[här](https://wiki.fileformat.com/compression/zip/) . |
| VCard | `28` | En VCard-fil. VCF (Virtual Card Format) eller vCard är ett digitalt filformat för att lagra kontaktinformation. Formatet används ofta för datautbyte bland populära program för informationsutbyte. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/vcf/) . |
| Epub | `29` | En EPUB elektronisk bok. Filer med filtillägget .EPUB är ett e-boksfilformat som tillhandahåller ett standard digitalt publiceringsformat för förlag och konsumenter. Formatet har varit så vanligt vid det här laget att det stöds av många e-läsare och program. Läs mer om detta filformat[här](https://wiki.fileformat.com/ebook/epub/) . |
| OpenType | `30` | Ett OpenType-teckensnitt. |
| Dxf | `31` | En DXF (Drawing Exchange Format)-ritning. DXF, Drawing Interchange Format eller Drawing Exchange Format, är en taggad datarepresentation av AutoCAD-ritningsfil. Varje element i filen har ett prefix heltal som kallas en gruppkod. Lär dig mer om detta filformat[här](https://wiki.fileformat.com/cad/dxf/) . |
| Dwg | `32` | En DWG-ritning. Filer med DWG-tillägg representerar proprietära binära filer som används för att innehålla 2D- och 3D-designdata. Liksom DXF, som är ASCII-filer, representerar DWG det binära filformatet för CAD (Computer Aided Design)-ritningar._x000 om detta filformat[här](https://wiki.fileformat.com/cad/dwg/) . |
| Eml | `33` | Ett EML-e-postmeddelande. EML-filformat representerar e-postmeddelanden som sparats med Outlook och andra relevanta applikationer. Nästan alla e-postklienter stöder detta filformat för dess överensstämmelse med RFC-822 Internet Message Format Standard. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/eml/) . |
| Msg | `34` | Ett MSG-e-postmeddelande. MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter. Sådana meddelanden kan innehålla ett eller flera e-postfält, med avsändaren, mottagaren, ämne, datum, och meddelandetext, eller kontaktinformation, mötesuppgifter och en eller flera uppgiftsspecifikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/msg/) . |
| Torrent | `35` | En torrentfil som innehåller metadata om filer och mappar som ska distribueras. |
| Heif | `36` | En HEIF/HEIC-bild. |

### Se även

* namnutrymme [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
