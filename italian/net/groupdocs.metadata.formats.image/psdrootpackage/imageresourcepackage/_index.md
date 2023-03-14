---
title: ImageResourcePackage
second_title: Riferimento API GroupDocs.Metadata per .NET
description: Ottiene il pacchetto di metadati di Photoshop Image Resource. I blocchi di risorse immagine sono lunità di base del formato di file nativo di Photoshop.
type: docs
weight: 20
url: /it/net/groupdocs.metadata.formats.image/psdrootpackage/imageresourcepackage/
---
## PsdRootPackage.ImageResourcePackage property

Ottiene il pacchetto di metadati di Photoshop Image Resource. I blocchi di risorse immagine sono l'unità di base del formato di file nativo di Photoshop.

```csharp
public ImageResourcePackage ImageResourcePackage { get; }
```

### Valore della proprietà

Il pacchetto di metadati della risorsa immagine.

### Osservazioni

**Scopri di più**

* [Lavorare con i metadati nelle immagini PSD](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Esempi

L'esempio di codice riportato di seguito mostra come estrarre blocchi di risorse immagine (elementi costitutivi del formato file Photoshop) da un'immagine PSD.

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithIrb))
{
    var root = metadata.GetRootPackage<PsdRootPackage>();

    if (root.ImageResourcePackage != null)
    {
        foreach (var block in root.ImageResourcePackage.ToList())
        {
            Console.WriteLine(block.Signature);
            Console.WriteLine(block.ID);
            Console.WriteLine(block.Name);
            Console.WriteLine(block.Data);
        }
    }
}
```

### Guarda anche

* class [ImageResourcePackage](../../imageresourcepackage)
* class [PsdRootPackage](../../psdrootpackage)
* spazio dei nomi [GroupDocs.Metadata.Formats.Image](../../psdrootpackage)
* assemblea [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->