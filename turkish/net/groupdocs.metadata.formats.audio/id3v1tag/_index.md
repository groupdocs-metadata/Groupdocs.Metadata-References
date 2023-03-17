---
title: ID3V1Tag
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir ID3v1 etiketini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsinizhttps//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /tr/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

Bir ID3v1 etiketini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsiniz:[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | Yeni bir örneğini başlatır.[`ID3V1Tag`](../id3v1tag) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | Albümü alır veya ayarlar. Maksimum uzunluk 30 karakterdir. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | Sanatçıyı alır veya ayarlar. Maksimum uzunluk 30 karakterdir. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | Yorumu alır veya ayarlar. Maksimum uzunluk 30 karakterdir. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | Tür tanımlayıcısını alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | Başlığı alır veya ayarlar. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | Parça numarasını alır veya ayarlar. Yalnızca ID3v1.1 etiketinde sunulur. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | ID3 sürümünü alır. ID3 veya ID3v1.1 olabilir |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | Yılı alır veya ayarlar. Maksimum uzunluk 4 karakterdir. |

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

### Notlar

ID3(v1) etiketi, MP3. 'nin sonundaki küçük bir ekstra veri yığınıdır. Lütfen daha fazla bilgiyi şu adreste bulabilirsiniz:[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**Daha fazla bilgi edin**

* [ID3v1 etiketinin işlenmesi](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### Örnekler

Bu kod örneği, bir MP3 dosyasındaki ID3v1 etiketinin nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### Ayrıca bakınız

* class [ID3Tag](../id3tag)
* ad alanı [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
