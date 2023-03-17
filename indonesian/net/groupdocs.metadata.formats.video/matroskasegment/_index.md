---
title: MatroskaSegment
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili elemen SEGMENTINFO yang berisi informasi umum tentang SEGMEN dalam video Matroska.
type: docs
weight: 2490
url: /id/net/groupdocs.metadata.formats.video/matroskasegment/
---
## MatroskaSegment class

Mewakili elemen SEGMENTINFO yang berisi informasi umum tentang SEGMEN dalam video Matroska.

```csharp
public class MatroskaSegment : MatroskaBasePackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DateUtc](../../groupdocs.metadata.formats.video/matroskasegment/dateutc) { get; } | Mendapat tanggal dan waktu pembuatan Segmen oleh aplikasi atau pustaka muxing. |
| [Duration](../../groupdocs.metadata.formats.video/matroskasegment/duration) { get; } | Mendapatkan durasi SEGMENT. Silakan lihat[`TimecodeScale`](./timecodescale) untuk informasi lebih lanjut. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [MuxingApp](../../groupdocs.metadata.formats.video/matroskasegment/muxingapp) { get; } | Mendapat nama lengkap aplikasi atau pustaka diikuti dengan nomor versi. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [ScaledDuration](../../groupdocs.metadata.formats.video/matroskasegment/scaledduration) { get; } | Mendapatkan durasi skala SEGMEN. |
| [SegmentFilename](../../groupdocs.metadata.formats.video/matroskasegment/segmentfilename) { get; } | Mendapatkan nama file yang sesuai dengan Segmen ini. |
| [SegmentUid](../../groupdocs.metadata.formats.video/matroskasegment/segmentuid) { get; } | Mendapatkan nomor 128 bit unik yang mengidentifikasi SEGMENT. Tentunya, file hanya dapat dirujuk oleh file lain jika ada SEGMENTUID, namun, pemutaran dapat dilakukan tanpa UID tersebut. |
| [TimecodeScale](../../groupdocs.metadata.formats.video/matroskasegment/timecodescale) { get; } | Mendapat nilai skala kode waktu. Setiap kode waktu yang diskalakan dalam file MATROSKA dikalikan dengan TIMECODESCALE untuk mendapatkan kode waktu dalam nanodetik. Perhatikan bahwa tidak semua kode waktu diskalakan! |
| [Title](../../groupdocs.metadata.formats.video/matroskasegment/title) { get; } | Mendapatkan nama umum Segmen. |
| [WritingApp](../../groupdocs.metadata.formats.video/matroskasegment/writingapp) { get; } | Mendapat nama lengkap aplikasi diikuti dengan nomor versi. |

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

* class [MatroskaBasePackage](../matroskabasepackage)
* ruang nama [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
