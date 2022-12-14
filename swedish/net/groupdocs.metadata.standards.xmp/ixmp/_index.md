---
title: IXmp
second_title: GroupDocs.Metadata for .NET API-referens
description: Definierar basoperationer avsedda att fungera med XMPmetadata.
type: docs
weight: 3040
url: /sv/net/groupdocs.metadata.standards.xmp/ixmp/
---
## IXmp interface

Definierar basoperationer avsedda att fungera med XMP-metadata.

```csharp
public interface IXmp
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [XmpPackage](../../groupdocs.metadata.standards.xmp/ixmp/xmppackage) { get; set; } | Hämtar eller ställer in XMP-metadatapaketet. |

### Anmärkningar

**Läs mer**

* [Arbeta med XMP-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Exempel

Det här exemplet visar hur man extraherar XMP-metadata från en fil.

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

### Se även

* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
