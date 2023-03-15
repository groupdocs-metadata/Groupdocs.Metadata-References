---
title: DublinCorePackage
second_title: GroupDocs.Metadata untuk Referensi .NET API
description: Mendapatkan paket metadata Dublin Core yang diekstrak dari dokumen.
type: docs
weight: 20
url: /id/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage/
---
## WordProcessingRootPackage.DublinCorePackage property

Mendapatkan paket metadata Dublin Core yang diekstrak dari dokumen.

```csharp
public DublinCorePackage DublinCorePackage { get; }
```

### Nilai properti

Paket metadata Dublin Core diekstraksi dari dokumen.

### Perkataan

**Belajarlah lagi**

* [Bekerja dengan metadata dalam dokumen WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Contoh

Contoh ini menunjukkan cara mengekstrak metadata Dublin Core dari dokumen WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    if (root.DublinCorePackage != null)
    {
        Console.WriteLine(root.DublinCorePackage.Format);
        Console.WriteLine(root.DublinCorePackage.Contributor);
        Console.WriteLine(root.DublinCorePackage.Coverage);
        Console.WriteLine(root.DublinCorePackage.Creator);
        Console.WriteLine(root.DublinCorePackage.Source);
        Console.WriteLine(root.DublinCorePackage.Description);

        // ...
    }
}
```

### Lihat juga

* class [DublinCorePackage](../../../groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* ruang nama [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* perakitan [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->