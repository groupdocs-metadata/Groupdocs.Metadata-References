---
title: XmpColorantLab
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili Pewarna LAB.
type: docs
weight: 3330
url: /id/net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
---
## XmpColorantLab class

Mewakili Pewarna LAB.

```csharp
public sealed class XmpColorantLab : XmpColorantBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpColorantLab](xmpcolorantlab#constructor)() | Menginisialisasi instance baru dari[`XmpColorantLab`](../xmpcolorantlab) kelas. |
| [XmpColorantLab](xmpcolorantlab#constructor_1)(sbyte, sbyte, double) | Menginisialisasi instance baru dari[`XmpColorantLab`](../xmpcolorantlab) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [A](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/a) { get; set; } | Mendapat atau menyetel komponen A. |
| [B](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/b) { get; set; } | Mendapat atau menyetel komponen B. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Mendapat atau mengatur jenis warna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [L](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/l) { get; set; } | Mendapat atau menyetel komponen L. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Mendapat ruang warna di mana warna ditentukan. Salah satu dari: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Mendapat URI namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Mendapat prefiks namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Mendapat atau menetapkan nama swatch. |

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

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [MaxL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/maxl) | Nilai maks komponen L. |
| const [MinL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/minl) | Nilai komponen L min. |

### Lihat juga

* class [XmpColorantBase](../xmpcolorantbase)
* ruang nama [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
