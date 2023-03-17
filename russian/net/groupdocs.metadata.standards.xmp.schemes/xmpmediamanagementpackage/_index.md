---
title: XmpMediaManagementPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет пространство имен XMP Media Management.
type: docs
weight: 3170
url: /ru/net/groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/
---
## XmpMediaManagementPackage class

Представляет пространство имен XMP Media Management.

```csharp
public sealed class XmpMediaManagementPackage : XmpPackage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpMediaManagementPackage](xmpmediamanagementpackage)() | Инициализирует новый экземпляр[`XmpMediaManagementPackage`](../xmpmediamanagementpackage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [DerivedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/derivedfrom) { get; set; } | Получает или задает ссылку на ресурс, из которого получен этот. |
| [DocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/documentid) { get; set; } | Получает или задает общий идентификатор для всех версий и представлений ресурса. |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/history) { get; set; } | Получает или задает массив высокоуровневых действий, которые привели к этому ресурсу. |
| [Ingredients](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/ingredients) { get; set; } | Получает или задает ссылки на ресурсы, которые были включены путем включения или ссылки в этот ресурс. |
| [InstanceID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/instanceid) { get; set; } | Получает или задает идентификатор конкретного воплощения ресурса, который обновляется при каждом сохранении файла. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [ManagedFrom](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managedfrom) { get; set; } | Получает или задает ссылку на документ, каким он был до того, как стал управляемым. |
| [Manager](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manager) { get; set; } | Получает или задает имя системы управления активами, которая управляет этим ресурсом. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/managervariant) { get; set; } | Получает или задает конкретный вариант системы управления активами. |
| [ManageTo](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageto) { get; set; } | Получает или задает URI, идентифицирующий управляемый ресурс для системы управления активами |
| [ManageUI](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/manageui) { get; set; } | Получает или задает URI, который можно использовать для доступа к информации об управляемом ресурсе через веб-браузер. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Получает URI пространства имен. |
| [OriginalDocumentID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/originaldocumentid) { get; set; } | Получает или задает общий идентификатор исходного ресурса, из которого получен текущий ресурс. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Получает префикс xmlns. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Получает набор дескрипторов, содержащих информацию о свойствах, доступных через поисковую систему GroupDocs.Metadata. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionclass) { get; set; } | Получает или задает имя класса представления для этого ресурса. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/renditionparams) { get; set; } | Получает или задает значение, используемое для предоставления дополнительных параметров воспроизведения , которые слишком сложны или многословны для кодирования в xmpMM:RenditionClass. |
| [VersionID](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versionid) { get; set; } | Получает или задает идентификатор версии документа для этого ресурса. |
| [Versions](../../groupdocs.metadata.standards.xmp.schemes/xmpmediamanagementpackage/versions) { get; set; } | Получает или задает историю версий, связанную с этим ресурсом. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Устанавливает строковое свойство. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Устанавливает значение, унаследованное от[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Устанавливает значение, унаследованное от[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Устанавливает значение, унаследованное от[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Смотрите также

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* пространство имен [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
