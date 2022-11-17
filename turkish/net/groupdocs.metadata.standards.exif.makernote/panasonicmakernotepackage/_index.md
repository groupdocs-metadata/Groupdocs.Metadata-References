---
title: PanasonicMakerNotePackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: PANASONIC MakerNote meta verilerini temsil eder.
type: docs
weight: 2850
url: /tr/net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/
---
## PanasonicMakerNotePackage class

PANASONIC MakerNote meta verilerini temsil eder.

```csharp
public class PanasonicMakerNotePackage : MakerNotePackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AccessorySerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessoryserialnumber) { get; } | Aksesuar seri numarasını alır. |
| [AccessoryType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessorytype) { get; } | Aksesuarın türünü alır. |
| [AFMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/afmode) { get; } | AF modunu alır. |
| [Audio](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/audio) { get; } | Ses modunu alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [FirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/firmwareversion) { get; } | Donanım yazılımı sürümünü alır. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/focusmode) { get; } | Odak modunu alır. |
| [ImageQuality](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagequality) { get; } | Görüntü kalitesini alır. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagestabilization) { get; } | Görüntü sabitleme modunu alır. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Belirtilen kimliğe sahip TIFF etiketini alır. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LensSerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lensserialnumber) { get; } | Lens seri numarasını alır. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lenstype) { get; } | Merceğin türünü alır. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/macromode) { get; } | Makro modunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [ShootingMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/shootingmode) { get; } | Çekim modunu alır. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/whitebalance) { get; } | Beyaz dengesini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Pakette saklanan tüm TIFF etiketlerini kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Belirtilen kimliğe sahip özelliği kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Belirtilen etiketi ekler veya değiştirir. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Paketten bir liste oluşturur. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Ayrıca bakınız

* class [MakerNotePackage](../makernotepackage)
* ad alanı [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
