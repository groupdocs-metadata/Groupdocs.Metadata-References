---
title: FileType
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Получает пакет метаданных типа файла.
type: docs
weight: 20
url: /ru/net/groupdocs.metadata.formats.document/pdfrootpackage/filetype/
---
## PdfRootPackage.FileType property

Получает пакет метаданных типа файла.

```csharp
public PdfTypePackage FileType { get; }
```

### Стоимость имущества

Пакет метаданных типа файла.

### Примеры

Этот фрагмент кода показывает, как определить PDF-версию загруженного документа и извлечь дополнительную информацию о формате файла.

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

### Смотрите также

* class [PdfTypePackage](../../pdftypepackage)
* class [PdfRootPackage](../../pdfrootpackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../pdfrootpackage)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->