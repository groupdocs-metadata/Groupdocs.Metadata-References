---
title: VCardOrganizationalRecordset
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir Kurumsal vCard kayıtları kümesini temsil eder. Bu özellikler vCardın temsil ettiği nesnenin kuruluşunun veya kuruluş birimlerinin özellikleriyle ilişkili bilgilerle ilgilidir.
type: docs
weight: 750
url: /tr/net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/
---
## VCardOrganizationalRecordset class

Bir Kurumsal vCard kayıtları kümesini temsil eder. Bu özellikler, vCard'ın temsil ettiği nesnenin kuruluşunun veya kuruluş birimlerinin özellikleriyle ilişkili bilgilerle ilgilidir.

```csharp
public class VCardOrganizationalRecordset : VCardRecordset
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AgentObjectRecord](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentobjectrecord) { get; } | vCard nesnesi adına hareket edecek başka bir kişi hakkında bilgi alır. |
| [AgentRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentrecords) { get; } | vCard nesnesi adına hareket edecek başka bir kişi hakkında bilgi alır. |
| [AgentUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agenturirecords) { get; } | vCard nesnesi adına hareket edecek başka bir kişi hakkında bilgi alır. |
| [BinaryLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/binarylogos) { get; } | Nesneyle ilişkili logonun grafik görüntülerini alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LogoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logobinaryrecords) { get; } | Nesneyle ilişkili logonun grafik görüntülerini alır. |
| [LogoRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logorecords) { get; } | Nesneyle ilişkili logonun grafik görüntülerini alır. |
| [LogoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logourirecords) { get; } | Nesneyle ilişkili logonun grafik görüntülerinin URI'lerini alır. |
| [MemberRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/memberrecords) { get; } | Bu vCard'ın temsil ettiği gruptaki üyeleri alır. |
| [Members](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/members) { get; } | Bu vCard'ın temsil ettiği gruptaki üyeleri alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [ObjectAgent](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/objectagent) { get; } | vCard nesnesi adına hareket edecek başka bir kişi hakkında bilgi alır. |
| [OrganizationNameRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnamerecords) { get; } | Nesneyle ilişkili kuruluş adlarını ve birimleri alır. |
| [OrganizationNames](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnames) { get; } | Nesneyle ilişkili kuruluş adlarını ve birimleri alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [RelationshipRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationshiprecords) { get; } | Başka bir varlık ile bu vCard tarafından temsil edilen varlık arasındaki ilişkileri alır. |
| [Relationships](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationships) { get; } | Başka bir varlık ile bu vCard tarafından temsil edilen varlık arasındaki ilişkileri alır. |
| [RoleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/rolerecords) { get; } | Belirli bir durumda nesne tarafından oynanan işlevleri veya parçaları alır. |
| [Roles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/roles) { get; } | Belirli bir durumda nesne tarafından oynanan işlevleri veya parçaları alır. |
| [TitleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titlerecords) { get; } | Nesnenin konumlarını veya işlerini alır. |
| [Titles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titles) { get; } | Nesnenin konumlarını veya işlerini alır. |
| [UriAgents](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uriagents) { get; } | vCard nesnesi adına hareket edecek başka bir kişi hakkında bilgi alır. |
| [UriLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/urilogos) { get; } | Nesneyle ilişkili logonun grafik görüntülerinin URI'lerini alır. |

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
