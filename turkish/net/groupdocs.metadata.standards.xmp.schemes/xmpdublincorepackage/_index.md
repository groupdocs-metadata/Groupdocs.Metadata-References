---
title: XmpDublinCorePackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Dublin Core şemasını temsil eder.
type: docs
weight: 3120
url: /tr/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

Dublin Core şemasını temsil eder.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | Yeni bir örneğini başlatır.[`XmpDublinCorePackage`](../xmpdublincorepackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | Katkıda bulunanların bir dizisini alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | Kaynağın kapsamını veya kapsamını alır veya ayarlar. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | Yaratıcıların bir dizisini alır veya ayarlar. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | Kaynağın yaşam döngüsündeki bir olayla ilişkili bir dizi tarih alır veya ayarlar. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | Çeşitli dillerde verilen, kaynağın içeriğinin bir dizi metinsel açıklamasını alır veya ayarlar. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | Kaynağın MIME türünü alır veya ayarlar. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | Belirli bir bağlamda kaynağa açık bir başvuruyu temsil eden bir dize değeri alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | Kaynağın içeriğinde kullanılan dil dizisini alır veya ayarlar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ad alanı URI'sini alır. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns önekini alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | Kaynağı kullanılabilir hale getiren bir yayıncı dizisini alır veya ayarlar. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | İlgili kaynakların bir dizisini alır veya ayarlar. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | Çeşitli dillerde verilen resmi olmayan hak bildirimlerinin bir dizisini alır veya ayarlar. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | Tanımlanan kaynağın türetildiği ilgili kaynağı alır veya ayarlar. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | Kaynağın içeriğini belirten bir dizi açıklayıcı ifade veya anahtar sözcük alır veya ayarlar. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | Çeşitli dillerde verilen kaynağın başlığını veya adını alır veya ayarlar. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | Kaynağın doğasını veya türünü temsil eden bir dizi dize değeri alır veya ayarlar. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Dizi özelliğini ayarlar. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | Miras alınan değeri ayarlar[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Miras alınan değeri ayarlar[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Miras alınan değeri ayarlar[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | Kaynağın tek bir katılımcısını ayarlar. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | Kaynağın tek bir oluşturucusunu ayarlar. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | Kaynakla ilişkili tek bir tarih ayarlar. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | Tek bir dilde verilen kaynak açıklamasını ayarlar. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | Kaynakla ilişkili tek bir dil ayarlar. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | Kaynağın tek bir yayıncısını ayarlar. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | İlgili tek bir kaynak ayarlar. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | Tek bir dilde verilen kaynak haklarını ayarlar. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | Kaynağın tek konusunu ayarlar. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | Tek bir dilde verilen kaynak başlığını ayarlar. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | Tek bir kaynak türü ayarlar. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

Daha fazla bilgi için bakınız: http://dublincore.org/documents/usageguide/elements.shtml.

### Ayrıca bakınız

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* ad alanı [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
