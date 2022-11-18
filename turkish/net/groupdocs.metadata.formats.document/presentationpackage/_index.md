---
title: PresentationPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir sunumdaki yerel meta veri paketini temsil eder.
type: docs
weight: 1090
url: /tr/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Bir sunumdaki yerel meta veri paketini temsil eder.

```csharp
public class PresentationPackage : DocumentPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Uygulama şablonunu alır veya ayarlar. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Belgenin yazarını alır veya ayarlar. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Kategoriyi alır veya ayarlar. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Yorumları alır veya ayarlar. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Şirketi alır veya ayarlar. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | İçerik durumunu alır veya ayarlar. Yalnızca bir PPTX belgesinde güncellenebilir. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | İçerik türünü alır veya ayarlar. Yalnızca bir PPTX belgesinde güncellenebilir. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Belgenin oluşturulma tarihini alır veya ayarlar. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Köprü tabanını alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Anahtar sözcükleri alır veya ayarlar. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Son yazdırılan tarihi alır veya ayarlar. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Son yazarın adını alır veya ayarlar. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Sunumun en son değiştirildiği tarihi ve saati alır. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Yöneticiyi alır veya ayarlar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Belgeyi oluşturan uygulamanın adını alır. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Sunum biçimini alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Revizyon numarasını alır veya ayarlar. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını gösteren bir değer alır veya ayarlar. Yalnızca bir PPTX belgesinde güncellenebilir. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Konuyu alır veya ayarlar. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Belgenin başlığını alır veya ayarlar. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Belgenin toplam düzenleme süresini alır veya ayarlar. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Uygulama sürümünü alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Tüm yazılabilir meta veri özelliklerini paketten kaldırır. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Tüm yerleşik meta veri özelliklerini kaldırır. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Tüm özel meta veri özelliklerini kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Belirtilen ada göre yazılabilir bir meta veri özelliğini kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [Sunumlarda meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Örnekler

Bu örnek, bir sunumdaki yerleşik meta veri özelliklerinin nasıl güncelleneceğini gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### Ayrıca bakınız

* class [DocumentPackage](../documentpackage)
* ad alanı [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
