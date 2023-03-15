---
title: ProjectManagementPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket metadata asli dalam file manajemen proyek.
type: docs
weight: 1130
url: /id/net/groupdocs.metadata.formats.document/projectmanagementpackage/
---
## ProjectManagementPackage class

Merupakan paket metadata asli dalam file manajemen proyek.

```csharp
public sealed class ProjectManagementPackage : DocumentPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/projectmanagementpackage/author) { get; set; } | Mendapat atau menetapkan pembuat proyek. |
| [Category](../../groupdocs.metadata.formats.document/projectmanagementpackage/category) { get; set; } | Mendapat atau menetapkan kategori. |
| [Comments](../../groupdocs.metadata.formats.document/projectmanagementpackage/comments) { get; set; } | Mendapat atau menyetel komentar pengguna. |
| [Company](../../groupdocs.metadata.formats.document/projectmanagementpackage/company) { get; set; } | Mendapat atau menetapkan perusahaan. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreationDate](../../groupdocs.metadata.formats.document/projectmanagementpackage/creationdate) { get; set; } | Mendapat atau menyetel tanggal pembuatan. |
| [Guid](../../groupdocs.metadata.formats.document/projectmanagementpackage/guid) { get; set; } | Mendapat atau menetapkan id proyek. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/projectmanagementpackage/hyperlinkbase) { get; set; } | Mendapat atau menyetel basis hyperlink. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.formats.document/projectmanagementpackage/keywords) { get; set; } | Mendapat atau menetapkan kata kunci. |
| [LastAuthor](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastauthor) { get; set; } | Mendapat atau menetapkan penulis terakhir. |
| [LastPrinted](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastprinted) { get; set; } | Mendapat atau menyetel waktu cetak terakhir proyek. |
| [LastSaved](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastsaved) { get; set; } | Mendapat atau menyetel tanggal saat proyek disimpan terakhir kali. |
| [Manager](../../groupdocs.metadata.formats.document/projectmanagementpackage/manager) { get; set; } | Mendapat atau menyetel manajer proyek. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.formats.document/projectmanagementpackage/revision) { get; set; } | Mendapat atau menetapkan nomor revisi. |
| [SaveVersion](../../groupdocs.metadata.formats.document/projectmanagementpackage/saveversion) { get; } | Mendapat versi Proyek Microsoft Office tempat file proyek disimpan. |
| [Subject](../../groupdocs.metadata.formats.document/projectmanagementpackage/subject) { get; set; } | Mendapat atau menyetel subjek. |
| [Template](../../groupdocs.metadata.formats.document/projectmanagementpackage/template) { get; set; } | Mendapat atau menyetel template. |
| [Title](../../groupdocs.metadata.formats.document/projectmanagementpackage/title) { get; set; } | Mendapatkan atau menetapkan judul. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Menghapus semua properti metadata yang dapat ditulis dari paket. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Menghapus semua properti metadata bawaan. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Menghapus semua properti metadata khusus. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Menghapus properti metadata yang dapat ditulis dengan nama yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set)(string, bool) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_3)(string, DateTime) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_1)(string, double) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_2)(string, int) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_4)(string, string) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata dalam format Manajemen Proyek](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+ProjectManagement+formats)

### Contoh

Contoh kode ini menunjukkan cara memperbarui properti bawaan dalam dokumen Manajemen Proyek.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMpp))
{
    var root = metadata.GetRootPackage<ProjectManagementRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreationDate = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Comments = "test comment";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputMpp);
}
```

### Lihat juga

* class [DocumentPackage](../documentpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
