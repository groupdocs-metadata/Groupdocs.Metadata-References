---
title: Header
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Haalt het AVIheaderpakket op.
type: docs
weight: 10
url: /nl/net/groupdocs.metadata.formats.video/avirootpackage/header/
---
## AviRootPackage.Header property

Haalt het AVI-headerpakket op.

```csharp
public AviHeader Header { get; }
```

### Eigendoms-waarde

Het AVI-headerpakket.

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in AVI-bestanden](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Voorbeelden

Dit codefragment laat zien hoe AVI-headereigenschappen moeten worden gelezen.

```csharp
using (Metadata metadata = new Metadata(Constants.InputAvi))
{
    var root = metadata.GetRootPackage<AviRootPackage>();

    Console.WriteLine(root.Header.AviHeaderFlags);
    Console.WriteLine(root.Header.Height);
    Console.WriteLine(root.Header.Width);
    Console.WriteLine(root.Header.TotalFrames);
    Console.WriteLine(root.Header.InitialFrames);
    Console.WriteLine(root.Header.MaxBytesPerSec);
    Console.WriteLine(root.Header.PaddingGranularity);
    Console.WriteLine(root.Header.Streams);

    // ...
}
```

### Zie ook

* class [AviHeader](../../aviheader)
* class [AviRootPackage](../../avirootpackage)
* naamruimte [GroupDocs.Metadata.Formats.Video](../../avirootpackage)
* montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->