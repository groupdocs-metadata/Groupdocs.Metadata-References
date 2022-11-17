---
title: ProjectManagementPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir proje yönetim dosyasındaki yerel meta veri paketini temsil eder.
type: docs
weight: 1130
url: /tr/net/groupdocs.metadata.formats.document/projectmanagementpackage/
---
## ProjectManagementPackage class

Bir proje yönetim dosyasındaki yerel meta veri paketini temsil eder.

```csharp
public sealed class ProjectManagementPackage : DocumentPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/projectmanagementpackage/author) { get; set; } | Projenin yazarını alır veya ayarlar. |
| [Category](../../groupdocs.metadata.formats.document/projectmanagementpackage/category) { get; set; } | Kategoriyi alır veya ayarlar. |
| [Comments](../../groupdocs.metadata.formats.document/projectmanagementpackage/comments) { get; set; } | Kullanıcı yorumlarını alır veya ayarlar. |
| [Company](../../groupdocs.metadata.formats.document/projectmanagementpackage/company) { get; set; } | Şirketi alır veya ayarlar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [CreationDate](../../groupdocs.metadata.formats.document/projectmanagementpackage/creationdate) { get; set; } | Oluşturma tarihini alır veya ayarlar. |
| [Guid](../../groupdocs.metadata.formats.document/projectmanagementpackage/guid) { get; set; } | Projenin kimliğini alır veya ayarlar. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/projectmanagementpackage/hyperlinkbase) { get; set; } | Köprü tabanını alır veya ayarlar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Keywords](../../groupdocs.metadata.formats.document/projectmanagementpackage/keywords) { get; set; } | Anahtar sözcükleri alır veya ayarlar. |
| [LastAuthor](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastauthor) { get; set; } | Son yazarı alır veya ayarlar. |
| [LastPrinted](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastprinted) { get; set; } | Projenin son yazdırma zamanını alır veya ayarlar. |
| [LastSaved](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastsaved) { get; set; } | Projenin en son kaydedildiği tarihi alır veya ayarlar. |
| [Manager](../../groupdocs.metadata.formats.document/projectmanagementpackage/manager) { get; set; } | Proje yöneticisini alır veya ayarlar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Revision](../../groupdocs.metadata.formats.document/projectmanagementpackage/revision) { get; set; } | Revizyon numarasını alır veya ayarlar. |
| [SaveVersion](../../groupdocs.metadata.formats.document/projectmanagementpackage/saveversion) { get; } | Bir proje dosyasının kaydedildiği Microsoft Office Project sürümünü alır. |
| [Subject](../../groupdocs.metadata.formats.document/projectmanagementpackage/subject) { get; set; } | Konuyu alır veya ayarlar. |
| [Template](../../groupdocs.metadata.formats.document/projectmanagementpackage/template) { get; set; } | Şablonu alır veya ayarlar. |
| [Title](../../groupdocs.metadata.formats.document/projectmanagementpackage/title) { get; set; } | Başlığı alır veya ayarlar. |

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
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set)(string, bool) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_3)(string, DateTime) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_1)(string, double) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_2)(string, int) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_4)(string, string) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [ProjectManagement formatlarında meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+ProjectManagement+formats)

### Örnekler

Bu kod örneği, bir ProjectManagement belgesindeki yerleşik özelliklerin nasıl güncelleneceğini gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMpp))
{
    var root = metadata.GetRootPackage<ProjectManagementRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreationDate = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Comments = "test comment";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputMpp);
}
```

### Ayrıca bakınız

* class [DocumentPackage](../documentpackage)
* ad alanı [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
