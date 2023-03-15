---
title: MsgRootPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili paket root yang memungkinkan bekerja dengan metadata dalam pesan email MSG.
type: docs
weight: 1410
url: /id/net/groupdocs.metadata.formats.email/msgrootpackage/
---
## MsgRootPackage class

Mewakili paket root yang memungkinkan bekerja dengan metadata dalam pesan email MSG.

```csharp
public class MsgRootPackage : EmailRootPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [EmailPackage](../../groupdocs.metadata.formats.email/msgrootpackage/emailpackage) { get; } | Mendapatkan paket metadata MSG. (2 properties) |
| [FileType](../../groupdocs.metadata.common/rootmetadatapackage/filetype) { get; } | Mendapatkan paket metadata tipe file. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [ClearAttachments](../../groupdocs.metadata.formats.email/emailrootpackage/clearattachments)() | Menghapus semua lampiran dari pesan email. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan Email yang disimpan](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Contoh

Contoh kode ini menunjukkan cara mengekstrak metadata dari pesan MSG.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMsg))
{
    var root = metadata.GetRootPackage<MsgRootPackage>();

    Console.WriteLine(root.EmailPackage.Sender);
    Console.WriteLine(root.EmailPackage.Subject);
    foreach (string recipient in root.EmailPackage.Recipients)
    {
        Console.WriteLine(recipient);
    }

    foreach (var attachedFileName in root.EmailPackage.AttachedFileNames)
    {
        Console.WriteLine(attachedFileName);
    }

    foreach (var header in root.EmailPackage.Headers)
    {
        Console.WriteLine("{0} = {1}", header.Name, header.Value);
    }

    Console.WriteLine(root.EmailPackage.Body);
    Console.WriteLine(root.EmailPackage.DeliveryTime);

    // ...
}
```

### Lihat juga

* class [EmailRootPackage](../emailrootpackage)
* ruang nama [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
