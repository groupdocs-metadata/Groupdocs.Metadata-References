---
title: PdfTypePackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет пакет метаданных содержащий информацию о формате файла PDF.
type: docs
weight: 1050
url: /ru/net/groupdocs.metadata.formats.document/pdftypepackage/
---
## PdfTypePackage class

Представляет пакет метаданных, содержащий информацию о формате файла PDF.

```csharp
public class PdfTypePackage : FileTypePackage
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Extension](../../groupdocs.metadata.common/filetypepackage/extension) { get; } | Получает расширение файла. |
| [FileFormat](../../groupdocs.metadata.common/filetypepackage/fileformat) { get; } | Получает формат файла. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [MimeType](../../groupdocs.metadata.common/filetypepackage/mimetype) { get; } | Получает тип MIME. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Version](../../groupdocs.metadata.formats.document/pdftypepackage/version) { get; } | Получает версию формата. |

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

### Смотрите также

* class [FileTypePackage](../../groupdocs.metadata.common/filetypepackage)
* пространство имен [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
