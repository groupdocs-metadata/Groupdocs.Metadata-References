---
title: DublinCorePackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar Dublin Coremetadatapaketet extraherat från eboken.
type: docs
weight: 10
url: /sv/net/groupdocs.metadata.formats.ebook/epubrootpackage/dublincorepackage/
---
## EpubRootPackage.DublinCorePackage property

Hämtar Dublin Core-metadatapaketet extraherat från e-boken.

```csharp
public DublinCorePackage DublinCorePackage { get; }
```

### Fastighetsvärde

Dublin Core-metadatapaketet extraherat från e-boken.

### Anmärkningar

**Läs mer**

* [Arbeta med metadata i EPUB E-böcker](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+EPUB+E-Books)

### Exempel

Det här exemplet visar hur du extraherar Dublin Core-metadata från en EPUB-fil.

```csharp
using (Metadata metadata = new Metadata(Constants.InputEpub))
{
    var root = metadata.GetRootPackage<EpubRootPackage>();

    if (root.DublinCorePackage != null)
    {
        Console.WriteLine(root.DublinCorePackage.Rights);
        Console.WriteLine(root.DublinCorePackage.Publisher);
        Console.WriteLine(root.DublinCorePackage.Title);
        Console.WriteLine(root.DublinCorePackage.Creator);
        Console.WriteLine(root.DublinCorePackage.Language);
        Console.WriteLine(root.DublinCorePackage.Date);

        // ...
    }
}
```

### Se även

* class [DublinCorePackage](../../../groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [EpubRootPackage](../../epubrootpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Ebook](../../epubrootpackage)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->