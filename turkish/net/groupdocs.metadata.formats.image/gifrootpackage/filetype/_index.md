---
title: FileType
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Meta veri paketi dosya türünü alır.
type: docs
weight: 10
url: /tr/net/groupdocs.metadata.formats.image/gifrootpackage/filetype/
---
## GifRootPackage.FileType property

Meta veri paketi dosya türünü alır.

```csharp
public GifImageTypePackage FileType { get; }
```

### Mülk değeri

Dosya türü meta veri paketi.

### Örnekler

Bu kod parçacığı, yüklü bir GIF görüntüsünün sürümünün nasıl algılanacağını ve bazı ek dosya biçimi bilgilerinin nasıl çıkarılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputGif))
{
    var root = metadata.GetRootPackage<GifRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.Version);
    Console.WriteLine(root.FileType.ByteOrder);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
    Console.WriteLine(root.FileType.Width);
    Console.WriteLine(root.FileType.Height);
}
```

### Ayrıca bakınız

* class [GifImageTypePackage](../../gifimagetypepackage)
* class [GifRootPackage](../../gifrootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Image](../../gifrootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
