---
title: LyricsTag
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Lyrics3 v2.00 meta verilerini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsinizhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /tr/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Lyrics3 v2.00 meta verilerini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsiniz:http://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LyricsTag](lyricstag)() | Yeni bir örneğini başlatır.[`LyricsTag`](../lyricstag) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Ek bilgileri alır veya ayarlar. Bu değer, INF alanı tarafından temsil edilir. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Albüm adını alır veya ayarlar. Bu değer, EAL alanı tarafından temsil edilir. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Sanatçı adını alır veya ayarlar. Bu değer, EAR alanı tarafından temsil edilir. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Yazarı alır veya ayarlar. Bu değer, AUT alanı tarafından temsil edilir. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Sözleri alır veya ayarlar. Bu değer LYR alanı tarafından temsil edilir. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Parça başlığını alır veya ayarlar. Bu değer, ETT alanı tarafından temsil edilir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Belirtilen kimliğe sahip alanın değerini alır. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Belirtilen kimliğe sahip alanı kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Belirtilen Sözler3 alanını ekler veya değiştirir. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Paketten bir liste oluşturur. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

Lyrics3 v2.00, bilgileri temsil etmek için alanları kullanır. Bir alandaki veriler, standarda göre 01 ila 254 aralığında ASCII karakterlerinden oluşabilir. ASCII karakter haritası yalnızca 00 ila 128 arasında tanımlandığı için ISO-8859- 1 varsayılabilir. Sayısal alanlar, konuma bağlı olarak 5 veya 6 karakter uzunluğundadır ve sıfırlarla doldurulur.

**Daha fazla bilgi edin**

* [Lyrics etiketini kullanma](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Örnekler

Bu kod örneği, Lyrics etiketinin bir MP3 dosyasından nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Alternatif olarak, etiket alanlarının tam listesi arasında geçiş yapabilirsiniz
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
