---
title: IptcApplicationRecord
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili Catatan Aplikasi IPTC.
type: docs
weight: 2880
url: /id/net/groupdocs.metadata.standards.iptc/iptcapplicationrecord/
---
## IptcApplicationRecord class

Mewakili Catatan Aplikasi IPTC.

```csharp
public sealed class IptcApplicationRecord : IptcRecord
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [IptcApplicationRecord](iptcapplicationrecord)() | Menginisialisasi instance baru dari[`IptcApplicationRecord`](../iptcapplicationrecord) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AllKeywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/allkeywords) { get; set; } | Mendapat atau menetapkan kata kunci. |
| [ByLine](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/byline) { get; set; } | Mendapat atau menetapkan nama pembuat objek, misalnya penulis, fotografer, atau seniman grafis. |
| [ByLines](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylines) { get; set; } | Mendapat atau menetapkan nama pembuat objek, misalnya penulis, fotografer, atau seniman grafis. |
| [ByLineTitle](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitle) { get; set; } | Mendapat atau menetapkan judul pembuat atau pembuat objek. |
| [ByLineTitles](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitles) { get; set; } | Mendapat atau menetapkan judul pencipta atau pembuat objek. |
| [CaptionAbstract](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/captionabstract) { get; set; } | Mendapat atau menyetel deskripsi tekstual dari objek, terutama digunakan jika objeknya bukan teks. |
| [City](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/city) { get; set; } | Mendapat atau mengatur kota. |
| [Contact](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contact) { get; set; } | Mendapat atau menetapkan informasi tentang orang atau organisasi yang dapat memberikan informasi latar belakang lebih lanjut tentang objek. |
| [Contacts](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contacts) { get; set; } | Mendapat atau menetapkan informasi tentang orang atau organisasi yang dapat memberikan informasi latar belakang lebih lanjut tentang objek. |
| [ContentLocationCode](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcode) { get; set; } | Mendapat atau menyetel kode lokasi konten. |
| [ContentLocationCodes](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcodes) { get; set; } | Mendapat atau menyetel kode lokasi konten. |
| [ContentLocationName](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationname) { get; set; } | Mendapat atau menyetel nama lokasi konten. |
| [ContentLocationNames](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationnames) { get; set; } | Mendapat atau menyetel nama lokasi konten. |
| [CopyrightNotice](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/copyrightnotice) { get; set; } | Mendapat atau menyetel pemberitahuan hak cipta. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Credit](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/credit) { get; set; } | Mendapat atau menetapkan informasi tentang penyedia objek, tidak harus pemilik/pembuat. |
| [DateCreated](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/datecreated) { get; set; } | Mendapat atau mengatur tanggal pembuatan konten intelektual objek. |
| [Headline](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/headline) { get; set; } | Mendapat atau menyetel entri yang dapat diterbitkan dengan menyediakan sinopsis konten objek. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/item) { get; } | Mendapatkan[`IptcDataSet`](../iptcdataset) dengan nomor yang ditentukan. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/keywords) { get; set; } | Mendapat atau menetapkan kata kunci. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [ProgramVersion](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/programversion) { get; set; } | Mendapat atau menyetel versi program. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Mendapatkan nomor record. |
| [ReferenceDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedate) { get; set; } | Mendapat atau menetapkan tanggal amplop sebelumnya yang merujuk objek saat ini. |
| [ReferenceDates](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedates) { get; } | Mendapat tanggal dari amplop sebelumnya yang merujuk objek saat ini. |
| [ReleaseDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/releasedate) { get; set; } | Mendapat atau menetapkan tanggal rilis. |

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
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Membuat daftar dari paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata IIM IPTC](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Lihat juga

* class [IptcRecord](../iptcrecord)
* ruang nama [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
