---
title: PropertyTypeTagCategory
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir özelliğin amacından ziyade türü hakkında ek bilgi içeren etiketler sağlar. Bu etiketleri kullanarak harici kaynaklara URL bağlantıları içeren meta veri özelliklerini yazı tiplerini renkleri coğrafi konumu vb. açıklayan özelliklerini tespit edebilirsiniz.
type: docs
weight: 3710
url: /tr/net/groupdocs.metadata.tagging/propertytypetagcategory/
---
## PropertyTypeTagCategory class

Bir özelliğin amacından ziyade türü hakkında ek bilgi içeren etiketler sağlar. Bu etiketleri kullanarak, harici kaynaklara URL bağlantıları içeren meta veri özelliklerini, yazı tiplerini, renkleri, coğrafi konumu vb. açıklayan özelliklerini tespit edebilirsiniz.

```csharp
public class PropertyTypeTagCategory : TagCategory
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Color](../../groupdocs.metadata.tagging/propertytypetagcategory/color) { get; } | Bir rengi açıklayan bir özelliği etiketleyen etiketi alır. |
| [DigitalSignature](../../groupdocs.metadata.tagging/propertytypetagcategory/digitalsignature) { get; } | Bir dijital imzayı etiketleyen etiketi alır. |
| [Font](../../groupdocs.metadata.tagging/propertytypetagcategory/font) { get; } | Yazı tipi özelliklerini açıklayan bir özelliği gösteren etiketi alır. |
| [Hash](../../groupdocs.metadata.tagging/propertytypetagcategory/hash) { get; } | Dosya içeriğinin karmasını tutan bir özelliği etiketleyen etiketi alır. |
| [Identifier](../../groupdocs.metadata.tagging/propertytypetagcategory/identifier) { get; } | İçeriğin tanımlayıcısını içeren bir özelliği etiketleyen etiketi alır. |
| [Link](../../groupdocs.metadata.tagging/propertytypetagcategory/link) { get; } | Bir özelliğin harici bir kaynağa bağlantı olduğunu gösteren etiketi alır. |
| [Location](../../groupdocs.metadata.tagging/propertytypetagcategory/location) { get; } | Bir özelliğin coğrafi konuma referans olduğunu gösteren etiketi alır. Özellik bir şehrin adını, tam adresini, GPS koordinatlarını vb. içerebilir. |
| [Measure](../../groupdocs.metadata.tagging/propertytypetagcategory/measure) { get; } | Bir özelliğin içeriğin ölçülü bir özelliği olduğunu gösteren etiketi alır. Dosya boyutu, sayfa sayısı, sayfa boyutu vb. olabilir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [TagCategory](../tagcategory)
* ad alanı [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->