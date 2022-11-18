---
title: MsgPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: MSG mesajı meta verilerini temsil eder.
type: docs
weight: 1400
url: /tr/net/groupdocs.metadata.formats.email/msgpackage/
---
## MsgPackage class

MSG mesajı meta verilerini temsil eder.

```csharp
public class MsgPackage : EmailPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | Ekli dosyaların adlarının bir dizisini alır. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | E-posta mesajının BCC (gizli karbon kopya) alıcı dizisini alır veya ayarlar. |
| [Body](../../groupdocs.metadata.formats.email/msgpackage/body) { get; } | E-posta mesajı metnini alır. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | E-posta mesajının CC (karbon kopya) alıcı dizisini alır veya ayarlar. |
| [Categories](../../groupdocs.metadata.formats.email/msgpackage/categories) { get; } | Kategorilerin veya anahtar sözcüklerin dizisini alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DeliveryTime](../../groupdocs.metadata.formats.email/msgpackage/deliverytime) { get; } | Mesajın teslim edildiği tarih ve saati alır. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | E-posta başlıklarını içeren bir meta veri paketi alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | E-posta alıcılarının dizisini alır veya ayarlar. |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | Gönderenin e-posta adresini alır. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | E-posta konusunu alır veya ayarlar. |

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

* [Kayıtlı E-postalarla çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Ayrıca bakınız

* class [EmailPackage](../emailpackage)
* ad alanı [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
