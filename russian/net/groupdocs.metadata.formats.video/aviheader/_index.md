---
title: AviHeader
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет структуру AVIMAINHEADER в видео AVI.
type: docs
weight: 2380
url: /ru/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

Представляет структуру AVIMAINHEADER в видео AVI.

```csharp
public sealed class AviHeader : CustomPackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AviHeader](aviheader)() | Инициализирует новый экземпляр[`AviHeader`](../aviheader) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | Получает побитовую комбинацию из нуля или более флагов AVI. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | Получает высоту файла AVI в пикселях. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | Получает начальный кадр для чередующихся файлов.  Файлы без чередования должны указывать ноль. Если вы создаете чередующиеся файлы, укажите количество кадров в файле до начального кадра последовательности AVI в этом элементе. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | Получает приблизительную максимальную скорость передачи данных файла.  Это значение указывает количество байтов в секунду, которое система должна обработать, чтобы представить последовательность AVI как , заданную другими параметрами, содержащимися в основном заголовке и фрагментах заголовка потока. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | Получает количество микросекунд между кадрами. Это значение указывает общее время для файла. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | Получает выравнивание данных в байтах. Дополните данные кратными этому значению. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | Получает количество потоков в файле. Например, файл с аудио и видео имеет два потока. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | Получает рекомендуемый размер буфера для чтения файла.  Как правило, этот размер должен быть достаточно большим, чтобы вместить самый большой блок в файле. Если установлено значение 0 или слишком маленькое значение, программе воспроизведения придется перераспределять память во время воспроизведения, что снизит производительность. Для файла с чередованием размер буфера должен быть достаточно большим для чтения всей записи, а не только фрагмента. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | Получает общее количество кадров данных в файле. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | Получает ширину файла AVI в пикселях. |

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

* [Работа с метаданными в файлах AVI](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### Смотрите также

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* пространство имен [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
