---
title: VCardExplanatoryRecordset
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Açıklayıcı vCard kayıtları kümesini temsil eder. Bu özellikler vCarda özgü bilgi notları veya revizyonlarla ilgili olanlar gibi ek açıklamalarla ilgilidir.
type: docs
weight: 710
url: /tr/net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/
---
## VCardExplanatoryRecordset class

Açıklayıcı vCard kayıtları kümesini temsil eder. Bu özellikler, vCard'a özgü bilgi notları veya revizyonlarla ilgili olanlar gibi ek açıklamalarla ilgilidir.

```csharp
public class VCardExplanatoryRecordset : VCardRecordset
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BinarySounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/binarysounds) { get; } | vCard. 'nin bazı yönlerine açıklama ekleyen dijital ses içeriği bilgilerini alır. |
| [Categories](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categories) { get; } | "etiketler" olarak da bilinen vCard hakkında uygulama kategorisi bilgilerini alır. |
| [CategoryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categoryrecords) { get; } | "etiketler" olarak da bilinen vCard hakkında uygulama kategorisi bilgilerini alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NoteRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/noterecords) { get; } | vCard. ile ilişkili ek bilgileri veya yorumları alır. |
| [Notes](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/notes) { get; } | vCard. ile ilişkili ek bilgileri veya yorumları alır. |
| [PidIdentifierRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifierrecords) { get; } | Yerel PID kaynak tanımlayıcısının genel anlamını alır. |
| [PidIdentifiers](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifiers) { get; } | Yerel PID kaynak tanımlayıcısının genel anlamını alır. |
| [ProductIdentifier](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifier) { get; } | vCard nesnesini oluşturan ürünün tanımlayıcısını alır. |
| [ProductIdentifierRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifierrecord) { get; } | vCard nesnesini oluşturan ürünün tanımlayıcısını alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Revision](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/revision) { get; } | Geçerli vCard. hakkında revizyon bilgilerini alır |
| [SortString](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sortstring) { get; } | Ulusal dile özgü sıralama için kullanılacak aile adını veya verilen ad metnini alır.[`FormattedNames`](../vcardidentificationrecordset/formattednames) Ve[`Name`](../vcardidentificationrecordset/name) türleri. |
| [SoundBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundbinaryrecords) { get; } | vCard. 'nin bazı yönlerine açıklama ekleyen dijital ses içeriği bilgilerini alır. |
| [SoundRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundrecords) { get; } | vCard. 'nin bazı yönlerine açıklama ekleyen dijital ses içeriği bilgilerini alır. |
| [SoundUriRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundurirecords) { get; } | vCard. 'nin bazı yönlerine açıklama ekleyen dijital ses içeriği bilgilerini alır. |
| [Uid](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid) { get; } | vCard. ile ilişkili kişi veya kaynağa karşılık gelen, genel olarak benzersiz bir tanımlayıcıyı temsil eden değeri alır. |
| [UidRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uidrecord) { get; } | vCard. ile ilişkili kişi veya kaynağa karşılık gelen, genel olarak benzersiz bir tanımlayıcıyı temsil eden değeri alır. |
| [UriSounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urisounds) { get; } | vCard. 'nin bazı yönlerine açıklama ekleyen dijital ses içeriği bilgilerini alır. |
| [UrlRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urlrecords) { get; } | Kişiyi bir şekilde temsil eden web sitelerine işaret eden bir dizi URL alır. |
| [Urls](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urls) { get; } | Kişiyi bir şekilde temsil eden web sitelerine işaret eden bir dizi URL alır. |
| [Version](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/version) { get; } | vCard belirtiminin sürümünü alır. |

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

**Daha fazla bilgi edin**

* [vCard meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Ayrıca bakınız

* class [VCardRecordset](../vcardrecordset)
* ad alanı [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
