---
title: DublinCorePackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ett Dublin Coremetadatapaket.
type: docs
weight: 2730
url: /sv/net/groupdocs.metadata.standards.dublincore/dublincorepackage/
---
## DublinCorePackage class

Representerar ett Dublin Core-metadatapaket.

```csharp
public sealed class DublinCorePackage : CustomPackage
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Contributor](../../groupdocs.metadata.standards.dublincore/dublincorepackage/contributor) { get; } | Får bidragsgivaren Dublin Core-element. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Coverage](../../groupdocs.metadata.standards.dublincore/dublincorepackage/coverage) { get; } | Får täckningselementet Dublin Core. |
| [Creator](../../groupdocs.metadata.standards.dublincore/dublincorepackage/creator) { get; } | Får skaparen Dublin Core-elementet. |
| [Date](../../groupdocs.metadata.standards.dublincore/dublincorepackage/date) { get; } | Hämtar datumet Dublin Core-element. |
| [Description](../../groupdocs.metadata.standards.dublincore/dublincorepackage/description) { get; } | Hämtar beskrivningen Dublin Core element. |
| [Format](../../groupdocs.metadata.standards.dublincore/dublincorepackage/format) { get; } | Får formatet Dublin Core element. |
| [Identifier](../../groupdocs.metadata.standards.dublincore/dublincorepackage/identifier) { get; } | Hämtar identifieraren Dublin Core-element. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Language](../../groupdocs.metadata.standards.dublincore/dublincorepackage/language) { get; } | Hämtar språket Dublin Core element. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Publisher](../../groupdocs.metadata.standards.dublincore/dublincorepackage/publisher) { get; } | Får utgivarens Dublin Core-element. |
| [Relation](../../groupdocs.metadata.standards.dublincore/dublincorepackage/relation) { get; } | Får relationen Dublin Core element. |
| [Rights](../../groupdocs.metadata.standards.dublincore/dublincorepackage/rights) { get; } | Får rättigheterna Dublin Core-element. |
| [Source](../../groupdocs.metadata.standards.dublincore/dublincorepackage/source) { get; } | Hämtar källelementet Dublin Core. |
| [Subject](../../groupdocs.metadata.standards.dublincore/dublincorepackage/subject) { get; } | Får ämnet Dublin Core element. |
| [Title](../../groupdocs.metadata.standards.dublincore/dublincorepackage/title) { get; } | Får titeln Dublin Core element. |
| [Type](../../groupdocs.metadata.standards.dublincore/dublincorepackage/type) { get; } | Får typen Dublin Core element. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Standards.DublinCore](../../groupdocs.metadata.standards.dublincore)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
