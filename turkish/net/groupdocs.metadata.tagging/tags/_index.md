---
title: Tags
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: En önemli meta veri özelliklerinin işaretlendiği çeşitli etiket kümeleri içerir. Etiketler meta veri standardı ve dosya biçiminden bağımsız olarak farklı paketlerdeki meta veri özelliklerini bulmanızı ve güncellemenizi sağlar.
type: docs
weight: 3730
url: /tr/net/groupdocs.metadata.tagging/tags/
---
## Tags class

En önemli meta veri özelliklerinin işaretlendiği çeşitli etiket kümeleri içerir. Etiketler, meta veri standardı ve dosya biçiminden bağımsız olarak farklı paketlerdeki meta veri özelliklerini bulmanızı ve güncellemenizi sağlar.

```csharp
public static class Tags
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [Content](../../groupdocs.metadata.tagging/tags/content) { get; } | Bir dosyanın içeriğini açıklayan meta veri özelliklerine eklenen etiketleri alır. Etiketler, içerik dilini, türünü (tür), konuyu, derecelendirmeyi vb. öğrenmek için kullanışlıdır. |
| static [Corporate](../../groupdocs.metadata.tagging/tags/corporate) { get; } | Dosya oluşturmaya katılan bir şirketle ilgili meta veri özelliklerini işaretlemeyi amaçlayan bir dizi etiket alır. |
| static [Document](../../groupdocs.metadata.tagging/tags/document) { get; } | Yalnızca belgeye özgü özelliklere uygulanan bir dizi etiket alır. Etiketler, bir özelliğin bir ofis belgesinin hangi bölümünden çıkarıldığını belirlemek için yararlı olabilir. |
| static [Legal](../../groupdocs.metadata.tagging/tags/legal) { get; } | dosya içeriğinin sahipleri ve içeriğin kullanılabileceği kurallar hakkında bilgi tutan meta veri özelliklerine eklenmiş bir dizi etiket alır. |
| static [Origin](../../groupdocs.metadata.tagging/tags/origin) { get; } | Kullanıcının bir dosyanın kaynağını (örn. şablon veya başka bir kaynak) belirlemesine yardımcı olan etiketleri alır. |
| static [Person](../../groupdocs.metadata.tagging/tags/person) { get; } | Dosya veya entelektüel içerik oluşturmaya katkıda bulunan kişiler hakkında bilgi tutan meta veri özelliklerini işaretleyen bir dizi etiket alır. Bu etiketler, belge oluşturucuyu, düzenleyiciyi ve hatta işin gerçekleştirildiği müşteriyi bulmanıza yardımcı olabilir. Kategorinin adına rağmen, etiketlerle işaretlenen bazı meta veri özellikleri kişi adı yerine şirket adı içerebilir. |
| static [PropertyType](../../groupdocs.metadata.tagging/tags/propertytype) { get; } | Bir özelliğin amacından ziyade türü hakkında ek bilgi taşıyan bir dizi etiket alır. Bu etiketleri kullanarak, harici kaynaklara URL bağlantıları içeren meta veri özelliklerini, yazı tiplerini, renkleri, coğrafi konumu vb. açıklayan özelliklerini tespit edebilirsiniz. . |
| static [Time](../../groupdocs.metadata.tagging/tags/time) { get; } | Bir dosyanın yaşam döngüsünü açıklamak için kullanılan meta veri özelliklerini işaretleyen bir dizi etiket alır. Etiketler, bir dosyanın veya fikri içeriğin oluşturulduğu, düzenlendiği, yazdırıldığı vb. zaman noktalarını ele alır. |
| static [Tool](../../groupdocs.metadata.tagging/tags/tool) { get; } | Dosya oluşturmak için kullanılan araçlarla (yazılım ve donanım) ilgili meta veri özelliklerini işaretlemeyi amaçlayan etiketleri alır. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
