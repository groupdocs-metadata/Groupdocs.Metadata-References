---
title: XmpFont
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Belgede kullanılan bir yazı tipinin özelliklerini içeren bir yapı.
type: docs
weight: 3400
url: /tr/net/groupdocs.metadata.standards.xmp/xmpfont/
---
## XmpFont class

Belgede kullanılan bir yazı tipinin özelliklerini içeren bir yapı.

```csharp
public sealed class XmpFont : XmpComplexType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpFont](xmpfont#constructor)() | Yeni bir örneğini başlatır.[`XmpFont`](../xmpfont) sınıf. |
| [XmpFont](xmpfont#constructor_1)(string) | Yeni bir örneğini başlatır.[`XmpFont`](../xmpfont) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ChildFontFiles](../../groupdocs.metadata.standards.xmp/xmpfont/childfontfiles) { get; set; } | Bileşik bir yazı tipini oluşturan yazı tiplerinin dosya adlarının listesini alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [FontFace](../../groupdocs.metadata.standards.xmp/xmpfont/fontface) { get; set; } | Yazı tipi yüz adını alır veya ayarlar. |
| [FontFamily](../../groupdocs.metadata.standards.xmp/xmpfont/fontfamily) { get; set; } | Yazı tipi aile adını alır veya ayarlar. |
| [FontFileName](../../groupdocs.metadata.standards.xmp/xmpfont/fontfilename) { get; set; } | Yazı tipi dosyası adını alır veya ayarlar (tam bir yol değil). |
| [FontName](../../groupdocs.metadata.standards.xmp/xmpfont/fontname) { get; set; } | Yazı tipinin PostScript adını alır veya ayarlar. |
| [FontType](../../groupdocs.metadata.standards.xmp/xmpfont/fonttype) { get; set; } | Yazı tipi türünü alır veya ayarlar. |
| [IsComposite](../../groupdocs.metadata.standards.xmp/xmpfont/iscomposite) { get; set; } | Yazı tipinin bileşik olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Kullanılan ad alanı URI'lerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Kullanılan ad alanı öneklerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Version](../../groupdocs.metadata.standards.xmp/xmpfont/version) { get; set; } | Yazı tipi sürümünü alır veya ayarlar. |

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
