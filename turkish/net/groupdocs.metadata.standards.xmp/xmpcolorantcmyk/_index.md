---
title: XmpColorantCmyk
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: CMYK Renklendiriciyi Temsil Eder.
type: docs
weight: 3310
url: /tr/net/groupdocs.metadata.standards.xmp/xmpcolorantcmyk/
---
## XmpColorantCmyk class

CMYK Renklendiriciyi Temsil Eder.

```csharp
public sealed class XmpColorantCmyk : XmpColorantBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpColorantCmyk](xmpcolorantcmyk#constructor)() | Yeni bir örneğini başlatır.[`XmpColorantCmyk`](../xmpcolorantcmyk) sınıf. |
| [XmpColorantCmyk](xmpcolorantcmyk#constructor_1)(double, double, double, double) | Yeni bir örneğini başlatır.[`XmpColorantCmyk`](../xmpcolorantcmyk) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Black](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/black) { get; set; } | Siyah bileşeni alır veya ayarlar. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Rengin türünü alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Cyan](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/cyan) { get; set; } | Cyan bileşenini alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Magenta](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/magenta) { get; set; } | Macenta bileşeni alır veya ayarlar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Rengin tanımlandığı renk uzayını alır. Şunlardan biri: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Kullanılan ad alanı URI'lerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Kullanılan ad alanı öneklerini alır.[`XmpComplexType`](../xmpcomplextype) örnek. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Renk örneğinin adını alır veya ayarlar. |
| [Yellow](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/yellow) { get; set; } | Sarı bileşeni alır veya ayarlar. |

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

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [ColorValueMax](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/colorvaluemax) | CMYK renklendiricide maksimum renk değeri. |
| const [ColorValueMin](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/colorvaluemin) | CMYK renklendiricide minimum renk değeri. |

### Ayrıca bakınız

* class [XmpColorantBase](../xmpcolorantbase)
* ad alanı [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
