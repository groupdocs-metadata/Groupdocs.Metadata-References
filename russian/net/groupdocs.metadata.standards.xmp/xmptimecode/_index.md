---
title: XmpTimecode
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет значение временного кода в видео.
type: docs
weight: 3600
url: /ru/net/groupdocs.metadata.standards.xmp/xmptimecode/
---
## XmpTimecode class

Представляет значение временного кода в видео.

```csharp
public sealed class XmpTimecode : XmpComplexType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpTimecode](xmptimecode#constructor)() | Инициализирует новый экземпляр[`XmpTimecode`](../xmptimecode) класс. |
| [XmpTimecode](xmptimecode#constructor_1)(XmpTimeFormat, string) | Инициализирует новый экземпляр[`XmpTimecode`](../xmptimecode) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Получает URI пространства имен, которые используются в[`XmpComplexType`](../xmpcomplextype) экземпляр. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Получает префиксы пространств имен, используемые в[`XmpComplexType`](../xmpcomplextype) экземпляр. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [TimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/timeformat) { get; set; } | Получает или задает формат, используемый в значении времени. |
| [TimeValue](../../groupdocs.metadata.standards.xmp/xmptimecode/timevalue) { get; set; } | Получает или задает значение времени в указанном формате. Значения времени используют разделитель двоеточия во всех форматах, кроме 2997drop и 5994drop, в которых используется точка с запятой. Четыре поля указывают часы, минуты, секунды и кадры: чч:мм:сс:фф |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Получает URI пространства имен, связанный с указанным префиксом. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Возвращает строковое значение в формате XMP. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [SetTimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/settimeformat)(XmpTimeFormat) | Устанавливает формат времени. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | ВозвращаетString который представляет этот экземпляр. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Смотрите также

* class [XmpComplexType](../xmpcomplextype)
* пространство имен [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
