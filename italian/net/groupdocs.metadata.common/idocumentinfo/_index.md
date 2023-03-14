---
title: IDocumentInfo
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Fornisce informazioni comuni su un documento caricato.
type: docs
weight: 90
url: /it/net/groupdocs.metadata.common/idocumentinfo/
---
## IDocumentInfo interface

Fornisce informazioni comuni su un documento caricato.

```csharp
public interface IDocumentInfo
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FileType](../../groupdocs.metadata.common/idocumentinfo/filetype) { get; } | Ottiene il tipo di file del documento caricato. |
| [IsEncrypted](../../groupdocs.metadata.common/idocumentinfo/isencrypted) { get; } | Ottiene un valore che indica se il documento è crittografato e richiede una password per essere aperto. |
| [PageCount](../../groupdocs.metadata.common/idocumentinfo/pagecount) { get; } | Ottiene il numero di pagine (diapositive, fogli di lavoro, ecc.) nel documento caricato. |
| [Pages](../../groupdocs.metadata.common/idocumentinfo/pages) { get; } | Ottiene una raccolta di oggetti che rappresentano informazioni comuni sulle pagine del documento (diapositive, fogli di lavoro, ecc.). |
| [Size](../../groupdocs.metadata.common/idocumentinfo/size) { get; } | Ottiene la dimensione del documento caricato in byte. |

### Osservazioni

**Scopri di più**

* [Ottieni informazioni sul documento](https://docs.groupdocs.com/display/metadatanet/Get+document+info)

### Esempi

Questo esempio mostra come estrarre informazioni sul formato di base da un file.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    if (metadata.FileFormat != FileFormat.Unknown)
    {
        IDocumentInfo info = metadata.GetDocumentInfo();

        Console.WriteLine("File format: {0}", info.FileType.FileFormat);
        Console.WriteLine("File extension: {0}", info.FileType.Extension);
        Console.WriteLine("MIME Type: {0}", info.FileType.MimeType);
        Console.WriteLine("Number of pages: {0}", info.PageCount);
        Console.WriteLine("Document size: {0} bytes", info.Size);
        Console.WriteLine("Is document encrypted: {0}", info.IsEncrypted);
    }
}
```

### Guarda anche

* spazio dei nomi [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* assemblea [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->