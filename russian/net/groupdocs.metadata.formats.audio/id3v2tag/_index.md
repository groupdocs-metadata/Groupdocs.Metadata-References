---
title: ID3V2Tag
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет тег ID3v2. Дополнительную информацию см.https//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /ru/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

Представляет тег ID3v2. Дополнительную информацию см.[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | Инициализирует новый экземпляр[`ID3V2Tag`](../id3v2tag) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | Получает или задает название альбома/фильма/шоу. Это значение представлено кадром TALB. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | Получает или задает ведущего исполнителя(ей)/ведущего исполнителя(ей)/солиста(ов)/группу исполнителей. Это значение представлено фреймом TPE1. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | Получает или задает прикрепленные изображения, непосредственно связанные с аудиофайлом. Это значение представлено кадром APIC. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Получает или устанавливает полосу/оркестр/аккомпанемент. Это значение представлено кадром TPE2. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | Получает или задает количество ударов в минуту в основной части аудио. Это значение представлено кадром TBPM. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | Получает или задает пользовательские комментарии. Это значение представлено фреймом COMM. Фрейм предназначен для любой полнотекстовой информации, которая не помещается ни в какой другой фрейм. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | Получает или задает композиторов. Имена разделяются символом "/". Это значение представлено кадром TCOM. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | Получает или задает тип содержимого. Это значение представлено кадром TCON. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | Получает или устанавливает сообщение об авторских правах. Это значение представлено кадром TCOP. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | Получает или задает числовую строку в формате DDMM, содержащую дату записи. Это поле всегда состоит из четырех символов. Это значение представлено кадром TDAT. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | Получает или задает имя человека или организации, которые закодировали аудиофайл. Это значение представлено кадром TENC. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | Получает или задает Международный стандартный код записи (ISRC) (12 символов). Это значение представлено кадром TSRC. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | Получает или задает длину аудиофайла в миллисекундах, представленную в виде числовой строки. Это значение представлено кадром TLEN. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | Получает или устанавливает музыкальную тональность, в которой начинается звук. Это значение представлено кадром TKEY. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | Получает или задает исходное название альбома/фильма/шоу. Это значение представлено кадром TOAL. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | Получает или задает имя лейбла или издателя. Это значение представлено кадром TPUB. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | Получает или задает размер аудиофайла в байтах, исключая тег ID3v2, представленный в виде числовой строки. Это значение представлено кадром TSIZ. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | Получает или задает используемый аудиокодер и его настройки при кодировании файла. Это значение представлено кадром TSSE. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | Получает или задает уточнение подзаголовка/описания. Это значение представлено кадром TIT3. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | Получает размер тега. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | Получает или задает числовую строку в формате ЧЧММ, содержащую время записи. Это поле всегда состоит из четырех символов. Это значение представлено кадром TIME. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | Получает или задает заголовок/название песни/описание содержимого. Это значение представлено кадром TIT2. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | Получает или задает числовую строку, содержащую порядковый номер аудиофайла в его исходной записи. Это значение представлено кадром TRCK. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | Получает количество воспроизведений файла. Это значение представлено кадром PCNT. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | Получает версию ID3. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | Получает или задает числовую строку с годом записи. Этот кадр всегда состоит из четырех символов (до 10000 года). Это значение представлено кадром TYER. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | Добавляет рамку к тегу. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | Удаляет все кадры с указанным идентификатором. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | Получает массив кадров с указанным идентификатором. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | Удаляет указанный кадр из тега. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | Удаляет все прикрепленные изображения, хранящиеся в кадрах APIC. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | Удаляет все кадры с таким же идентификатором, как указанный, и добавляет новый кадр в тег. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | Создает список из пакета. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Учить больше**

* [Обработка тега ID3v2](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Примеры

В этом примере показано, как прочитать тег ID3v2 в файле MP3.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### Смотрите также

* class [ID3Tag](../id3tag)
* пространство имен [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
