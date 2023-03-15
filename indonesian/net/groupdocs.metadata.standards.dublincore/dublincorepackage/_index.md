---
title: DublinCorePackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket metadata Dublin Core.
type: docs
weight: 2730
url: /id/net/groupdocs.metadata.standards.dublincore/dublincorepackage/
---
## DublinCorePackage class

Merupakan paket metadata Dublin Core.

```csharp
public sealed class DublinCorePackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Contributor](../../groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) { get; } | Mendapat elemen Dublin Core kontributor. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Coverage](../../groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) { get; } | Mendapatkan cakupan elemen Inti Dublin. |
| [Creator](../../groupdocs.metadata.standards.dublincore/dublincorepackage/creator) { get; } | Mendapat elemen Dublin Core kreator. |
| [Date](../../groupdocs.metadata.standards.dublincore/dublincorepackage/date) { get; } | Mendapat elemen Dublin Core tanggal. |
| [Description](../../groupdocs.metadata.standards.dublincore/dublincorepackage/description) { get; } | Mendapatkan deskripsi elemen Dublin Core. |
| [Format](../../groupdocs.metadata.standards.dublincore/dublincorepackage/format) { get; } | Mendapat format elemen Dublin Core. |
| [Identifier](../../groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) { get; } | Mendapat pengidentifikasi elemen Dublin Core. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Language](../../groupdocs.metadata.standards.dublincore/dublincorepackage/language) { get; } | Mendapat elemen bahasa Dublin Core. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) { get; } | Mendapat elemen Dublin Core penerbit. |
| [Relation](../../groupdocs.metadata.standards.dublincore/dublincorepackage/relation) { get; } | Mendapat elemen Dublin Core relasi. |
| [Rights](../../groupdocs.metadata.standards.dublincore/dublincorepackage/rights) { get; } | Mendapatkan hak elemen Dublin Core. |
| [Source](../../groupdocs.metadata.standards.dublincore/dublincorepackage/source) { get; } | Mendapat sumber elemen Dublin Core. |
| [Subject](../../groupdocs.metadata.standards.dublincore/dublincorepackage/subject) { get; } | Mendapat subjek elemen Dublin Core. |
| [Title](../../groupdocs.metadata.standards.dublincore/dublincorepackage/title) { get; } | Mendapat judul Dublin Core element. |
| [Type](../../groupdocs.metadata.standards.dublincore/dublincorepackage/type) { get; } | Mendapat tipe elemen Dublin Core. |

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

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Standards.DublinCore](../../groupdocs.metadata.standards.dublincore)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
