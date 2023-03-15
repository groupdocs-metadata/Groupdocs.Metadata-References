---
title: CadPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata CAD Computeraided design.
type: docs
weight: 840
url: /id/net/groupdocs.metadata.formats.cad/cadpackage/
---
## CadPackage class

Mewakili metadata CAD (Computer-aided design).

```csharp
public sealed class CadPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AcadVersion](../../groupdocs.metadata.formats.cad/cadpackage/acadversion) { get; } | Mendapatkan nomor versi database gambar AutoCAD. |
| [Author](../../groupdocs.metadata.formats.cad/cadpackage/author) { get; } | Mendapatkan pembuat gambar. |
| [Comments](../../groupdocs.metadata.formats.cad/cadpackage/comments) { get; } | Mendapat komentar pengguna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreatedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/createddatetime) { get; } | Mendapat tanggal dan waktu pembuatan gambar. |
| [CustomProperties](../../groupdocs.metadata.formats.cad/cadpackage/customproperties) { get; } | Mendapatkan paket yang berisi properti metadata khusus. |
| [Height](../../groupdocs.metadata.formats.cad/cadpackage/height) { get; } | Mendapatkan tinggi gambar. |
| [HyperlinkBase](../../groupdocs.metadata.formats.cad/cadpackage/hyperlinkbase) { get; } | Mendapatkan basis hyperlink. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.formats.cad/cadpackage/keywords) { get; } | Mendapat kata kunci. |
| [LastSavedBy](../../groupdocs.metadata.formats.cad/cadpackage/lastsavedby) { get; } | Mendapatkan nama editor terakhir. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [ModifiedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/modifieddatetime) { get; } | Mendapat tanggal dan waktu saat gambar diubah. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.cad/cadpackage/revisionnumber) { get; } | Mendapat nomor revisi. |
| [Subject](../../groupdocs.metadata.formats.cad/cadpackage/subject) { get; } | Mendapatkan subjek. |
| [Title](../../groupdocs.metadata.formats.cad/cadpackage/title) { get; } | Mendapatkan judul. |
| [Width](../../groupdocs.metadata.formats.cad/cadpackage/width) { get; } | Mendapatkan lebar gambar. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata CAD](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
