---
title: XmpColorantCmyk
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili Pewarna CMYK.
type: docs
weight: 3310
url: /id/net/groupdocs.metadata.standards.xmp/xmpcolorantcmyk/
---
## XmpColorantCmyk class

Mewakili Pewarna CMYK.

```csharp
public sealed class XmpColorantCmyk : XmpColorantBase
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpColorantCmyk](xmpcolorantcmyk#constructor)() | Menginisialisasi instance baru dari[`XmpColorantCmyk`](../xmpcolorantcmyk) kelas. |
| [XmpColorantCmyk](xmpcolorantcmyk#constructor_1)(double, double, double, double) | Menginisialisasi instance baru dari[`XmpColorantCmyk`](../xmpcolorantcmyk) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Black](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/black) { get; set; } | Mendapat atau menyetel komponen hitam. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Mendapat atau mengatur jenis warna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Cyan](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/cyan) { get; set; } | Mendapat atau menyetel komponen cyan. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Magenta](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/magenta) { get; set; } | Mendapat atau menyetel komponen magenta. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Mendapat ruang warna di mana warna ditentukan. Salah satu dari: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Mendapat URI namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Mendapat prefiks namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Mendapat atau menetapkan nama swatch. |
| [Yellow](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/yellow) { get; set; } | Mendapat atau menyetel komponen kuning. |

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
| const [ColorValueMax](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/colorvaluemax) | Nilai maks warna dalam pewarna CMYK. |
| const [ColorValueMin](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/colorvaluemin) | Nilai min warna dalam pewarna CMYK. |

### Lihat juga

* class [XmpColorantBase](../xmpcolorantbase)
* ruang nama [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
