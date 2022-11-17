---
title: VCardCommunicationRecordset
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir İletişim vCard kaydı kümesini temsil eder. Bu özellikler vCardın temsil ettiği nesneyle nasıl iletişim kurulacağına ilişkin bilgileri açıklar.
type: docs
weight: 660
url: /tr/net/groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/
---
## VCardCommunicationRecordset class

Bir İletişim vCard kaydı kümesini temsil eder. Bu özellikler, vCard'ın temsil ettiği nesneyle nasıl iletişim kurulacağına ilişkin bilgileri açıklar.

```csharp
public class VCardCommunicationRecordset : VCardRecordset
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [EmailRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emailrecords) { get; } | Nesne ile iletişim için elektronik posta adreslerini alır. |
| [Emails](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/emails) { get; } | Nesne ile iletişim için elektronik posta adreslerini alır. |
| [ImppEntries](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/imppentries) { get; } | Nesneyle anında mesajlaşma ve iletişim durumu protokolü iletişimleri için URI'leri alır. |
| [ImppRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/impprecords) { get; } | Nesneyle anında mesajlaşma ve iletişim durumu protokolü iletişimleri için URI'leri alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LanguageRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languagerecords) { get; } | Nesneyle bağlantı kurmak için kullanılabilecek dilleri alır. |
| [Languages](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/languages) { get; } | Nesneyle bağlantı kurmak için kullanılabilecek dilleri alır. |
| [Mailer](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/mailer) { get; } | vCard ile ilişkili kişi tarafından kullanılan elektronik posta yazılımının türünü alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [TelephoneRecords](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephonerecords) { get; } | Nesne ile telefon iletişimi için telefon numaralarını alır. |
| [Telephones](../../groupdocs.metadata.formats.businesscard/vcardcommunicationrecordset/telephones) { get; } | Nesne ile telefon iletişimi için telefon numaralarını alır. |

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

* [vCard meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Ayrıca bakınız

* class [VCardRecordset](../vcardrecordset)
* ad alanı [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
