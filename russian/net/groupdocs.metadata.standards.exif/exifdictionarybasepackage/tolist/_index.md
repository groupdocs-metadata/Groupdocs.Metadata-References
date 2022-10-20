---
title: ToList
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Создает список из пакета.
type: docs
weight: 50
url: /ru/net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist/
---
## ExifDictionaryBasePackage.ToList method

Создает список из пакета.

```csharp
public IReadOnlyList<TiffTag> ToList()
```

### Возвращаемое значение

Список, содержащий все теги TIFF из пакета.

### Примеры

В этом примере показано, как прочитать все теги EXIF, извлеченные из файла.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null && root.ExifPackage != null)
    {
        const string pattern = "{0} = {1}";

        foreach (TiffTag tag in root.ExifPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }

        foreach (TiffTag tag in root.ExifPackage.ExifIfdPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }

        foreach (TiffTag tag in root.ExifPackage.GpsPackage.ToList())
        {
            Console.WriteLine(pattern, tag.TagID, tag.Value);
        }
    }
}
```

### Смотрите также

* interface [IReadOnlyList&lt;T&gt;](../../../groupdocs.metadata.common/ireadonlylist-1)
* class [TiffTag](../../../groupdocs.metadata.formats.image/tifftag)
* class [ExifDictionaryBasePackage](../../exifdictionarybasepackage)
* пространство имен [GroupDocs.Metadata.Standards.Exif](../../exifdictionarybasepackage)
* сборка [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->