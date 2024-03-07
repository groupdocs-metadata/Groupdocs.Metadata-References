---
title: FileFormat
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the recognized format of a loaded file.
type: docs
weight: 40
url: /net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

Represents the recognized format of a loaded file.

```csharp
public enum FileFormat
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Unknown | `0` | The file type is not recognized. |
| Presentation | `1` | A presentation file. You must be familiar with PPTX and PPT extension files while working with Microsoft PowerPoint. These are Presentation file formats that store collection of records to accommodate presentation data such as slides, shapes, text, animations, video, audio and embedded objects. Learn more about this file format [here](https://wiki.fileformat.com/presentation/). |
| Spreadsheet | `2` | A spreadsheet file. A spreadsheet file contains data in the form of rows and columns. You can open, view and edit such files using spreadsheet software applications such as Microsoft Excel that is now available for both Windows and MacOS operating system. Similarly, Google sheets is a free online spreadsheet creating and editing tool that works from any web browser. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/). |
| WordProcessing | `3` | A word processing file. A word processing file contains user information in plain text or rich text format. A plain text file format contains unformatted text and no font or page settings etc. can be applied. In contrast, a rich text file format allows formatting options such as setting fonts type, styles (bold, italic, underline, etc.), page margins, headings, bullets and numbers, and several other formatting features. Learn more about this file format [here](https://wiki.fileformat.com/word-processing/). |
| Diagram | `4` | A diagram file. |
| Note | `5` | An electronic note file. Note-taking programs such as Microsoft OneNote lets you create, open and edit notes files that contain sections and pages for storing notes. A note document can be as simple as a text document as well as more detailed consisting of digital images, audio/video clips, and hand sketch drawings. Learn more about this file format [here](https://wiki.fileformat.com/note-taking/). |
| ProjectManagement | `6` | A project management format. Have you ever come across and wondered what is an MPP file or how to open it? MPP and other similar files are Project file formats that are created by Project Management software such as Microsoft Project. A project file is a collection of tasks, resources, and their scheduling to get a measurable output in the form or a product or a service. Learn more about this file format [here](https://wiki.fileformat.com/project-management/). |
| Pdf | `7` | A PDF file. Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format [here](https://wiki.fileformat.com/view/pdf/). |
| Tiff | `8` | A TIFF image. TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. Learn more about this file format [here](https://wiki.fileformat.com/image/tiff/). |
| Jpeg | `9` | A JPEG image. JPEG is a type of image format that is saved using the method of lossy compression. Learn more about this file format [here](https://wiki.fileformat.com/image/jpeg/). |
| Psd | `10` | A PSD image. PSD, Photoshop Document, represents Adobe Photoshop's native file format used for graphics designing and development. PSD files may include image layers, adjustment layers, layer masks, annotations, file information, keywords and other Photoshop-specific elements. Learn more about this file format [here](https://wiki.fileformat.com/image/psd/). |
| Jpeg2000 | `11` | A Jpeg2000 image. JPEG 2000 (JPX) is an image coding system and state-of-the-art image compression standard. Designed, using wavelet technology JPEG 2000 can code lossless content in any quality at once. Learn more about this file format [here](https://wiki.fileformat.com/image/jp2/). |
| Gif | `12` | A GIF image. A GIF or Graphical Interchange Format is a type of highly compressed image. Learn more about this file format [here](https://wiki.fileformat.com/image/gif/). |
| Png | `13` | A PNG image. PNG, Portable Network Graphics, refers to a type of raster image file format that use lossless compression. Learn more about this file format [here](https://wiki.fileformat.com/image/png/). |
| Bmp | `14` | A BMP image. Files having extension .BMP represent Bitmap Image files that are used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format. Learn more about this file format [here](https://wiki.fileformat.com/image/bmp/). |
| Dicom | `15` | A DICOM image. DICOM is the acronym for Digital Imaging and Communications in Medicine and pertains to the field of Medical Informatics. DICOM is the combination of file format definition and a network communications protocol. Learn more about this file format [ here ](https://wiki.fileformat.com/image/dicom/). |
| WebP | `16` | A WEBP image. WebP, introduced by Google, is a modern raster web image file format that is based on lossless and lossy compression. It provides same image quality while considerably reducing the image size. Learn more about this file format [here](https://wiki.fileformat.com/image/webp/). |
| Emf | `17` | An EMF image. Enhanced metafile format (EMF) stores graphical images device-independently. Metafiles of EMF comprises of variable-length records in chronological order that can render the stored image after parsing on any output device. Learn more about this file format [here](https://wiki.fileformat.com/image/emf/). |
| Wmf | `18` | A WMF image. Files with WMF extension represent Microsoft Windows Metafile (WMF) for storing vector as well as bitmap-format images data. To be more accurate, WMF belongs to the vector file format category of Graphics file formats that is device independent. Learn more about this file format [here](https://wiki.fileformat.com/image/wmf/). |
| DjVu | `19` | A DjVu file. DjVu is a graphics file format intended for scanned documents and books especially those which contain the combination of text, drawings, images and photographs. It was developed by AT&amp;T Labs. Learn more about this file format [here](https://wiki.fileformat.com/image/djvu/). |
| Wav | `20` | A WAV audio file. WAV, known for WAVE (Waveform Audio File Format), is a subset of Microsoft's Resource Interchange File Format (RIFF) specification for storing digital audio files. The format doesn't apply any compression to the bitstream and stores the audio recordings with different sampling rates and bitrates. Learn more about this file format [here](https://wiki.fileformat.com/audio/wav/). |
| Mp3 | `21` | An Mp3 audio file. Files with MP3 extension are digitally encoded file formats for audio files that are formally based on the MPEG-1 Audio Layer III or MPEG-2 Audio Layer III. It was developed by the Moving Picture Experts Group (MPEG) that uses Layer 3 audio compression. Learn more about this file format [here](https://wiki.fileformat.com/audio/mp3/). |
| Avi | `22` | An AVI video. The AVI file format is an Audio Video multimedia container file format that was introduced by Microsoft. It holds the audio and video data created and compressed using several codecs (Coders/Decoders) such as Xvid and DivX. Learn more about this file format [here](https://wiki.fileformat.com/video/avi/). |
| Flv | `23` | An FLV video. |
| Asf | `24` | An ASF video. The Advanced Systems Format (ASF) is a digital multimedia container designed primarily for storing and transmitting media streams. Microsoft Windows Media Video (WMV) is the compressed video format and Microsoft Windows Media Audio (WMA) is the compressed audio format along with additional metadata in the ASF container developed by Microsoft. Learn more about this file format [here](https://wiki.fileformat.com/video/wmv/). |
| Mov | `25` | A QuickTime video. Mov or QuickTime File format is multimedia container which is developed by Apple: contains one or more tracks, each track holds a particular type of data i.e. Video, Audio, text etc. Mov format is compatible both in Windows and Macintosh systems. Learn more about this file format [here](https://wiki.fileformat.com/video/mov/). |
| Matroska | `26` | A video encoded with the Matroska multimedia container. |
| Zip | `27` | A ZIP archive. ZIP file extension represents archives that can hold one or more files or directories. The archive can have compression applied to the included files in order to reduce the ZIP file size. ZIP file format was made public back in February 1989 by Phil Katz for achieving archiving of files and folders. Learn more about this file format [here](https://wiki.fileformat.com/compression/zip/). |
| SevenZip | `28` | 7z is a compressed archive file format that supports several different data compression, encryption and pre-processing algorithms. The 7z format initially appeared as implemented by the 7-Zip archiver. The 7-Zip program is publicly available under the terms of the GNU Lesser General Public License. |
| VCard | `29` | A VCard file. VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications. Learn more about this file format [here](https://wiki.fileformat.com/email/vcf/). |
| Epub | `30` | An EPUB electronic book. Files with .EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. Learn more about this file format [here](https://wiki.fileformat.com/ebook/epub/). |
| OpenType | `31` | An OpenType font. |
| Dxf | `32` | A DXF (Drawing Exchange Format) drawing. DXF, Drawing Interchange Format, or Drawing Exchange Format, is a tagged data representation of AutoCAD drawing file. Each element in the file has a prefix integer number called a group code. Learn more about this file format [here](https://wiki.fileformat.com/cad/dxf/). |
| Dwg | `33` | A DWG drawing. Files with DWG extension represent proprietary binary files used for containing 2D and 3D design data. Like DXF, which are ASCII files, DWG represent the binary file format for CAD (Computer Aided Design) drawings. Learn more about this file format [here](https://wiki.fileformat.com/cad/dwg/). |
| Eml | `34` | An EML email message. EML file format represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. Learn more about this file format [here](https://wiki.fileformat.com/email/eml/). |
| Msg | `35` | An MSG email message. MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Such messages may contain one or more email fields, with the sender, recipient, subject, date, and message body, or contact information, appointment particulars, and one or more task specifications. Learn more about this file format [here](https://wiki.fileformat.com/email/msg/). |
| Torrent | `36` | A torrent file that contains metadata about files and folders to be distributed. |
| Heif | `37` | A HEIF/HEIC image. |
| Dng | `38` | A dng RAW image. |
| Cr2 | `39` | A CR2 image. |
| Rar | `40` | RAR is a proprietary archive file format that supports data compression, error correction and file spanning. |
| Tar | `41` | In computing, tar is a computer software utility for collecting many files into one archive file, often referred to as a tarball, for distribution or backup purposes. |
| ThreeDS | `42` | 3DS is one of the file formats used by the Autodesk 3ds Max 3D modeling, animation and rendering software. |
| Dae | `43` | A DAE file is a Digital Asset Exchange file format that is used for exchanging data between interactive 3D applications. |
| Fbx | `44` | FBX (Filmbox) is a proprietary file format (.fbx) developed by Kaydara and owned by Autodesk since 2006. It is used to provide interoperability between digital content creation applications. FBX is also part of Autodesk Gameware, a series of video game middleware. |
| Stl | `45` | STL is a file format native to the stereolithography CAD software created by 3D Systems.[3][4][5] Chuck Hull, the inventor of stereolithography and 3D Systems’ founder, reports that the file extension is an abbreviation for stereolithography. |
| Gis | `46` | Gis file. |

### See Also

* namespace [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
