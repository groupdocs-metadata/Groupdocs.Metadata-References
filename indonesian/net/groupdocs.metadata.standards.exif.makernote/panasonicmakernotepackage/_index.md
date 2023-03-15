---
title: PanasonicMakerNotePackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan metadata PANASONIC MakerNote.
type: docs
weight: 2850
url: /id/net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/
---
## PanasonicMakerNotePackage class

Merupakan metadata PANASONIC MakerNote.

```csharp
public class PanasonicMakerNotePackage : MakerNotePackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AccessorySerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessoryserialnumber) { get; } | Mendapat nomor seri aksesori. |
| [AccessoryType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessorytype) { get; } | Mendapatkan jenis aksesori. |
| [AFMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/afmode) { get; } | Mendapatkan mode AF. |
| [Audio](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/audio) { get; } | Mendapat mode audio. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [FirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/firmwareversion) { get; } | Mendapat versi firmware. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/focusmode) { get; } | Mendapatkan mode fokus. |
| [ImageQuality](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagequality) { get; } | Mendapatkan kualitas gambar. |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagestabilization) { get; } | Mendapatkan mode stabilisasi gambar. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Mendapat tag TIFF dengan id yang ditentukan. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [LensSerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lensserialnumber) { get; } | Mendapatkan nomor seri lensa. |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lenstype) { get; } | Mendapat jenis lensa. |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/macromode) { get; } | Mendapatkan mode makro. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [ShootingMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/shootingmode) { get; } | Mendapatkan mode pemotretan. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/whitebalance) { get; } | Mendapatkan white balance. |

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
