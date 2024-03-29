---
title: RemoveProperties
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Menghapus properti metadata yang memenuhi predikat yang ditentukan.
type: docs
weight: 110
url: /id/net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties/
---
## WordProcessingInspectionPackage.RemoveProperties method

Menghapus properti metadata yang memenuhi predikat yang ditentukan.

```csharp
public override int RemoveProperties(Func<MetadataProperty, bool> predicate)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| predicate | Func`2 | Fungsi untuk menguji setiap properti metadata untuk suatu kondisi. |

### Nilai Pengembalian

Jumlah properti yang terpengaruh.

### Lihat juga

* delegate [Func&lt;T,TResult&gt;](../../../groupdocs.metadata.common/func-2)
* class [MetadataProperty](../../../groupdocs.metadata.common/metadataproperty)
* class [WordProcessingInspectionPackage](../../wordprocessinginspectionpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../wordprocessinginspectionpackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
