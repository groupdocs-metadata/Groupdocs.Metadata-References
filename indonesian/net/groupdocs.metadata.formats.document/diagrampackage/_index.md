---
title: DiagramPackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan paket metadata asli dalam format diagram.
type: docs
weight: 890
url: /id/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Merupakan paket metadata asli dalam format diagram.

```csharp
public class DiagramPackage : DocumentPackage
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Mendapat atau menetapkan nama alternatif untuk dokumen. Hanya dapat diperbarui dalam format VDX dan VSX. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Mendapatkan nomor build lengkap dari instance yang digunakan untuk membuat dokumen. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Mendapatkan nomor build dari instance yang terakhir digunakan untuk mengedit dokumen. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Mendapat atau menyetel teks deskriptif untuk jenis gambar, seperti bagan alur atau tata letak kantor. Teks ini juga dapat dimasukkan di antarmuka pengguna Microsoft Visio di kotak Kategori di kotak dialog Properti. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Mendapat atau menetapkan informasi yang dimasukkan pengguna yang mengidentifikasi perusahaan yang membuat gambar atau perusahaan tempat gambar dibuat. Panjang maksimum adalah 63 karakter. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Mendapat atau menetapkan orang yang membuat atau terakhir memperbarui file. Panjang maksimum adalah 63 karakter.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Mendapat atau menyetel string teks deskriptif untuk dokumen. Gunakan elemen ini untuk menyimpan informasi penting tentang dokumen, seperti tujuannya, perubahan terbaru, atau perubahan yang tertunda. Maksimum adalah 191 karakter. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Mendapat atau menyetel jalur yang akan digunakan untuk hyperlink relatif (hyperlink yang lokasi file tertautnya dijelaskan dalam kaitannya dengan diagram Microsoft Visio). Secara default, jalur hyperlink relatif terhadap dokumen saat ini kecuali jalur yang berbeda ditentukan dalam elemen ini. Panjang maksimum adalah 256 karakter. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Mendapat atau menetapkan string teks yang mengidentifikasi topik atau informasi penting lainnya tentang file, seperti nama proyek, nama klien, atau nomor versi. Panjang string maksimum adalah 63 karakter. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Mendapat atau menyetel bahasa dokumen. Hanya dapat diperbarui dalam format VSD dan VSDX. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Mendapat atau menetapkan string teks yang dimasukkan pengguna yang mengidentifikasi penanggung jawab proyek atau departemen. Panjang maksimum adalah 63 karakter. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Mendapat atau menyetel gambar pratinjau. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Mendapat atau menetapkan string teks yang ditentukan pengguna yang mendeskripsikan konten dokumen. Panjang maksimum adalah 63 karakter. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Mendapat atau menyetel nilai string yang menentukan nama file template tempat dokumen dibuat. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Mendapat atau menetapkan nilai tanggal dan waktu yang menunjukkan kapan dokumen dibuat. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Mendapat nilai tanggal dan waktu yang menunjukkan kapan dokumen terakhir diedit. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Mendapat nilai tanggal dan waktu yang menunjukkan kapan dokumen terakhir dicetak. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Mendapat nilai tanggal dan waktu yang menunjukkan kapan dokumen terakhir disimpan. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Mendapat atau menyetel string teks yang ditentukan pengguna yang berfungsi sebagai judul deskriptif untuk dokumen. Panjang maksimum adalah 63 karakter. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menambahkan properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Menghapus semua properti metadata yang dapat ditulis dari paket. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Menghapus semua properti metadata bawaan. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Menghapus semua properti metadata khusus. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Menentukan apakah paket berisi properti metadata dengan nama yang ditentukan. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Menemukan properti metadata yang memenuhi predikat yang ditentukan. Pencarian bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Mengembalikan pencacah yang mengulang melalui koleksi. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Menghapus properti metadata yang dapat ditulis dengan nama yang ditentukan. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Menghapus properti metadata yang memenuhi predikat yang ditentukan. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Menghapus properti metadata yang dapat ditulisi dari paket. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Menambahkan atau mengganti properti metadata dengan nama yang ditentukan. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Menyetel properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. Metode ini merupakan kombinasi dari[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) Dan[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Jika properti yang ada memenuhi predikat, nilainya diperbarui. Jika ada properti yang diketahui hilang dalam paket yang memenuhi predikat itu ditambahkan ke paket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Memperbarui properti metadata yang dikenal yang memenuhi predikat yang ditentukan. Operasi bersifat rekursif sehingga memengaruhi semua paket bersarang juga. |

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata di Diagram](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Contoh

Contoh kode ini menunjukkan cara mengekstrak properti metadata bawaan dari diagram.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Lihat juga

* class [DocumentPackage](../documentpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
