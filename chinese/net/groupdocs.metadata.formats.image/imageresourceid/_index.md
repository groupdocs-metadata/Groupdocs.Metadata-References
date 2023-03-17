---
title: ImageResourceID
second_title: GroupDocs.Metadata for .NET API 参考
description: 图像资源标准 ID 号并非所有文件格式都使用所有 ID一些信息可能存储在文件的其他部分
type: docs
weight: 1750
url: /zh/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

图像资源标准 ID 号。并非所有文件格式都使用所有 ID。一些信息可能存储在文件的其他部分。

```csharp
public enum ImageResourceID
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo 结构。请参阅 Photoshop API 指南 PDF 文档中的附录 A. |
| NamesOfAlphaChannels | `1006` | alpha 通道的名称作为一系列 Pascal 字符串。 |
| Caption | `1008` | 作为 Pascal 字符串的标题。 |
| BorderInformation | `1009` | 边界信息。 包含边框宽度的固定数字（2 字节实数，2 字节小数）， 和边框单位的 2 字节（1 = 英寸，2 = 厘米，3 = 点，4 = 派卡，5 = 列）。 |
| BackgroundColor | `1010` | 背景颜色. [查看更多。](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | 打印标志。 一系列单字节布尔值（参见页面设置对话框）： 标签、裁切标记、颜色条、注册标记、负片、翻转、插值、标题、打印标志。 |
| Grayscale | `1012` | 灰度和多通道半色调信息。 |
| ColorHalftoning | `1013` | 颜色半色调信息。 |
| DuotoneHalftoning | `1014` | 双色调半色调信息。 |
| GrayscaleFunction | `1015` | 灰度和多通道传递函数. |
| ColorTransferFunctions | `1016` | 颜色传递函数. |
| DuotoneTransferFunctions | `1017` | 双色调传递函数. |
| DuotoneImageInformation | `1018` | 双色调图像信息。 |
| EPSOptions | `1021` | EPS 选项。 |
| QuickMaskInformation | `1022` | 快速蒙版信息。 2 个字节包含 Quick Mask 通道 ID； 1 字节布尔值，指示掩码最初是否为空。 |
| LayerStateInformation | `1024` | 层状态信息。 2 个字节包含目标层的索引（0 = 底层）. |
| WorkingPath | `1025` | 工作路径（未保存）。请参见路径资源格式。 |
| LayersGroupInformation | `1026` | 层组信息。 每层 2 个字节，包含拖动组的组 ID。组中的图层具有相同的组 ID. |
| Iptc | `1028` | IPTC-NAA 记录。包含文件信息...信息。参见Documentation文件夹的IPTC文件夹中的文档。 |
| ImageModeForRawFormat | `1029` | 原始格式文件的图像模式。 |
| JpegQuality | `1030` | JPEG 质量。私人. |
| GridAndGuidesInfoPhotoshop4 | `1032` | 网格和指南信息。 |
| ThumbnailResourcePhotoshop4 | `1033` | 仅适用于 Photoshop 4.0 的缩略图资源。 |
| CopyrightFlagPhotoshop4 | `1034` | 版权标志。指示图像是否受版权保护的布尔值。可以通过属性套件或由用户在文件信息中设置... |
| UrlPhotoshop4 | `1035` | 网址。具有统一资源定位器的文本字符串句柄。可以通过属性套件或由用户在文件信息中设置... |
| ThumbnailResourcePhotoshop5 | `1036` | 缩略图资源（取代资源 1033）。请参见缩略图资源格式。 |
| GlobalAnglePhotoshop5 | `1037` | 全局角度。 4个字节，包含0到359之间的整数，这是效果层的全局光照角度。如果不存在，则假定为 30. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC 配置文件。 ICC（国际色彩联盟）格式配置文件的原始字节。请参阅 Documentation 文件夹中的 ICC1v42_2006-05.pdf 和 Sample Code\Common\Includes. 中的 icProfileHeader.h |
| WatermarkPhotoshop5 | `1040` | 水印。一个字节. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC 未标记配置文件。 1 个字节，用于在打开文件时禁用任何假设的配置文件处理。 1 = 故意未标记. |
| TransparencyIndexPhotoshop6 | `1047` | 透明度指数。 2 个字节用于透明颜色的索引，如果有的话。 |
| GlobalAltitudePhotoshop6 | `1049` | 全球海拔高度。海拔高度的 4 字节条目. |
| SlicesPhotoshop6 | `1050` | 切片 (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | 工作流 URL。 Unicode 字符串。 Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | 字母标识符。 4 个字节的长度，后跟每个 alpha 标识符各 4 个字节。 |
| UrlListPhotoshop6 | `1054` | URL 内部列表。 4 字节的 URL 计数，后跟 4 字节长、4 字节 ID 和每个计数的 Unicode 字符串。 |
| VersionInfoPhotoshop6 | `1057` | 版本信息。 4字节版本，1字节 hasRealMergedData ，Unicode字符串：作者姓名，Unicode字符串：读者姓名，4字节文件版本. |
| ExifData1Photoshop7 | `1058` | EXIF 数据 1,[查看更多](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf). |
| ExifData3Photoshop7 | `1059` | [EXIF 数据 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP 元数据。文件信息作为 XML 描述，[查看更多](http://www.adobe.com/devnet/xmp). |
| CaptionDigestPhotoshop7 | `1061` | 字幕摘要。 16 字节：RSA 数据安全，MD5 消息摘要算法. |
| PrintScalePhotoshop7 | `1062` | 打印比例。 2 字节样式（0 = 居中，1 = 大小适合，2 = 用户定义）。 4 字节 x 位置（浮点数）。 4 字节 y 位置（浮点数）。 4 字节标度（浮点数）. |
| PixelAspectRatio | `1064` | 像素纵横比。 4 字节（version = 1 或 2），8 字节双精度，x / y 像素。 版本 2，试图更正 NTSC 和 PAL 的值，之前关闭了大约一个因子。 5%. |
| LayerComps | `1065` | 图层合成。 4 个字节（描述符版本 = 16），Descriptor. |
| LayerSelectionIds | `1069` | 图层选择 ID。 2 字节计数，每次计数重复以下内容：4 字节层 ID. |
| PrintInfoCS2 | `1071` | 打印信息 (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | 层组启用 ID。 文档中每一层 1 个字节，按资源长度重复。 注意：图层组有开始和结束标记 (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | 颜色采样器资源。另见旧格式 ID 1038. |
| MeasurementScaleCS3 | `1074` | 测量比例。 4 个字节（描述符版本 = 16），Descriptor. |
| TimelineInformationCS3 | `1075` | 时间线信息。 4 个字节（描述符版本 = 16），Descriptor. |
| SheetDisclosureCS3 | `1076` | 表披露。 4 个字节（描述符版本 = 16），Descriptor. |
| PrintInformationCS5 | `1082` | 打印信息 (Photoshop CS5). |
| PrintStyleCS5 | `1083` | 打印样式 (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo。 Macintosh 的可变操作系统特定信息。 NS打印信息。 建议您不要解释或使用此数据。 (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows 开发模式。 适用于 Windows 的可变操作系统特定信息。开发模式。 建议您不要解释或使用此数据。 (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | 自动保存文件路径。 Unicode 字符串。 (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | 自动保存格式。 Unicode 字符串。 (Photoshop CS6). |
| PathSelectionStateCC | `1088` | 路径选择状态。 (Photoshop CC). |
| ImageReadyVariables | `7000` | 图像就绪变量。变量定义的 XML 表示形式. |
| ImageReadyDatasets | `7001` | 图像就绪数据集。 |
| PrintFlagsInformation | `10000` | 打印标志信息。 2 字节版本（= 1）， 1 字节中心裁剪标记， 1 字节（= 0），4 字节出血宽度值，2 字节出血宽度比例。 |

### 也可以看看

* 命名空间 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
