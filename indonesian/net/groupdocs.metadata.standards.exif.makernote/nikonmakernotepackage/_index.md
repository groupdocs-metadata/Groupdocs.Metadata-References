---
title: NikonMakerNotePackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata NIKON MakerNote.
type: docs
weight: 2840
url: /id/net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/
---
## NikonMakerNotePackage class

Mewakili metadata NIKON MakerNote.

```csharp
public sealed class NikonMakerNotePackage : MakerNotePackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [NikonMakerNotePackage](nikonmakernotepackage)(TiffTag[]) | Menginisialisasi instance baru dari[`NikonMakerNotePackage`](../nikonmakernotepackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/colormode) { get; } | Mendapatkan mode warna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [FlashSetting](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashsetting) { get; } | Mendapatkan pengaturan flash. |
| [FlashType](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashtype) { get; } | Mendapat jenis flash. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/focusmode) { get; } | Mendapatkan mode fokus. |
| [Iso](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/iso) { get; } | Mendapatkan iso. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Mendapat tag TIFF dengan id yang ditentukan. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MakerNoteVersion](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/makernoteversion) { get; } | Mendapatkan versi MakerNote. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/quality) { get; } | Mendapat string kualitas. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sharpness) { get; } | Mendapat ketajaman. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/whitebalance) { get; } | Mendapatkan white balance. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Menghapus semua tag TIFF yang disimpan dalam paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Menghapus properti dengan id yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Menambahkan atau mengganti tag yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Membuat daftar dari paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Lihat juga

* class [MakerNotePackage](../makernotepackage)
* ruang nama [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
