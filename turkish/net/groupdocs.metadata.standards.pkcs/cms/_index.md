---
title: Cms
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Şifreleme İleti Sözdizimi CMS  IETFnin kriptografik olarak korunan iletiler standardı ile oluşturulmuş bir dijital işareti temsil eder. CMS RFC 5652. de belirtilen PKCS 7 sözdizimini temel alır. Lütfen bkz.https//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 daha fazla bilgi için.
type: docs
weight: 2960
url: /tr/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Şifreleme İleti Sözdizimi (CMS) - IETF'nin kriptografik olarak korunan iletiler standardı ile oluşturulmuş bir dijital işareti temsil eder. CMS, RFC 5652. 'de belirtilen PKCS #7 sözdizimini temel alır. Lütfen bkz.[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) daha fazla bilgi için.

```csharp
public class Cms : DigitalSignature
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Sertifika ham verilerini alır. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Sertifika koleksiyonunu alır. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Bir sertifikadan konu ayırt edici adını alır. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | İmzalama amacı yorumunu alır. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | İleti özet algoritma tanımlayıcılarının dizisini alır. Koleksiyonda, zero. dahil olmak üzere herhangi bir sayıda öğe olabilir. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Bir içerik türü tanımlayıcısından ve içeriğin kendisinden oluşan imzalı içeriği alır. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | İmzanın geçerli olup olmadığını gösteren bir değer alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | İmzalayan başına bilgi paketlerinin toplanmasını alır. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | İmzalayanın (sözde) imzalama işlemini gerçekleştirdiği zamanı alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Ayrıca bakınız

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* ad alanı [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
