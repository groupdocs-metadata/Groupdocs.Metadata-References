---
title: CanonCameraSettingsPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 代表CANON相机设置
type: docs
weight: 2810
url: /zh/net/groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/
---
## CanonCameraSettingsPackage class

代表CANON相机设置。

```csharp
public sealed class CanonCameraSettingsPackage : CustomPackage
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AFPoint](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/afpoint) { get; } | 获取自动对焦点。 |
| [CameraIso](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/cameraiso) { get; } | 获取相机 iso. |
| [CanonExposureMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonexposuremode) { get; } | 获取佳能曝光模式。 |
| [CanonFlashMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonflashmode) { get; } | 获取佳能闪光灯模式。 |
| [CanonImageSize](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonimagesize) { get; } | 获取佳能图像的大小。 |
| [ContinuousDrive](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/continuousdrive) { get; } | 获取连续驱动。 |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/contrast) { get; } | 获取对比度。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DigitalZoom](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/digitalzoom) { get; } | 获取数字变焦。 |
| [EasyMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/easymode) { get; } | 获取简单模式。 |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusmode) { get; } | 获取对焦模式。 |
| [FocusRange](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusrange) { get; } | 获取对焦范围。 |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/imagestabilization) { get; } | 获取图像稳定。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定名称. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/lenstype) { get; } | 获取镜头的类型。 |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/macromode) { get; } | 获取宏模式。 |
| [MaxFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/maxfocallength) { get; } | 获取焦点的最大长度。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [MeteringMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/meteringmode) { get; } | 获取测光模式。 |
| [MinFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/minfocallength) { get; } | 获取焦点的最小长度。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/quality) { get; } | 获取质量。 |
| [RecordMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/recordmode) { get; } | 获取记录模式。 |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/saturation) { get; } | 获取饱和度。 |
| [SelfTimer](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/selftimer) { get; } | 获取自拍定时器。 |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/sharpness) { get; } | 获取锐度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 也可以看看

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 命名空间 [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
