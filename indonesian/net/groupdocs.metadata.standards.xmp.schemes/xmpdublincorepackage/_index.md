---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili skema Dublin Core.
type: docs
weight: 3120
url: /id/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

Mewakili skema Dublin Core.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | Menginisialisasi instance baru dari[`XmpDublinCorePackage`](../xmpdublincorepackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | Mendapat atau mengatur larik kontributor. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | Mendapat atau menetapkan batas atau ruang lingkup sumber daya. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | Mendapat atau menyetel larik pembuat. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | Mendapat atau menetapkan larik tanggal yang terkait dengan peristiwa dalam siklus hidup sumber daya. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | Mendapat atau menetapkan larik deskripsi tekstual dari konten sumber daya, yang diberikan dalam berbagai bahasa. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | Mendapat atau menyetel tipe MIME sumber daya. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | Mendapat atau menetapkan nilai string yang mewakili referensi yang jelas ke sumber daya dalam konteks tertentu. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | Mendapat atau menyetel larik bahasa yang digunakan dalam konten sumber daya. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Mendapat URI namespace. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Mendapatkan awalan xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | Mendapat atau menyetel larik penerbit yang menyediakan sumber daya. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | Mendapat atau mengatur larik sumber daya terkait. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | Mendapat atau menyetel larik pernyataan hak informal, diberikan dalam berbagai bahasa. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | Mendapat atau menyetel sumber daya terkait dari mana sumber daya yang dijelaskan berasal. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | Mendapat atau menyetel larik frase deskriptif atau kata kunci yang menentukan konten sumber daya. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | Mendapatkan atau menetapkan judul atau nama sumber daya, diberikan dalam berbagai bahasa. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | Mendapat atau menetapkan larik nilai string yang mewakili sifat atau genre sumber daya. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Mengatur properti string. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | Menetapkan nilai yang diwarisi dari[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Menetapkan nilai yang diwarisi dari[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Menetapkan nilai yang diwarisi dari[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | Menetapkan satu kontributor sumber daya. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | Menetapkan satu pembuat sumber daya. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | Menetapkan satu tanggal yang terkait dengan sumber daya. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | Mengatur deskripsi sumber daya, diberikan dalam satu lagu. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | Menetapkan satu bahasa yang terkait dengan sumber daya. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | Menetapkan satu penerbit sumber daya. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | Menetapkan satu sumber daya terkait. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | Menetapkan hak sumber daya, diberikan dalam satu lagu. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | Menetapkan subjek tunggal sumber daya. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | Menetapkan judul sumber daya, diberikan dalam satu lagu. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | Menetapkan satu jenis sumber daya. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

Untuk informasi lebih lanjut lihat: http://dublincore.org/documents/usageguide/elements.shtml.

### Lihat juga

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* ruang nama [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
