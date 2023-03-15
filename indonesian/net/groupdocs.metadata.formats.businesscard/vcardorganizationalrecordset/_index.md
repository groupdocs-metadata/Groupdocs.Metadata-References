---
title: VCardOrganizationalRecordset
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili kumpulan catatan vCard Organisasi. Properti ini terkait dengan informasi yang terkait dengan karakteristik organisasi atau unit organisasi dari objek yang diwakili oleh vCard.
type: docs
weight: 750
url: /id/net/groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/
---
## VCardOrganizationalRecordset class

Mewakili kumpulan catatan vCard Organisasi. Properti ini terkait dengan informasi yang terkait dengan karakteristik organisasi atau unit organisasi dari objek yang diwakili oleh vCard.

```csharp
public class VCardOrganizationalRecordset : VCardRecordset
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AgentObjectRecord](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentobjectrecord) { get; } | Mendapat informasi tentang orang lain yang akan bertindak atas nama objek vCard. |
| [AgentRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agentrecords) { get; } | Mendapat informasi tentang orang lain yang akan bertindak atas nama objek vCard. |
| [AgentUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/agenturirecords) { get; } | Mendapat informasi tentang orang lain yang akan bertindak atas nama objek vCard. |
| [BinaryLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/binarylogos) { get; } | Mendapat gambar grafis dari logo yang diasosiasikan dengan objek. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [LogoBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logobinaryrecords) { get; } | Mendapat gambar grafis dari logo yang diasosiasikan dengan objek. |
| [LogoRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logorecords) { get; } | Mendapat gambar grafis dari logo yang diasosiasikan dengan objek. |
| [LogoUriRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/logourirecords) { get; } | Mendapatkan URI dari gambar grafik logo yang terkait dengan objek. |
| [MemberRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/memberrecords) { get; } | Mendapatkan anggota dalam grup yang diwakili oleh vCard ini. |
| [Members](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/members) { get; } | Mendapatkan anggota dalam grup yang diwakili oleh vCard ini. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [ObjectAgent](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/objectagent) { get; } | Mendapat informasi tentang orang lain yang akan bertindak atas nama objek vCard. |
| [OrganizationNameRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnamerecords) { get; } | Mendapat nama organisasi dan unit yang terkait dengan objek. |
| [OrganizationNames](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/organizationnames) { get; } | Mendapat nama organisasi dan unit yang terkait dengan objek. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [RelationshipRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationshiprecords) { get; } | Mendapatkan relasi antara entitas lain dan entitas yang diwakili oleh vCard ini. |
| [Relationships](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/relationships) { get; } | Mendapatkan relasi antara entitas lain dan entitas yang diwakili oleh vCard ini. |
| [RoleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/rolerecords) { get; } | Mendapat fungsi atau bagian yang dimainkan dalam situasi tertentu oleh objek. |
| [Roles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/roles) { get; } | Mendapat fungsi atau bagian yang dimainkan dalam situasi tertentu oleh objek. |
| [TitleRecords](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titlerecords) { get; } | Mendapat posisi atau pekerjaan objek. |
| [Titles](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/titles) { get; } | Mendapat posisi atau pekerjaan objek. |
| [UriAgents](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/uriagents) { get; } | Mendapat informasi tentang orang lain yang akan bertindak atas nama objek vCard. |
| [UriLogos](../../groupdocs.metadata.formats.businesscard/vcardorganizationalrecordset/urilogos) { get; } | Mendapatkan URI dari gambar grafik logo yang terkait dengan objek. |

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
