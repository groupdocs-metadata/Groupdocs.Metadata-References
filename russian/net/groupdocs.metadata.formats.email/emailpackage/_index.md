---
title: EmailPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет метаданные сообщения электронной почты.
type: docs
weight: 1360
url: /ru/net/groupdocs.metadata.formats.email/emailpackage/
---
## EmailPackage class

Представляет метаданные сообщения электронной почты.

```csharp
public abstract class EmailPackage : CustomPackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | Получает массив имен вложенных файлов. |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | Получает или задает массив получателей BCC (скрытая копия) сообщения электронной почты. |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | Получает или задает массив получателей копии (копии) сообщения электронной почты. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | Получает пакет метаданных, содержащий заголовки электронной почты. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | Получает или задает массив получателей электронной почты. |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | Получает адрес электронной почты отправителя. |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | Получает или задает тему сообщения электронной почты. |

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

* [Работа с сохраненными электронными письмами](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### Примеры

В этом примере показано, как удалить все вложения из сообщения электронной почты.

```csharp
using (Metadata metadata = new Metadata(Constants.InputEml))
{
    var root = metadata.GetRootPackage<EmailRootPackage>();

    root.ClearAttachments();

    metadata.Save(Constants.OutputEml);
}
```

### Смотрите также

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* пространство имен [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
