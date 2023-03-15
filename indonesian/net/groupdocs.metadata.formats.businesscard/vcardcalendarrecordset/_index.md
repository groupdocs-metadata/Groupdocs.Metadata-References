---
title: VCardCalendarRecordset
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili kumpulan catatan vCard Kalender.
type: docs
weight: 640
url: /id/net/groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/
---
## VCardCalendarRecordset class

Mewakili kumpulan catatan vCard Kalender.

```csharp
public class VCardCalendarRecordset : VCardRecordset
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BusyTimeEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimeentries) { get; } | Mendapatkan URI untuk waktu sibuk yang terkait dengan objek. |
| [BusyTimeRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/busytimerecords) { get; } | Mendapatkan URI untuk waktu sibuk yang terkait dengan objek. |
| [CalendarAddresses](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddresses) { get; } | Mendapatkan alamat pengguna kalender yang harus dikirimi permintaan penjadwalan untuk objek yang diwakili oleh vCard. |
| [CalendarAddressRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendaraddressrecords) { get; } | Mendapatkan alamat pengguna kalender yang harus dikirimi permintaan penjadwalan untuk objek yang diwakili oleh vCard. |
| [CalendarUriRecords](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/calendarurirecords) { get; } | Mendapatkan URI untuk kalender yang terkait dengan objek yang diwakili oleh vCard. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [UriCalendarEntries](../../groupdocs.metadata.formats.businesscard/vcardcalendarrecordset/uricalendarentries) { get; } | Mendapatkan URI untuk kalender yang terkait dengan objek yang diwakili oleh vCard. |

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
