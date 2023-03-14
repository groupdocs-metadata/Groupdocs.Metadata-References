---
title: XmpPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar eller ställer in XMPmetadatapaketet.
type: docs
weight: 10
url: /sv/net/groupdocs.metadata.standards.xmp/ixmp/xmppackage/
---
## IXmp.XmpPackage property

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

Detta kodexempel visar hur man tar bort XMP-metadata från en fil.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        root.XmpPackage = null;
        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Se även

* class [XmpPacketWrapper](../../xmppacketwrapper)
* interface [IXmp](../../ixmp)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../ixmp)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->