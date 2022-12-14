---
title: XmpSchemes
second_title: GroupDocs.Metadata for .NET API-referens
description: Ger tillgång till kända XMPscheman.
type: docs
weight: 3560
url: /sv/net/groupdocs.metadata.standards.xmp/xmpschemes/
---
## XmpSchemes class

Ger tillgång till kända XMP-scheman.

```csharp
public sealed class XmpSchemes
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BasicJobTicket](../../groupdocs.metadata.standards.xmp/xmpschemes/basicjobticket) { get; set; } | Hämtar eller ställer in BasicJobTicket-schemat. |
| [CameraRaw](../../groupdocs.metadata.standards.xmp/xmpschemes/cameraraw) { get; set; } | Hämtar eller ställer in Camera Raw-schemat. |
| [DublinCore](../../groupdocs.metadata.standards.xmp/xmpschemes/dublincore) { get; set; } | Hämtar eller ställer in Dublin Core-schemat. |
| [PagedText](../../groupdocs.metadata.standards.xmp/xmpschemes/pagedtext) { get; set; } | Hämtar eller ställer in PagedText-schemat. |
| [Pdf](../../groupdocs.metadata.standards.xmp/xmpschemes/pdf) { get; set; } | Hämtar eller ställer in PDF-schemat. |
| [Photoshop](../../groupdocs.metadata.standards.xmp/xmpschemes/photoshop) { get; set; } | Hämtar eller ställer in Photoshop-schemat. |
| [XmpBasic](../../groupdocs.metadata.standards.xmp/xmpschemes/xmpbasic) { get; set; } | Hämtar eller ställer in XmpBasic-schemat. |
| [XmpDynamicMedia](../../groupdocs.metadata.standards.xmp/xmpschemes/xmpdynamicmedia) { get; set; } | Hämtar eller ställer in XmpDynamicMedia-schemat. |
| [XmpMediaManagement](../../groupdocs.metadata.standards.xmp/xmpschemes/xmpmediamanagement) { get; set; } | Hämtar eller ställer in XmpMediaManagement-schemat. |
| [XmpRightsManagement](../../groupdocs.metadata.standards.xmp/xmpschemes/xmprightsmanagement) { get; set; } | Hämtar eller ställer in XmpRightsManagement-schemat. |

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
