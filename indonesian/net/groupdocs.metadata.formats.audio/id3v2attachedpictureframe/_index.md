---
title: ID3V2AttachedPictureFrame
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan frame APIC dalam sebuahID3V2Tag./id3v2tag .
type: docs
weight: 420
url: /id/net/groupdocs.metadata.formats.audio/id3v2attachedpictureframe/
---
## ID3V2AttachedPictureFrame class

Merupakan frame APIC dalam sebuah[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2AttachedPictureFrame : ID3V2TagFrame
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor)(byte[]) | Menginisialisasi instance baru dari[`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) kelas. |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor_1)(ID3V2AttachedPictureType, string, byte[]) | Menginisialisasi instance baru dari[`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) kelas. |
| [ID3V2AttachedPictureFrame](id3v2attachedpictureframe#constructor_2)(ID3V2EncodingType, string, ID3V2AttachedPictureType, string, byte[]) | Menginisialisasi instance baru dari[`ID3V2AttachedPictureFrame`](../id3v2attachedpictureframe) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AttachedPictureType](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/attachedpicturetype) { get; } | Mendapat jenis gambar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Mendapatkan data bingkai. |
| [Description](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/description) { get; } | Mendapatkan deskripsi gambar. Deskripsi memiliki panjang maksimum 64 karakter, tetapi boleh kosong. |
| [DescriptionEncoding](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/descriptionencoding) { get; } | Mendapat pengkodean yang digunakan untuk mengkodekan deskripsi gambar. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Mendapat bendera bingkai. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Mendapatkan id dari frame (empat karakter cocok dengan pola [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [MimeType](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/mimetype) { get; } | Mendapatkan tipe MIME dari gambar. |
| [PictureData](../../groupdocs.metadata.formats.audio/id3v2attachedpictureframe/picturedata) { get; } | Mengambil data gambar. |
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

### Perkataan

**Belajarlah lagi**

* [Menangani tag ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Lihat juga

* class [ID3V2TagFrame](../id3v2tagframe)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
