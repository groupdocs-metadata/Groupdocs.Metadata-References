---
title: FileType
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Получает пакет метаданных типа файла.
type: docs
weight: 20
url: /ru/net/groupdocs.metadata.formats.document/presentationrootpackage/filetype/
---
## PresentationRootPackage.FileType property

Получает пакет метаданных типа файла.

```csharp
public PresentationTypePackage FileType { get; }
```

### Стоимость имущества

Пакет метаданных типа файла.

### Примеры

В этом примере показано, как определить точный тип презентации и извлечь дополнительную информацию о формате файла.

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

### Смотрите также

* class [PresentationTypePackage](../../presentationtypepackage)
* class [PresentationRootPackage](../../presentationrootpackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../presentationrootpackage)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
