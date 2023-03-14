---
title: XmpVersion
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет версию документа.
type: docs
weight: 3630
url: /ru/net/groupdocs.metadata.standards.xmp/xmpversion/
---
## XmpVersion class

Представляет версию документа.

```csharp
public sealed class XmpVersion : XmpComplexType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpVersion](xmpversion)() | Инициализирует новый экземпляр[`XmpVersion`](../xmpversion) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Comments](../../groupdocs.metadata.standards.xmp/xmpversion/comments) { get; set; } | Получает или задает комментарии относительно того, что было изменено. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Event](../../groupdocs.metadata.standards.xmp/xmpversion/event) { get; set; } | Получает или задает высокоуровневое формальное описание операции, которую выполнил пользователь. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [Modifier](../../groupdocs.metadata.standards.xmp/xmpversion/modifier) { get; set; } | Получает или задает пользователя, который изменил эту версию. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp/xmpversion/modifydate) { get; set; } | Получает или задает дату возврата этой версии. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Получает URI пространства имен, которые используются в[`XmpComplexType`](../xmpcomplextype) экземпляр. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Получает префиксы пространств имен, используемые в[`XmpComplexType`](../xmpcomplextype) экземпляр. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [VersionNumber](../../groupdocs.metadata.standards.xmp/xmpversion/versionnumber) { get; set; } | Получает или задает номер новой версии. |

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

### Смотрите также

* class [XmpComplexType](../xmpcomplextype)
* пространство имен [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
