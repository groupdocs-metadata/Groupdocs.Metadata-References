---
title: ID3V2AttachedPictureFrame
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir APIC çerçevesini temsil eder.ID3V2Tag./id3v2tag .
type: docs
weight: 420
url: /tr/net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/
---
## ID3V2AttachedPictureFrame class

Bir APIC çerçevesini temsil eder.[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2AttachedPictureFrame : ID3V2TagFrame
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor)(byte[]) | Yeni bir örneğini başlatır.[`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) sınıf. |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor_1)(ID3V2AttachedPictureType, string, byte[]) | Yeni bir örneğini başlatır.[`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) sınıf. |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor_2)(ID3V2EncodingType, string, ID3V2AttachedPictureType, string, byte[]) | Yeni bir örneğini başlatır.[`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AttachedPictureType](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/attachedpicturetype) { get; } | Resmin türünü alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Çerçeve verilerini alır. |
| [Description](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description) { get; } | Resim açıklamasını alır. Açıklamanın maksimum uzunluğu 64 karakterdir, ancak boş olabilir. |
| [DescriptionEncoding](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/descriptionencoding) { get; } | Resim açıklamasını kodlamak için kullanılan kodlamayı alır. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Çerçeve bayraklarını alır. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Çerçevenin kimliğini alır ([A-Z0-9] kalıbıyla eşleşen dört karakter). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [MimeType](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/mimetype) { get; } | Resmin MIME türünü alır. |
| [PictureData](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/picturedata) { get; } | Resim verilerini alır. |
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

### Notlar

**Daha fazla bilgi edin**

* [ID3v2 etiketinin işlenmesi](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Ayrıca bakınız

* class [ID3V2TagFrame](../id3v2tagframe)
* ad alanı [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
