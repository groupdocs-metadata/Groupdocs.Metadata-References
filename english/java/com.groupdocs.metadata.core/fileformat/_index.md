---
title: FileFormat
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the recognized format of a loaded file.
type: docs
weight: 361
url: /java/com.groupdocs.metadata.core/fileformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum FileFormat extends Enum<FileFormat> implements IEnumValue
```

Represents the recognized format of a loaded file.
## Fields

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | The file type is not recognized. |
| [Presentation](#Presentation) | A presentation file. |
| [Spreadsheet](#Spreadsheet) | A spreadsheet file. |
| [WordProcessing](#WordProcessing) | A word processing file. |
| [Diagram](#Diagram) | A diagram file. |
| [Note](#Note) | An electronic note file. |
| [ProjectManagement](#ProjectManagement) | A project management format. |
| [Pdf](#Pdf) | A PDF file. |
| [Tiff](#Tiff) | A TIFF image. |
| [Jpeg](#Jpeg) | A JPEG image. |
| [Psd](#Psd) | A PSD image. |
| [Jpeg2000](#Jpeg2000) | A Jpeg2000 image. |
| [Gif](#Gif) | A GIF image. |
| [Png](#Png) | A PNG image. |
| [Bmp](#Bmp) | A BMP image. |
| [Dicom](#Dicom) | A DICOM image. |
| [WebP](#WebP) | A WEBP image. |
| [Emf](#Emf) | An EMF image. |
| [Wmf](#Wmf) | A WMF image. |
| [DjVu](#DjVu) | A DjVu file. |
| [Wav](#Wav) | A WAV audio file. |
| [Mp3](#Mp3) | An Mp3 audio file. |
| [Avi](#Avi) | An AVI video. |
| [Flv](#Flv) | An FLV video. |
| [Asf](#Asf) | An ASF video. |
| [Mov](#Mov) | A QuickTime video. |
| [Matroska](#Matroska) | A video encoded with the Matroska multimedia container. |
| [Zip](#Zip) | A ZIP archive. |
| [VCard](#VCard) | A VCard file. |
| [Epub](#Epub) | An EPUB electronic book. |
| [OpenType](#OpenType) | An OpenType font. |
| [Dxf](#Dxf) | A DXF (Drawing Exchange Format) drawing. |
| [Dwg](#Dwg) | A DWG drawing. |
| [Eml](#Eml) | An EML email message. |
| [Msg](#Msg) | An MSG email message. |
| [Torrent](#Torrent) | A torrent file that contains metadata about files and folders to be distributed. |
| [Heif](#Heif) | A HEIF/HEIC image. |
| [Dng](#Dng) | A dng RAW image. |
| [Cr2](#Cr2) | A CR2 image. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
### Unknown {#Unknown}
```
public static final FileFormat Unknown
```


The file type is not recognized.

### Presentation {#Presentation}
```
public static final FileFormat Presentation
```


A presentation file. You must be familiar with PPTX and PPT extension files while working with Microsoft PowerPoint. These are Presentation file formats that store collection of records to accommodate presentation data such as slides, shapes, text, animations, video, audio and embedded objects. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/

### Spreadsheet {#Spreadsheet}
```
public static final FileFormat Spreadsheet
```


A spreadsheet file. A spreadsheet file contains data in the form of rows and columns. You can open, view and edit such files using spreadsheet software applications such as Microsoft Excel that is now available for both Windows and MacOS operating system. Similarly, Google sheets is a free online spreadsheet creating and editing tool that works from any web browser. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/spreadsheet/

### WordProcessing {#WordProcessing}
```
public static final FileFormat WordProcessing
```


A word processing file. A word processing file contains user information in plain text or rich text format. A plain text file format contains unformatted text and no font or page settings etc. can be applied. In contrast, a rich text file format allows formatting options such as setting fonts type, styles (bold, italic, underline, etc.), page margins, headings, bullets and numbers, and several other formatting features. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/word-processing/

### Diagram {#Diagram}
```
public static final FileFormat Diagram
```


A diagram file.

### Note {#Note}
```
public static final FileFormat Note
```


An electronic note file. Note-taking programs such as Microsoft OneNote lets you create, open and edit notes files that contain sections and pages for storing notes. A note document can be as simple as a text document as well as more detailed consisting of digital images, audio/video clips, and hand sketch drawings. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/note-taking/

### ProjectManagement {#ProjectManagement}
```
public static final FileFormat ProjectManagement
```


A project management format. Have you ever come across and wondered what is an MPP file or how to open it? MPP and other similar files are Project file formats that are created by Project Management software such as Microsoft Project. A project file is a collection of tasks, resources, and their scheduling to get a measurable output in the form or a product or a service. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/project-management/

### Pdf {#Pdf}
```
public static final FileFormat Pdf
```


A PDF file. Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/view/pdf/

### Tiff {#Tiff}
```
public static final FileFormat Tiff
```


A TIFF image. TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/tiff/

### Jpeg {#Jpeg}
```
public static final FileFormat Jpeg
```


A JPEG image. JPEG is a type of image format that is saved using the method of lossy compression. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/jpeg/

### Psd {#Psd}
```
public static final FileFormat Psd
```


A PSD image. PSD, Photoshop Document, represents Adobe Photoshop's native file format used for graphics designing and development. PSD files may include image layers, adjustment layers, layer masks, annotations, file information, keywords and other Photoshop-specific elements. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/psd/

### Jpeg2000 {#Jpeg2000}
```
public static final FileFormat Jpeg2000
```


A Jpeg2000 image. JPEG 2000 (JPX) is an image coding system and state-of-the-art image compression standard. Designed, using wavelet technology JPEG 2000 can code lossless content in any quality at once. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/jp2/

### Gif {#Gif}
```
public static final FileFormat Gif
```


A GIF image. A GIF or Graphical Interchange Format is a type of highly compressed image. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/gif/

### Png {#Png}
```
public static final FileFormat Png
```


A PNG image. PNG, Portable Network Graphics, refers to a type of raster image file format that use lossless compression. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/png/

### Bmp {#Bmp}
```
public static final FileFormat Bmp
```


A BMP image. Files having extension .BMP represent Bitmap Image files that are used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/bmp/

### Dicom {#Dicom}
```
public static final FileFormat Dicom
```


A DICOM image. DICOM is the acronym for Digital Imaging and Communications in Medicine and pertains to the field of Medical Informatics. DICOM is the combination of file format definition and a network communications protocol. Learn more about this file format  [ here ][here] .


[here]: https://wiki.fileformat.com/image/dicom/

### WebP {#WebP}
```
public static final FileFormat WebP
```


A WEBP image. WebP, introduced by Google, is a modern raster web image file format that is based on lossless and lossy compression. It provides same image quality while considerably reducing the image size. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/webp/

### Emf {#Emf}
```
public static final FileFormat Emf
```


An EMF image. Enhanced metafile format (EMF) stores graphical images device-independently. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/emf/

### Wmf {#Wmf}
```
public static final FileFormat Wmf
```


A WMF image. Files with WMF extension represent Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format images data. To be more accurate, WMF belongs to the vector file format category of Graphics file formats that is device independent. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/wmf/

### DjVu {#DjVu}
```
public static final FileFormat DjVu
```


A DjVu file. DjVu is a graphics file format intended for scanned documents and books especially those which contain the combination of text, drawings, images and photographs. It was developed by AT&T Labs. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/djvu/

### Wav {#Wav}
```
public static final FileFormat Wav
```


A WAV audio file. WAV, known for WAVE (Waveform Audio File Format), is a subset of Microsoft's Resource Interchange File Format (RIFF) specification for storing digital audio files. The format doesn't apply any compression to the bitstream and stores the audio recordings with different sampling rates and bitrates. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/audio/wav/

### Mp3 {#Mp3}
```
public static final FileFormat Mp3
```


An Mp3 audio file. Files with MP3 extension are digitally encoded file formats for audio files that are formally based on the MPEG-1 Audio Layer III or MPEG-2 Audio Layer III. It was developed by the Moving Picture Experts Group (MPEG) that uses Layer 3 audio compression. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/audio/mp3/

### Avi {#Avi}
```
public static final FileFormat Avi
```


An AVI video. The AVI file format is an Audio Video multimedia container file format that was introduced by Microsoft. It holds the audio and video data created and compressed using several codecs (Coders/Decoders) such as Xvid and DivX. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/video/avi/

### Flv {#Flv}
```
public static final FileFormat Flv
```


An FLV video.

### Asf {#Asf}
```
public static final FileFormat Asf
```


An ASF video. The Advanced Systems Format (ASF) is a digital multimedia container designed primarily for storing and transmitting media streams. Microsoft Windows Media Video (WMV) is the compressed video format and Microsoft Windows Media Audio (WMA) is the compressed audio format along with additional metadata in the ASF container developed by Microsoft. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/video/wmv/

### Mov {#Mov}
```
public static final FileFormat Mov
```


A QuickTime video. Mov or QuickTime File format is multimedia container which is developed by Apple: contains one or more tracks, each track holds a particular type of data i.e. Video, Audio, text etc. Mov format is compatible both in Windows and Macintosh systems. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/video/mov/

### Matroska {#Matroska}
```
public static final FileFormat Matroska
```


A video encoded with the Matroska multimedia container.

### Zip {#Zip}
```
public static final FileFormat Zip
```


A ZIP archive. ZIP file extension represents archives that can hold one or more files or directories. The archive can have compression applied to the included files in order to reduce the ZIP file size. ZIP file format was made public back in February 1989 by Phil Katz for achieving archiving of files and folders. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/compression/zip/

### VCard {#VCard}
```
public static final FileFormat VCard
```


A VCard file. VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/email/vcf/

### Epub {#Epub}
```
public static final FileFormat Epub
```


An EPUB electronic book. Files with .EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/ebook/epub/

### OpenType {#OpenType}
```
public static final FileFormat OpenType
```


An OpenType font.

### Dxf {#Dxf}
```
public static final FileFormat Dxf
```


A DXF (Drawing Exchange Format) drawing. DXF, Drawing Interchange Format, or Drawing Exchange Format, is a tagged data representation of AutoCAD drawing file. Each element in the file has a prefix integer number called a group code. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/cad/dxf/

### Dwg {#Dwg}
```
public static final FileFormat Dwg
```


A DWG drawing. Files with DWG extension represent proprietary binary files used for containing 2D and 3D design data. Like DXF, which are ASCII files, DWG represent the binary file format for CAD (Computer Aided Design) drawings. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/cad/dwg/

### Eml {#Eml}
```
public static final FileFormat Eml
```


An EML email message. EML file format represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/email/eml/

### Msg {#Msg}
```
public static final FileFormat Msg
```


An MSG email message. MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Such messages may contain one or more email fields, with the sender, recipient, subject, date, and message body, or contact information, appointment particulars, and one or more task specifications. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/email/msg/

### Torrent {#Torrent}
```
public static final FileFormat Torrent
```


A torrent file that contains metadata about files and folders to be distributed.

### Heif {#Heif}
```
public static final FileFormat Heif
```


A HEIF/HEIC image.

### Dng {#Dng}
```
public static final FileFormat Dng
```


A dng RAW image.

### Cr2 {#Cr2}
```
public static final FileFormat Cr2
```


A CR2 image.

### values() {#values--}
```
public static FileFormat[] values()
```




**Returns:**
com.groupdocs.metadata.core.FileFormat[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileFormat valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[FileFormat](../../com.groupdocs.metadata.core/fileformat)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static FileFormat getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[FileFormat](../../com.groupdocs.metadata.core/fileformat)
### getFirst() {#getFirst--}
```
public static IEnumValue getFirst()
```




**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getAllValues() {#getAllValues--}
```
public Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[]
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getRawValueType() {#getRawValueType--}
```
public RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype)
### getRawValue() {#getRawValue--}
```
public int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int
