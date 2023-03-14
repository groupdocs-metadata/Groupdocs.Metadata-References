---
title: FileType
second_title: GroupDocs.Metadata for .NET API-referens
description: Hämtar filtypens metadatapaket.
type: docs
weight: 20
url: /sv/net/groupdocs.metadata.formats.document/presentationrootpackage/filetype/
---
## PresentationRootPackage.FileType property

Hämtar filtypens metadatapaket.

```csharp
public PresentationTypePackage FileType { get; }
```

### Fastighetsvärde

Filtypens metadatapaket.

### Exempel

Det här exemplet visar hur man identifierar den exakta typen av en presentation och extraherar ytterligare information om filformat.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.PresentationFormat);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### Se även

* class [PresentationTypePackage](../../presentationtypepackage)
* class [PresentationRootPackage](../../presentationrootpackage)
* namnutrymme [GroupDocs.Metadata.Formats.Document](../../presentationrootpackage)
* hopsättning [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->