---
title: DiagramPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет собственный пакет метаданных в формате схемы.
type: docs
weight: 890
url: /ru/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Представляет собственный пакет метаданных в формате схемы.

```csharp
public class DiagramPackage : DocumentPackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Получает или задает альтернативные имена для документа. Может обновляться только в форматах VDX и VSX. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Получает полный номер сборки экземпляра, использованного для создания документа. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Получает номер сборки экземпляра, который последний раз использовался для редактирования документа. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Получает или задает описательный текст для типа чертежа, например блок-схемы или макета офиса. Этот текст также можно ввести в пользовательском интерфейсе Microsoft Visio в поле "Категория" диалогового окна "Свойства". |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Получает или задает введенную пользователем информацию, идентифицирующую компанию, создающую чертеж, или компанию, для которой создается чертеж. Максимальная длина — 63 символа. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Получает или задает пользователя, создавшего или обновившего файл в последний раз. Максимальная длина — 63 символа.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Получает или задает строку описательного текста для документа. Используйте этот элемент для хранения важной информации о документе, такой как его цель, последние изменения или ожидающие изменения. Максимум 191 символ. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Получает или задает путь, который будет использоваться для относительных гиперссылок (гиперссылок, для которых расположение связанного файла описано относительно диаграммы Microsoft Visio). По умолчанию путь гиперссылки относится к текущему документу, если не указан другой путь в этом элементе. Максимальная длина 256 символов. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Получает или задает текстовую строку, идентифицирующую темы или другую важную информацию о файле, такую как имя проекта, имя клиента или номер версии. Максимальная длина строки — 63 символа. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Получает или задает язык документа. Может обновляться только в форматах VSD и VSDX. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Получает или задает введенную пользователем текстовую строку, идентифицирующую лицо, ответственное за проект или отдел. Максимальная длина — 63 символа. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Получает или задает изображение предварительного просмотра. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Получает или задает определяемую пользователем текстовую строку, описывающую содержимое документа. Максимальная длина — 63 символа. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Получает или задает строковое значение, указывающее имя файла шаблона, из которого был создан документ. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Получает или задает значение даты и времени, указывающее, когда был создан документ. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Получает значение даты и времени, указывающее, когда документ редактировался в последний раз. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Получает значение даты и времени, указывающее, когда документ был распечатан в последний раз. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Получает значение даты и времени, указывающее, когда документ был сохранен в последний раз. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Получает или задает определяемую пользователем текстовую строку, которая служит описательным заголовком документа. Максимальная длина — 63 символа. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Удаляет все доступные для записи свойства метаданных из пакета. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Удаляет все встроенные свойства метаданных. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Удаляет все пользовательские свойства метаданных. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Удаляет доступное для записи свойство метаданных по указанному имени. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Добавляет или заменяет свойство метаданных указанным именем. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Добавляет или заменяет свойство метаданных указанным именем. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Добавляет или заменяет свойство метаданных указанным именем. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Добавляет или заменяет свойство метаданных указанным именем. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Узнать больше**

* [Работа с метаданными в диаграммах](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Примеры

В этом примере кода показано, как извлечь встроенные свойства метаданных из диаграммы.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### Смотрите также

* class [DocumentPackage](../documentpackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
