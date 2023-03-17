---
title: ID3V2Tag
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili tag ID3v2. Temukan informasi lebih lanjut dihttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /id/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Mewakili tag ID3v2. Temukan informasi lebih lanjut di[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Menginisialisasi instance baru dari[`ID3V2Tag`](../id3v2tag) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Mendapat atau menyetel judul Album/Film/Pertunjukan. Nilai ini diwakili oleh bingkai TALB. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Mendapat atau menetapkan Artis utama/Penampil utama/Penampil solo/Grup tampil. Nilai ini diwakili oleh bingkai TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Mendapat atau menyetel gambar terlampir yang terkait langsung dengan file audio. Nilai ini diwakili oleh bingkai APIC. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Mendapat atau menyetel Band/Orkestra/Iringan. Nilai ini diwakili oleh bingkai TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Mendapat atau mengatur jumlah ketukan per menit di bagian utama audio. Nilai ini diwakili oleh frame TBPM. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Mendapatkan atau menyetel komentar pengguna. Nilai ini diwakili oleh bingkai COMM. Bingkai ditujukan untuk segala jenis informasi teks lengkap yang tidak muat di bingkai lain. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Mendapat atau mengatur komposer. Nama dipisahkan dengan karakter "/". Nilai ini diwakili oleh frame TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Mendapat atau menyetel jenis konten. Nilai ini diwakili oleh bingkai TCON. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Mendapat atau menyetel pesan hak cipta. Nilai ini diwakili oleh bingkai TCP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Mendapat atau menetapkan string numerik dalam format DDMM yang berisi tanggal perekaman. Panjang bidang ini selalu empat karakter. Nilai ini diwakili oleh bingkai TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Mendapat atau menetapkan nama orang atau organisasi yang menyandikan file audio. Nilai ini diwakili oleh bingkai TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Mendapat atau menyetel International Standard Recording Code (ISRC) (12 karakter). Nilai ini diwakili oleh frame TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Mendapat atau menyetel panjang file audio dalam milidetik, direpresentasikan sebagai string numerik. Nilai ini direpresentasikan oleh bingkai TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Mendapat atau menyetel kunci musik tempat suara dimulai. Nilai ini diwakili oleh bingkai TKEY. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Mendapat atau menetapkan judul album/film/acara asli. Nilai ini diwakili oleh bingkai TOAL. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Mendapat atau menetapkan nama label atau penerbit. Nilai ini diwakili oleh bingkai TPUB. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Mendapat atau mengatur ukuran file audio dalam byte, tidak termasuk tag ID3v2, direpresentasikan sebagai string numerik. Nilai ini direpresentasikan oleh bingkai TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Mendapat atau menyetel enkoder audio yang digunakan dan pengaturannya saat file dikodekan. Nilai ini diwakili oleh bingkai TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Mendapatkan atau menyetel penyempurnaan Subtitel/Deskripsi. Nilai ini diwakili oleh bingkai TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Mendapatkan ukuran tag. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Mendapat atau menyetel string numerik dalam format HHMM yang berisi waktu perekaman. Bidang ini selalu terdiri dari empat karakter. Nilai ini diwakili oleh bingkai WAKTU. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Mendapat atau menyetel Judul/Nama lagu/Deskripsi konten. Nilai ini diwakili oleh bingkai TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Mendapat atau menetapkan string numerik yang berisi nomor urut file audio pada rekaman aslinya. Nilai ini diwakili oleh bingkai TRCK. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Mendapat berapa kali file telah diputar. Nilai ini diwakili oleh bingkai PCNT. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Mendapatkan versi ID3. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Mendapat atau menyetel string numerik dengan tahun rekaman. Panjang frame ini selalu empat karakter (hingga tahun 10000). Nilai ini diwakili oleh frame TYER. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Menambahkan bingkai ke tag. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Menghapus semua bingkai dengan id yang ditentukan. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Mendapat array frame dengan id yang ditentukan. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Menghapus bingkai yang ditentukan dari tag. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Menghapus semua lampiran gambar yang disimpan dalam bingkai APIC. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Menghapus semua bingkai yang memiliki id yang sama dengan yang ditentukan dan menambahkan bingkai baru ke tag. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Membuat daftar dari paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Menangani tag ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Contoh

Contoh ini menunjukkan cara membaca tag ID3v2 dalam file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### Lihat juga

* class [ID3Tag](../id3tag)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
