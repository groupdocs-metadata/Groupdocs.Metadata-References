---
title: MpegAudioPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: MPEG ses meta verilerini temsil eder.
type: docs
weight: 2150
url: /tr/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

MPEG ses meta verilerini temsil eder.

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | Yeni bir örneğini başlatır.[`MpegAudioPackage`](../mpegaudiopackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | Bit hızını alır. |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | Kanal modunu alır. |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | Telif hakkı bitini alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | Vurgu alır. |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | Frekansı alır. |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | Başlık ofsetini alır. |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | Orijinal biti alır. |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | Alır`doğru` korumalıysa. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | Katman açıklamasını alır. MP3 sesi için '3'. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | Mod uzantısı bitlerini alır. |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | MPEG ses sürümünü alır. MPEG-1, MPEG-2 vb. olabilir |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | Dolgu bitini alır. |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | [özel bit]. olup olmadığını gösteren bir değer alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |

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

### Örnekler

Bu örnek, MPEG ses meta verilerinin bir MP3 dosyasından nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    Console.WriteLine(root.MpegAudioPackage.Bitrate);
    Console.WriteLine(root.MpegAudioPackage.ChannelMode);
    Console.WriteLine(root.MpegAudioPackage.Emphasis);
    Console.WriteLine(root.MpegAudioPackage.Frequency);
    Console.WriteLine(root.MpegAudioPackage.HeaderPosition);
    Console.WriteLine(root.MpegAudioPackage.Layer);

    // ...
}
```

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
