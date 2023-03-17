---
title: NoteRootPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket akar dimaksudkan untuk bekerja dengan metadata dalam file catatan elektronik.
type: docs
weight: 970
url: /id/net/groupdocs.metadata.formats.document/noterootpackage/
---
## NoteRootPackage class

Merupakan paket akar dimaksudkan untuk bekerja dengan metadata dalam file catatan elektronik.

```csharp
public class NoteRootPackage : RootMetadataPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/noterootpackage/documentstatistics) { get; } | Mendapatkan paket statistik dokumen. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Mendapatkan paket metadata tipe file. |
| [InspectionPackage](../../groupdocs.metadata.formats.document/noterootpackage/inspectionpackage) { get; } | Mendapat paket metadata yang berisi hasil pemeriksaan untuk dokumen tersebut. Paket tersebut berisi informasi tentang bagian dokumen yang dapat dianggap sebagai metadata dalam beberapa kasus. |
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

* [Bekerja dengan metadata dalam format Catatan](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Note+formats)

### Contoh

Contoh kode ini menunjukkan cara memeriksa dokumen catatan.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    var root = metadata.GetRootPackage<NoteRootPackage>();

    if (root.InspectionPackage.Pages != null)
    {
        foreach (var page in root.InspectionPackage.Pages)
        {
            Console.WriteLine(page.Title);
            Console.WriteLine(page.Author);
            Console.WriteLine(page.CreationTime);
            Console.WriteLine(page.LastModificationTime);
        }
    }
}
```

### Lihat juga

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
