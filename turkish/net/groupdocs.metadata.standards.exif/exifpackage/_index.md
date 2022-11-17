---
title: ExifPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir EXIF meta veri paketini Değiştirilebilir Görüntü Dosyası Biçimi temsil eder.
type: docs
weight: 2790
url: /tr/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Bir EXIF meta veri paketini (Değiştirilebilir Görüntü Dosyası Biçimi) temsil eder.

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ExifPackage](exifpackage)() | Yeni bir örneğini başlatır.[`ExifPackage`](../exifpackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Kamera sahibinin, fotoğrafçının veya görüntü oluşturucunun adını alır veya ayarlar. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Telif hakkı bildirimini alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Görüntü oluşturmanın tarih ve saatini alır veya ayarlar. EXIF standardında, dosyanın değiştirildiği tarih ve saattir. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | EXIF IFD verilerini alır. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | GPS verilerini alır. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Görüntünün başlığını veren bir karakter dizisini alır veya ayarlar. "1988 şirket pikniği" veya benzeri bir yorum olabilir. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Görüntü verilerinin satır sayısını alır veya ayarlar. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Görüntü verilerinin sütun sayısını, satır başına piksel sayısına eşit olarak alır veya ayarlar. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Belirtilen kimliğe sahip TIFF etiketini alır. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Kayıt ekipmanı üreticisini alır veya ayarlar. Bu, görüntüyü oluşturan DSC, tarayıcı, video sayısallaştırıcı veya diğer ekipmanın üreticisidir. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Ekipmanın model adını veya model numarasını alır veya ayarlar. Bu, görüntüyü oluşturan DSC, tarayıcı, video sayısallaştırıcı veya diğer ekipmanın model adı veya numarasıdır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Görüntüyü oluşturmak için kullanılan kameranın veya görüntü giriş cihazının yazılımının veya sabit yazılımının adını ve sürümünü alır veya ayarlar. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Bir bayt dizisi olarak temsil edilen görüntünün küçük resmini alır. |

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

### Örnekler

Bu kod örneği, ortak EXIF özelliklerinin nasıl güncelleneceğini gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // EXIF paketi yoksa ayarlayın
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Ayrıca bakınız

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* ad alanı [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
