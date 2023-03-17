---
title: ExifGpsPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 EXIF 元数据包中的 GPS 元数据
type: docs
weight: 2770
url: /zh/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

表示 EXIF 元数据包中的 GPS 元数据。

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | 初始化一个新的实例[`ExifGpsPackage`](../exifgpspackage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | 获取或设置基于参考的高度[`AltitudeRef`](./altituderef). 参考单位为米. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | 获取或设置用作参考高度的高度。如果参考是海平面并且高度高于海平面，则给出 0。 如果高度低于海平面，则给出值 1 并且高度在[`Altitude`](./altitude)标签. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | 获取或设置记录GPS区域名称的字符串。第一个字节表示使用的字符代码，后面是GPS区域的名称。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | 获取或设置GPS DOP（数据精度）。 二维测量时写入HDOP值，三维测量时写入PDOP值。 |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | 获取或设置字符串记录相对于UTC（协调世界时）的日期和时间信息。格式为 YYYY:MM:DD. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | 获取或设置目标点的GPS方位。 取值范围为0.00到359.99。 |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | 获取或设置用于将方位指向目标点的 GPS 参考。 'T' 表示真实方向，'M' 是磁方向。 |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | 获取或设置到目的地点的GPS距离。 |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | 获取或设置用于表示到目的地点距离的GPS单位。 'K'、'M'和'N'分别代表公里、英里和节。 |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | 获取或设置目的地点的GPS纬度。 |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | 获取或设置目的地点的纬度为北纬还是南纬的GPS值。 ASCII值'N'表示北纬，'S'为南纬。 |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | 获取或设置目的地点的GPS经度。 |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | 获取或设置目的地经度为东经或西经的GPS值。 ASCII 'E'表示东经，'W'为西经。 |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | 获取或设置一个 GPS 值，该值指示差分校正是否应用于 GPS 接收器。 |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | 获取或设置 GPS 接收器移动的方向。 |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | 获取或设置图片拍摄时的GPS方向。 取值范围为0.00到359.99。 |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | 获取或设置 GPS 参考，用于在捕获图像时给出图像的方向。 'T' 表示真实方向，'M' 是磁方向。 |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 获取指定id的TIFF标签。 (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | 获取或设置 GPS 纬度。 |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | 获取或设置一个GPS值，表示纬度是北纬还是南纬。 |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | 获取或设置 GPS 经度。 |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | 获取或设置一个GPS值，表示经度是东经还是西经。 |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | 获取或设置 GPS 接收器使用的大地测量数据。 |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | 获取或设置GPS测量模式。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | 获取或设置一个字符串，记录用于定位的方法名。 第一个字节表示使用的字符编码，后面是方法名。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | 获取或设置用于测量的GPS卫星。 该标签可以用ASCII符号描述卫星的数量， 它们的ID号、仰角、方位角、信噪比等信息。格式未指定 。如果 GPS 接收器无法进行测量，则标签的值应设置为 NULL. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | 获取或设置 GPS 接收器移动的速度。 |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | 获取或设置用于表示 GPS 接收器移动速度的单位。 'K' 'M' 和 'N' 表示千米每小时、英里每小时和节。 |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | 获取或设置记录图像时GPS接收器的状态。 |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | 获取或设置时间为 UTC（协调世界时）。 TimeStamp 表示为给出小时、分钟和秒的三个 RATIONAL 值。 |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | 获取或设置用于给出 GPS 接收器移动方向的参考。 'T' 表示真实方向，'M' 是磁方向。 |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | 获取或设置 GPS IFD 的版本。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | 删除存储在包中的所有 TIFF 标签。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | 删除具有指定 id 的属性。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | 添加或替换指定的标记。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | 从包中创建一个列表。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**了解更多**

* [使用 EXIF 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### 也可以看看

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* 命名空间 [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
