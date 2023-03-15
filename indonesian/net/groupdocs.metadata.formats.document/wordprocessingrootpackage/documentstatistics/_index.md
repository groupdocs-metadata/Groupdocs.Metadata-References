---
title: DocumentStatistics
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendapatkan paket statistik dokumen.
type: docs
weight: 10
url: /id/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/documentstatistics/
---
## WordProcessingRootPackage.DocumentStatistics property

Mendapatkan paket statistik dokumen.

```csharp
public DocumentStatistics DocumentStatistics { get; }
```

### Nilai properti

Paket statistik dokumen.

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata dalam dokumen WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Contoh

Contoh kode ini menunjukkan cara mendapatkan statistik teks sederhana untuk dokumen WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    Console.WriteLine(root.DocumentStatistics.CharacterCount);
    Console.WriteLine(root.DocumentStatistics.PageCount);
    Console.WriteLine(root.DocumentStatistics.WordCount);
}
```

### Lihat juga

* class [DocumentStatistics](../../documentstatistics)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->