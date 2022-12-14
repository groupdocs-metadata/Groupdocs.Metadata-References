---
title: DocumentTagCategory
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Yalnızca belgeye özgü özelliklere uygulanan etiketler sağlar. Etiketler bir özelliğin bir ofis belgesinin hangi bölümünden çıkarıldığını belirlemek için yararlı olabilir.
type: docs
weight: 3660
url: /tr/net/groupdocs.metadata.tagging/documenttagcategory/
---
## DocumentTagCategory class

Yalnızca belgeye özgü özelliklere uygulanan etiketler sağlar. Etiketler, bir özelliğin bir ofis belgesinin hangi bölümünden çıkarıldığını belirlemek için yararlı olabilir.

```csharp
public class DocumentTagCategory : TagCategory
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BuiltIn](../../groupdocs.metadata.tagging/documenttagcategory/builtin) { get; } | Etiketlediği özelliğin yerleşik olduğunu gösteren etiketi alır. |
| [Field](../../groupdocs.metadata.tagging/documenttagcategory/field) { get; } | Bir belgeden çıkarılan bir form alanı veya hesaplanan alan hakkında bilgi tutan bir özelliği gösteren etiketi alır. |
| [HiddenData](../../groupdocs.metadata.tagging/documenttagcategory/hiddendata) { get; } | Normal kullanıcılar için görünmeyen bir belge bölümünü gösteren etiketi alır. |
| [Page](../../groupdocs.metadata.tagging/documenttagcategory/page) { get; } | Bir belge sayfası hakkında bilgi tutan bir özelliği gösteren etiketi alır. |
| [ReadOnly](../../groupdocs.metadata.tagging/documenttagcategory/readonly) { get; } | Etiketlediği özelliğin salt okunur olduğunu ve GroupDocs.Metadata. tarafından değiştirilemeyeceğini belirten etiketi alır. |
| [Revision](../../groupdocs.metadata.tagging/documenttagcategory/revision) { get; } | Bir belge revizyonu (izlenen değişiklik) hakkında bilgi içeren bir özelliği etiketleyen etiketi alın. |
| [Statistic](../../groupdocs.metadata.tagging/documenttagcategory/statistic) { get; } | Belge istatistiklerini (kelime sayısı, karakter sayısı vb.) içeren bir özelliği gösteren etiketi alır. |
| [UserComment](../../groupdocs.metadata.tagging/documenttagcategory/usercomment) { get; } | Belge içeriğinde gösterilen kullanıcı yorumlarını etiketleyen etiketi alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [TagCategory](../tagcategory)
* ad alanı [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
