---
title: CadRootPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket root yang memungkinkan bekerja dengan metadata dalam gambar CAD.
type: docs
weight: 850
url: /id/net/groupdocs.metadata.formats.cad/cadrootpackage/
---
## CadRootPackage class

Mewakili paket root yang memungkinkan bekerja dengan metadata dalam gambar CAD.

```csharp
public abstract class CadRootPackage : RootMetadataPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CadPackage](../../groupdocs.metadata.formats.cad/cadrootpackage/cadpackage) { get; } | Mendapatkan paket metadata CAD. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Mendapatkan paket metadata tipe file. |
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

* [Bekerja dengan metadata CAD](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Contoh

Contoh kode ini menunjukkan cara membaca metadata gambar CAD.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDxf))
{
    var root = metadata.GetRootPackage<CadRootPackage>();

    Console.WriteLine(root.CadPackage.AcadVersion);
    Console.WriteLine(root.CadPackage.Author);
    Console.WriteLine(root.CadPackage.Comments);
    Console.WriteLine(root.CadPackage.CreatedDateTime);
    Console.WriteLine(root.CadPackage.HyperlinkBase);
    Console.WriteLine(root.CadPackage.Keywords);
    Console.WriteLine(root.CadPackage.LastSavedBy);
    Console.WriteLine(root.CadPackage.Title);

    // ...
}
```

### Lihat juga

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* ruang nama [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->