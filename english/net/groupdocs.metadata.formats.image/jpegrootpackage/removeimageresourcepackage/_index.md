---
title: RemoveImageResourcePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Removes Photoshop Image Resource metadata package.
type: docs
weight: 70
url: /net/groupdocs.metadata.formats.image/jpegrootpackage/removeimageresourcepackage/
---
## JpegRootPackage.RemoveImageResourcePackage method

Removes Photoshop Image Resource metadata package.

```csharp
public void RemoveImageResourcePackage()
```

### Remarks

**Learn more**

* [Working with metadata in JPEG images](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### Examples

This code snippet demonstrates how to remove Photoshop metadata from a JPEG image.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIrb))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();
    root.RemoveImageResourcePackage();

    metadata.Save(Constants.OutputJpeg);
}
```

### See Also

* class [JpegRootPackage](../../jpegrootpackage)
* namespace [GroupDocs.Metadata.Formats.Image](../../../groupdocs.metadata.formats.image)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
