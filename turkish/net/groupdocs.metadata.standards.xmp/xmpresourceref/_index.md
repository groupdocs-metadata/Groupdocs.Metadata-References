---
title: XmpResourceRef
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir kaynağa çok parçalı bir başvuruyu temsil eder. Önceki sürümleri yorumlamaların orijinallerini türetilmiş belgelerin orijinallerini vb. belirtmek için kullanılır.
type: docs
weight: 3550
url: /tr/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Bir kaynağa çok parçalı bir başvuruyu temsil eder. Önceki sürümleri, yorumlamaların orijinallerini, türetilmiş belgelerin orijinallerini vb. belirtmek için kullanılır.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Yeni bir örneğini başlatır.[`XmpResourceRef`](../xmpresourceref) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Başvurulan kaynağın yedek dosya yollarını veya URL'lerini alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Başvurulan kaynaktan xmpMM:DocumentID özelliğinin değerini alır veya ayarlar. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Başvurulan kaynağın dosya yolunu veya URL'sini alır veya ayarlar. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Başvurulan kaynaktan xmpMM:InstanceID özelliğinin değerini alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Dosyanın en son yazıldığı zaman stEvt değerini alır veya ayarlar. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Başvurulan kaynağın xmpMM:Manager'ını alır veya ayarlar. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Başvurulan kaynağın xmpMM:Manager'ını alır veya ayarlar. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Başvurulan kaynağın xmpMM:ManageTo değerini alır veya ayarlar. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Başvurulan kaynağın xmpMM:ManageUI. değerini alır veya ayarlar |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Kullanılan ad alanı URI'lerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | fromPart'ı toPart'a eşlemek için kullanılan bir eşleme işlevinin adını veya URI'sini alır veya ayarlar. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Kullanılan ad alanı öneklerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Başvurulan kaynaktan xmpMM:RenditionClass özelliğinin değerini alır veya ayarlar. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Başvurulan kaynaktan xmpMM:RenditionParams özelliğinin değerini alır veya ayarlar. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Başvurulan kaynaktan xmpMM:RenditionParams özelliğinin değerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Belirtilen önekle ilişkili ad alanı URI'sini alır. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | XMP biçiminde dizge içerdiği değeri döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | a döndürürString bu örneği temsil eder. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Ayrıca bakınız

* class [XmpComplexType](../xmpcomplextype)
* ad alanı [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
