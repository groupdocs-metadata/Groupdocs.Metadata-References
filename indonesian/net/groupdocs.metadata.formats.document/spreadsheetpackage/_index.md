---
title: SpreadsheetPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket metadata asli dalam spreadsheet.
type: docs
weight: 1200
url: /id/net/groupdocs.metadata.formats.document/spreadsheetpackage/
---
## SpreadsheetPackage class

Mewakili paket metadata asli dalam spreadsheet.

```csharp
public class SpreadsheetPackage : DocumentPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/spreadsheetpackage/author) { get; set; } | Mendapat atau menyetel penulis dokumen. |
| [Category](../../groupdocs.metadata.formats.document/spreadsheetpackage/category) { get; set; } | Mendapat atau menetapkan kategori. |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetpackage/comments) { get; set; } | Mendapat atau menyetel komentar. |
| [Company](../../groupdocs.metadata.formats.document/spreadsheetpackage/company) { get; set; } | Mendapat atau menetapkan perusahaan. |
| [ContentStatus](../../groupdocs.metadata.formats.document/spreadsheetpackage/contentstatus) { get; set; } | Mendapat atau menyetel status konten. |
| [ContentType](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttype) { get; set; } | Mendapat atau menyetel jenis konten. |
| [ContentTypeProperties](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttypeproperties) { get; } | Mendapatkan paket metadata yang berisi properti tipe konten. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreatedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/createdtime) { get; set; } | Mendapat atau menetapkan tanggal pembuatan dokumen. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/spreadsheetpackage/hyperlinkbase) { get; set; } | Mendapat atau menyetel basis hyperlink. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.formats.document/spreadsheetpackage/keywords) { get; set; } | Mendapat atau menetapkan kata kunci. |
| [Language](../../groupdocs.metadata.formats.document/spreadsheetpackage/language) { get; set; } | Mendapat atau menyetel bahasa dokumen. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastprinteddate) { get; set; } | Mendapat atau menyetel tanggal cetak terakhir dalam UTC. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedby) { get; set; } | Mendapat atau menetapkan nama penulis terakhir. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedtime) { get; set; } | Mendapat atau menyetel waktu penyimpanan terakhir di UTC. |
| [Manager](../../groupdocs.metadata.formats.document/spreadsheetpackage/manager) { get; set; } | Mendapat atau menetapkan manajer. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/spreadsheetpackage/nameofapplication) { get; set; } | Mendapatkan atau menetapkan nama aplikasi. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.formats.document/spreadsheetpackage/revision) { get; set; } | Mendapat atau menetapkan nomor revisi dokumen. |
| [Subject](../../groupdocs.metadata.formats.document/spreadsheetpackage/subject) { get; set; } | Mendapat atau menyetel subjek. |
| [Template](../../groupdocs.metadata.formats.document/spreadsheetpackage/template) { get; set; } | Mendapat atau menyetel nama templat dokumen. |
| [Title](../../groupdocs.metadata.formats.document/spreadsheetpackage/title) { get; set; } | Mendapat atau mengatur judul dokumen. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/totaleditingtime) { get; set; } | Mendapatkan atau menyetel total waktu pengeditan dalam hitungan menit. |
| [Version](../../groupdocs.metadata.formats.document/spreadsheetpackage/version) { get; set; } | Mendapat atau menyetel nomor versi aplikasi yang membuat dokumen. |

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
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set)(string, bool) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_3)(string, DateTime) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_1)(string, double) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_2)(string, int) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_4)(string, string) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata di Spreadsheet](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Contoh

Contoh ini menunjukkan cara memperbarui properti metadata bawaan di spreadsheet.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputXlsx);
}
```

### Lihat juga

* class [DocumentPackage](../documentpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
