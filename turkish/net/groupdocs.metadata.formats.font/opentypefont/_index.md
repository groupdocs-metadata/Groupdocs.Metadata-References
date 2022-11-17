---
title: OpenTypeFont
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir dosyadan çıkarılan tek bir yazı tipini temsil eder.
type: docs
weight: 1460
url: /tr/net/groupdocs.metadata.formats.font/opentypefont/
---
## OpenTypeFont class

Bir dosyadan çıkarılan tek bir yazı tipini temsil eder.

```csharp
public class OpenTypeFont : CustomPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Created](../../groupdocs.metadata.formats.font/opentypefont/created) { get; } | Oluşturulan tarihi alır. |
| [DirectionHint](../../groupdocs.metadata.formats.font/opentypefont/directionhint) { get; } | Yön ipucunu alır. |
| [EmbeddingLicensingRights](../../groupdocs.metadata.formats.font/opentypefont/embeddinglicensingrights) { get; } | Yerleştirme lisanslama hakları türünü alır. |
| [Flags](../../groupdocs.metadata.formats.font/opentypefont/flags) { get; } | Başlık işaretlerini alır. |
| [FontFamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontfamilyname) { get; } | Yazı tipi ailesinin adını alır. |
| [FontRevision](../../groupdocs.metadata.formats.font/opentypefont/fontrevision) { get; } | Yazı tipi revizyonunu alır. |
| [FontSubfamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontsubfamilyname) { get; } | Yazı tipi alt ailesinin adını alır. |
| [FullFontName](../../groupdocs.metadata.formats.font/opentypefont/fullfontname) { get; } | Yazı tipinin tam adını alır. |
| [GlyphBounds](../../groupdocs.metadata.formats.font/opentypefont/glyphbounds) { get; } | Glif sınırlarını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MajorVersion](../../groupdocs.metadata.formats.font/opentypefont/majorversion) { get; } | Üstbilgi ana sürümünü alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [MinorVersion](../../groupdocs.metadata.formats.font/opentypefont/minorversion) { get; } | Üst bilgi küçük sürümünü alır. |
| [Modified](../../groupdocs.metadata.formats.font/opentypefont/modified) { get; } | Değiştirilen tarihi alır. |
| [Names](../../groupdocs.metadata.formats.font/opentypefont/names) { get; } | İsim kayıtlarını alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [SfntVersion](../../groupdocs.metadata.formats.font/opentypefont/sfntversion) { get; } | Başlık SFNT sürümünü alır. |
| [Style](../../groupdocs.metadata.formats.font/opentypefont/style) { get; } | Yazı tipi stilini alır. |
| [TypographicFamily](../../groupdocs.metadata.formats.font/opentypefont/typographicfamily) { get; } | Tipografik aileyi alır. |
| [TypographicSubfamily](../../groupdocs.metadata.formats.font/opentypefont/typographicsubfamily) { get; } | Tipografik alt aileyi alır. |
| [Weight](../../groupdocs.metadata.formats.font/opentypefont/weight) { get; } | Yazı tipi ağırlığını alır. |
| [Width](../../groupdocs.metadata.formats.font/opentypefont/width) { get; } | Yazı tipi genişliğini alır. |

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

* [OpenType yazı tipleriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### Ayrıca bakınız

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ad alanı [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
