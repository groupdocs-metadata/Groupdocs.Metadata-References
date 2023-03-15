---
title: XmpLangAlt
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Merupakan Alternatif Bahasa XMP.
type: docs
weight: 3450
url: /id/net/groupdocs.metadata.standards.xmp/xmplangalt/
---
## XmpLangAlt class

Merupakan Alternatif Bahasa XMP.

Array alternatif dari item teks sederhana. Alternatif bahasa memfasilitasi pemilihan item teks sederhana berdasarkan bahasa yang diinginkan. Setiap item array harus memiliki kualifikasi xml:lang. Setiap nilai xml:lang harus unik di antara item.

```csharp
public sealed class XmpLangAlt : XmpArray
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpLangAlt](xmplangalt#constructor)(IDictionary&lt;string, string&gt;) | Menginisialisasi instance baru dari[`XmpLangAlt`](../xmplangalt) kelas. |
| [XmpLangAlt](xmplangalt#constructor_1)(string) | Menginisialisasi instance baru dari[`XmpLangAlt`](../xmplangalt) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | Mendapatkan tipe array XMP. |
| [Item](../../groupdocs.metadata.standards.xmp/xmplangalt/item) { get; } | Mendapat nilai yang terkait dengan bahasa yang ditentukan. |
| [Languages](../../groupdocs.metadata.standards.xmp/xmplangalt/languages) { get; } | Mendapat array dari semua bahasa yang terdaftar di contoh[`XmpLangAlt`](../xmplangalt) . |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Mendapat nilai mentah. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Mendapatkan[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Mengekstrak nilai properti menggunakan kebiasaan[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| [Contains](../../groupdocs.metadata.standards.xmp/xmplangalt/contains)(string) | Menentukan apakah[`XmpLangAlt`](../xmplangalt) berisi bahasa yang ditentukan. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmplangalt/getxmprepresentation)() | Mengonversi nilai XMP ke representasi xml. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Mengubah nilai properti menjadi larik dengan tipe yang ditentukan. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Mengubah nilai properti menjadi tipe referensi. |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | Mengubah[`XmpArray`](../xmparray) ke array khusus platform. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Mengembalikan string yang mewakili nilai properti. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Mengubah nilai properti menjadi tipe nilai. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Mengubah nilai properti menjadi tipe nilai. |

### Lihat juga

* class [XmpArray](../xmparray)
* ruang nama [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->