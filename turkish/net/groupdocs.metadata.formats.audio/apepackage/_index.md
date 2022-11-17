---
title: ApePackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir APE v2 meta veri paketini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsinizhttp//wiki.hidrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /tr/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

Bir APE v2 meta veri paketini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsiniz:[http://wiki.hidrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | Soyut bağlantıyı alır. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | Albümü alır. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | Sanatçıyı alır. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | Kaynakçayı alır. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | Yorumu alır. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | Besteciyi alır. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | Kondüktörü alır. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | Telif hakkını alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | İlk albümü alır. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | Dosyayı alır. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | Türü alır. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | Kontrol haneli ISBN numarasını alır. Daha fazlasını görün: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | Uluslararası Standart Kayıt Numarasını Alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | Dili alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | Yayını doğru yapar. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | Yayıncıyı alır. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | Kayıt konumunu alır. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | Altyazıyı alır. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | Başlığı alır. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | Parça numarasını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [APEv2 etiketinin işlenmesi](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### Örnekler

Bu örnek, bir MP3 dosyasındaki APEv2 etiketinin nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
