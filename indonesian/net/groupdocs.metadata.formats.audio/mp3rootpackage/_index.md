---
title: MP3RootPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket root yang memungkinkan bekerja dengan metadata dalam audio MP3.
type: docs
weight: 580
url: /id/net/groupdocs.metadata.formats.audio/mp3rootpackage/
---
## MP3RootPackage class

Mewakili paket root yang memungkinkan bekerja dengan metadata dalam audio MP3.

```csharp
public class MP3RootPackage : RootMetadataPackage, IXmp
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [ApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/apev2) { get; } | Mendapatkan metadata APE v2. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Mendapatkan paket metadata tipe file. |
| [ID3V1](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v1) { get; set; } | Mendapatkan atau menyetel tag metadata ID3v1. Temukan informasi lebih lanjut di[http://id3.org/ID3v1](http://id3.org/ID3v1) . |
| [ID3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/id3v2) { get; set; } | Mendapat atau menyetel tag metadata ID3v2. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Lyrics3V2](../../groupdocs.metadata.formats.audio/mp3rootpackage/lyrics3v2) { get; set; } | Mendapat atau menyetel tag metadata Lyrics3v2. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [MpegAudioPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage) { get; } | Mendapatkan paket metadata audio MPEG. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [XmpPackage](../../groupdocs.metadata.formats.audio/mp3rootpackage/xmppackage) { get; set; } | Mendapat atau menyetel paket metadata XMP. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [RemoveApeV2](../../groupdocs.metadata.formats.audio/mp3rootpackage/removeapev2)() | Menghapus tag audio APEv2. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| override [Sanitize](../../groupdocs.metadata.formats.audio/mp3rootpackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata MP3](https://docs.groupdocs.com/display/metadatanet/Working+with+MP3+metadata)
* [Bekerja dengan metadata XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Lihat juga

* class [RootMetadataPackage](../../groupdocs.metadata.common/rootmetadatapackage)
* interface [IXmp](../../groupdocs.metadata.standards.xmp/ixmp)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
