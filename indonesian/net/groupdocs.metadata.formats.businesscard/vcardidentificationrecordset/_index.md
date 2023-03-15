---
title: VCardIdentificationRecordset
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili kumpulan catatan vCard Identifikasi. Jenis ini digunakan untuk menangkap informasi yang terkait dengan identifikasi dan penamaan entitas yang terkait dengan vCard.
type: docs
weight: 740
url: /id/net/groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/
---
## VCardIdentificationRecordset class

Mewakili kumpulan catatan vCard Identifikasi. Jenis ini digunakan untuk menangkap informasi yang terkait dengan identifikasi dan penamaan entitas yang terkait dengan vCard.

```csharp
public class VCardIdentificationRecordset : VCardRecordset
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AnniversaryDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarydatetimerecord) { get; } | Mendapatkan tanggal pernikahan yang direpresentasikan sebagai nilai tanggal dan atau waktu tunggal. |
| [AnniversaryRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversaryrecord) { get; } | Mendapat tanggal pernikahan, atau yang setara, dari objek. |
| [AnniversaryTextRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/anniversarytextrecord) { get; } | Mendapatkan tanggal pernikahan yang direpresentasikan sebagai nilai teks tunggal. |
| [BinaryPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/binaryphotos) { get; } | Mendapat larik yang berisi informasi gambar atau foto yang direpresentasikan sebagai data biner yang menjelaskan beberapa aspek objek. |
| [BirthdateDateTimeRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatedatetimerecord) { get; } | Mendapat tanggal lahir objek. |
| [BirthdateRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdaterecords) { get; } | Mendapat array yang berisi tanggal lahir objek dalam representasi yang berbeda. |
| [BirthdateTextRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/birthdatetextrecords) { get; } | Mendapat array yang berisi tanggal lahir objek dalam representasi teks yang berbeda. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DateTimeAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimeanniversary) { get; } | Mendapatkan tanggal pernikahan yang direpresentasikan sebagai nilai tanggal dan atau waktu tunggal. |
| [DateTimeBirthdate](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/datetimebirthdate) { get; } | Mendapat tanggal lahir objek. |
| [FormattedNameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednamerecords) { get; } | Mendapat larik yang berisi teks berformat yang sesuai dengan nama objek. |
| [FormattedNames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/formattednames) { get; } | Mendapat larik yang berisi teks berformat yang sesuai dengan nama objek. |
| [Gender](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/gender) { get; } | Mendapat komponen jenis kelamin dan identitas gender objek. |
| [GenderRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/genderrecord) { get; } | Mendapat komponen jenis kelamin dan identitas gender objek. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [Name](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/name) { get; } | Mendapat komponen nama objek. |
| [NameRecord](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/namerecord) { get; } | Mendapat komponen nama objek. |
| [NicknameRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknamerecords) { get; } | Mendapat array yang berisi teks yang sesuai dengan nama panggilan objek. |
| [Nicknames](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/nicknames) { get; } | Mendapat array yang berisi teks yang sesuai dengan nama panggilan objek. |
| [PhotoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photobinaryrecords) { get; } | Mendapat larik yang berisi informasi gambar atau foto yang direpresentasikan sebagai data biner yang menjelaskan beberapa aspek objek. |
| [PhotoRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photorecords) { get; } | Mendapat larik yang berisi informasi gambar atau foto yang menganotasi beberapa aspek objek. |
| [PhotoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/photourirecords) { get; } | Mendapat larik yang berisi informasi gambar atau foto yang diwakili oleh URI yang menganotasi beberapa aspek objek. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [TextAnniversary](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textanniversary) { get; } | Mendapatkan tanggal pernikahan yang direpresentasikan sebagai nilai teks tunggal. |
| [TextBirthdates](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/textbirthdates) { get; } | Mendapat array yang berisi tanggal lahir objek dalam representasi teks yang berbeda. |
| [UriPhotos](../../groupdocs.metadata.formats.businesscard/vcardidentificationrecordset/uriphotos) { get; } | Mendapat larik yang berisi informasi gambar atau foto yang diwakili oleh URI yang menganotasi beberapa aspek objek. |

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
