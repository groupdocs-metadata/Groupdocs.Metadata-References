---
title: DublinCorePackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Ottiene il pacchetto di metadati Dublin Core estratto dal documento.
type: docs
weight: 20
url: /it/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/dublincorepackage/
---
## WordProcessingRootPackage.DublinCorePackage property

Ottiene il pacchetto di metadati Dublin Core estratto dal documento.

```csharp
public DublinCorePackage DublinCorePackage { get; }
```

### Valore della proprietà

Il pacchetto di metadati Dublin Core estratto dal documento.

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati nei documenti di WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Esempi

Questo esempio mostra come estrarre i metadati Dublin Core da un documento WordProcessing.

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

        //...
    }
}
```

### Guarda anche

* class [DublinCorePackage](../../../groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
