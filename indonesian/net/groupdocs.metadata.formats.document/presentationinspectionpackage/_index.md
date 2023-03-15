---
title: PresentationInspectionPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Berisi informasi tentang bagian presentasi yang dapat dianggap sebagai metadata dalam beberapa kasus.
type: docs
weight: 1080
url: /id/net/groupdocs.metadata.formats.document/presentationinspectionpackage/
---
## PresentationInspectionPackage class

Berisi informasi tentang bagian presentasi yang dapat dianggap sebagai metadata dalam beberapa kasus.

```csharp
public sealed class PresentationInspectionPackage : CustomPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/presentationinspectionpackage/comments) { get; } | Mendapat susunan komentar. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [HiddenSlides](../../groupdocs.metadata.formats.document/presentationinspectionpackage/hiddenslides) { get; } | Mendapat susunan slide tersembunyi. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [ClearComments](../../groupdocs.metadata.formats.document/presentationinspectionpackage/clearcomments)() | Menghapus semua komentar pengguna yang terdeteksi dari presentasi. |
| [ClearHiddenSlides](../../groupdocs.metadata.formats.document/presentationinspectionpackage/clearhiddenslides)() | Menghapus semua slide tersembunyi yang terdeteksi dari presentasi. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/presentationinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| override [Sanitize](../../groupdocs.metadata.formats.document/presentationinspectionpackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata di Presentasi](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### Contoh

Contoh kode ini menunjukkan cara membersihkan properti pemeriksaan dalam presentasi.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPpt))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearHiddenSlides();

    metadata.Save(Constants.OutputPpt);
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
