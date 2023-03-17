---
title: ApePackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket metadata APE v2. Temukan informasi lebih lanjut dihttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /id/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

Mewakili paket metadata APE v2. Temukan informasi lebih lanjut di[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | Mendapat tautan abstrak. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | Mendapat album. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | Mendapatkan artis. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | Mendapatkan bibliografi. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | Mendapat komentar. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | Mendapatkan komposer. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | Mendapat konduktor. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | Mendapat hak cipta. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | Mendapat album debut. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | Mendapat file. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | Mendapatkan genre. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | Mendapatkan nomor ISBN dengan cek digit. Lihat selengkapnya: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | Mendapatkan Nomor Rekaman Standar Internasional. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | Mendapatkan bahasa. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | Mendapat publikasi dengan benar. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | Mendapatkan penerbit. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | Mendapat lokasi rekaman. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | Mendapat subtitle. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | Mendapatkan judul. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | Mendapat nomor trek. |

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

* [Menangani tag APEv2](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### Contoh

Contoh ini menunjukkan cara membaca tag APEv2 dalam file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
