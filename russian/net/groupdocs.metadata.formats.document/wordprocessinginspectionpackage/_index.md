---
title: WordProcessingInspectionPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Содержит информацию о частях документа которые в некоторых случаях могут рассматриваться как метаданные.
type: docs
weight: 1270
url: /ru/net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
---
## WordProcessingInspectionPackage class

Содержит информацию о частях документа, которые в некоторых случаях могут рассматриваться как метаданные.

```csharp
public sealed class WordProcessingInspectionPackage : CustomPackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments) { get; } | Получает массив комментариев пользователя. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digitalsignatures) { get; } | Получает массив цифровых подписей, представленных в документе. |
| [Fields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields) { get; } | Получает массив полей документа. |
| [HiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hiddentext) { get; } | Получает массив извлеченных из документа фрагментов скрытого текста. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Revisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions) { get; } | Получает массив цифровых подписей, представленных в документе. |

## Методы

| Имя | Описание |
| --- | --- |
| [AcceptAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/acceptallrevisions)() | Принимает все обнаруженные исправления в документе. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [ClearComments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearcomments)() | Удаляет все обнаруженные комментарии пользователей из документа. |
| [ClearFields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearfields)() | Удаляет все обнаруженные поля из документа. |
| [ClearHiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearhiddentext)() | Удаляет все скрытые фрагменты текста из документа. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [RejectAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/rejectallrevisions)() | Отклоняет все обнаруженные исправления в документе. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| override [Sanitize](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Узнать больше**

* [Работа с метаданными в документах WordProcessing](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Примеры

В этом примере кода показано, как обновить свойства проверки в документе WordProcessing.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.AcceptAllRevisions();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearHiddenText();

    metadata.Save(Constants.OutputDoc);
}
```

### Смотрите также

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
