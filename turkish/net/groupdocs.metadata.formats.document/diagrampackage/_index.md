---
title: DiagramPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Diyagram biçiminde yerel bir meta veri paketini temsil eder.
type: docs
weight: 890
url: /tr/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Diyagram biçiminde yerel bir meta veri paketini temsil eder.

```csharp
public class DiagramPackage : DocumentPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Belge için alternatif adları alır veya ayarlar. Yalnızca VDX ve VSX biçimlerinde güncellenebilir. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Belgeyi oluşturmak için kullanılan örneğin tam yapı numarasını alır. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Belgeyi düzenlemek için en son kullanılan örneğin yapı numarasını alır. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Akış şeması veya ofis düzeni gibi çizim türü için açıklayıcı metni alır veya ayarlar. Bu metin, Özellikler iletişim kutusundaki Kategori kutusuna Microsoft Visio kullanıcı arabiriminde de girilebilir. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Çizimi oluşturan şirketi veya çizimin kendisi için oluşturulmakta olan şirketi tanımlayan, kullanıcı tarafından girilen bilgileri alır veya ayarlar. Maksimum uzunluk 63 karakterdir. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Dosyayı oluşturan veya en son güncelleyen kişiyi alır veya ayarlar. Maksimum uzunluk 63 karakterdir.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Belge için açıklayıcı bir metin dizesi alır veya ayarlar. Belgeyle ilgili amacı, son değişiklikler veya bekleyen değişiklikler gibi önemli bilgileri depolamak için bu öğeyi kullanın. Maksimum 191 karakterdir. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Göreli köprüler için kullanılacak yolu alır veya ayarlar (bağlı dosya konumunun Microsoft Visio diyagramına göre açıklandığı köprüler). Varsayılan olarak, farklı bir yol belirtilmedikçe köprü yolu geçerli belgeye göredir bu öğede. Maksimum uzunluk 256 karakterdir. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Konuları veya dosyayla ilgili proje adı, müşteri adı veya sürüm numarası gibi diğer önemli bilgileri tanımlayan bir metin dizesi alır veya ayarlar. Maksimum dize uzunluğu 63 karakterdir. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Belgenin dilini alır veya ayarlar. Yalnızca VSD ve VSDX biçimlerinde güncellenebilir. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Proje veya departmandan sorumlu kişiyi tanımlayan, kullanıcı tarafından girilen bir metin dizisini alır veya ayarlar. Maksimum uzunluk 63 karakterdir. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Önizleme resmini alır veya ayarlar. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Belgenin içeriğini açıklayan kullanıcı tanımlı bir metin dizesi alır veya ayarlar. Maksimum uzunluk 63 karakterdir. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Belgenin oluşturulduğu şablonun dosya adını belirten bir dize değeri alır veya ayarlar. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Belgenin ne zaman oluşturulduğunu gösteren bir tarih ve saat değeri alır veya ayarlar. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Belgenin en son ne zaman düzenlendiğini gösteren bir tarih ve saat değeri alır. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Belgenin en son ne zaman yazdırıldığını gösteren bir tarih ve saat değeri alır. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Belgenin en son ne zaman kaydedildiğini gösteren bir tarih ve saat değeri alır. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Belge için açıklayıcı bir başlık işlevi gören kullanıcı tanımlı bir metin dizesi alır veya ayarlar. Maksimum uzunluk 63 karakterdir. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Metadata özelliğini belirtilen adla ekler veya değiştirir. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [Diyagramlarda meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Örnekler

Bu kod örneği, yerleşik meta veri özelliklerinin bir diyagramdan nasıl çıkarılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Ayrıca bakınız

* class [DocumentPackage](../documentpackage)
* ad alanı [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
