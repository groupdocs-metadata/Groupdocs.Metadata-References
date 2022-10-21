---
title: CmsSigner
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет информацию CMS для каждого подписавшего.
type: docs
weight: 3010
url: /ru/net/groupdocs.metadata.standards.pkcs/cmssigner/
---
## CmsSigner class

Представляет информацию CMS для каждого подписавшего.

```csharp
public class CmsSigner : CustomPackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DigestAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/digestalgorithm) { get; } | Получает алгоритм дайджеста сообщения и любые связанные параметры, используемые подписывающей стороной. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [SignatureAlgorithm](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturealgorithm) { get; } | Получает алгоритм подписи и любые связанные параметры, используемые подписывающей стороной для создания цифровой подписи. |
| [SignatureValue](../../groupdocs.metadata.standards.pkcs/cmssigner/signaturevalue) { get; } | Получает результат генерации цифровой подписи, используя дайджест сообщения и закрытый ключ подписавшего. |
| [SignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/signedattributes) { get; } | Получает коллекцию подписанных атрибутов. |
| [SignerIdentifier](../../groupdocs.metadata.standards.pkcs/cmssigner/signeridentifier) { get; } | Получает необработанные данные сертификата подписывающей стороны (и, следовательно, открытого ключа подписывающей стороны). |
| [SigningTime](../../groupdocs.metadata.standards.pkcs/cmssigner/signingtime) { get; } | Получает время, когда подписывающая сторона (предположительно) выполнила процесс подписания. |
| [UnsignedAttributes](../../groupdocs.metadata.standards.pkcs/cmssigner/unsignedattributes) { get; } | Получает коллекцию неподписанных атрибутов. |

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
* пространство имен [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
