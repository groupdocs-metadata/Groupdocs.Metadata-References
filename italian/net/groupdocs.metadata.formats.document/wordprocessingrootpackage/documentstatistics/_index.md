---
title: DocumentStatistics
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Ottiene il pacchetto delle statistiche del documento.
type: docs
weight: 10
url: /it/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/documentstatistics/
---
## WordProcessingRootPackage.DocumentStatistics property

Ottiene il pacchetto delle statistiche del documento.

```csharp
public DocumentStatistics DocumentStatistics { get; }
```

### Valore della proprietà

Il pacchetto di statistiche del documento.

### Osservazioni

**Scopri di più**

* [Lavorare con i metadati nei documenti di WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Esempi

Questo esempio di codice mostra come ottenere semplici statistiche di testo per un documento WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    Console.WriteLine(root.DocumentStatistics.CharacterCount);
    Console.WriteLine(root.DocumentStatistics.PageCount);
    Console.WriteLine(root.DocumentStatistics.WordCount);
}
```

### Guarda anche

* class [DocumentStatistics](../../documentstatistics)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->