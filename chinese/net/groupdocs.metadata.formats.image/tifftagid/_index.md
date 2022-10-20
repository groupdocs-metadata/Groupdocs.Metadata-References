---
title: TiffTagID
second_title: GroupDocs.Metadata for .NET API 参考
description: 定义 TIFF 标签的 ID
type: docs
weight: 2100
url: /zh/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

定义 TIFF 标签的 ID。

```csharp
public enum TiffTagID : ushort
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| GpsVersionID | `0` | 表示 GPSInfoIFD 的版本。 |
| GpsLatitudeRef | `1` | 表示纬度是北纬还是南纬。 |
| GpsLatitude | `2` | 表示纬度。 |
| GpsLongitudeRef | `3` | 表示经度是东经还是西经。 |
| GpsLongitude | `4` | 表示经度。 |
| GpsAltitudeRef | `5` | 表示用作参考高度的高度。 |
| GpsAltitude | `6` | 指示基于 GPSAltitudeRef 中的参考的高度。 |
| GpsTimeStamp | `7` | 将时间表示为 UTC（协调世界时）。 |
| GpsSatellites | `8` | 表示用于测量的 GPS 卫星。 |
| GpsStatus | `9` | 表示记录图像时 GPS 接收器的状态。 |
| GpsMeasureMode | `10` | 表示 GPS 测量模式。 |
| GpsDop | `11` | 表示 GPS DOP（数据精度）。 |
| GpsSpeedRef | `12` | 表示GPS接收器运动速度的单位 |
| GpsSpeed | `13` | 表示 GPS 接收器移动的速度。 |
| GpsTrackRef | `14` | 表示 GPS 接收器运动方向的参考。 |
| GpsTrack | `15` | 指示 GPS 接收器移动的方向。 |
| GpsImgDirectionRef | `16` | 表示拍摄图像时给出方向的参考。 |
| GpsImgDirection | `17` | 表示图像拍摄时的方向。 |
| GpsMapDatum | `18` | 表示 GPS 接收器使用的大地测量数据。 |
| GpsDestLatitudeRef | `19` | 表示目的点的纬度是北纬还是南纬。 |
| GpsDestLatitude | `20` | 表示目的地的纬度。 |
| GpsDestLongitudeRef | `21` | 指示目的地点的经度是东经还是西经。 |
| GpsDestLongitude | `22` | 表示目的点的经度。 |
| GpsDestBearingRef | `23` | 表示用于给目标点方位的参考。 |
| GpsDestBearing | `24` | 表示到目标点的方位。 |
| GpsDestDistanceRef | `25` | 表示到目的地距离的单位。 |
| GpsDestDistance | `26` | 表示到目标点的距离。 |
| GpsProcessingMethod | `27` | 一个字符串，记录用于定位的方法的名称。 |
| GpsAreaInformation | `28` | 记录 GPS 区域名称的字符串。 |
| GpsDateStamp | `29` | 记录相对于 UTC（协调世界时）的日期和时间信息的字符串。 |
| GpsDifferential | `30` | 指示是否对 GPS 接收器应用差分校正。 |
| GpsHPositioningError | `31` | 此标签以米为单位表示水平定位误差。 |
| NewSubfileType | `254` | 此子文件中包含的数据类型的一般指示。 |
| SubfileType | `255` | 此子文件中包含的数据类型的一般指示。 此字段已弃用。应该使用 NewSubfileType 字段 |
| ImageWidth | `256` | 图像中的列数，即每条扫描线的像素数。 |
| ImageLength | `257` | 图像中的行数（有时称为扫描线）。 |
| BitsPerSample | `258` | 每个组件的位数。 |
| Compression | `259` | 用于图像数据的压缩方案。 |
| PhotometricInterpretation | `262` | 图像数据的色彩空间。 |
| Threshholding | `263` | 对于表示灰色阴影的黑白 TIFF 文件，用于将灰色像素转换为黑白像素的技术。 |
| CellWidth | `264` | 用于创建抖动或 半色调双层文件的抖动或半色调矩阵的宽度。 |
| CellLength | `265` | 用于创建抖动或 半色调双层文件的抖动或半色调矩阵的长度。 |
| FillOrder | `266` | 一个字节内位的逻辑顺序。 |
| DocumentName | `269` | 扫描此图像的文档的名称。 |
| ImageDescription | `270` | 描述图像主题的字符串。 |
| Make | `271` | 扫描仪制造商。 |
| Model | `272` | 扫描仪型号名称或编号。 |
| StripOffsets | `273` | 对于每个条带，该条带的字节偏移量。 |
| Orientation | `274` | 图像相对于行和列的方向。 |
| SamplesPerPixel | `277` | 每个像素的组件数。 |
| RowsPerStrip | `278` | 每条带的行数。 |
| StripByteCounts | `279` | 对于每个条带，压缩后条带中的字节数。 |
| MinSampleValue | `280` | 使用的最小组件值。 |
| MaxSampleValue | `281` | 使用的最大组件值。 |
| XResolution | `282` | ImageWidth 方向上每个 ResolutionUnit 的像素数。 |
| YResolution | `283` | ImageLength 方向上每个 ResolutionUnit 的像素数。 |
| PlanarConfiguration | `284` | 如何存储每个像素的分量。 |
| PageName | `285` | 扫描此图像的页面的名称。 |
| XPosition | `286` | 图像的 X 位置。 |
| YPosition | `287` | 图像的 Y 位置。 |
| FreeOffsets | `288` | 对于 TIFF 文件中的每个连续未使用字节的字符串，该字符串的字节偏移量。 |
| FreeByteCounts | `289` | 对于 TIFF 文件中的每个连续未使用字节字符串，字符串中的字节数。 |
| GrayResponseUnit | `290` | GrayResponseCurve 中包含的信息的精度。 |
| GrayResponseCurve | `291` | 对于灰度数据，每个可能像素值的光密度。 |
| T4Options | `292` | T4 编码选项。 |
| T6Options | `293` | T6 编码选项。 |
| ResolutionUnit | `296` | XResolution 和 YResolution 的测量单位。 |
| PageNumber | `297` | 扫描此图像的页面的页码。 |
| TransferFunction | `301` | 以表格形式描述图像的传递函数。像素分量可以 被伽马补偿、压扩、非均匀量化或以 some 其他方式编码。 TransferFunction 将像素分量从 non-linear BitsPerSample（例如 8 位）形式映射到 16 位线性形式，而没有可察觉的 loss 精度。 |
| Software | `305` | 用于创建映像的软件包的名称和版本号。 |
| DateTime | `306` | 图像创建的日期和时间。 |
| Artist | `315` | 创建图像的人。 |
| HostComputer | `316` | 创建映像时使用的计算机和/或操作系统。 |
| Predictor | `317` | 本节定义了一个预测器，可以大大提高某些图像的压缩率。 |
| WhitePoint | `318` | 图像白点的色度。 |
| PrimaryChromaticities | `319` | 图像原色的色度。 |
| ColorMap | `320` | 调色板彩色图像的颜色图。 |
| HalftoneHints | `321` | HalftoneHints 字段的目的是向半色调函数传达 应保留 色调细节的比色指定图像中的灰度级范围。 |
| TileWidth | `322` | 平铺宽度（以像素为单位）。这是每个图块中的列数。 |
| TileLength | `323` | 瓦片长度（高度），以像素为单位。这是每个图块中的行数。 |
| TileOffsets | `324` | 对于每个图块，该图块的字节偏移量，已压缩并存储在磁盘上。 相对于 TIFF 文件的开头指定偏移量。 请注意，这意味着每个图块的位置独立于其他图块的位置。 |
| TileByteCounts | `325` | 对于每个图块，该图块中（压缩的）字节数。 |
| InkSet | `332` | 分离的 (PhotometricInterpretation=5) 图像中使用的油墨组。 |
| InkNames | `333` | 在分离的 (PhotometricInterpretation=5) 图像中使用的每种墨水的名称， 写为连接的、以 NUL 结尾的 ASCII 字符串列表。 |
| NumberOfInks | `334` | 墨水数。通常等于 SamplesPerPixel，除非有额外的样本。 |
| DotRange | `336` | 对应于 0% 点和 100% 点的组件值。 DotRange[0] 对应 0% 点，DotRange[1] 对应 100% 点。 |
| ExtraSamples | `338` | 额外组件说明。 |
| SampleFormat | `339` | 该字段指定如何解释像素中的每个数据样本。 |
| SMinSampleValue | `340` | 此字段指定最小样本值。 |
| SMaxSampleValue | `341` | 这个新字段指定了最大样本值。 |
| TransferRange | `342` | 扩展 TransferFunction 的范围。 |
| JpegProc | `512` | 该字段表示用于生成压缩数据的 JPEG 过程。 |
| JpegInterchangeFormat | `513` | 此字段指示 TIFF 文件中是否存在 JPEG 交换格式比特流。 |
| JpegInterchangeFormatLength | `514` | 该字段表示 JPEG 交换格式 bitstream 的字节长度 |
| JpegRestartInterval | `515` | 该字段表示压缩图像数据中使用的重启间隔的长度。 |
| JpegLosslessPredictors | `517` | 此字段指向无损预测器选择值列表，每个组件一个。 |
| JpegPointTransforms | `518` | 该字段指向一个点变换值列表，每个组件一个。 |
| JpegQTables | `519` | 该字段指向量化表的偏移列表，每个分量一个。 |
| JpegDCTables | `520` | 该字段指向 DC Huffman 表或 lossless Huffman 表的偏移列表，每个组件一个。 |
| JpegACTables | `521` | 此字段指向 Huffman AC 表的偏移列表，每个组件一个。 |
| YCbCrCoefficients | `529` | 从 RGB 转换为 YCbCr 图像数据的矩阵系数。 |
| YCbCrSubSampling | `530` | 色度分量相对于亮度分量的采样率。 |
| YCbCrPositioning | `531` | 指定子采样色度分量相对于亮度样本的位置。 |
| ReferenceBlackWhite | `532` | 为每个像素分量指定一对头部空间和底部空间图像数据值（代码）。 |
| Copyright | `33432` | 版权声明。 |
| UserComment | `37510` | 图片上的关键词或评论；补充 ImageDescription. |
| Xmp | `700` | 指向 XMP 元数据的指针。 |
| ImageID | `32781` | OPI 相关。 |
| Iptc | `33723` | IPTC（国际新闻电信委员会）元数据。 通常，数据类型被错误地指定为 LONG。 |
| Photoshop | `34377` | Photoshop“图像资源块”的集合。 |
| ImageLayer | `34732` | 图像层. |
| IccProfile | `34675` | 颜色配置文件数据。 |
| ExifIfd | `34665` | 指向所有 EXIF 元数据集合的指针。 EXIF 使用字段名称而不是标签来表示字段内容。 |
| GpsIfd | `34853` | 指向 GPS 数据的指针。 |
| Makernotes | `37500` | 指向 makernotes 数据的指针。 |
| InteroperabilityIfd | `40965` | Exif 相关的互操作性 IFD. |
| CameraOwnerName | `42032` | 相机所有者名称为 ASCII 字符串。 |
| BodySerialNumber | `42033` | 相机机身序列号为 ASCII 字符串。 |
| CfaPattern | `41730` | 表示使用单芯片彩色区域传感器时图像传感器的彩色滤光片阵列 (CFA) 几何图案。它不适用于所有传感方法。 |
| ExifVersion | `36864` | 支持的 EXIF 标准的版本。 |
| ComponentsConfiguration | `37121` | 特定于压缩数据的信息。每个组件的通道按从第 1 个组件到第 4 个组件的顺序排列。 |
| FlashpixVersion | `40960` | FPXR 文件支持的 Flashpix 格式版本。如果 FPXR 功能支持 Flashpix 格式 Ver. 1.0，这与 ExifVersion 类似，通过将“0100”记录为 4 字节 ASCII. |
| ColorSpace | `40961` | 颜色空间信息标签（ColorSpace）总是被记录为颜色空间说明符。 通常 sRGB (=1) 用于根据 PC 显示器条件和环境定义色彩空间。 如果使用 sRGB 以外的颜色空间，则设置未校准 (=FFFF.H)。 |
| PixelXDimension | `40962` | 特定于压缩数据的信息。记录压缩文件时， 有意义的图像的有效宽度应记录在此标签中，无论是否有填充数据或重新启动标记。 |
| PixelYDimension | `40963` | 特定于压缩数据的信息。记录压缩文件时， 有意义的图像的有效高度应记录在此标签中，无论是否有填充数据或重新开始标记。 |
| SceneCaptureType | `41990` | 这个标签表示拍摄的场景类型。它也可以用来记录拍摄图像的模式。 |
| Gamma | `42240` | 表示系数gamma的值。 |
| CompressedBitsPerPixel | `37122` | 特定于压缩数据的信息。用于压缩图像的压缩模式以每像素单位位表示。 |
| RelatedSoundFile | `40964` | 该标签用于记录与图像数据相关的音频文件的名称。 这里记录的唯一关系信息是Exif音频文件名和扩展名 （由8个字符+'.'+3个字符组成的ASCII字符串）。 |
| DateTimeOriginal | `36867` | 生成原始图像数据的日期和时间。 对于 DSC，会记录拍摄照片的日期和时间。 格式为“YYYY:MM:DD HH:MM:SS”，时间以 24 小时格式显示，日期和时间用一个空白字符分隔。 |
| DateTimeDigitized | `36868` | 图像作为数字数据存储的日期和时间。 例如，如果 DSC 捕获图像并同时记录文件，则 DateTimeOriginal 和 DateTimeDigitized 将具有相同的内容。 格式为“YYYY:MM:DD HH:MM:SS”，时间以 24 小时格式显示，日期和时间用一个空白字符分隔。 |
| OffsetTime | `36880` | 一个标签，用于记录 DateTime 标签的时间与 UTC（与世界协调时间的时差，包括夏令时）的偏移量。 记录偏移量时的格式为“±HH:MM”。 “±”部分记为“+”或“-”。 |
| OffsetTimeOriginal | `36881` | 用于记录DateTimeOriginal 标记的时间与UTC（包括夏令时在内的世界协调时间的时差）的偏移量的标记。 记录偏移量时的格式为“±HH:MM”。 “±”部分记为“+”或“-”。 |
| OffsetTimeDigitized | `36882` | 用于记录 DateTimeDigitized 标记的时间与 UTC（与协调世界时的时差，包括夏令时）的偏移量的标记。 记录偏移量时的格式为“±HH:MM”。 “±”部分记为“+”或“-”。 |
| SubsecTime | `37520` | 用于记录 DateTime 标记的秒数的标记。 |
| SubsecTimeOriginal | `37521` | 用于记录 DateTimeOriginal 标记的秒数的标记。 |
| SubsecTimeDigitized | `37522` | 用于记录 DateTimeDigitized 标记的秒数的标记。 |
| ExposureTime | `33434` | 曝光时间，以秒 (sec) 为单位。 |
| FNumber | `33437` | F 号。 |
| ExposureProgram | `34850` | 相机在拍照时设置曝光的程序的类。 |
| SpectralSensitivity | `34852` | 表示所用相机各通道的光谱灵敏度。 标签值是一个ASCII字符串，兼容ASTM技术委员会制定的标准。 |
| PhotographicSensitivity | `34855` | 此标签表示拍摄图像时相机或输入设备的灵敏度。 |
| Oecf | `34856` | 表示 ISO 14524 中规定的光电转换函数 (OECF)。 OECF 是相机光学输入与图像值之间的关系。 |
| SensitivityType | `34864` | SensitivityType标签表示ISO12232的哪一个参数是PhotographicSensitivity标签。 虽然是可选标签，但在记录PhotographicSensitivity标签时应该记录下来。 |
| StandardOutputSensitivity | `34865` | 此标签表示 ISO 12232 中定义的相机或输入设备的标准输出灵敏度值。 记录此标签时，还应记录PhotographicSensitivity 和SensitivityType 标签。 |
| RecommendedExposureIndex | `34866` | 这个标签表示ISO 12232定义的相机或输入设备的推荐曝光指数值。 记录这个标签时，还需要记录PhotographicSensitivity和SensitivityType标签。 |
| IsoSpeed | `34867` | 此标签表示相机或输入设备的 ISO 感光度值，在 ISO 12232 中定义。 记录此标签时，还应记录PhotographicSensitivity 和SensitivityType 标签。 |
| ISOSpeedLatitudeYyy | `34868` | 此标签表示 ISO 12232 中定义的相机或输入设备的 ISO 感光度纬度 yyy 值。 |
| ISOSpeedLatitudeZzz | `34869` | 此标签表示 ISO 12232 中定义的相机或输入设备的 ISO 感光度纬度 zzz 值。 |
| ShutterSpeedValue | `37377` | 快门速度。单位是 APEX（摄影曝光的加法系统）设置。 |
| ApertureValue | `37378` | 镜头光圈。单位是APEX值。 |
| BrightnessValue | `37379` | 亮度值。单位是 APEX 值。 |
| ExposureBiasValue | `37380` | 曝光偏差。单位是APEX值。 |
| MaxApertureValue | `37381` | 镜头的最小F数。单位是APEX值。 |
| SubjectDistance | `37382` | 到主体的距离，以米为单位。 |
| MeteringMode | `37383` | 测光模式。 |
| LightSource | `37384` | 光源的种类。 |
| Flash | `37385` | 该标签表示拍摄图像时闪光灯的状态。 位0表示闪光灯闪光状态，位1和2表示闪光返回状态， 位3和4表示闪光模式，位5表示是否存在闪光功能，位6表示“红眼”模式。 |
| SubjectArea | `37396` | 这个标签表示整个场景中主要被摄体的位置和区域。 |
| FocalLength | `37386` | 镜头的实际焦距，单位为mm。不转换为 35 毫米胶片相机的焦距。 |
| FlashEnergy | `41483` | 表示拍摄图像时的频闪能量，以光束烛光功率秒 (BCPS) 为单位。 |
| SpatialFrequencyResponse | `41484` | 此标签记录相机或输入设备空间频率表和图像宽度方向、 图像高度和对角线方向的 SFR 值，如 ISO 12233 中规定的。 |
| FocalPlaneXResolution | `41486` | 表示相机焦平面上每个 FocalPlaneResolutionUnit 在图像宽度 (X) 方向上的像素数。 |
| FocalPlaneYResolution | `41487` | 表示相机焦平面上每个 FocalPlaneResolutionUnit 在像高 (Y) 方向上的像素数。 |
| FocalPlaneResolutionUnit | `41488` | 表示 FocalPlaneXResolution 和 FocalPlaneYResolution 的测量单位。此值与 ResolutionUnit. 相同 |
| SubjectLocation | `41492` | 表示场景中主要主体的位置。 此标签的值表示在根据旋转标签进行旋转处理之前，主体中心相对于左边缘的像素。 第一个值表示X列号，第二个表示Y行号。 |
| ExposureIndex | `41493` | 表示在拍摄图像时在相机或输入设备上选择的曝光指数。 |
| SensingMethod | `41495` | 表示相机或输入设备上的图像传感器类型。 |
| FileSource | `41728` | 表示图片来源。如果 DSC 记录了图像，则该标签值始终应设置为 3. |
| SceneType | `41729` | 表示场景的类型。如果 DSC 记录了图像，则该标签值应始终设置为 1，表示图像是直接拍摄的。 |
| CustomRendered | `41985` | 这个标签表示对图像数据进行了特殊处理，比如渲染适合输出。 |
| ExposureMode | `41986` | 此标签表示拍摄图像时设置的曝光模式。在自动包围模式下， 相机以不同的曝光设置拍摄同一场景的一系列帧。 |
| WhiteBalance | `41987` | 此标签表示拍摄图像时设置的白平衡模式。 |
| DigitalZoomRatio | `41988` | 该标签表示拍摄图像时的数码变焦倍率。 如果记录值的分子为0，表示没有使用数码变焦。 |
| FocalLengthIn35mmFilm | `41989` | 该标签表示假设 35mm 胶片相机的等效焦距，单位为 mm。 值为 0 表示焦距未知。请注意，此标记与 FocalLength 标记不同。 |
| GainControl | `41991` | 这个标签表示整体图像增益调整的程度。 |
| Contrast | `41992` | 此标签表示拍摄图像时相机应用的对比度处理方向。 |
| Saturation | `41993` | 该标签表示拍摄图像时相机应用的饱和度处理方向。 |
| Sharpness | `41994` | 此标签指示拍摄图像时相机应用的锐度处理方向。 |
| DeviceSettingDescription | `41995` | 该标签表示特定相机型号的拍照条件信息。 |
| SubjectDistanceRange | `41996` | 这个标签表示到主体的距离。 |
| CompositeImage | `42080` | 此标签指示记录的图像是否为合成图像*。 |
| SourceImageNumberOfCompositeImage | `42081` | 此标签表示为合成图像捕获的源图像（暂定图像）的数量。 |
| SourceExposureTimesOfCompositeImage | `42082` | 对于合成图像，该标签记录了用于生成所述合成图像的曝光的曝光时间相关参数， 例如捕获的源图像（暂定图像）的各个曝光时间。 |
| Temperature | `37888` | 温度作为拍摄时的环境情况，例如摄影师拿着相机的室温。单位是°C。 |
| Humidity | `37889` | 湿度作为拍摄时的环境情况，例如摄影师拿着相机的房间湿度。单位是%。 |
| Pressure | `37890` | 压力作为拍摄时的环境情况， 例如摄影师拿着相机的房间气氛或海下的水压。 单位为 hPa。 |
| WaterDepth | `37891` | 水深作为拍摄时的环境情况，例如水下摄影时相机的水深。单位是 m. |
| Acceleration | `37892` | 加速度（与方向无关的标量）作为拍摄时的环境情况，例如摄影师在拍摄时乘坐的车辆的行驶加速度。 单位为 mGal (10-5 m/s2)。 |
| CameraElevationAngle | `37893` | 升高/降低。相机方向的角度（成像光轴）作为拍摄时的环境情况。单位是度（°）。 |
| ImageUniqueID | `42016` | 这个标签表示一个唯一分配给每个图像的标识符。 |
| LensSpecification | `42034` | 这个标签标注了最小焦距、最大焦距、最小焦距中的最小 F 值、 和最大焦距中的最小 F 值，这些是摄影中使用的镜头的规格信息。 |
| LensMake | `42035` | 此标签将镜头制造商记录为 ASCII 字符串。 |
| LensModel | `42036` | 此标签将镜头的型号名称和型号记录为 ASCII 字符串。 |
| LensSerialNumber | `42037` | 此标签将摄影中使用的可更换镜头的序列号记录为 ASCII 字符串。 |

### 也可以看看

* 命名空间 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
