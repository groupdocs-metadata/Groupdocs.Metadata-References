---
title: MatroskaSubtitleTrack
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata subtitle dalam video Matroska.
type: docs
weight: 2520
url: /id/net/groupdocs.metadata.formats.video/matroskasubtitletrack/
---
## MatroskaSubtitleTrack class

Mewakili metadata subtitle dalam video Matroska.

```csharp
public class MatroskaSubtitleTrack : MatroskaTrack
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Mendapat ID yang sesuai dengan codec. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Mendapat string yang dapat dibaca manusia yang menentukan codec. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Mendapat jumlah nanodetik (tidak diskalakan melalui[`TimecodeScale`](../matroskasegment/timecodescale) ) per bingkai. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Mendapat bendera yang diaktifkan, benar jika trek dapat digunakan. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Mendapat bahasa trek dalam bentuk bahasa Matroska. Elemen ini HARUS diabaikan jika[`LanguageIetf`](../matroskatrack/languageietf) Elemen digunakan dalam TrackEntry. yang sama |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Mendapatkan bahasa trek sesuai dengan BCP 47 dan menggunakan Registri Subtag Bahasa IANA. Jika Elemen ini digunakan, maka apapun[`Language`](../matroskatrack/language) Elemen yang digunakan dalam TrackEntry yang sama HARUS diabaikan. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Mendapatkan nama trek yang dapat dibaca manusia. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Subtitles](../../groupdocs.metadata.formats.video/matroskasubtitletrack/subtitles) { get; } | Mendapatkan subtitle. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Mendapat nomor track seperti yang digunakan di Block Header. Menggunakan lebih dari 127 track tidak dianjurkan, meskipun desain memungkinkan jumlah yang tidak terbatas. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Mendapat jenis trek. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Mendapatkan ID unik untuk mengidentifikasi Track. Ini HARUS tetap sama saat membuat salinan aliran langsung dari Track ke file lain. |

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

* [Bekerja dengan metadata dalam file Matroska (MKV).](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Lihat juga

* class [MatroskaTrack](../matroskatrack)
* ruang nama [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
