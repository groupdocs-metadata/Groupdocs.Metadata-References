---
title: VCardExplanatoryRecordset
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili satu set catatan vCard Penjelasan. Properti ini berkaitan dengan penjelasan tambahan seperti yang terkait dengan catatan informasi atau revisi khusus untuk vCard.
type: docs
weight: 710
url: /id/net/groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/
---
## VCardExplanatoryRecordset class

Mewakili satu set catatan vCard Penjelasan. Properti ini berkaitan dengan penjelasan tambahan, seperti yang terkait dengan catatan informasi atau revisi khusus untuk vCard.

```csharp
public class VCardExplanatoryRecordset : VCardRecordset
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BinarySounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/binarysounds) { get; } | Mendapatkan informasi konten suara digital yang menganotasi beberapa aspek vCard. |
| [Categories](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categories) { get; } | Mendapat informasi kategori aplikasi tentang vCard, juga dikenal sebagai "tag". |
| [CategoryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/categoryrecords) { get; } | Mendapat informasi kategori aplikasi tentang vCard, juga dikenal sebagai "tag". |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NoteRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/noterecords) { get; } | Mendapat informasi tambahan atau komentar yang terkait dengan vCard. |
| [Notes](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/notes) { get; } | Mendapat informasi tambahan atau komentar yang terkait dengan vCard. |
| [PidIdentifierRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifierrecords) { get; } | Mendapatkan arti global dari pengenal sumber PID lokal. |
| [PidIdentifiers](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/pididentifiers) { get; } | Mendapatkan arti global dari pengenal sumber PID lokal. |
| [ProductIdentifier](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifier) { get; } | Mendapatkan pengenal produk yang membuat objek vCard. |
| [ProductIdentifierRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/productidentifierrecord) { get; } | Mendapatkan pengenal produk yang membuat objek vCard. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Revision](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/revision) { get; } | Mendapat informasi revisi tentang vCard saat ini. |
| [SortString](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/sortstring) { get; } | Mendapat nama keluarga atau teks nama yang diberikan untuk digunakan untuk penyortiran khusus bahasa nasional[`FormattedNames`](../vcardidentificationrecordset/formattednames) Dan[`Name`](../vcardidentificationrecordset/name) jenis. |
| [SoundBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundbinaryrecords) { get; } | Mendapatkan informasi konten suara digital yang menganotasi beberapa aspek vCard. |
| [SoundRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundrecords) { get; } | Mendapatkan informasi konten suara digital yang menganotasi beberapa aspek vCard. |
| [SoundUriRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/soundurirecords) { get; } | Mendapatkan informasi konten suara digital yang menganotasi beberapa aspek vCard. |
| [Uid](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uid) { get; } | Mendapat nilai yang mewakili pengidentifikasi unik global yang sesuai dengan individu atau sumber daya yang terkait dengan vCard. |
| [UidRecord](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/uidrecord) { get; } | Mendapat nilai yang mewakili pengidentifikasi unik global yang sesuai dengan individu atau sumber daya yang terkait dengan vCard. |
| [UriSounds](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urisounds) { get; } | Mendapatkan informasi konten suara digital yang menganotasi beberapa aspek vCard. |
| [UrlRecords](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urlrecords) { get; } | Mendapatkan larik URL yang mengarah ke situs web yang mewakili orang tersebut dengan cara tertentu. |
| [Urls](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/urls) { get; } | Mendapatkan larik URL yang mengarah ke situs web yang mewakili orang tersebut dengan cara tertentu. |
| [Version](../../groupdocs.metadata.formats.businesscard/vcardexplanatoryrecordset/version) { get; } | Mendapatkan versi spesifikasi vCard. |

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

* [Bekerja dengan metadata vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Lihat juga

* class [VCardRecordset](../vcardrecordset)
* ruang nama [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
