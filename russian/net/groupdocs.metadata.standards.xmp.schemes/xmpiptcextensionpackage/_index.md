---
title: XmpIptcExtensionPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет XMPпакет расширения IPTC.
type: docs
weight: 3150
url: /ru/net/groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/
---
## XmpIptcExtensionPackage class

Представляет XMP-пакет расширения IPTC.

```csharp
public sealed class XmpIptcExtensionPackage : XmpPackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpIptcExtensionPackage](xmpiptcextensionpackage)() | Инициализирует новый экземпляр[`XmpIptcExtensionPackage`](../xmpiptcextensionpackage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AdditionalModelInformation](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/additionalmodelinformation) { get; set; } | Получает или задает информацию об этнической принадлежности и других аспектах модели(ей) в образе, выпущенном моделью. |
| [AgesOfModels](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/agesofmodels) { get; set; } | Получает или задает возраст моделей людей на момент создания этого изображения в опубликованном образе модели. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DigitalImageGuid](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalimageguid) { get; set; } | Получает или задает глобальный уникальный идентификатор для этого цифрового изображения. |
| [DigitalSourceType](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/digitalsourcetype) { get; set; } | Получает или задает тип источника этого цифрового изображения. |
| [Event](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/event) { get; set; } | Получает или задает описание конкретного события, на котором была сделана фотография. |
| [IptcLastEdited](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/iptclastedited) { get; set; } | Получает или задает дату и, возможно, время, когда любое из полей метаданных фотографий IPTC последний раз редактировалось. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MaxAvailableHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailableheight) { get; set; } | Получает или задает максимально доступную высоту в пикселях исходной фотографии, из которой эта фотография была получена путем уменьшения размера. |
| [MaxAvailableWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/maxavailablewidth) { get; set; } | Получает или задает максимально доступную ширину в пикселях исходной фотографии, из которой эта фотография была получена путем уменьшения размера. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Получает URI пространства имен. |
| [OrganisationInImageCodes](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagecodes) { get; set; } | Получает или задает коды из контролируемого словаря для идентификации организаций или компаний, представленных на изображении. |
| [OrganisationInImageNames](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/organisationinimagenames) { get; set; } | Получает или задает названия организаций или компаний, представленных на изображении. |
| [PersonsInImage](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/personsinimage) { get; set; } | Получает или задает имена лиц, о которых идет речь в элементе. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Получает префикс xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Получает пространство имен XML. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Добавляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Удаляет все свойства XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Определяет, содержит ли пакет свойство метаданных с указанным именем. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Находит свойства метаданных, удовлетворяющие указанному предикату. Поиск является рекурсивным, поэтому он затрагивает также все вложенные пакеты. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Преобразует значение XMP в представление XML. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Удаляет свойство с указанным именем. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Удаляет свойства метаданных, удовлетворяющие указанному предикату. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Удаляет доступные для записи свойства метаданных из пакета. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Устанавливает логическое свойство. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | НаборыDateTime свойство. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Устанавливает двойное свойство. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Устанавливает целочисленное свойство. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_7)(string, string) | Устанавливает строковое свойство. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpiptcextensionpackage/set#set_2)(string, XmpArray) | Устанавливает значение, унаследованное от[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Устанавливает значение, унаследованное от[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Устанавливает значение, унаследованное от[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) а также[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Смотрите также

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* пространство имен [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
