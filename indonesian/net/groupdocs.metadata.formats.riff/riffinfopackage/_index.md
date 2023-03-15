---
title: RiffInfoPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket metadata yang berisi properti yang diekstraksi dari RIFF INFO chunk.
type: docs
weight: 2220
url: /id/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Merupakan paket metadata yang berisi properti yang diekstraksi dari RIFF INFO chunk.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Mendapatkan artis dari subjek asli file. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Mendapat komentar tentang file atau subjek file. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Mendapat informasi hak cipta untuk file tersebut. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Mendapatkan tanggal pembuatan subjek file. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Mendapat nama insinyur yang mengerjakan file. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Mendapatkan genre karya asli. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Mendapat kata kunci yang merujuk ke file atau subjek file. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Mendapat judul subjek file. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Mendapat nama paket perangkat lunak yang digunakan untuk membuat file. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Mendapat nama orang atau organisasi yang menyediakan subjek asli file. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Mendapat deskripsi isi file, seperti "Aerial view of Seattle." |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Mendapat teknisi yang mendigitalkan file subjek. |

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

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
