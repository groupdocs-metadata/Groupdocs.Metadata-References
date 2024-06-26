---
title: IptcPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Gets or sets the IPTC metadata package associated with the file.
type: docs
weight: 10
url: /net/groupdocs.metadata.standards.iptc/iiptc/iptcpackage/
---
## IIptc.IptcPackage property

Gets or sets the IPTC metadata package associated with the file.

```csharp
public IptcRecordSet IptcPackage { get; set; }
```

### Property Value

The IPTC metadata package associated with the file.

### Remarks

**Learn more**

* [Working with IPTC IIM metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Examples

This code sample shows how to remove IPTC metadata from a file.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIptc))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null)
    {
        root.IptcPackage = null;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### See Also

* class [IptcRecordSet](../../iptcrecordset)
* interface [IIptc](../../iiptc)
* namespace [GroupDocs.Metadata.Standards.Iptc](../../../groupdocs.metadata.standards.iptc)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
