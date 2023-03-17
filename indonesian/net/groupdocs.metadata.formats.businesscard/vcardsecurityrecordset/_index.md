---
title: VCardSecurityRecordset
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili sekumpulan catatan Keamanan vCard. Properti ini berkaitan dengan keamanan jalur komunikasi atau akses ke vCard.
type: docs
weight: 800
url: /id/net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/
---
## VCardSecurityRecordset class

Mewakili sekumpulan catatan Keamanan vCard. Properti ini berkaitan dengan keamanan jalur komunikasi atau akses ke vCard.

```csharp
public class VCardSecurityRecordset : VCardRecordset
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AccessClassification](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/accessclassification) { get; } | Mendapatkan sensitivitas informasi di vCard. |
| [BinaryPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/binarypublickeys) { get; } | Mendapatkan kunci publik atau sertifikat autentikasi yang terkait dengan objek. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [PublicKeyBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeybinaryrecords) { get; } | Mendapatkan kunci publik atau sertifikat autentikasi yang terkait dengan objek. |
| [PublicKeyRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyrecords) { get; } | Mendapatkan kunci publik atau sertifikat autentikasi yang terkait dengan objek. |
| [PublicKeyUriRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyurirecords) { get; } | Mendapatkan kunci publik atau sertifikat autentikasi yang terkait dengan objek. |
| [UriPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/uripublickeys) { get; } | Mendapatkan kunci publik atau sertifikat autentikasi yang terkait dengan objek. |

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
