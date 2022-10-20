---
title: NikonMakerNotePackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет метаданные NIKON MakerNote.
type: docs
weight: 2840
url: /ru/net/groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/
---
## NikonMakerNotePackage class

Представляет метаданные NIKON MakerNote.

```csharp
public sealed class NikonMakerNotePackage : MakerNotePackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NikonMakerNotePackage](nikonmakernotepackage)(TiffTag[]) | Инициализирует новый экземпляр[`NikonMakerNotePackage`](../nikonmakernotepackage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/colormode) { get; } | Получает цветовой режим. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [FlashSetting](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashsetting) { get; } | Получает настройки вспышки. |
| [FlashType](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/flashtype) { get; } | Получает тип flash. |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/focusmode) { get; } | Получает режим фокусировки. |
| [Iso](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/iso) { get; } | Получает iso. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Получает тег TIFF с указанным идентификатором. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MakerNoteVersion](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/makernoteversion) { get; } | Получает версию MakerNote. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/quality) { get; } | Получает строку качества. |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/sharpness) { get; } | Получает резкость. |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/nikonmakernotepackage/whitebalance) { get; } | Получает баланс белого. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Удаляет все теги TIFF, хранящиеся в пакете. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Удаляет свойство с указанным идентификатором. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Добавляет или заменяет указанный тег. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Создает список из пакета. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Смотрите также

* class [MakerNotePackage](../makernotepackage)
* пространство имен [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
