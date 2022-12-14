---
title: FileType
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Ottiene il pacchetto di metadati del tipo di file.
type: docs
weight: 20
url: /it/net/groupdocs.metadata.formats.document/pdfrootpackage/filetype/
---
## PdfRootPackage.FileType property

Ottiene il pacchetto di metadati del tipo di file.

```csharp
public PdfTypePackage FileType { get; }
```

### Valore della proprietà

Il pacchetto di metadati del tipo di file.

### Esempi

Questo frammento di codice mostra come rilevare la versione PDF di un documento caricato ed estrarre alcune informazioni aggiuntive sul formato del file.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.Version);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### Guarda anche

* class [PdfTypePackage](../../pdftypepackage)
* class [PdfRootPackage](../../pdfrootpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../pdfrootpackage)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
