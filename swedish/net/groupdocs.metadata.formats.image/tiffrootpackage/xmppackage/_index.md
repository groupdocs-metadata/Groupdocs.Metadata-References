---
title: XmpPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar eller ställer in XMPmetadatapaketet.
type: docs
weight: 30
url: /sv/net/groupdocs.metadata.formats.image/tiffrootpackage/xmppackage/
---
## TiffRootPackage.XmpPackage property

Hämtar eller ställer in XMP-metadatapaketet.

```csharp
public XmpPacketWrapper XmpPackage { get; set; }
```

### Fastighetsvärde

XMP-metadatapaketet.

### Anmärkningar

**Läs mer**

* [Arbeta med XMP-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Exempel

Det här exemplet visar hur man extraherar XMP-metadata från en fil.

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithXmp))
{
    var root = metadata.GetRootPackage<TiffRootPackage>();
    if (root.XmpPackage != null)
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

* class [XmpPacketWrapper](../../../groupdocs.metadata.standards.xmp/xmppacketwrapper)
* class [TiffRootPackage](../../tiffrootpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Image](../../tiffrootpackage)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->