---
title: Metadata
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Menginisialisasi instance baru dariMetadatagroupdocs.metadata/metadata kelas.
type: docs
weight: 10
url: /id/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Menginisialisasi instance baru dari[`Metadata`](../../metadata) kelas.

```csharp
public Metadata(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Sebuah string yang berisi nama lengkap dari file yang akan dibuat a[`Metadata`](../../metadata) contoh. |

### Perkataan

**Belajarlah lagi**

* [Muat dari disk lokal](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Muat dari aliran](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Muat file dengan format tertentu](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Muat dokumen yang dilindungi kata sandi](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Contoh

Contoh ini menunjukkan cara memuat file dari disk lokal.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Ekstrak, edit, atau hapus metadata di sini
}
```

### Lihat juga

* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Menginisialisasi instance baru dari[`Metadata`](../../metadata) kelas.

```csharp
public Metadata(Stream document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran yang berisi dokumen untuk dimuat. |

### Perkataan

**Belajarlah lagi**

* [Muat dari disk lokal](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Muat dari aliran](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Muat file dengan format tertentu](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Muat dokumen yang dilindungi kata sandi](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Contoh

Contoh ini menunjukkan cara memuat file dari aliran.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Ekstrak, edit, atau hapus metadata di sini
}
```

### Lihat juga

* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Menginisialisasi instance baru dari[`Metadata`](../../metadata) kelas.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Sebuah string yang berisi nama lengkap dari file yang akan dibuat a[`Metadata`](../../metadata) contoh. |
| loadOptions | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |

### Perkataan

**Belajarlah lagi**

* [Muat dari disk lokal](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Muat dari aliran](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Muat file dengan format tertentu](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Muat dokumen yang dilindungi kata sandi](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Contoh

Contoh ini menunjukkan cara memuat dokumen yang dilindungi kata sandi.

```csharp
// Tentukan kata sandi
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Ekstrak, edit, atau hapus metadata di sini
}
```

### Lihat juga

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Menginisialisasi instance baru dari[`Metadata`](../../metadata) kelas.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran yang berisi dokumen untuk dimuat. |
| loadOptions | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |

### Perkataan

**Belajarlah lagi**

* [Muat dari disk lokal](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Muat dari aliran](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Muat file dengan format tertentu](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Muat dokumen yang dilindungi kata sandi](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Lihat juga

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
