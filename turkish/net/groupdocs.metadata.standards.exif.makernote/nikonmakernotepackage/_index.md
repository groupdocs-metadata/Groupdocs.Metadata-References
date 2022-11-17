---
title: NikonMakerNotePackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: NIKON MakerNote meta verilerini temsil eder.
type: docs
weight: 2840
url: /tr/net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/
---
## NikonMakerNotePackage class

NIKON MakerNote meta verilerini temsil eder.

```csharp
public sealed class NikonMakerNotePackage : MakerNotePackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [NikonMakerNotePackage](nikonmakernotepackage)(TiffTag[]) | Yeni bir örneğini başlatır.[`NikonMakerNotePackage`](../nikonmakernotepackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/colormode) { get; } | Renk modunu alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [FlashSetting](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashsetting) { get; } | Flaş ayarını alır. |
| [FlashType](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashtype) { get; } | Flaşın türünü alır. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/focusmode) { get; } | Odak modunu alır. |
| [Iso](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/iso) { get; } | iso. 'yi alır |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Belirtilen kimliğe sahip TIFF etiketini alır. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MakerNoteVersion](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/makernoteversion) { get; } | MakerNote sürümünü alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/quality) { get; } | Kalite dizesini alır. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sharpness) { get; } | Keskinliği alır. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/whitebalance) { get; } | Beyaz dengesini alır. |

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
