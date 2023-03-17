---
title: XmpBasicPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili namespace dasar XMP.
type: docs
weight: 3090
url: /id/net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
---
## XmpBasicPackage class

Mewakili namespace dasar XMP.

```csharp
public sealed class XmpBasicPackage : XmpPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage)() | Menginisialisasi instance baru dari[`XmpBasicPackage`](../xmpbasicpackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BaseUrl](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/baseurl) { get; set; } | Mendapat atau menyetel URL dasar untuk URL relatif dalam konten dokumen. Jika dokumen ini berisi tautan Internet, dan tautan tersebut relatif, tautan tersebut relatif terhadap URL dasar ini. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreateDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/createdate) { get; set; } | Mendapat atau mengatur tanggal dan waktu sumber daya dibuat. |
| [CreatorTool](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creatortool) { get; set; } | Mendapatkan atau menyetel nama alat yang digunakan untuk membuat sumber daya. |
| [Identifiers](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) { get; set; } | Mendapat atau menyetel larik string teks tak terurut yang secara jelas mengidentifikasi sumber daya dalam konteks tertentu. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Label](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) { get; set; } | Mendapat atau menyetel kata atau frasa pendek yang mengidentifikasi sumber daya sebagai anggota koleksi yang ditentukan pengguna. |
| [MetadataDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadatadate) { get; set; } | Mendapat atau menyetel tanggal dan waktu metadata apa pun untuk sumber daya ini terakhir diubah. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modifydate) { get; set; } | Mendapatkan atau menetapkan tanggal dan waktu sumber daya terakhir diubah. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Mendapat URI namespace. |
| [Nickname](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) { get; set; } | Mendapat atau menetapkan nama informal singkat untuk sumber daya. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Mendapatkan awalan xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Rating](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) { get; set; } | Mendapat atau menetapkan peringkat yang ditetapkan pengguna untuk file ini. Nilai harus -1 atau dalam rentang [0..5], di mana -1 menunjukkan “ditolak” dan 0 menunjukkan “tidak diberi peringkat”. |
| [Thumbnails](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) { get; set; } | Mendapat atau menyetel larik gambar mini untuk file, yang dapat berbeda dalam karakteristik seperti ukuran atau penyandian gambar. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Mendapatkan ruang nama XML. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Menghapus semua properti XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Mengubah nilai XMP menjadi representasi XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Menghapus properti dengan nama yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Mengatur properti boolean. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | SetDateTime properti. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Mengatur properti ganda. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Mengatur properti bilangan bulat. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set#set_7)(string, string) | Menambahkan properti string. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Menetapkan nilai yang diwarisi dari[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Menetapkan nilai yang diwarisi dari[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Menetapkan nilai yang diwarisi dari[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [RatingMax](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmax) | Peringkat nilai maks. |
| const [RatingMin](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmin) | Peringkat min nilai. |
| const [RatingRejected](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingrejected) | Peringkat ditolak nilai. |

### Lihat juga

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* ruang nama [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
