---
title: FileType
second_title: GroupDocs.Metadata for .NET API Reference
description: Gets the file type metadata package.
type: docs
weight: 30
url: /net/groupdocs.metadata.formats.document/wordprocessingrootpackage/filetype/
---
## WordProcessingRootPackage.FileType property

Gets the file type metadata package.

```csharp
public WordProcessingTypePackage FileType { get; }
```

### Property Value

The file type metadata package.

### Examples

This example shows how to detect the exact type of a loaded document and extract some additional file format information.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.WordProcessingFormat);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### See Also

* class [WordProcessingTypePackage](../../wordprocessingtypepackage)
* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
