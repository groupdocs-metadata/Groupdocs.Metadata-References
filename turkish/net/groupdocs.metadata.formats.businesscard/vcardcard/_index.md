---
title: VCardCard
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir VCard dosyasından çıkarılan tek bir kartı temsil eder.
type: docs
weight: 650
url: /tr/net/groupdocs.metadata.formats.businesscard/vcardcard/
---
## VCardCard class

Bir VCard dosyasından çıkarılan tek bir kartı temsil eder.

```csharp
public class VCardCard : VCardRecordset
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CalendarRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/calendarrecordset) { get; } | Takvim kayıtlarını alır. |
| [CommunicationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/communicationrecordset) { get; } | İletişim kayıtlarını alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DeliveryAddressingRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/deliveryaddressingrecordset) { get; } | Teslimat adresleme kayıtlarını alır. |
| [ExplanatoryRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/explanatoryrecordset) { get; } | Açıklayıcı kayıtları alır. |
| [ExtensionRecords](../../groupdocs.metadata.formats.businesscard/vcardcard/extensionrecords) { get; } | Özel uzantı kayıtlarını alır. |
| [GeneralRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/generalrecordset) { get; } | Genel kayıtları alır. |
| [GeographicalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/geographicalrecordset) { get; } | Coğrafi kayıtları alır. |
| [IdentificationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/identificationrecordset) { get; } | Kimlik kayıtlarını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [OrganizationalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/organizationalrecordset) { get; } | Kuruluş kayıtlarını alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [SecurityRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/securityrecordset) { get; } | Güvenlik kayıtlarını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| [FilterByGroup](../../groupdocs.metadata.formats.businesscard/vcardcard/filterbygroup)(string) | Parametre olarak iletilen grup adına göre tüm vCard kayıtlarını filtreler. Daha fazla bilgi için lütfen bkz. yöntem. |
| [FilterHomeTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterhometags)() | HOME etiketiyle işaretlenmiş tüm vCard kayıtlarını filtreler. |
| [FilterPreferred](../../groupdocs.metadata.formats.businesscard/vcardcard/filterpreferred)() | Tercih edilen kayıtları filtreler. |
| [FilterWorkTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterworktags)() | WORK etiketiyle işaretlenmiş tüm vCard kayıtlarını filtreler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetAvailableGroups](../../groupdocs.metadata.formats.businesscard/vcardcard/getavailablegroups)() | Kullanılabilir grup adlarını alır. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [vCard meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Örnekler

Bu örnek, vCard özellik filtrelerinin nasıl kullanılacağını gösterir.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.InputVcf))
    {
        var root = metadata.GetRootPackage<VCardRootPackage>();

        foreach (var vCard in root.VCardPackage.Cards)
        {
            // En çok tercih edilen iş telefon numaralarını ve iş e-postalarını yazdırın
            var filtered = vCard.FilterWorkTags().FilterPreferred();
            PrintArray(filtered.CommunicationRecordset.Telephones);
            PrintArray(filtered.CommunicationRecordset.Emails);
        }
    }
}

private static void PrintArray(string[] values)
{
    if (values != null)
    {
        foreach (string value in values)
        {
            Console.WriteLine(value);
        }
    }
}
```

### Ayrıca bakınız

* class [VCardRecordset](../vcardrecordset)
* ad alanı [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
