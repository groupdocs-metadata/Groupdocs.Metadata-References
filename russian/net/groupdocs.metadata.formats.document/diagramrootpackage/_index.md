---
title: DiagramRootPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет корневой пакет предназначенный для работы с метаданными на диаграмме.
type: docs
weight: 900
url: /ru/net/groupdocs.metadata.formats.document/diagramrootpackage/
---
## DiagramRootPackage class

Представляет корневой пакет, предназначенный для работы с метаданными на диаграмме.

```csharp
public class DiagramRootPackage : DocumentRootPackage<DiagramPackage>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Получает собственные свойства метаданных, представленные в документе. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/diagramrootpackage/documentstatistics) { get; } | Получает пакет статистики документа. |
| [FileType](../../groupdocs.metadata.formats.document/diagramrootpackage/filetype) { get; } | Получает пакет метаданных типа файла. (2 properties) |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| override [Sanitize](../../groupdocs.metadata.common/rootmetadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Учить больше**

* [Работа с метаданными в диаграммах](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Примеры

В следующем примере кода показано, как обновить встроенные свойства метаданных в документе схемы.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    root.DocumentProperties.Creator = "test author";
    root.DocumentProperties.TimeCreated = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputVdx);
}
```

### Смотрите также

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [DiagramPackage](../diagrampackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
