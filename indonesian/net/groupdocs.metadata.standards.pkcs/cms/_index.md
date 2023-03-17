---
title: Cms
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili tanda digital yang dibuat dengan Cryptographic Message Syntax CMS  standar IETF untuk pesan yang dilindungi secara kriptografis. CMS didasarkan pada sintaks PKCS 7 ditentukan dalam RFC 5652. Silakan lihathttps//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 untuk informasi lebih lanjut.
type: docs
weight: 2960
url: /id/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Mewakili tanda digital yang dibuat dengan Cryptographic Message Syntax (CMS) - standar IETF untuk pesan yang dilindungi secara kriptografis. CMS didasarkan pada sintaks PKCS #7, ditentukan dalam RFC 5652. Silakan lihat[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) untuk informasi lebih lanjut.

```csharp
public class Cms : DigitalSignature
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Mendapat data mentah sertifikat. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Mendapat kumpulan sertifikat. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Mendapatkan nama subjek yang berbeda dari sertifikat. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Mendapat komentar tujuan penandatanganan. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Mendapat jumlah properti metadata. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Mendapatkan larik pengidentifikasi algoritme intisari pesan. Mungkin ada sejumlah elemen dalam koleksi, termasuk nol. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Mendapat konten yang ditandatangani, terdiri dari pengidentifikasi tipe konten dan konten itu sendiri. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Mendapat nilai yang menunjukkan apakah tanda tangan itu valid. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Mendapatkan[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) dengan nama yang ditentukan. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Mendapat kumpulan nama properti metadata. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Mendapatkan jenis metadata. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Mendapat kumpulan deskriptor yang berisi informasi tentang properti yang dapat diakses melalui mesin pencari GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Mendapatkan kumpulan paket informasi per penanda tangan. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Mendapat waktu di mana penanda tangan (konon) melakukan proses penandatanganan. |

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

### Lihat juga

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* ruang nama [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
