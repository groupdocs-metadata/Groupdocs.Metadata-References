---
title: XmpColorantLab
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar LABfärgämnet.
type: docs
weight: 3330
url: /sv/net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
---
## XmpColorantLab class

Representerar LAB-färgämnet.

```csharp
public sealed class XmpColorantLab : XmpColorantBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpColorantLab](xmpcolorantlab#constructor)() | Initierar en ny instans av[`XmpColorantLab`](../xmpcolorantlab) class. |
| [XmpColorantLab](xmpcolorantlab#constructor_1)(sbyte, sbyte, double) | Initierar en ny instans av[`XmpColorantLab`](../xmpcolorantlab) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [A](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/a) { get; set; } | Hämtar eller ställer in A-komponenten. |
| [B](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/b) { get; set; } | Hämtar eller ställer in B-komponenten. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Hämtar eller ställer in typ av färg. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [L](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/l) { get; set; } | Hämtar eller ställer in L-komponenten. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Hämtar färgrymden där färgen är definierad. En av: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Hämtar namnområdets URI:er som används i[`XmpComplexType`](../xmpcomplextype) instans. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Hämtar namnutrymmesprefixen som används i[`XmpComplexType`](../xmpcomplextype) instans. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Hämtar eller ställer in namnet på färgrutan. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Hämtar namnutrymmes-URI som är kopplat till det angivna prefixet. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Returnerar stränginnehållet värde i XMP-format. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Returnerar enString som representerar denna instans. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [MaxL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/maxl) | Komponent L maxvärde. |
| const [MinL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/minl) | Komponent L min värde. |

### Se även

* class [XmpColorantBase](../xmpcolorantbase)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
