---
title: SpreadsheetRootPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir elektronik tabloda meta verilerle çalışmaya izin veren kök paketi temsil eder.
type: docs
weight: 1210
url: /tr/net/groupdocs.metadata.formats.document/spreadsheetrootpackage/
---
## SpreadsheetRootPackage class

Bir elektronik tabloda meta verilerle çalışmaya izin veren kök paketi temsil eder.

```csharp
public class SpreadsheetRootPackage : DocumentRootPackage<SpreadsheetPackage>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Belgede sunulan yerel meta veri özelliklerini alır. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/spreadsheetrootpackage/documentstatistics) { get; } | Belge istatistikleri paketini alır. |
| [FileType](../../groupdocs.metadata.formats.document/spreadsheetrootpackage/filetype) { get; } | Meta veri paketi dosya türünü alır. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/spreadsheetrootpackage/inspectionpackage) { get; } | Belge için inceleme sonuçlarını içeren bir meta veri paketi alır. Paket, bazı durumlarda meta veri olarak kabul edilebilecek belge bölümleri hakkında bilgi içerir. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren tanımlayıcılardan oluşan bir koleksiyon alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [Elektronik Tablolarda meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Örnekler

Bu kod parçacığı, yerleşik meta veri özelliklerinin bir elektronik tablodan nasıl çıkarılacağını gösterir.

```csharp
/// (Meta veri meta verisi = yeni Meta veri (Constants.InputXlsx)) kullanılarak
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedTime);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Category);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.ContentType);

    // ... 
}
```

### Ayrıca bakınız

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [SpreadsheetPackage](../spreadsheetpackage)
* ad alanı [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
