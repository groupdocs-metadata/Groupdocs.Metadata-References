---
title: PsdPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar metadatapaketet som innehåller information om PSDfilen.
type: docs
weight: 40
url: /sv/net/groupdocs.metadata.formats.image/psdrootpackage/psdpackage/
---
## PsdRootPackage.PsdPackage property

Hämtar metadatapaketet som innehåller information om PSD-filen.

```csharp
public PsdPackage PsdPackage { get; }
```

### Fastighetsvärde

Metadatapaketet som innehåller information om PSD-filen.

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i PSD-bilder](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### Exempel

Detta kodexempel visar hur man läser rubriken på en PSD-fil och extraherar lite information om PSD-lagren.

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithIptc))
{
    var root = metadata.GetRootPackage<PsdRootPackage>();

    Console.WriteLine(root.PsdPackage.ChannelCount);
    Console.WriteLine(root.PsdPackage.ColorMode);
    Console.WriteLine(root.PsdPackage.Compression);
    Console.WriteLine(root.PsdPackage.PhotoshopVersion);

    foreach (var layer in root.PsdPackage.Layers)
    {
        Console.WriteLine(layer.Name);
        Console.WriteLine(layer.BitsPerPixel);
        Console.WriteLine(layer.ChannelCount);
        Console.WriteLine(layer.Flags);
        Console.WriteLine(layer.Height);
        Console.WriteLine(layer.Width);

        // ...
    }

    // ...
}
```

### Se även

* class [PsdPackage](../../psdpackage)
* class [PsdRootPackage](../../psdrootpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Image](../../psdrootpackage)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->