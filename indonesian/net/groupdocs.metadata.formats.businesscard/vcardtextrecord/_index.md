---
title: VCardTextRecord
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili kelas metadata catatan teks vCard.
type: docs
weight: 810
url: /id/net/groupdocs.metadata.formats.businesscard/vcardtextrecord/
---
## VCardTextRecord class

Mewakili kelas metadata catatan teks vCard.

```csharp
public class VCardTextRecord : VCardRecord
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AltIdParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/altidparameter) { get; } | Mendapatkan nilai parameter representasi alternatif. |
| [AnonymParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/anonymparameters) { get; } | Mendapatkan parameter anonim. |
| [CharsetParameter](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/charsetparameter) { get; } | Mendapatkan parameter charset. |
| override [ContentType](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/contenttype) { get; } | Mendapat jenis konten rekaman. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [EncodingParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/encodingparameter) { get; } | Mendapat nilai parameter penyandian. |
| [Group](../../groupdocs.metadata.formats.businesscard/vcardrecord/group) { get; } | Mendapatkan nilai pengelompokan. |
| [IsQuotedPrintable](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/isquotedprintable) { get; } | Mendapat nilai yang menunjukkan apakah instance ini dikutip string yang dapat dicetak. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [LanguageParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/languageparameter) { get; } | Mendapatkan nilai parameter bahasa. |
| [MediaTypeParameter](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/mediatypeparameter) { get; } | Mendapatkan nilai parameter jenis media. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PrefParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/prefparameter) { get; } | Mendapatkan parameter pilihan. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [TypeName](../../groupdocs.metadata.formats.businesscard/vcardrecord/typename) { get; } | Mendapatkan jenis record. |
| [TypeParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/typeparameters) { get; } | Mendapatkan nilai parameter tipe. |
| [Value](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/value) { get; } | Mendapat nilai record. |
| [ValueParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/valueparameters) { get; } | Mendapat parameter nilai. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [GetReadabilityValue](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/getreadabilityvalue)(string) | Mendapatkan nilai keterbacaan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata vCard](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### Lihat juga

* class [VCardRecord](../vcardrecord)
* ruang nama [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
