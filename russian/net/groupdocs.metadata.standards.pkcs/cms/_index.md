---
title: Cms
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет цифровой знак созданный с помощью криптографического синтаксиса сообщений CMS  стандарта IETF для криптографически защищенных сообщений. CMS основан на синтаксисе PKCS 7 указанном в RFC 5652. См.https//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 для получения дополнительной информации.
type: docs
weight: 2960
url: /ru/net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Представляет цифровой знак, созданный с помощью криптографического синтаксиса сообщений (CMS) — стандарта IETF для криптографически защищенных сообщений. CMS основан на синтаксисе PKCS #7, указанном в RFC 5652. См.[https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) для получения дополнительной информации.

```csharp
public class Cms : DigitalSignature
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Получает необработанные данные сертификата. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Получает коллекцию сертификатов. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Получает различающееся имя субъекта из сертификата. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Получает комментарий к цели подписания. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Получает массив идентификаторов алгоритма дайджеста сообщения. В коллекции может быть любое количество элементов, включая ноль. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Получает подписанный контент, состоящий из идентификатора типа контента и самого контента. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Получает значение, указывающее, действительна ли подпись. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Получает коллекцию информационных пакетов для каждого подписавшего. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Получает время, когда подписывающая сторона (предположительно) выполнила процесс подписания. |

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

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* пространство имен [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
