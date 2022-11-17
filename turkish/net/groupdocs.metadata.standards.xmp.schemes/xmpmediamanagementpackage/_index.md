---
title: XmpMediaManagementPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: XMP Ortam Yönetimi ad alanını temsil eder.
type: docs
weight: 3170
url: /tr/net/groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/
---
## XmpMediaManagementPackage class

XMP Ortam Yönetimi ad alanını temsil eder.

```csharp
public sealed class XmpMediaManagementPackage : XmpPackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpMediaManagementPackage](xmpmediamanagementpackage)() | Yeni bir örneğini başlatır.[`XmpMediaManagementPackage`](../xmpmediamanagementpackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DerivedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/derivedfrom) { get; set; } | Bunun türetildiği kaynağa başvuruyu alır veya ayarlar. |
| [DocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/documentid) { get; set; } | Kaynağın tüm sürümleri ve yorumlamaları için ortak tanımlayıcıyı alır veya ayarlar. |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/history) { get; set; } | Bu kaynakla sonuçlanan bir dizi üst düzey eylemi alır veya ayarlar. |
| [Ingredients](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/ingredients) { get; set; } | Dahil etme veya gönderme yoluyla bu kaynağa dahil edilen kaynaklara yapılan başvuruları alır veya ayarlar. |
| [InstanceID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/instanceid) { get; set; } | Dosya her kaydedildiğinde güncellenen, bir kaynağın belirli bir enkarnasyonu için tanımlayıcıyı alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [ManagedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managedfrom) { get; set; } | Yönetilmeden önceki haliyle belgeye yapılan başvuruyu alır veya ayarlar. |
| [Manager](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manager) { get; set; } | Bu kaynağı yöneten varlık yönetimi sisteminin adını alır veya ayarlar. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managervariant) { get; set; } | Varlık yönetimi sisteminin belirli varyantını alır veya ayarlar. |
| [ManageTo](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageto) { get; set; } | Varlık yönetim sistemine yönetilen kaynağı tanımlayan URI'yi alır veya ayarlar |
| [ManageUI](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageui) { get; set; } | Bir web tarayıcısı aracılığıyla yönetilen kaynak hakkındaki bilgilere erişmek için kullanılabilecek URI'yi alır veya ayarlar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Ad alanı URI'sini alır. |
| [OriginalDocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/originaldocumentid) { get; set; } | Geçerli kaynağın türetildiği orijinal kaynak için ortak tanımlayıcıyı alır veya ayarlar. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns önekini alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionclass) { get; set; } | Bu kaynak için yorumlama sınıfı adını alır veya ayarlar. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionparams) { get; set; } | xmpMM:RenditionClass. içinde kodlamak için fazla karmaşık veya ayrıntılı olan ek yorumlama parametreleri sağlamak için kullanılan değeri alır veya ayarlar. |
| [VersionID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versionid) { get; set; } | Bu kaynak için belge sürümü tanımlayıcısını alır veya ayarlar. |
| [Versions](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versions) { get; set; } | Bu kaynakla ilişkili sürüm geçmişini alır veya ayarlar. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Miras alınan değeri ayarlar[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Miras alınan değeri ayarlar[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Miras alınan değeri ayarlar[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Ayrıca bakınız

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* ad alanı [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
