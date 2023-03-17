---
title: FileFormat
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示加载文件的识别格式
type: docs
weight: 40
url: /zh/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

表示加载文件的识别格式。

```csharp
public enum FileFormat
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Unknown | `0` | 无法识别文件类型。 |
| Presentation | `1` | 演示文稿文件。 在使用 Microsoft PowerPoint 时，您必须熟悉 PPTX 和 PPT 扩展文件。 这些是演示文稿文件格式，用于存储记录集合以容纳演示文稿数据，例如幻灯片、形状、 文本、动画、视频、音频和嵌入对象。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/presentation/). |
| Spreadsheet | `2` | 电子表格文件。 电子表格文件包含行和列形式的数据。 您可以使用电子表格软件应用程序（例如现在可用于 Windows 和 MacOS 操作系统的 Microsoft Excel）打开、查看和编辑此类文件。 同样，Google 表格是一种免费的在线电子表格创建和编辑工具，可在任何网络浏览器中使用。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/). |
| WordProcessing | `3` | 文字处理文件。 文字处理文件包含纯文本或富文本格式的用户信息。纯文本文件 format 包含未格式化的文本，无法应用字体或页面设置等。 相反，富文本文件格式允许设置字体类型、样式（粗体、斜体、下划线等）等格式选项， 页边距、标题、项目符号和编号以及其他几种格式设置功能。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/word-processing/). |
| Diagram | `4` | 图表文件. |
| Note | `5` | 电子笔记文件。 Microsoft OneNote 等笔记记录程序可让您创建、打开和编辑包含用于存储笔记的部分和页面的笔记文件。 笔记文档可以像文本文档一样简单，也可以更详细由数字图像、音频/视频剪辑和手绘草图组成。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/note-taking/). |
| ProjectManagement | `6` | 一种项目管理格式。 您是否遇到过并想知道什么是 MPP 文件或如何打开它？ MPP 和其他类似文件是由 Microsoft Project 等项目管理软件创建的项目文件格式。 一个项目文件是任务、资源及其调度的集合，以获取形式或产品或服务的可测量输出。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/project-management/). |
| Pdf | `7` | PDF 文件。 便携式文档格式 (PDF) 是 Adobe 在 1990 年代创建的一种文档。 this 文件格式的目的是在 中引入文档和其他参考资料的表示标准，这是一种独立于应用程序软件、硬件和操作系统的格式。了解有关此文件格式的更多信息 [这里](https://wiki.fileformat.com/view/pdf/). |
| Tiff | `8` | TIFF 图像。 TIFF 或 TIF，标记图像文件格式，表示用于各种 符合此文件格式标准的设备的光栅图像。详细了解此文件格式 [这里](https://wiki.fileformat.com/image/tiff/). |
| Jpeg | `9` | JPEG 图像。 JPEG 是一种使用有损压缩方法保存的图像格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/jpeg/). |
| Psd | `10` | PSD 图像。 PSD，Photoshop 文档，代表 Adobe Photoshop 用于图形设计和开发的本机文件格式。 PSD 文件可能包括图像图层、调整图层、图层蒙版、注释、文件信息、关键字和其他 Photoshop 特定元素. 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/psd/). |
| Jpeg2000 | `11` | Jpeg2000 图像。 JPEG 2000 (JPX) 是图像编码系统和最先进的图像压缩标准。 使用小波技术设计的 JPEG 2000 可以一次对任何质量的无损内容进行编码。详细了解 此文件格式[这里](https://wiki.fileformat.com/image/jp2/). |
| Gif | `12` | GIF 图像。 GIF 或图形交换格式是一种高度压缩的图像。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/gif/). |
| Png | `13` | PNG 图像。 PNG，便携式网络图形，指的是一种使用无损压缩的光栅图像文件格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/png/). |
| Bmp | `14` | BMP 图像。 扩展名为 .BMP 的文件表示用于存储位图数字图像的位图图像文件。 这些图像独立于图形适配器，也称为设备独立位图 (DIB) 文件 格式。了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/bmp/). |
| Dicom | `15` | DICOM 图像。 DICOM 是医学数字成像和通信的首字母缩写词，属于医学信息学领域。 DICOM 是文件格式定义和网络通信协议的组合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/dicom/). |
| WebP | `16` | WEBP 图像。 WebP，由谷歌推出，是一种基于无损和 有损压缩的现代光栅网络图像文件格式。它提供相同的图像质量，同时显着减小图像大小。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/webp/). |
| Emf | `17` | EMF 图像。 增强型图元文件格式 (EMF) 独立于设备存储图形图像。 EMF 的图元文件包含按时间顺序排列的可变长度记录，可以在任何输出设备上解析后呈现存储的图像。 了解更多信息文件格式[这里](https://wiki.fileformat.com/image/emf/). |
| Wmf | `18` | WMF 图像。 具有 WMF 扩展名的文件表示用于存储矢量以及位图格式图像数据的 Microsoft Windows 图元文件 (WMF)。 更准确地说，WMF 属于图形文件格式的矢量文件格式类别，即设备independent. 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/wmf/). |
| DjVu | `19` | DjVu 文件。 DjVu 是一种图形文件格式，适用于扫描的文档和书籍，尤其是那些包含文本、 绘图、图像和照片的组合。它由 AT&amp;T 实验室开发。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/image/djvu/). |
| Wav | `20` | WAV 音频文件。 WAV，以 WAVE（波形音频文件格式）而闻名，是 Microsoft 用于存储数字音频文件的资源交换文件格式 (RIFF) 规范的子集。 该格式不对比特流应用任何压缩并存储具有不同采样率和比特率的录音。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/audio/wav/). |
| Mp3 | `21` | 一个 Mp3 音频文件。 具有 MP3 扩展名的文件是正式基于 MPEG-1 音频第三层或 MPEG-2 音频第三层的音频文件的数字编码文件格式。 它由运动图像专家组开发（使用第 3 层音频压缩的 MPEG）。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/audio/mp3/). |
| Avi | `22` | 一个 AVI 视频。 AVI 文件格式是 Microsoft 引入的音频视频多媒体容器文件格式。 它保存使用 Xvid 和 DivX 等多种编解码器（编码器/解码器）创建和压缩的音频和视频数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/video/avi/). |
| Flv | `23` | FLV 视频。 |
| Asf | `24` | ASF 视频。 高级系统格式 (ASF) 是一种数字多媒体容器，主要用于存储和传输媒体流。 Microsoft Windows Media Video (WMV) 是压缩视频格式，Microsoft Windows Media Audio (WMA) 是压缩音频格式 以及 Microsoft 开发的 ASF 容器中的其他元数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/video/wmv/). |
| Mov | `25` | QuickTime 视频。 Mov 或 QuickTime 文件格式是由 Apple 开发的多媒体容器：包含一个或多个轨道， 每个轨道包含特定类型的数据，即视频、音频、文本等。 Mov 格式兼容Windows 和 Macintosh 系统。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/video/mov/). |
| Matroska | `26` | 使用 Matroska 多媒体容器编码的视频。 |
| Zip | `27` | 一个 ZIP 存档。 ZIP 文件扩展名表示可以保存一个或多个文件或目录的存档。 存档可以对包含的文件应用压缩以减小 ZIP 文件大小。 ZIP 文件格式已于Phil Katz 于 1989 年 2 月实现了文件和文件夹的归档。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/compression/zip/). |
| VCard | `28` | VCard 文件。 VCF（虚拟卡格式）或 vCard 是一种用于存储联系人信息的数字文件格式。 该格式广泛用于流行信息交换应用程序之间的数据交换。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/vcf/). |
| Epub | `29` | 一本 EPUB 电子书。 扩展名为 .EPUB 的文件是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。 该格式现在非常普遍，许多电子阅读器都支持它，并且software applications. 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/ebook/epub/). |
| OpenType | `30` | OpenType 字体。 |
| Dxf | `31` | DXF（绘图交换格式）绘图。 DXF，绘图交换格式，或绘图交换格式，是 AutoCAD 绘图文件的标记数据表示。 文件中的每个元素都有一个称为组代码的前缀整数。 学习有关此文件格式的更多信息[这里](https://wiki.fileformat.com/cad/dxf/). |
| Dwg | `32` | DWG 工程图。 具有 DWG 扩展名的文件表示用于包含 2D 和 3D 设计数据的专有二进制文件。 与 DXF 一样，它们是 ASCII 文件，DWG 表示 CAD（计算机辅助设计）工程图的二进制文件格式。 了解更多关于这种文件格式[这里](https://wiki.fileformat.com/cad/dwg/). |
| Eml | `33` | EML 电子邮件。 EML 文件格式表示使用 Outlook 和其他相关应用程序保存的电子邮件。 几乎所有电子邮件客户端都支持此文件格式，因为它符合 RFC-822 Internet 邮件格式标准。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/eml/). |
| Msg | `34` | MSG 电子邮件消息。 MSG 是 Microsoft Outlook 和 Exchange 用于存储电子邮件消息、联系人、约会或其他任务的一种文件格式。 此类消息可能包含一个或多个电子邮件字段，包括发件人、收件人、主题、日期、 和消息正文，或联系信息、约会详情和一项或多项任务规范。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/email/msg/). |
| Torrent | `35` | 包含有关要分发的文件和文件夹的元数据的 torrent 文件。 |
| Heif | `36` | HEIF/HEIC 图像。 |

### 也可以看看

* 命名空间 [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
