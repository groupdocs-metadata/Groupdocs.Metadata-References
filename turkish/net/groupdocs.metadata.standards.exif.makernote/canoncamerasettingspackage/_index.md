---
title: CanonCameraSettingsPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: CANON kamera ayarlarını temsil eder.
type: docs
weight: 2810
url: /tr/net/groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/
---
## CanonCameraSettingsPackage class

CANON kamera ayarlarını temsil eder.

```csharp
public sealed class CanonCameraSettingsPackage : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AFPoint](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/afpoint) { get; } | AFPoint'i alır. |
| [CameraIso](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/cameraiso) { get; } | Kameranın iso. değerini alır |
| [CanonExposureMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonexposuremode) { get; } | Standart pozlama modunu alır. |
| [CanonFlashMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonflashmode) { get; } | Canon flaş modunu alır. |
| [CanonImageSize](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/canonimagesize) { get; } | Standart görüntünün boyutunu alır. |
| [ContinuousDrive](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/continuousdrive) { get; } | Sürekli sürücüyü alır. |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/contrast) { get; } | Kontrastı alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DigitalZoom](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/digitalzoom) { get; } | Dijital yakınlaştırmayı alır. |
| [EasyMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/easymode) { get; } | Kolay modu alır. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusmode) { get; } | Odak modunu alır. |
| [FocusRange](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/focusrange) { get; } | Odak aralığını alır. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/imagestabilization) { get; } | Görüntü sabitlemeyi alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/lenstype) { get; } | Merceğin türünü alır. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/macromode) { get; } | Makro modunu alır. |
| [MaxFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/maxfocallength) { get; } | Maksimum odak uzunluğunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [MeteringMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/meteringmode) { get; } | Ölçüm modunu alır. |
| [MinFocalLength](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/minfocallength) { get; } | Minimum odak uzunluğunu alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/quality) { get; } | Kaliteyi alır. |
| [RecordMode](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/recordmode) { get; } | Kayıt modunu alır. |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/saturation) { get; } | Doygunluğu alır. |
| [SelfTimer](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/selftimer) { get; } | Otomatik zamanlayıcıyı alır. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/canoncamerasettingspackage/sharpness) { get; } | Keskinliği alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
