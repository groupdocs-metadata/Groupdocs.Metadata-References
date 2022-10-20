---
title: DigitalSignature
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет цифровую подпись используемую для подписания документа.
type: docs
weight: 3030
url: /ru/net/groupdocs.metadata.standards.signing/digitalsignature/
---
## DigitalSignature class

Представляет цифровую подпись, используемую для подписания документа.

```csharp
public class DigitalSignature : CustomPackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Получает необработанные данные сертификата. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Получает различающееся имя субъекта из сертификата. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Получает комментарий к цели подписания. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Получает значение, указывающее, действительна ли подпись. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| virtual [SignTime](../../groupdocs.metadata.standards.signing/digitalsignature/signtime) { get; } | Получает время подписания документа. |

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

### Смотрите также

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* пространство имен [GroupDocs.Metadata.Standards.Signing](../../groupdocs.metadata.standards.signing)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->