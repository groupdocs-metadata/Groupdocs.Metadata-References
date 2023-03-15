---
title: PdfInspectionPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Berisi informasi tentang bagian dokumen PDF yang dapat dianggap sebagai metadata dalam beberapa kasus.
type: docs
weight: 1020
url: /id/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Berisi informasi tentang bagian dokumen PDF yang dapat dianggap sebagai metadata dalam beberapa kasus.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Mendapat larik anotasi. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Mendapat susunan lampiran. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Mendapat larik bookmark. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Mendapat larik tanda tangan digital. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Mendapat larik bidang formulir. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Menghapus semua anotasi yang terdeteksi dari dokumen. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Menghapus semua lampiran yang terdeteksi dari dokumen. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Menghapus semua bookmark yang terdeteksi dari dokumen. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Menghapus semua tanda tangan digital yang terdeteksi dari dokumen. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Menghapus semua bidang formulir yang terdeteksi dari dokumen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata dalam dokumen PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Contoh

Contoh kode ini menunjukkan cara menghapus properti pemeriksaan dalam dokumen PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
