---
title: ExifPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket metadata EXIF Format File Gambar yang Dapat Ditukar.
type: docs
weight: 2790
url: /id/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Merupakan paket metadata EXIF (Format File Gambar yang Dapat Ditukar).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ExifPackage](exifpackage)() | Menginisialisasi instance baru dari[`ExifPackage`](../exifpackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Mendapatkan atau menetapkan nama pemilik kamera, fotografer, atau pembuat gambar. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Mendapat atau menyetel pemberitahuan hak cipta. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Mendapat atau menyetel tanggal dan waktu pembuatan gambar. Dalam standar EXIF, ini adalah tanggal dan waktu file diubah. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Mendapat data IFD EXIF. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Mendapat data GPS. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Mendapat atau menetapkan string karakter yang memberi judul gambar. Ini mungkin berupa komentar seperti "piknik perusahaan 1988" atau sejenisnya. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Mendapat atau mengatur jumlah baris data gambar. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Mendapat atau mengatur jumlah kolom data gambar, sama dengan jumlah piksel per baris. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Mendapat tag TIFF dengan id yang ditentukan. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Mendapat atau menyetel pembuat peralatan rekaman. Ini adalah pembuat DSC, pemindai, digitizer video, atau peralatan lain yang menghasilkan gambar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Mendapatkan atau menetapkan nama model atau nomor model peralatan. Ini adalah nama model atau nomor DSC, pemindai, digitizer video, atau peralatan lain yang menghasilkan gambar. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Mendapatkan atau menyetel nama dan versi perangkat lunak atau firmware kamera atau perangkat input gambar yang digunakan untuk menghasilkan gambar. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Membuat thumbnail gambar direpresentasikan sebagai larik byte. |

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

### Contoh

Contoh kode ini menunjukkan cara memperbarui properti EXIF umum.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Tetapkan paket EXIF jika tidak ada
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Lihat juga

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* ruang nama [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
