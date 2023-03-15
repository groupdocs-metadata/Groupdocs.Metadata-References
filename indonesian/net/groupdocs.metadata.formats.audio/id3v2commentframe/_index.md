---
title: ID3V2CommentFrame
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan frame COMM dalam sebuahID3V2Tag./id3v2tag .
type: docs
weight: 440
url: /id/net/groupdocs.metadata.formats.audio/id3v2commentframe/
---
## ID3V2CommentFrame class

Merupakan frame COMM dalam sebuah[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2CommentFrame : ID3V2TagFrame
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [ID3V2CommentFrame](id3v2commentframe)(ID3V2EncodingType, string, string, string) | Menginisialisasi instance baru dari[`ID3V2CommentFrame`](../id3v2commentframe) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [CommentEncoding](../../groupdocs.metadata.formats.audio/id3v2commentframe/commentencoding) { get; } | Mendapat penyandian komentar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Mendapatkan data bingkai. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Mendapat bendera bingkai. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Mendapatkan id dari frame (empat karakter cocok dengan pola [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Language](../../groupdocs.metadata.formats.audio/id3v2commentframe/language) { get; } | Mendapatkan bahasa komentar (3 karakter). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [ShortContentDescription](../../groupdocs.metadata.formats.audio/id3v2commentframe/shortcontentdescription) { get; } | Mendapat deskripsi konten singkat. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2commentframe/text) { get; } | Mendapat teks komentar. |

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

Bingkai ini ditujukan untuk segala jenis informasi teks lengkap yang tidak muat di bingkai lainnya.

**Belajarlah lagi**

* [Menangani tag ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Lihat juga

* class [ID3V2TagFrame](../id3v2tagframe)
* ruang nama [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
