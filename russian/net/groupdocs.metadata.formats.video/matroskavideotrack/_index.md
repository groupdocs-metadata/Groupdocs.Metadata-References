---
title: MatroskaVideoTrack
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет метаданные видео в видео Matroska.
type: docs
weight: 2610
url: /ru/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Представляет метаданные видео в видео Matroska.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | Получает альфа-режим видео. Наличие этого элемента указывает на то, что элемент BlockAdditional может содержать альфа-данные. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Получает идентификатор, соответствующий кодеку. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Получает удобочитаемую строку с указанием кодека. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Получает количество наносекунд (не масштабируется через[`TimecodeScale`](../matroskasegment/timecodescale) ) за кадр. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | Получает высоту отображаемых видеокадров. Применяется к кадру видео после кадрирования (элементы PixelCrop*). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | Получает как[`DisplayWidth`](./displaywidth) а также[`DisplayHeight`](./displayheight) интерпретируются. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | Получает ширину отображаемых видеокадров. Применяется к кадру видео после кадрирования (элементы PixelCrop*). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | Get объявляет порядок полей видео. Если для параметра FlagInterlaced не установлено значение 1, этот элемент ДОЛЖЕН игнорироваться. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Получает флаг включения, true если дорожку можно использовать. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | Получает флаг для объявления того, является ли видео прогрессивным или чересстрочным, и, если применимо, для объявления подробностей о чересстрочной развертке. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Получает язык дорожки в форме языков Matroska. Этот элемент ДОЛЖЕН игнорироваться, если[`LanguageIetf`](../matroskatrack/languageietf) Элемент используется в том же TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Получает язык дорожки в соответствии с BCP 47 и с использованием реестра языковых подтегов IANA. Если используется этот Элемент, то любой[`Language`](../matroskatrack/language) Элементы, используемые в одном и том же TrackEntry, ДОЛЖНЫ игнорироваться. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Получает удобочитаемое имя дорожки. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | Получает количество видеопикселей, которые необходимо удалить в нижней части изображения. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | Получает количество видеопикселей, которые необходимо удалить слева от изображения. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | Получает количество видеопикселей, которые необходимо удалить справа от изображения. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | Получает количество видеопикселей, которые необходимо удалить в верхней части изображения. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | Получает высоту закодированных видеокадров в пикселях. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | Получает ширину закодированных видеокадров в пикселях. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | Получает режим стерео-3D-видео. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | Получает номер дорожки, используемый в заголовке блока. Использование более 127 дорожек не рекомендуется, хотя дизайн допускает неограниченное количество. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | Получает тип дорожки. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | Получает уникальный идентификатор для идентификации дорожки. Его СЛЕДУЕТ сохранять одинаковым при прямом потоковом копировании дорожки в другой файл. |

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

**Учить больше**

* [Работа с метаданными в файлах Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Смотрите также

* class [MatroskaTrack](../matroskatrack)
* пространство имен [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
