---
title: FileType
second_title: GroupDocs.Metadata for .NET API Reference
description: Gets the file type metadata package.
type: docs
weight: 20
url: /net/groupdocs.metadata.formats.document/pdfrootpackage/filetype/
---
## PdfRootPackage.FileType property

Gets the file type metadata package.

```csharp
public PdfTypePackage FileType { get; }
```

### Property Value

The file type metadata package.

### Examples

This code snippet shows how to detect the PDF version a loaded document and extract some additional file format information.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.Version);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### See Also

* class [PdfTypePackage](../../pdftypepackage)
* class [PdfRootPackage](../../pdfrootpackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
