---
title: MpegAudioPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan metadata audio MPEG.
type: docs
weight: 2150
url: /id/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

Merupakan metadata audio MPEG.

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | Menginisialisasi instance baru dari[`MpegAudioPackage`](../mpegaudiopackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | Mendapat bitrate. |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | Mendapatkan mode saluran. |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | Mendapat bit hak cipta. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | Mendapat penekanan. |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | Mendapatkan frekuensi. |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | Mendapatkan header offset. |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | Mendapatkan bit asli. |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | Mendapat`BENAR` jika dilindungi. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | Mendapat deskripsi lapisan. Untuk audio MP3 adalah '3'. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | Mendapat bit ekstensi mode. |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | Mendapatkan versi audio MPEG. Bisa MPEG-1, MPEG-2 dll. |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | Mendapat bit padding. |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | Mendapat nilai yang menunjukkan apakah [bit pribadi]. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

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

### Contoh

Contoh ini menunjukkan cara membaca metadata audio MPEG dari file MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    Console.WriteLine(root.MpegAudioPackage.Bitrate);
    Console.WriteLine(root.MpegAudioPackage.ChannelMode);
    Console.WriteLine(root.MpegAudioPackage.Emphasis);
    Console.WriteLine(root.MpegAudioPackage.Frequency);
    Console.WriteLine(root.MpegAudioPackage.HeaderPosition);
    Console.WriteLine(root.MpegAudioPackage.Layer);

    // ...
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
