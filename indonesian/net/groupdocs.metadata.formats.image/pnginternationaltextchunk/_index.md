---
title: PngInternationalTextChunk
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan data tekstual internasional yang diekstraksi dari gambar PNG.
type: docs
weight: 1840
url: /id/net/groupdocs.metadata.formats.image/pnginternationaltextchunk/
---
## PngInternationalTextChunk class

Merupakan data tekstual internasional yang diekstraksi dari gambar PNG.

```csharp
public class PngInternationalTextChunk : PngCompressedTextChunk
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CompressionMethod](../../groupdocs.metadata.formats.image/pngcompressedtextchunk/compressionmethod) { get; } | Mendapatkan algoritme yang digunakan untuk mengompres data potongan. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [IsCompressed](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/iscompressed) { get; } | Mendapat nilai yang menunjukkan apakah potongan dikompresi. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keyword](../../groupdocs.metadata.formats.image/pngtextchunk/keyword) { get; } | Mendapat kata kunci yang menunjukkan jenis informasi yang diwakili oleh potongan. |
| [Language](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/language) { get; } | Mendapatkan bahasa manusia yang digunakan oleh kata kunci yang diterjemahkan dan teks. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Text](../../groupdocs.metadata.formats.image/pngtextchunk/text) { get; } | Mendapat string teks sebenarnya yang diwakili oleh potongan. |
| [TranslatedKeyword](../../groupdocs.metadata.formats.image/pnginternationaltextchunk/translatedkeyword) { get; } | Mendapat kata kunci terjemahan yang berisi terjemahan kata kunci ke dalam bahasa yang ditunjukkan oleh properti bahasa. |

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

### Lihat juga

* class [PngCompressedTextChunk](../pngcompressedtextchunk)
* ruang nama [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
