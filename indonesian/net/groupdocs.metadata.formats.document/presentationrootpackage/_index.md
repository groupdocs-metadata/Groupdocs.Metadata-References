---
title: PresentationRootPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket root yang ditujukan untuk bekerja dengan metadata dalam presentasi.
type: docs
weight: 1100
url: /id/net/groupdocs.metadata.formats.document/presentationrootpackage/
---
## PresentationRootPackage class

Mewakili paket root yang ditujukan untuk bekerja dengan metadata dalam presentasi.

```csharp
public class PresentationRootPackage : DocumentRootPackage<PresentationPackage>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Mendapat properti metadata asli yang disajikan dalam dokumen. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/presentationrootpackage/documentstatistics) { get; } | Mendapatkan paket statistik dokumen. |
| [FileType](../../groupdocs.metadata.formats.document/presentationrootpackage/filetype) { get; } | Mendapatkan paket metadata tipe file. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/presentationrootpackage/inspectionpackage) { get; } | Mendapat paket metadata yang berisi hasil pemeriksaan untuk dokumen tersebut. Paket tersebut berisi informasi tentang bagian dokumen yang dapat dianggap sebagai metadata dalam beberapa kasus. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata di Presentasi](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Contoh

Contoh ini menunjukkan cara mengekstrak properti metadata bawaan dari presentasi.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedTime);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Category);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.LastPrintedDate);
    Console.WriteLine(root.DocumentProperties.NameOfApplication);

    // ... 
}
```

### Lihat juga

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [PresentationPackage](../presentationpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
