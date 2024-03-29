---
title: EpubPackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Ottiene il pacchetto di metadati EPUB.
type: docs
weight: 20
url: /it/net/groupdocs.metadata.formats.ebook/epubrootpackage/epubpackage/
---
## EpubRootPackage.EpubPackage property

Ottiene il pacchetto di metadati EPUB.

```csharp
public EpubPackage EpubPackage { get; }
```

### Valore della proprietà

Il pacchetto di metadati EPUB.

### Osservazioni

**Saperne di più**

* [Lavorare con i metadati negli e-book EPUB](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+EPUB+E-Books)

### Esempi

Questo esempio di codice mostra come leggere le proprietà dei metadati specifici del formato EPUB.

```csharp
using (Metadata metadata = new Metadata(Constants.InputEpub))
{
    var root = metadata.GetRootPackage<EpubRootPackage>();

    Console.WriteLine(root.EpubPackage.Version);
    Console.WriteLine(root.EpubPackage.UniqueIdentifier);
    Console.WriteLine(root.EpubPackage.ImageCover != null ? root.EpubPackage.ImageCover.Length : 0);
}
```

### Guarda anche

* class [EpubPackage](../../epubpackage)
* class [EpubRootPackage](../../epubrootpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Ebook](../../epubrootpackage)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
