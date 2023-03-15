---
title: ExifIfdPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan Direktori File Gambar Exif. Exif IFD adalah sekumpulan tag untuk merekam informasi atribut khusus Exif.
type: docs
weight: 2780
url: /id/net/groupdocs.metadata.standards.exif/exififdpackage/
---
## ExifIfdPackage class

Merupakan Direktori File Gambar Exif. Exif IFD adalah sekumpulan tag untuk merekam informasi atribut khusus Exif.

```csharp
public sealed class ExifIfdPackage : ExifDictionaryBasePackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BodySerialNumber](../../groupdocs.metadata.standards.exif/exififdpackage/bodyserialnumber) { get; set; } | Mendapat atau menyetel nomor seri bodi kamera. |
| [CameraOwnerName](../../groupdocs.metadata.standards.exif/exififdpackage/cameraownername) { get; set; } | Mendapat atau menyetel nama pemilik kamera. |
| [CfaPattern](../../groupdocs.metadata.standards.exif/exififdpackage/cfapattern) { get; set; } | Mendapatkan atau menyetel pola geometris susunan filter warna (CFA) dari sensor gambar saat sensor area warna satu chip digunakan. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Mendapat tag TIFF dengan id yang ditentukan. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [UserComment](../../groupdocs.metadata.standards.exif/exififdpackage/usercomment) { get; set; } | Mendapat atau menyetel komentar pengguna. |

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

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Lihat juga

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* ruang nama [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
