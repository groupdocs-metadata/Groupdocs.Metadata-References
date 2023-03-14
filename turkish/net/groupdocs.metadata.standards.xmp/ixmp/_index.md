---
title: IXmp
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: XMP meta verileriyle çalışması amaçlanan temel işlemleri tanımlar.
type: docs
weight: 3040
url: /tr/net/groupdocs.metadata.standards.xmp/ixmp/
---
## IXmp interface

XMP meta verileriyle çalışması amaçlanan temel işlemleri tanımlar.

```csharp
public interface IXmp
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [XmpPackage](../../groupdocs.metadata.standards.xmp/ixmp/xmppackage) { get; set; } | XMP meta veri paketini alır veya ayarlar. |

### Notlar

**Daha fazla bilgi edin**

* [XMP meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Örnekler

Bu örnek, XMP meta verilerinin bir dosyadan nasıl çıkarılacağını gösterir.

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

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->