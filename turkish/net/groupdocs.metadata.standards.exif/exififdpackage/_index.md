---
title: ExifIfdPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Exif Görüntü Dosyası Dizinini temsil eder. Exif IFD Exife özgü öznitelik bilgilerini kaydetmek için bir dizi etikettir.
type: docs
weight: 2780
url: /tr/net/groupdocs.metadata.standards.exif/exififdpackage/
---
## ExifIfdPackage class

Exif Görüntü Dosyası Dizinini temsil eder. Exif IFD, Exif'e özgü öznitelik bilgilerini kaydetmek için bir dizi etikettir.

```csharp
public sealed class ExifIfdPackage : ExifDictionaryBasePackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BodySerialNumber](../../groupdocs.metadata.standards.exif/exififdpackage/bodyserialnumber) { get; set; } | Kamera gövdesi seri numarasını alır veya ayarlar. |
| [CameraOwnerName](../../groupdocs.metadata.standards.exif/exififdpackage/cameraownername) { get; set; } | Kamera sahibinin adını alır veya ayarlar. |
| [CfaPattern](../../groupdocs.metadata.standards.exif/exififdpackage/cfapattern) { get; set; } | Tek çipli bir renk alanı sensörü kullanıldığında, görüntü sensörünün renk filtresi dizisi (CFA) geometrik desenini alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Belirtilen kimliğe sahip TIFF etiketini alır. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [UserComment](../../groupdocs.metadata.standards.exif/exififdpackage/usercomment) { get; set; } | Kullanıcı yorumunu alır veya ayarlar. |

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

### Notlar

**Daha fazla bilgi edin**

* [EXIF meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Ayrıca bakınız

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* ad alanı [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
