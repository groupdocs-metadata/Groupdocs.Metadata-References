---
title: XmpThumbnail
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir dosya için küçük resim görüntüsünü temsil eder.
type: docs
weight: 3580
url: /tr/net/groupdocs.metadata.standards.xmp/xmpthumbnail/
---
## XmpThumbnail class

Bir dosya için küçük resim görüntüsünü temsil eder.

```csharp
public sealed class XmpThumbnail : XmpComplexType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpThumbnail](xmpthumbnail#constructor)() | Yeni bir örneğini başlatır.[`XmpThumbnail`](../xmpthumbnail) sınıf. |
| [XmpThumbnail](xmpthumbnail#constructor_1)(int, int) | Yeni bir örneğini başlatır.[`XmpThumbnail`](../xmpthumbnail) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Format](../../groupdocs.metadata.standards.xmp/xmpthumbnail/format) { get; set; } | Görüntü biçimini alır veya ayarlar. Tanımlanan değer: JPEG. |
| [Height](../../groupdocs.metadata.standards.xmp/xmpthumbnail/height) { get; set; } | Görüntü yüksekliğini piksel cinsinden alır veya ayarlar. |
| [ImageBase64](../../groupdocs.metadata.standards.xmp/xmpthumbnail/imagebase64) { get; set; } | 64 tabanlı notasyona dönüştürülen tam küçük resim verisini alır veya ayarlar. |
| [ImageData](../../groupdocs.metadata.standards.xmp/xmpthumbnail/imagedata) { get; } | Görüntü verilerini alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Kullanılan ad alanı URI'lerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Kullanılan ad alanı öneklerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [Width](../../groupdocs.metadata.standards.xmp/xmpthumbnail/width) { get; set; } | Görüntü genişliğini piksel cinsinden alır veya ayarlar. |

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
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | a döndürürString bu örneği temsil eder. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Ayrıca bakınız

* class [XmpComplexType](../xmpcomplextype)
* ad alanı [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
