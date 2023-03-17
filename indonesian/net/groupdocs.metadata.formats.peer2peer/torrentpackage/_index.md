---
title: TorrentPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata file deskriptor torrent. Temukan informasi lebih lanjut dihttps//en.wikipedia.org/wiki/Torrent_filehttps//en.wikipedia.org/wiki/Torrent_file .
type: docs
weight: 2190
url: /id/net/groupdocs.metadata.formats.peer2peer/torrentpackage/
---
## TorrentPackage class

Mewakili metadata file deskriptor torrent. Temukan informasi lebih lanjut di[https://en.wikipedia.org/wiki/Torrent_file](https://en.wikipedia.org/wiki/Torrent_file) .

```csharp
public sealed class TorrentPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Announce](../../groupdocs.metadata.formats.peer2peer/torrentpackage/announce) { get; set; } | Mendapat atau menyetel URL pelacak. |
| [Comment](../../groupdocs.metadata.formats.peer2peer/torrentpackage/comment) { get; set; } | Mendapat atau menyetel komentar penulis. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [CreatedBy](../../groupdocs.metadata.formats.peer2peer/torrentpackage/createdby) { get; set; } | Mendapatkan atau menyetel nama dan versi program yang digunakan untuk membuat torrent. |
| [CreationDate](../../groupdocs.metadata.formats.peer2peer/torrentpackage/creationdate) { get; set; } | Mendapat atau menyetel tanggal pembuatan torrent. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PieceLength](../../groupdocs.metadata.formats.peer2peer/torrentpackage/piecelength) { get; } | Mendapat jumlah byte di setiap bagian. Untuk informasi lebih lanjut silakan lihat . |
| [Pieces](../../groupdocs.metadata.formats.peer2peer/torrentpackage/pieces) { get; } | Mendapat array byte yang terdiri dari gabungan semua nilai hash SHA1 20-byte, satu per keping. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [SharedFiles](../../groupdocs.metadata.formats.peer2peer/torrentpackage/sharedfiles) { get; } | Mendapat larik yang berisi entri informasi file bersama. |

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

* [Bekerja dengan file TORRENT](https://docs.groupdocs.com/display/metadatanet/Working+with+TORRENT+files)

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Peer2Peer](../../groupdocs.metadata.formats.peer2peer)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
