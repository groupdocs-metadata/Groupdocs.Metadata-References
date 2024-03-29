---
title: Set
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Menambahkan atau mengganti tag yang ditentukan.
type: docs
weight: 40
url: /id/net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/set/
---
## ExifDictionaryBasePackage.Set method

Menambahkan atau mengganti tag yang ditentukan.

```csharp
public void Set(TiffTag tag)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| tag | TiffTag | Tag untuk mengatur. |

### Contoh

Contoh kode ini menunjukkan cara menambahkan tag khusus ke paket EXIF.

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Tetapkan paket EXIF jika tidak ada
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        // Tambahkan properti yang diketahui
        root.ExifPackage.Set(new TiffAsciiTag(TiffTagID.Artist, "test artist"));

        // Tambahkan properti yang sepenuhnya disesuaikan (yang tidak dijelaskan dalam spesifikasi EXIF).
        // Harap perhatikan bahwa ID yang dipilih mungkin bersinggungan dengan ID yang digunakan oleh beberapa alat pihak ketiga.
        root.ExifPackage.Set(new TiffAsciiTag((TiffTagID)65523, "custom"));

        metadata.Save(Constants.OutputTiff);
    }
}
```

### Lihat juga

* class [TiffTag](../../../groupdocs.metadata.formats.image/tifftag)
* class [ExifDictionaryBasePackage](../../exifdictionarybasepackage)
* ruang nama [GroupDocs.Metadata.Standards.Exif](../../exifdictionarybasepackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
