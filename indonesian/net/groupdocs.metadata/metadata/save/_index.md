---
title: Save
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Menyimpan semua perubahan yang dilakukan pada dokumen yang dimuat.
type: docs
weight: 110
url: /id/net/groupdocs.metadata/metadata/save/
---
## Save() {#save}

Menyimpan semua perubahan yang dilakukan pada dokumen yang dimuat.

```csharp
public void Save()
```

### Perkataan

**Belajarlah lagi**

* [Simpan file yang dimodifikasi ke sumber aslinya](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source)
* [Simpan file yang dimodifikasi ke lokasi yang ditentukan](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location)
* [Simpan file yang dimodifikasi ke aliran](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream)

### Contoh

Contoh ini menunjukkan cara menyimpan konten yang dimodifikasi ke sumber yang mendasarinya.

```csharp
using (Metadata metadata = new Metadata(Constants.OutputPpt))
{
    // Edit atau hapus metadata di sini

    // Menyimpan dokumen ke sumber yang mendasarinya (aliran atau file)
    metadata.Save();
}
```

### Lihat juga

* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

---

## Save(Stream) {#save_1}

Menyimpan konten dokumen ke dalam aliran.

```csharp
public void Save(Stream document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran keluaran untuk dokumen. |

### Perkataan

**Belajarlah lagi**

* [Simpan file yang dimodifikasi ke sumber aslinya](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source)
* [Simpan file yang dimodifikasi ke lokasi yang ditentukan](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location)
* [Simpan file yang dimodifikasi ke aliran](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream)

### Contoh

Contoh ini menunjukkan cara menyimpan dokumen ke aliran yang ditentukan.

```csharp
using (MemoryStream stream = new MemoryStream())
{
    using (Metadata metadata = new Metadata(Constants.InputPng))
    {
        // Edit atau hapus metadata di sini

        metadata.Save(stream);
    }
}
```

### Lihat juga

* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

---

## Save(string) {#save_2}

Menyimpan konten dokumen ke file yang ditentukan.

```csharp
public void Save(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Nama lengkap file keluaran. |

### Perkataan

**Belajarlah lagi**

* [Simpan file yang dimodifikasi ke sumber aslinya](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+the+original+source)
* [Simpan file yang dimodifikasi ke lokasi yang ditentukan](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+specified+location)
* [Simpan file yang dimodifikasi ke aliran](https://docs.groupdocs.com/display/metadatanet/Save+a+modified+file+to+a+stream)

### Contoh

Contoh ini menunjukkan cara menyimpan dokumen ke lokasi yang ditentukan.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    // Edit atau hapus metadata di sini

    metadata.Save(Constants.OutputJpeg);
}
```

### Lihat juga

* class [Metadata](../../metadata)
* ruang nama [GroupDocs.Metadata](../../metadata)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
