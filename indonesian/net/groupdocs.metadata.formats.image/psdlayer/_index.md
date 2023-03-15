---
title: PsdLayer
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan lapisan dalam file PSD.
type: docs
weight: 1900
url: /id/net/groupdocs.metadata.formats.image/psdlayer/
---
## PsdLayer class

Merupakan lapisan dalam file PSD.

```csharp
public sealed class PsdLayer : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BitsPerPixel](../../groupdocs.metadata.formats.image/psdlayer/bitsperpixel) { get; } | Mendapat nilai bit per piksel. |
| [Bottom](../../groupdocs.metadata.formats.image/psdlayer/bottom) { get; } | Mendapat posisi lapisan bawah. |
| [ChannelCount](../../groupdocs.metadata.formats.image/psdlayer/channelcount) { get; } | Mendapat jumlah saluran. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Flags](../../groupdocs.metadata.formats.image/psdlayer/flags) { get; } | Mendapat flag layer. |
| [Height](../../groupdocs.metadata.formats.image/psdlayer/height) { get; } | Mendapat ketinggian. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Left](../../groupdocs.metadata.formats.image/psdlayer/left) { get; } | Mendapat posisi lapisan kiri. |
| [Length](../../groupdocs.metadata.formats.image/psdlayer/length) { get; } | Mendapat panjang lapisan keseluruhan dalam byte. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Name](../../groupdocs.metadata.formats.image/psdlayer/name) { get; } | Mendapat nama layer. |
| [Opacity](../../groupdocs.metadata.formats.image/psdlayer/opacity) { get; } | Mendapat opacity layer. 0 = transparan, 255 = buram. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Right](../../groupdocs.metadata.formats.image/psdlayer/right) { get; } | Mendapat posisi layer yang tepat. |
| [Top](../../groupdocs.metadata.formats.image/psdlayer/top) { get; } | Mendapat posisi lapisan atas. |
| [Width](../../groupdocs.metadata.formats.image/psdlayer/width) { get; } | Mendapatkan lebarnya. |

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

* [Bekerja dengan metadata dalam gambar PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
