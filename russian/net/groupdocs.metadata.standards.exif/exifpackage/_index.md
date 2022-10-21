---
title: ExifPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет пакет метаданных EXIF формат файла сменного изображения.
type: docs
weight: 2790
url: /ru/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

Представляет пакет метаданных EXIF (формат файла сменного изображения).

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ExifPackage](exifpackage)() | Инициализирует новый экземпляр[`ExifPackage`](../exifpackage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | Получает или задает имя владельца камеры, фотографа или создателя изображения. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | Получает или задает уведомление об авторских правах. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | Получает или задает дату и время создания изображения. В стандарте EXIF это дата и время изменения файла. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | Получает данные EXIF IFD. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | Получает данные GPS. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | Получает или задает строку символов, задающую заголовок изображения. Это может быть комментарий, например "Пикник компании 1988" или тому подобное. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | Получает или задает количество строк данных изображения. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | Получает или задает количество столбцов данных изображения, равное количеству пикселей в строке. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Получает тег TIFF с указанным идентификатором. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | Получает или задает производителя записывающего оборудования. Это производитель ЦСК, сканера, видеодигитайзера или другого оборудования, создавшего изображение. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | Получает или задает название модели или номер модели оборудования. Это название модели или номер ЦСК, сканера, видеодигитайзера или другого оборудования, сгенерировавшего изображение. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | Получает или задает имя и версию программного обеспечения или прошивки камеры или устройства ввода изображения, используемого для создания изображения. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | Получает миниатюру изображения, представленную в виде массива байтов. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Удаляет все теги TIFF, хранящиеся в пакете. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Удаляет свойство с указанным идентификатором. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Добавляет или заменяет указанный тег. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Создает список из пакета. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Учить больше**

* [Работа с метаданными EXIF](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Примеры

В этом примере кода показано, как обновить общие свойства EXIF.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // Устанавливаем пакет EXIF, если он отсутствует
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Смотрите также

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* пространство имен [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
