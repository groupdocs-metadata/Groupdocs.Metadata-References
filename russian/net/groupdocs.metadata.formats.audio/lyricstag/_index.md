---
title: LyricsTag
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет метаданные Lyrics3 v2.00. Дополнительную информацию см.http//id3.org/Лирикс3v2 .
type: docs
weight: 570
url: /ru/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Представляет метаданные Lyrics3 v2.00. Дополнительную информацию см.http://id3.org/Лирикс3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LyricsTag](lyricstag)() | Инициализирует новый экземпляр[`LyricsTag`](../lyricstag) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Получает или задает дополнительную информацию. Это значение представлено полем INF. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Получает или задает название альбома. Это значение представлено полем EAL. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Получает или задает имя исполнителя. Это значение представлено полем EAR. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Получает или задает автора. Это значение представлено полем AUT. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Получает или устанавливает текст. Это значение представлено полем LYR. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Получает или задает название дорожки. Это значение представлено полем ETT. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Получает значение поля с указанным идентификатором. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Удаляет поле с указанным id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Добавляет или заменяет указанное поле Lyrics3. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Создает список из пакета. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

Lyrics3 v2.00 использует поля для представления информации. Данные в поле могут состоять из символов ASCII в диапазоне от 01 до 254 в соответствии со стандартом. Поскольку карта символов ASCII определяется только от 00 до 128, ISO-8859- 1 можно предположить. Числовые поля имеют длину 5 или 6 символов, в зависимости от местоположения, и дополняются нулями.

**Учить больше**

* [Обработка тега Lyrics](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Примеры

В этом примере кода показано, как прочитать тег Lyrics из файла MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Кроме того, вы можете просмотреть полный список полей тега
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Смотрите также

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* пространство имен [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
