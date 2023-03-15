---
title: XmpThumbnail
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan gambar thumbnail untuk file.
type: docs
weight: 3580
url: /id/net/groupdocs.metadata.standards.xmp/xmpthumbnail/
---
## XmpThumbnail class

Merupakan gambar thumbnail untuk file.

```csharp
public sealed class XmpThumbnail : XmpComplexType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpThumbnail](xmpthumbnail#constructor)() | Menginisialisasi instance baru dari[`XmpThumbnail`](../xmpthumbnail) kelas. |
| [XmpThumbnail](xmpthumbnail#constructor_1)(int, int) | Menginisialisasi instance baru dari[`XmpThumbnail`](../xmpthumbnail) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Format](../../groupdocs.metadata.standards.xmp/xmpthumbnail/format) { get; set; } | Mendapat atau mengatur format gambar. Nilai yang ditentukan: JPEG. |
| [Height](../../groupdocs.metadata.standards.xmp/xmpthumbnail/height) { get; set; } | Mendapat atau menyetel tinggi gambar dalam piksel. |
| [ImageBase64](../../groupdocs.metadata.standards.xmp/xmpthumbnail/imagebase64) { get; set; } | Mendapat atau menyetel data gambar thumbnail lengkap, dikonversi ke notasi basis 64. |
| [ImageData](../../groupdocs.metadata.standards.xmp/xmpthumbnail/imagedata) { get; } | Mendapat data gambar. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Mendapat URI namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Mendapat prefiks namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Width](../../groupdocs.metadata.standards.xmp/xmpthumbnail/width) { get; set; } | Mendapat atau menyetel lebar gambar dalam piksel. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Mendapat URI namespace yang terkait dengan prefiks yang ditentukan. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Mengembalikan string berisi nilai dalam format XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Mengembalikan aString yang mewakili instance ini. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Lihat juga

* class [XmpComplexType](../xmpcomplextype)
* ruang nama [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
