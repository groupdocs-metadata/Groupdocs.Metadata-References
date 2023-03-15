---
title: DicomPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili metadata DICOM asli.
type: docs
weight: 1670
url: /id/net/groupdocs.metadata.formats.image/dicompackage/
---
## DicomPackage class

Mewakili metadata DICOM asli.

```csharp
public sealed class DicomPackage : CustomPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DicomPackage](dicompackage)() | Menginisialisasi instance baru dari[`Metadata`](../../groupdocs.metadata/metadata) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BitsAllocated](../../groupdocs.metadata.formats.image/dicompackage/bitsallocated) { get; } | Mendapat nilai yang dialokasikan bit. |
| [Blues](../../groupdocs.metadata.formats.image/dicompackage/blues) { get; } | Mendapat array warna biru. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DicomInfo](../../groupdocs.metadata.formats.image/dicompackage/dicominfo) { get; } | Mendapat informasi header dari file DICOM. |
| [Greens](../../groupdocs.metadata.formats.image/dicompackage/greens) { get; } | Mendapat warna array hijau. |
| [HeaderBytes](../../groupdocs.metadata.formats.image/dicompackage/headerbytes) { get; } | Mendapat informasi header per byte. |
| [HeaderOffset](../../groupdocs.metadata.formats.image/dicompackage/headeroffset) { get; } | Mendapatkan header offset. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NumberOfFrames](../../groupdocs.metadata.formats.image/dicompackage/numberofframes) { get; } | Mendapat jumlah frame. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Reds](../../groupdocs.metadata.formats.image/dicompackage/reds) { get; } | Mendapat warna array merah. |

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

* [Bekerja dengan metadata DICOM](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
