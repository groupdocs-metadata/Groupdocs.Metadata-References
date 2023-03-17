---
title: ID3V2Tag
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir ID3v2 etiketini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsinizhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /tr/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Bir ID3v2 etiketini temsil eder. Lütfen daha fazla bilgiyi şu adreste bulabilirsiniz:[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Yeni bir örneğini başlatır.[`ID3V2Tag`](../id3v2tag) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Albüm/Film/Gösteri başlığını alır veya ayarlar. Bu değer, TALB çerçevesiyle temsil edilir. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Baş sanatçı(lar)/Baş sanatçı(lar)/Solist(ler)/Performans grubunu alır veya ayarlar. Bu değer, TPE1 çerçevesiyle temsil edilir. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Doğrudan ses dosyasıyla ilgili ekli resimleri alır veya ayarlar. Bu değer, APIC çerçevesiyle temsil edilir. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Bando/Orkestra/Eşliği alır veya ayarlar. Bu değer, TPE2 çerçevesiyle temsil edilir. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Sesin ana bölümündeki dakikadaki vuruş sayısını alır veya ayarlar. Bu değer TBPM çerçevesiyle temsil edilir. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Kullanıcı yorumlarını alır veya ayarlar. Bu değer, COMM çerçevesiyle temsil edilir. Çerçeve, başka hiçbir çerçeveye sığmayan her türlü tam metin bilgisi için tasarlanmıştır. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Oluşturucuları alır veya ayarlar. İsimler "/" karakteri ile ayrılır. Bu değer TCOM çerçevesi ile temsil edilir. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | İçerik türünü alır veya ayarlar. Bu değer, TCON çerçevesi tarafından temsil edilir. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Telif hakkı mesajını alır veya ayarlar. Bu değer, TCOP çerçevesiyle temsil edilir. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Kayıt tarihini içeren DDMM biçiminde bir sayısal dizi alır veya ayarlar. Bu alan her zaman dört karakter uzunluğundadır. Bu değer TDAT çerçevesi tarafından temsil edilir. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Ses dosyasını kodlayan kişi veya kuruluşun adını alır veya ayarlar. Bu değer TENC çerçevesiyle temsil edilir. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Uluslararası Standart Kayıt Kodunu (ISRC) (12 karakter) alır veya ayarlar. Bu değer, TSRC çerçevesiyle temsil edilir. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Ses dosyasının uzunluğunu sayısal bir dizi olarak temsil edilen milisaniye cinsinden alır veya ayarlar. Bu değer, TLEN çerçevesiyle temsil edilir. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Sesin başladığı müzikal anahtarı alır veya ayarlar. Bu değer, TKEY çerçevesiyle temsil edilir. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Orijinal albüm/film/şov başlığını alır veya ayarlar. Bu değer, TOAL çerçevesiyle temsil edilir. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Etiketin veya yayıncının adını alır veya ayarlar. Bu değer, TPUB çerçevesiyle temsil edilir. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Sayısal bir dizi olarak temsil edilen ID3v2 etiketi hariç, ses dosyasının boyutunu bayt cinsinden alır veya ayarlar. Bu değer, TSIZ çerçevesi ile temsil edilir. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Dosya kodlandığında kullanılan ses kodlayıcıyı ve ayarlarını alır veya ayarlar. Bu değer, TSSE çerçevesiyle temsil edilir. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Altyazı/Açıklama iyileştirmesini alır veya ayarlar. Bu değer, TIT3 çerçevesiyle temsil edilir. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Etiketin boyutunu alır. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Kayıt için zamanı içeren HHMM biçiminde bir sayısal dizi alır veya ayarlar. Bu alan her zaman dört karakter uzunluğundadır. Bu değer ZAMAN çerçevesiyle temsil edilir. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Başlık/Şarkı adını/İçerik açıklamasını alır veya ayarlar. Bu değer, TIT2 çerçevesiyle temsil edilir. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Orijinal kaydındaki ses dosyasının sıra numarasını içeren bir sayısal dizi alır veya ayarlar. Bu değer, TRCK çerçevesi tarafından temsil edilir. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Dosyanın oynatılma sayısını alır. Bu değer PCNT çerçevesiyle temsil edilir. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | ID3 sürümünü alır. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Kayıt yılıyla birlikte sayısal bir dizi alır veya ayarlar. Bu çerçeveler her zaman dört karakter uzunluğundadır (10000 yılına kadar). Bu değer, TYER çerçevesi ile temsil edilir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Etikete bir çerçeve ekler. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Belirtilen kimliğe sahip tüm çerçeveleri kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Belirtilen kimliğe sahip bir çerçeve dizisi alır. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Belirtilen çerçeveyi etiketten kaldırır. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | APIC çerçevelerinde saklanan tüm ekli resimleri kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Belirtilen çerçeveyle aynı kimliğe sahip tüm çerçeveleri kaldırır ve yeni çerçeveyi etikete ekler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Paketten bir liste oluşturur. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [ID3v2 etiketinin işlenmesi](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Örnekler

Bu örnek, bir MP3 dosyasındaki ID3v2 etiketinin nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### Ayrıca bakınız

* class [ID3Tag](../id3tag)
* ad alanı [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
