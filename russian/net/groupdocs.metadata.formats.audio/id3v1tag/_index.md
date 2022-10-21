---
title: ID3V1Tag
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет тег ID3v1. Дополнительную информацию см.https//en.wikipedia.org/wiki/ID3ID3v1https//en.wikipedia.org/wiki/ID3ID3v1 .
type: docs
weight: 410
url: /ru/net/groupdocs.metadata.formats.audio/id3v1tag/
---
## ID3V1Tag class

Представляет тег ID3v1. Дополнительную информацию см.[https://en.wikipedia.org/wiki/ID3#ID3v1](https://en.wikipedia.org/wiki/ID3#ID3v1) .

```csharp
public sealed class ID3V1Tag : ID3Tag
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ID3V1Tag](id3v1tag)() | Инициализирует новый экземпляр[`ID3V1Tag`](../id3v1tag) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v1tag/album) { get; set; } | Получает или задает альбом. Максимальная длина 30 символов. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v1tag/artist) { get; set; } | Получает или устанавливает исполнителя. Максимальная длина 30 символов. |
| [Comment](../../groupdocs.metadata.formats.audio/id3v1tag/comment) { get; set; } | Получает или задает комментарий. Максимальная длина 30 символов. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [GenreValue](../../groupdocs.metadata.formats.audio/id3v1tag/genrevalue) { get; } | Получает или задает идентификатор жанра. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Title](../../groupdocs.metadata.formats.audio/id3v1tag/title) { get; set; } | Получает или устанавливает заголовок. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v1tag/tracknumber) { get; set; } | Получает или задает номер дорожки. Представлено только в теге ID3v1.1. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v1tag/version) { get; } | Получает версию ID3. Это может быть ID3 или ID3v1.1 |
| [Year](../../groupdocs.metadata.formats.audio/id3v1tag/year) { get; set; } | Получает или устанавливает год. Максимальная длина 4 символа. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

Тег ID3(v1) — это небольшой фрагмент дополнительных данных в конце MP3. Дополнительную информацию см.[http://id3.org/ID3v1](http://id3.org/ID3v1) .

**Учить больше**

* [Обработка тега ID3v1](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v1+tag)

### Примеры

В этом примере кода показано, как читать тег ID3v1 в файле MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 != null)
    {
        Console.WriteLine(root.ID3V1.Album);
        Console.WriteLine(root.ID3V1.Artist);
        Console.WriteLine(root.ID3V1.Title);
        Console.WriteLine(root.ID3V1.Version);
        Console.WriteLine(root.ID3V1.Comment);

        // ...
    }
}
```

### Смотрите также

* class [ID3Tag](../id3tag)
* пространство имен [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
