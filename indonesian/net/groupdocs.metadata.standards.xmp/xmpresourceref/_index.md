---
title: XmpResourceRef
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan referensi beberapa bagian ke sumber daya. Digunakan untuk menunjukkan versi sebelumnya asli terjemahan asli untuk dokumen turunan dan sebagainya.
type: docs
weight: 3550
url: /id/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Merupakan referensi beberapa bagian ke sumber daya. Digunakan untuk menunjukkan versi sebelumnya, asli terjemahan, asli untuk dokumen turunan, dan sebagainya.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Menginisialisasi instance baru dari[`XmpResourceRef`](../xmpresourceref) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Mendapat atau menyetel jalur atau URL file fallback sumber daya yang direferensikan. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Mendapat atau menetapkan nilai properti xmpMM:DocumentID dari resource yang direferensikan. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Mendapat atau menetapkan jalur file atau URL sumber daya yang direferensikan. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Mendapat atau menetapkan nilai properti xmpMM:InstanceID dari resource yang direferensikan. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Mendapat atau menetapkan nilai stEvt:kapan terakhir kali file ditulis. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Mendapatkan atau menyetel xmpMM:Manager sumber daya yang direferensikan. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Mendapatkan atau menyetel xmpMM:Manager sumber daya yang direferensikan. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Mendapat atau menyetel xmpMM sumber daya yang direferensikan: ManageTo. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Mendapat atau menyetel xmpMM sumber daya yang direferensikan: Kelola UI. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Mendapat URI namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | Mendapat atau menetapkan nama atau URI dari fungsi pemetaan yang digunakan untuk memetakan fromPart ke toPart. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Mendapat prefiks namespace yang digunakan di[`XmpComplexType`](../xmpcomplextype) contoh. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Mendapat atau menyetel nilai properti xmpMM:RenditionClass dari resource yang direferensikan. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Mendapat atau menyetel nilai properti xmpMM:RenditionParams dari resource yang direferensikan. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Mendapat atau menyetel nilai properti xmpMM:RenditionParams dari resource yang direferensikan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Mendapat URI namespace yang terkait dengan prefiks yang ditentukan. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Mengembalikan string berisi nilai dalam format XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Mengembalikan aString yang mewakili instance ini. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Lihat juga

* class [XmpComplexType](../xmpcomplextype)
* ruang nama [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
