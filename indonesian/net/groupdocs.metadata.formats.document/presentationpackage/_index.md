---
title: PresentationPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket metadata asli dalam presentasi.
type: docs
weight: 1090
url: /id/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

Mewakili paket metadata asli dalam presentasi.

```csharp
public class PresentationPackage : DocumentPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | Mendapat atau menyetel template aplikasi. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | Mendapat atau mengatur pembuat dokumen. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | Mendapat atau menetapkan kategori. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | Mendapat atau menyetel komentar. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | Mendapat atau menetapkan perusahaan. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | Mendapat atau menyetel status konten. Hanya dapat diperbarui dalam dokumen PPTX. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | Mendapat atau menyetel tipe konten. Hanya dapat diperbarui dalam dokumen PPTX. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | Mendapat atau menetapkan tanggal pembuatan dokumen. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | Mendapat atau menyetel basis hyperlink. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | Mendapat atau menetapkan kata kunci. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | Mendapat atau menyetel tanggal cetak terakhir. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | Mendapat atau menetapkan nama penulis terakhir. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | Mendapatkan tanggal dan waktu saat presentasi diubah terakhir kali. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | Mendapat atau menetapkan manajer. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | Mendapat nama aplikasi yang membuat dokumen. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | Mendapatkan format presentasi. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | Mendapat atau menetapkan nomor revisi. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah presentasi dibagikan di antara banyak orang. Hanya dapat diperbarui dalam dokumen PPTX. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | Mendapat atau menyetel subjek. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | Mendapat atau mengatur judul dokumen. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | Mendapat atau mengatur total waktu pengeditan dokumen. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | Mendapatkan versi aplikasi. |

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
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata di Presentasi](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Contoh

Contoh ini menunjukkan cara memperbarui properti metadata bawaan dalam presentasi.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### Lihat juga

* class [DocumentPackage](../documentpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
