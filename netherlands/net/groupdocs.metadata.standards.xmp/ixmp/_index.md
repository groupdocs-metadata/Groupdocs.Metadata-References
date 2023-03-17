---
title: IXmp
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Definieert basisbewerkingen die bedoeld zijn om te werken met XMPmetadata.
type: docs
weight: 3040
url: /nl/net/groupdocs.metadata.standards.xmp/ixmp/
---
## IXmp interface

Definieert basisbewerkingen die bedoeld zijn om te werken met XMP-metadata.

```csharp
public interface IXmp
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [XmpPackage](../../groupdocs.metadata.standards.xmp/ixmp/xmppackage) { get; set; } | Haalt het XMP-metadatapakket op of stelt het in. |

### Opmerkingen

**Kom meer te weten**

* [Werken met XMP-metagegevens](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Voorbeelden

Dit voorbeeld laat zien hoe XMP-metagegevens uit een bestand kunnen worden geëxtraheerd.

```csharp
using (Metadata metadata = new Metadata(Constants.PngWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null && root.XmpPackage != null)
    {
        if (root.XmpPackage.Schemes.XmpBasic != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreatorTool);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreateDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.ModifyDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Label);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Nickname);

            // ...
        }

        if (root.XmpPackage.Schemes.DublinCore != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Format);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Coverage);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Identifier);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Source);

            // ...
        }

        if (root.XmpPackage.Schemes.Photoshop != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.ColorMode);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.IccProfile);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.Country);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.City);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.DateCreated);

            // ... 
        }

        // ...
    }
}
```

### Zie ook

* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->