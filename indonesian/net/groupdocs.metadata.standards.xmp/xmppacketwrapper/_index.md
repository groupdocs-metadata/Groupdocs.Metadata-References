---
title: XmpPacketWrapper
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Berisi paket XMP berseri termasuk header dan trailer. Pembungkus yang terdiri dari sepasang instruksi pemrosesan XML PI dapat ditempatkan di sekitar elemen rdfRDF.
type: docs
weight: 3500
url: /id/net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Berisi paket XMP berseri termasuk header dan trailer. Pembungkus yang terdiri dari sepasang instruksi pemrosesan XML (PI) dapat ditempatkan di sekitar elemen rdf:RDF.

```csharp
public class XmpPacketWrapper : MetadataPackage, IXmpType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | Menginisialisasi instance baru dari[`XmpPacketWrapper`](../xmppacketwrapper) kelas. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPI, XmpTrailerPI, XmpMeta) | Menginisialisasi instance baru dari[`XmpPacketWrapper`](../xmppacketwrapper) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [HeaderPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/headerpi) { get; set; } | Mendapat atau menyetel instruksi pemrosesan tajuk. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Meta](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/meta) { get; set; } | Mendapat atau menyetel meta XMP. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PackageCount](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packagecount) { get; } | Mendapat jumlah paket di dalam struktur XMP. |
| [Packages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packages) { get; } | Mendapat berbagai[`XmpPackage`](../xmppackage) di dalam XMP. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Schemes](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes) { get; } | Memberikan akses ke skema XMP yang dikenal. |
| [TrailerPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/trailerpi) { get; set; } | Mendapat atau menyetel instruksi pemrosesan trailer. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage)(XmpPackage) | Menambahkan paket. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [ClearPackages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/clearpackages)() | Menghapus semua[`XmpPackage`](../xmppackage) di dalam XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| [ContainsPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/containspackage)(string) | Menentukan apakah paket ada di pembungkus XMP. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [GetPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getpackage)(string) | Mendapat paket dengan namespace uri. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getxmprepresentation)() | Mengembalikan string berisi nilai dalam format XMP. |
| [RemovePackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/removepackage)(XmpPackage) | Menghapus paket yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Contoh

Contoh ini menunjukkan cara memperbarui properti metadata XMP.

```csharp
using (Metadata metadata = new Metadata(Constants.GifWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null && root.XmpPackage != null)
    {
        // jika tidak ada skema seperti itu di paket XMP, kita harus membuatnya
        if (root.XmpPackage.Schemes.DublinCore == null)
        {
            root.XmpPackage.Schemes.DublinCore = new XmpDublinCorePackage();
        }
        root.XmpPackage.Schemes.DublinCore.Format = "image/gif";
        root.XmpPackage.Schemes.DublinCore.SetRights("Copyright (C) 2011-2022 GroupDocs. All Rights Reserved");
        root.XmpPackage.Schemes.DublinCore.SetSubject("test");

        if (root.XmpPackage.Schemes.CameraRaw == null)
        {
            root.XmpPackage.Schemes.CameraRaw = new XmpCameraRawPackage();
        }
        root.XmpPackage.Schemes.CameraRaw.Shadows = 50;
        root.XmpPackage.Schemes.CameraRaw.AutoBrightness = true;
        root.XmpPackage.Schemes.CameraRaw.AutoExposure = true;
        root.XmpPackage.Schemes.CameraRaw.CameraProfile = "test";
        root.XmpPackage.Schemes.CameraRaw.Exposure = 0.0001;

        // Jika Anda tidak ingin mempertahankan nilai lama, ganti saja seluruh skema
        root.XmpPackage.Schemes.XmpBasic = new XmpBasicPackage();
        root.XmpPackage.Schemes.XmpBasic.CreateDate = DateTime.Today;
        root.XmpPackage.Schemes.XmpBasic.BaseUrl = "https://groupdocs.com";
        root.XmpPackage.Schemes.XmpBasic.Rating = 5;

        root.XmpPackage.Schemes.BasicJobTicket = new XmpBasicJobTicketPackage();

        // Tetapkan properti tipe kompleks
        root.XmpPackage.Schemes.BasicJobTicket.Jobs = new[]
        {
            new XmpJob
            {
                ID = "1",
                Name = "test job",
                Url = "https://groupdocs.com"
            },
        };

        // ... 

        metadata.Save(Constants.OutputGif);
    }
}
```

### Lihat juga

* class [MetadataPackage](../../groupdocs.metadata.common/metadatapackage)
* interface [IXmpType](../ixmptype)
* ruang nama [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
