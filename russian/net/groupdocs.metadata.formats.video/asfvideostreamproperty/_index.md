---
title: AsfVideoStreamProperty
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет метаданные свойств видеопотока в медиаконтейнере ASF.
type: docs
weight: 2370
url: /ru/net/groupdocs.metadata.formats.video/asfvideostreamproperty/
---
## AsfVideoStreamProperty class

Представляет метаданные свойств видеопотока в медиаконтейнере ASF.

```csharp
public class AsfVideoStreamProperty : AsfBaseStreamProperty
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | Получает скорость утечки RAlt в битах в секунду для дырявого сегмента, содержащего часть данных потока без переполнения, исключая все служебные данные пакета данных ASF. |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | Получает средний битрейт. |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | Получает среднюю продолжительность каждого кадра, измеряемую в 100 наносекундах. |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | Получает скорость утечки R в битах в секунду для дырявого ведра, содержащего часть данных потока без переполнения, исключая все служебные данные пакета данных ASF. |
| [BitsPerPixels](../../groupdocs.metadata.formats.video/asfvideostreamproperty/bitsperpixels) { get; } | Получает количество бит на пиксель. |
| [Compression](../../groupdocs.metadata.formats.video/asfvideostreamproperty/compression) { get; } | Получает идентификатор сжатия видео. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | Получает время представления последнего объекта плюс продолжительность воспроизведения, указывая, где заканчивается этот цифровой медиапоток в контексте временной шкалы файла ASF в целом. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | Получает флаги. |
| [ImageHeight](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imageheight) { get; } | Получает высоту закодированного изображения в пикселях. |
| [ImageWidth](../../groupdocs.metadata.formats.video/asfvideostreamproperty/imagewidth) { get; } | Получает ширину закодированного изображения в пикселях. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | Получает язык потока. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | Получает время презентации первого объекта, указывая, где этот цифровой медиапоток начинается в контексте временной шкалы файла ASF в целом. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | Получает номер этого потока. |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | Получает тип этого потока. |

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

* [Работа с метаданными в файлах ASF](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### Смотрите также

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* пространство имен [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
