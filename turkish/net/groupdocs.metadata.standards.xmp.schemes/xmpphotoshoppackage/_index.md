---
title: XmpPhotoshopPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Adobe Photoshop ad alanını temsil eder.
type: docs
weight: 3210
url: /tr/net/groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/
---
## XmpPhotoshopPackage class

Adobe Photoshop ad alanını temsil eder.

```csharp
public sealed class XmpPhotoshopPackage : XmpPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpPhotoshopPackage](xmpphotoshoppackage)() | Yeni bir örneğini başlatır.[`XmpPhotoshopPackage`](../xmpphotoshoppackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AuthorsPosition](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/authorsposition) { get; set; } | Yan satır başlığını alır veya ayarlar. |
| [CaptionWriter](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/captionwriter) { get; set; } | Yazarı/düzenleyiciyi alır veya ayarlar. |
| [Category](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/category) { get; set; } | Kategoriyi alır veya ayarlar. 3 adet 7 bitlik ASCII karakterle sınırlıdır. |
| [City](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/city) { get; set; } | Şehri alır veya ayarlar. |
| [ColorMode](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/colormode) { get; set; } | Renk modunu alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Country](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/country) { get; set; } | Ülkeyi alır veya ayarlar. |
| [Credit](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/credit) { get; set; } | Krediyi alır veya ayarlar. |
| [DateCreated](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/datecreated) { get; set; } | Belgenin fikri içeriğinin oluşturulduğu tarihi alır veya ayarlar. |
| [Headline](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/headline) { get; set; } | Başlığı alır veya ayarlar. |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/history) { get; set; } | Uygulama tercihlerinde etkinleştirildiyse, FileInfo panelinde görünen geçmişi alır veya ayarlar. |
| [IccProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/iccprofile) { get; set; } | AppleRGB, AdobeRGB1998. gibi renk profilini alır veya ayarlar |
| [Instructions](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/instructions) { get; set; } | Özel talimatları alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ad alanı URI'sini alır. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns önekini alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/source) { get; set; } | Kaynağı alır veya ayarlar. |
| [State](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/state) { get; set; } | İl/eyaleti alır veya ayarlar. |
| [SupplementalCategories](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/supplementalcategories) { get; set; } | Ek kategorileri alır veya ayarlar. |
| [TransmissionReference](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/transmissionreference) { get; set; } | Orijinal iletim referansını alır veya ayarlar. |
| [Urgency](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgency) { get; set; } | Aciliyeti alır veya ayarlar. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | XML ad alanını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Tüm XMP özelliklerini kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | XMP değerini XML gösterimine dönüştürür. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Belirtilen ada sahip özelliği kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Boole özelliğini ayarlar. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | KümelerDateTime özellik. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Çift özelliği ayarlar. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Tamsayı özelliğini ayarlar. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/set#set_7)(string, string) | Dizi özelliğini ayarlar. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Miras alınan değeri ayarlar[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Miras alınan değeri ayarlar[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Miras alınan değeri ayarlar[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [UrgencyMax](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgencymax) | Aciliyet maks değeri. |
| const [UrgencyMin](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgencymin) | Aciliyet min değeri. |

### Ayrıca bakınız

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* ad alanı [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
