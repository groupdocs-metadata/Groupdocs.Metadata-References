---
title: XmpColorantLab
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет краситель LAB.
type: docs
weight: 3330
url: /ru/net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
---
## XmpColorantLab class

Представляет краситель LAB.

```csharp
public sealed class XmpColorantLab : XmpColorantBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpColorantLab](xmpcolorantlab#constructor)() | Инициализирует новый экземпляр[`XmpColorantLab`](../xmpcolorantlab) класс. |
| [XmpColorantLab](xmpcolorantlab#constructor_1)(sbyte, sbyte, double) | Инициализирует новый экземпляр[`XmpColorantLab`](../xmpcolorantlab) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [A](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/a) { get; set; } | Получает или задает компонент A. |
| [B](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/b) { get; set; } | Получает или задает компонент B. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Получает или задает тип цвета. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [L](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/l) { get; set; } | Получает или задает компонент L. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Получает цветовое пространство, в котором определен цвет. Один из: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Получает URI пространства имен, которые используются в[`XmpComplexType`](../xmpcomplextype) экземпляр. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Получает префиксы пространств имен, используемые в[`XmpComplexType`](../xmpcomplextype) экземпляр. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Получает или задает имя образца. |

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
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | ВозвращаетString который представляет этот экземпляр. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

## Поля

| Имя | Описание |
| --- | --- |
| const [MaxL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/maxl) | Максимальное значение компонента L. |
| const [MinL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/minl) | Минимальное значение компонента L. |

### Смотрите также

* class [XmpColorantBase](../xmpcolorantbase)
* пространство имен [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
