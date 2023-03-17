---
title: XmpPackage
second_title: Справочник по API GroupDocs.Metadata для .NET
description: Представляет базовую абстракцию для пакета XMP.
type: docs
weight: 3490
url: /ru/net/groupdocs.metadata.standards.xmp/xmppackage/
---
## XmpPackage class

Представляет базовую абстракцию для пакета XMP.

```csharp
public class XmpPackage : XmpMetadataContainer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpPackage](xmppackage)(string, string) | Инициализирует новый экземпляр[`XmpPackage`](../xmppackage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Получает количество свойств метаданных. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Получает[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) с указанным именем. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Получает коллекцию имен свойств метаданных. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Получает тип метаданных. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Получает URI пространства имен. |
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
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set)(string, bool) | Устанавливает логическое свойство. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_6)(string, DateTime) | НаборыDateTime свойство. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_1)(string, double) | Устанавливает двойное свойство. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_5)(string, int) | Устанавливает целочисленное свойство. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_7)(string, string) | Устанавливает строковое свойство. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_2)(string, XmpArray) | Устанавливает значение, унаследованное от[`XmpArray`](../xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_3)(string, XmpComplexType) | Устанавливает значение, унаследованное от[`XmpComplexType`](../xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_4)(string, XmpValueBase) | Устанавливает значение, унаследованное от[`XmpValueBase`](../xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Устанавливает известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она влияет также на все вложенные пакеты. Этот метод представляет собой комбинацию[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) и[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Если существующее свойство удовлетворяет предикату, его значение обновляется. Если в пакете отсутствует известное свойство, удовлетворяющее предикату, оно добавляется в пакет. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Обновляет известные свойства метаданных, удовлетворяющие указанному предикату. Операция является рекурсивной, поэтому она также влияет на все вложенные пакеты. |

### Примечания

**Узнать больше**

* [Работа с метаданными XMP](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### Примеры

В этом примере показано, как добавить пользовательский пакет XMP в файл любого поддерживаемого формата.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        var packet = new XmpPacketWrapper();

        var custom = new XmpPackage("gd", "https://groupdocs.com");
        custom.Set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
        custom.Set("gd:CreationDate", DateTime.Today);
        custom.Set("gd:Company", XmpArray.From(new [] { "Aspose", "GroupDocs" }, XmpArrayType.Ordered));

        packet.AddPackage(custom);
        root.XmpPackage = packet;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### Смотрите также

* class [XmpMetadataContainer](../xmpmetadatacontainer)
* пространство имен [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* сборка [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
