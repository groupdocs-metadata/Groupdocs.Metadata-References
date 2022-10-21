---
title: SpreadsheetRootPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет корневой пакет позволяющий работать с метаданными в электронной таблице.
type: docs
weight: 1210
url: /ru/net/groupdocs.metadata.formats.document/spreadsheetrootpackage/
---
## SpreadsheetRootPackage class

Представляет корневой пакет, позволяющий работать с метаданными в электронной таблице.

```csharp
public class SpreadsheetRootPackage : DocumentRootPackage<SpreadsheetPackage>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| virtual [DocumentProperties](../../groupdocs.metadata.formats.document/documentrootpackage-1/documentproperties) { get; } | Получает собственные свойства метаданных, представленные в документе. |
| [DocumentStatistics](../../groupdocs.metadata.formats.document/spreadsheetrootpackage/documentstatistics) { get; } | Получает пакет статистики документа. |
| [FileType](../../groupdocs.metadata.formats.document/spreadsheetrootpackage/filetype) { get; } | Получает пакет метаданных типа файла. (2 properties) |
| [InspectionPackage](../../groupdocs.metadata.formats.document/spreadsheetrootpackage/inspectionpackage) { get; } | Получает пакет метаданных, содержащий результаты проверки документа. Пакет содержит информацию о частях документа, которые в некоторых случаях могут рассматриваться как метаданные. |
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

* [Работа с метаданными в электронных таблицах](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Примеры

Этот фрагмент кода демонстрирует, как извлечь встроенные свойства метаданных из электронной таблицы.

```csharp
/// использование (метаданные метаданных = новые метаданные (константы.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    Console.WriteLine(root.DocumentProperties.Author);
    Console.WriteLine(root.DocumentProperties.CreatedTime);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Category);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.ContentType);

    // ... 
}
```

### Смотрите также

* class [DocumentRootPackage&lt;TPackage&gt;](../documentrootpackage-1)
* class [SpreadsheetPackage](../spreadsheetpackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
