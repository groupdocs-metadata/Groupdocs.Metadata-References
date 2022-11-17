---
title: MsgRootPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir MSG eposta iletisinde meta verilerle çalışmaya izin veren kök paketi temsil eder.
type: docs
weight: 1410
url: /tr/net/groupdocs.metadata.formats.email/msgrootpackage/
---
## MsgRootPackage class

Bir MSG e-posta iletisinde meta verilerle çalışmaya izin veren kök paketi temsil eder.

```csharp
public class MsgRootPackage : EmailRootPackage
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [EmailPackage](../../groupdocs.metadata.formats.email/msgrootpackage/emailpackage) { get; } | MSG meta veri paketini alır. (2 properties) |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Meta veri paketi dosya türünü alır. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Şunu alır:[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) belirtilen ada sahip. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [ClearAttachments](../../groupdocs.metadata.formats.email/emailrootpackage/clearattachments)() | E-posta iletisindeki tüm ekleri kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [Kayıtlı E-postalarla çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Örnekler

Bu kod örneği, bir MSG mesajından meta verilerin nasıl çıkarılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMsg))
{
    var root = metadata.GetRootPackage<MsgRootPackage>();

    Console.WriteLine(root.EmailPackage.Sender);
    Console.WriteLine(root.EmailPackage.Subject);
    foreach (string recipient in root.EmailPackage.Recipients)
    {
        Console.WriteLine(recipient);
    }

    foreach (var attachedFileName in root.EmailPackage.AttachedFileNames)
    {
        Console.WriteLine(attachedFileName);
    }

    foreach (var header in root.EmailPackage.Headers)
    {
        Console.WriteLine("{0} = {1}", header.Name, header.Value);
    }

    Console.WriteLine(root.EmailPackage.Body);
    Console.WriteLine(root.EmailPackage.DeliveryTime);

    // ...
}
```

### Ayrıca bakınız

* class [EmailRootPackage](../emailrootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
