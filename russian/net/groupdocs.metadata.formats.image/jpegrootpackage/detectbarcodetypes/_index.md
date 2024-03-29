---
title: DetectBarcodeTypes
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Извлекает типы штрихкодов представленных на изображении.
type: docs
weight: 60
url: /ru/net/groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes/
---
## JpegRootPackage.DetectBarcodeTypes method

Извлекает типы штрих-кодов, представленных на изображении.

```csharp
public string[] DetectBarcodeTypes()
```

### Возвращаемое значение

Массив типов штрихкодов.

### Примечания

**Узнать больше**

* [Работа с метаданными в изображениях JPEG](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### Примеры

Этот фрагмент кода демонстрирует, как обнаруживать штрих-коды в изображении JPEG.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithBarcodes))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    var barcodeTypes = root.DetectBarcodeTypes();

    foreach (var barcodeType in barcodeTypes)
    {
        Console.WriteLine(barcodeType);
    }
}
```

### Смотрите также

* class [JpegRootPackage](../../jpegrootpackage)
* пространство имен [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
