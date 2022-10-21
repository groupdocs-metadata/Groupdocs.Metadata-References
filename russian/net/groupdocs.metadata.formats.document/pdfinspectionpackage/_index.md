---
title: PdfInspectionPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Содержит информацию о частях PDFдокумента которые в некоторых случаях можно рассматривать как метаданные.
type: docs
weight: 1020
url: /ru/net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Содержит информацию о частях PDF-документа, которые в некоторых случаях можно рассматривать как метаданные.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Получает массив аннотаций. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Получает массив вложений. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Получает массив закладок. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Получает массив цифровых подписей. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Получает массив полей формы. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Удаляет все обнаруженные аннотации из документа. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Удаляет все обнаруженные вложения из документа. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Удаляет все обнаруженные закладки из документа. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Удаляет все обнаруженные цифровые подписи из документа. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Удаляет все обнаруженные поля формы из документа. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Учить больше**

* [Работа с метаданными в документах PDF](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Примеры

В этом примере кода показано, как удалить свойства проверки в документе PDF.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### Смотрите также

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
