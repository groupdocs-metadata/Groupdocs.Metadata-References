---
title: ID3V1Tag
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili tag ID3v1. Temukan informasi lebih lanjut dihttps//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /id/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

Mewakili tag ID3v1. Temukan informasi lebih lanjut di[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | Menginisialisasi instance baru dari[`ID3V1Tag`](../id3v1tag) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | Mendapat atau menyetel album. Panjang maksimum adalah 30 karakter. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | Mendapat atau menyetel artis. Panjang maksimum adalah 30 karakter. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | Mendapat atau menyetel komentar. Panjang maksimum adalah 30 karakter. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | Mendapat atau menyetel pengidentifikasi genre. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | Mendapatkan atau menetapkan judul. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | Mendapat atau menetapkan nomor trek. Disajikan hanya dalam tag ID3v1.1. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | Mendapat versi ID3. Itu bisa ID3 atau ID3v1.1 |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | Mendapatkan atau menyetel tahun. Panjang maksimum adalah 4 karakter. |

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

ID3(v1) tag adalah bagian kecil dari data tambahan di akhir MP3. Silakan temukan informasi lebih lanjut di[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**Belajarlah lagi**

* [Menangani tag ID3v1](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### Contoh

Contoh kode ini menunjukkan cara membaca tag ID3v1 dalam file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### Lihat juga

* class [ID3Tag](../id3tag)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
