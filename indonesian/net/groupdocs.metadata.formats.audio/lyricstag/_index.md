---
title: LyricsTag
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata Lyrics3 v2.00. Silakan temukan informasi lebih lanjut dihttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /id/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Mewakili metadata Lyrics3 v2.00. Silakan temukan informasi lebih lanjut dihttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LyricsTag](lyricstag)() | Menginisialisasi instance baru dari[`LyricsTag`](../lyricstag) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Mendapat atau menetapkan informasi tambahan. Nilai ini diwakili oleh bidang INF. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Mendapat atau menetapkan nama album. Nilai ini diwakili oleh kolom EAL. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Mendapatkan atau menyetel nama artis. Nilai ini diwakili oleh kolom EAR. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Mendapat atau menetapkan penulis. Nilai ini diwakili oleh bidang AUT. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Mengambil atau menyetel lirik. Nilai ini diwakili oleh kolom LYR. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Mendapat atau menyetel judul trek. Nilai ini diwakili oleh kolom ETT. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Mendapatkan nilai bidang dengan id yang ditentukan. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Menghapus bidang dengan id yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Menambahkan atau mengganti kolom Lyrics3 yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Membuat daftar dari paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

Lyrics3 v2.00 menggunakan bidang untuk mewakili informasi. Data dalam bidang dapat terdiri dari karakter ASCII dalam rentang 01 hingga 254 menurut standar. Karena peta karakter ASCII hanya ditentukan dari 00 hingga 128 ISO-8859- 1 mungkin diasumsikan. Kolom numerik terdiri dari 5 atau 6 karakter, bergantung pada lokasi, dan diisi dengan nol.

**Belajarlah lagi**

* [Menangani tag Lirik](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Contoh

Contoh kode ini menunjukkan cara membaca tag Lirik dari file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Sebagai alternatif, Anda dapat mengulang daftar lengkap bidang tag
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
