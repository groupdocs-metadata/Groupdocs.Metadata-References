---
title: License
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mewakili lisensi GroupDocs.Metadata. Kelas lisensi harus diterapkan sekali per AppDomain.
type: docs
weight: 2650
url: /id/net/groupdocs.metadata/license/
---
## License class

Mewakili lisensi GroupDocs.Metadata. Kelas lisensi harus diterapkan sekali per AppDomain.

```csharp
public sealed class License
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [License](license)() | Menginisialisasi instance baru dari[`License`](../license) kelas. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [SetLicense](../../groupdocs.metadata/license/setlicense#setlicense)(Stream) | Lisensi komponen. |
| [SetLicense](../../groupdocs.metadata/license/setlicense#setlicense_1)(string) | Lisensi komponen. |

### Contoh

Contoh ini menunjukkan cara menyiapkan lisensi.

```csharp
// menginisialisasi kelas Lisensi
License license = new License();

// atur path ke file .lic
license.SetLicense(@"C:\\GroupDocs.Metadata.lic");
```

### Lihat juga

* ruang nama [GroupDocs.Metadata](../../groupdocs.metadata)
* perakitan [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->