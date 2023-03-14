---
title: MatroskaAudioTrack
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет звуковые метаданные в видео Matroska.
type: docs
weight: 2430
url: /ru/net/groupdocs.metadata.formats.video/matroskaaudiotrack/
---
## MatroskaAudioTrack class

Представляет звуковые метаданные в видео Matroska.

```csharp
public class MatroskaAudioTrack : MatroskaTrack
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BitDepth](../../groupdocs.metadata.formats.video/matroskaaudiotrack/bitdepth) { get; } | Получает количество битов на выборку, в основном используется для PCM. |
| [Channels](../../groupdocs.metadata.formats.video/matroskaaudiotrack/channels) { get; } | Получает номера каналов в дорожке. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | Получает идентификатор, соответствующий кодеку. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | Получает удобочитаемую строку с указанием кодека. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | Получает количество наносекунд (не масштабируется через[`TimecodeScale`](../matroskasegment/timecodescale) ) за кадр. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | Получает флаг включения, true если дорожку можно использовать. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Получает язык дорожки в форме языков Matroska. Этот элемент ДОЛЖЕН игнорироваться, если[`LanguageIetf`](../matroskatrack/languageietf) Элемент используется в том же TrackEntry. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | Получает язык дорожки в соответствии с BCP 47 и с использованием реестра языковых подтегов IANA. Если используется этот Элемент, то любой[`Language`](../matroskatrack/language) Элементы, используемые в одном и том же TrackEntry, ДОЛЖНЫ игнорироваться. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | Получает удобочитаемое имя дорожки. |
| [OutputSamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/outputsamplingfrequency) { get; } | Получает реальную частоту дискретизации выходного сигнала в Гц (используется для методов SBR). |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [SamplingFrequency](../../groupdocs.metadata.formats.video/matroskaaudiotrack/samplingfrequency) { get; } | Получает частоту дискретизации в Гц. |
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
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Узнать больше**

* [Работа с метаданными в файлах Matroska (MKV)](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Смотрите также

* class [MatroskaTrack](../matroskatrack)
* пространство имен [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
