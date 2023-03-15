---
title: XmpPhotoshopPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili ruang nama Adobe Photoshop.
type: docs
weight: 3210
url: /id/net/groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/
---
## XmpPhotoshopPackage class

Mewakili ruang nama Adobe Photoshop.

```csharp
public sealed class XmpPhotoshopPackage : XmpPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpPhotoshopPackage](xmpphotoshoppackage)() | Menginisialisasi instance baru dari[`XmpPhotoshopPackage`](../xmpphotoshoppackage) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AuthorsPosition](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/authorsposition) { get; set; } | Mendapat atau mengatur judul by-line. |
| [CaptionWriter](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/captionwriter) { get; set; } | Mendapatkan atau menyetel penulis/editor. |
| [Category](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/category) { get; set; } | Mendapat atau menetapkan kategori. Terbatas hingga 3 karakter ASCII 7-bit. |
| [City](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/city) { get; set; } | Mendapat atau mengatur kota. |
| [ColorMode](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/colormode) { get; set; } | Mendapat atau menyetel mode warna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Country](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/country) { get; set; } | Mendapat atau mengatur negara. |
| [Credit](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/credit) { get; set; } | Mendapatkan atau menetapkan kredit. |
| [DateCreated](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/datecreated) { get; set; } | Mendapatkan atau menetapkan tanggal pembuatan konten intelektual dokumen. |
| [Headline](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/headline) { get; set; } | Mendapat atau menetapkan judul. |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/history) { get; set; } | Mendapat atau menyetel riwayat yang muncul di panel FileInfo, jika diaktifkan di preferensi aplikasi. |
| [IccProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/iccprofile) { get; set; } | Mendapat atau menyetel profil warna, seperti AppleRGB, AdobeRGB1998. |
| [Instructions](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/instructions) { get; set; } | Mendapat atau menyetel instruksi khusus. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Mendapat URI namespace. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Mendapatkan awalan xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/source) { get; set; } | Mendapat atau menyetel sumber. |
| [State](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/state) { get; set; } | Mendapat atau menetapkan provinsi/negara bagian. |
| [SupplementalCategories](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/supplementalcategories) { get; set; } | Mendapat atau menetapkan kategori tambahan. |
| [TransmissionReference](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/transmissionreference) { get; set; } | Mendapat atau menyetel referensi transmisi asli. |
| [Urgency](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgency) { get; set; } | Mendapat atau menyetel urgensi. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/set#set_7)(string, string) | Mengatur properti string. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Menetapkan nilai yang diwarisi dari[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Menetapkan nilai yang diwarisi dari[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Menetapkan nilai yang diwarisi dari[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [UrgencyMax](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgencymax) | Nilai maks urgensi. |
| const [UrgencyMin](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgencymin) | Nilai min urgensi. |

### Lihat juga

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* ruang nama [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
