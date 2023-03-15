---
title: IptcRecordSet
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan kumpulan catatan IPTC.
type: docs
weight: 2940
url: /id/net/groupdocs.metadata.standards.iptc/iptcrecordset/
---
## IptcRecordSet class

Merupakan kumpulan catatan IPTC.

```csharp
public sealed class IptcRecordSet : CustomPackage
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [IptcRecordSet](iptcrecordset#constructor)() | Menginisialisasi instance baru dari[`IptcRecordSet`](../iptcrecordset) kelas. |
| [IptcRecordSet](iptcrecordset#constructor_1)(IptcDataSet[]) | Menginisialisasi instance baru dari[`IptcRecordSet`](../iptcrecordset) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ApplicationRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/applicationrecord) { get; set; } | Mendapat atau menyetel Catatan Aplikasi. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [EnvelopeRecord](../../groupdocs.metadata.standards.iptc/iptcrecordset/enveloperecord) { get; set; } | Mendapat atau menyetel Envelope Record. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcrecordset/item) { get; } | Mendapatkan[`IptcRecord`](../iptcrecord) dengan nomor yang ditentukan. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Add](../../groupdocs.metadata.standards.iptc/iptcrecordset/add)(IptcDataSet) | Menambahkan kumpulan data yang ditentukan ke rekaman yang sesuai. Set data dianggap dapat diulang jika set data dengan nomor yang ditentukan sudah ada. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.standards.iptc/iptcrecordset/clear)() | Menghapus semua rekaman dari koleksi. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove)(byte) | Menghapus record dengan nomor record yang ditentukan. |
| [Remove](../../groupdocs.metadata.standards.iptc/iptcrecordset/remove#remove_1)(byte, byte) | Menghapus kumpulan data dengan catatan dan nomor kumpulan data yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.standards.iptc/iptcrecordset/set)(IptcDataSet) | Menambahkan atau memperbarui kumpulan data yang ditentukan dalam catatan yang sesuai. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [ToDataSetList](../../groupdocs.metadata.standards.iptc/iptcrecordset/todatasetlist)() | Membuat daftar kumpulan data dari paket. |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecordset/tolist)() | Membuat daftar dari paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata IIM IPTC](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Contoh

Contoh kode ini menunjukkan panas untuk memperbarui properti metadata IPTC dasar.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        // Tetapkan paket IPTC jika tidak ada
        if (root.IptcPackage == null)
        {
            root.IptcPackage = new IptcRecordSet();
        }

        if (root.IptcPackage.EnvelopeRecord == null)
        {
            root.IptcPackage.EnvelopeRecord = new IptcEnvelopeRecord();
        }

        root.IptcPackage.EnvelopeRecord.DateSent = DateTime.Now;
        root.IptcPackage.EnvelopeRecord.ProductID = Guid.NewGuid().ToString();

        // ...

        if (root.IptcPackage.ApplicationRecord == null)
        {
            root.IptcPackage.ApplicationRecord = new IptcApplicationRecord();
        }

        root.IptcPackage.ApplicationRecord.ByLine = "GroupDocs";
        root.IptcPackage.ApplicationRecord.Headline = "test";
        root.IptcPackage.ApplicationRecord.ByLineTitle = "code sample";
        root.IptcPackage.ApplicationRecord.ReleaseDate = DateTime.Today;

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Lihat juga

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* ruang nama [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
