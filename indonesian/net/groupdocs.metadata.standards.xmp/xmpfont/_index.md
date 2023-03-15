---
title: XmpFont
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Struktur yang berisi karakteristik font yang digunakan dalam dokumen.
type: docs
weight: 3400
url: /id/net/groupdocs.metadata.standards.xmp/xmpfont/
---
## XmpFont class

Struktur yang berisi karakteristik font yang digunakan dalam dokumen.

```csharp
public sealed class XmpFont : XmpComplexType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpFont](xmpfont#constructor)() | Menginisialisasi instance baru dari[`XmpFont`](../xmpfont) kelas. |
| [XmpFont](xmpfont#constructor_1)(string) | Menginisialisasi instance baru dari[`XmpFont`](../xmpfont) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ChildFontFiles](../../groupdocs.metadata.standards.xmp/xmpfont/childfontfiles) { get; set; } | Mendapat atau menyetel daftar nama file untuk font yang membentuk font komposit. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [FontFace](../../groupdocs.metadata.standards.xmp/xmpfont/fontface) { get; set; } | Mendapat atau menyetel nama tampilan font. |
| [FontFamily](../../groupdocs.metadata.standards.xmp/xmpfont/fontfamily) { get; set; } | Mendapat atau menyetel nama keluarga font. |
| [FontFileName](../../groupdocs.metadata.standards.xmp/xmpfont/fontfilename) { get; set; } | Mendapat atau menyetel nama file font (bukan jalur lengkap). |
| [FontName](../../groupdocs.metadata.standards.xmp/xmpfont/fontname) { get; set; } | Mendapat atau menetapkan nama font PostScript. |
| [FontType](../../groupdocs.metadata.standards.xmp/xmpfont/fonttype) { get; set; } | Mendapat atau menyetel jenis font. |
| [IsComposite](../../groupdocs.metadata.standards.xmp/xmpfont/iscomposite) { get; set; } | Mendapat atau menetapkan nilai yang menunjukkan apakah font komposit. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Mendapat URI namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Mendapat prefiks namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Version](../../groupdocs.metadata.standards.xmp/xmpfont/version) { get; set; } | Mendapat atau menyetel versi font. |

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
