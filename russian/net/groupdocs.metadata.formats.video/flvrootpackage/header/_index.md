---
title: Header
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Получает пакет заголовков FLV.
type: docs
weight: 10
url: /ru/net/groupdocs.metadata.formats.video/flvrootpackage/header/
---
## FlvRootPackage.Header property

Получает пакет заголовков FLV.

```csharp
public FlvHeader Header { get; }
```

### Стоимость имущества

Пакет заголовков FLV.

### Примечания

**Учить больше**

* [Работа с метаданными в файлах FLV](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+FLV+files)

### Примеры

В этом примере показано, как читать свойства заголовка FLV.

```csharp
using (Metadata metadata = new Metadata(Constants.InputFlv))
{
    var root = metadata.GetRootPackage<FlvRootPackage>();

    Console.WriteLine(root.Header.Version);
    Console.WriteLine(root.Header.HasAudioTags);
    Console.WriteLine(root.Header.HasVideoTags);
    Console.WriteLine(root.Header.TypeFlags);
}
```

### Смотрите также

* class [FlvHeader](../../flvheader)
* class [FlvRootPackage](../../flvrootpackage)
* пространство имен [GroupDocs.Metadata.Formats.Video](../../flvrootpackage)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->