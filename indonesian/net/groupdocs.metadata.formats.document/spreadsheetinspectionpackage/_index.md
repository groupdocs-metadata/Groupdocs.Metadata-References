---
title: SpreadsheetInspectionPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Berisi informasi tentang bagian spreadsheet yang dalam beberapa kasus dapat dianggap sebagai metadata.
type: docs
weight: 1190
url: /id/net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/
---
## SpreadsheetInspectionPackage class

Berisi informasi tentang bagian spreadsheet yang dalam beberapa kasus dapat dianggap sebagai metadata.

```csharp
public sealed class SpreadsheetInspectionPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/comments) { get; } | Mendapat susunan komentar pengguna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/digitalsignatures) { get; } | Mendapat serangkaian tanda tangan digital yang disajikan dalam dokumen. |
| [HiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/hiddensheets) { get; } | Mendapat array dari lembar tersembunyi. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [ClearComments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearcomments)() | Menghapus semua komentar pengguna yang terdeteksi dari spreadsheet. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/cleardigitalsignatures)() | Menghapus semua tanda tangan digital yang terdeteksi dari spreadsheet. |
| [ClearHiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearhiddensheets)() | Menghapus semua sheet tersembunyi yang terdeteksi dari spreadsheet. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| override [Sanitize](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata di Spreadsheet](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Contoh

Contoh kode ini menunjukkan panas untuk menghapus properti inspeksi dari spreadsheet.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearDigitalSignatures();
    root.InspectionPackage.ClearHiddenSheets();

    metadata.Save(Constants.OutputXlsx);
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
