---
title: AviHeader
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili struktur AVIMAINHEADER dalam video AVI.
type: docs
weight: 2380
url: /id/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Mewakili struktur AVIMAINHEADER dalam video AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [AviHeader](aviheader)() | Menginisialisasi instance baru dari[`AviHeader`](../aviheader) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Mendapat kombinasi bitwise dari nol atau lebih flag AVI. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Mendapat tinggi file AVI dalam piksel. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Mendapat bingkai awal untuk file yang disisipkan.  File noninterleaved harus menentukan nol. Jika Anda membuat file interleaved, tentukan jumlah frame di file sebelum frame awal urutan AVI di anggota ini. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Mendapat perkiraan kecepatan data maksimum file.  Nilai ini menunjukkan jumlah byte per detik yang harus ditangani oleh sistem untuk menampilkan urutan AVI sebagai yang ditentukan oleh parameter lain yang terdapat dalam header utama dan potongan header aliran. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Mendapat jumlah mikrodetik antar bingkai. Nilai ini menunjukkan keseluruhan waktu untuk file. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Mendapatkan keselarasan untuk data, dalam byte. Pad data ke kelipatan dari nilai ini. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Mendapat jumlah aliran dalam file. Misalnya, file dengan audio dan video memiliki dua aliran. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Mendapatkan ukuran buffer yang disarankan untuk membaca file.  Umumnya, ukuran ini harus cukup besar untuk menampung potongan terbesar dalam file. Jika disetel ke nol, atau terlalu kecil, perangkat lunak pemutaran harus mengalokasikan kembali memori selama pemutaran, yang akan mengurangi kinerja. Untuk file yang disisipkan, ukuran buffer harus cukup besar untuk membaca seluruh record, dan bukan hanya sepotong. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Mendapat jumlah total frame data dalam file. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Mendapatkan lebar file AVI dalam piksel. |

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

* [Bekerja dengan metadata dalam file AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
