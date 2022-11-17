---
title: XmpVersion
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en version av ett dokument.
type: docs
weight: 3630
url: /sv/net/groupdocs.metadata.standards.xmp/xmpversion/
---
## XmpVersion class

Representerar en version av ett dokument.

```csharp
public sealed class XmpVersion : XmpComplexType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpVersion](xmpversion)() | Initierar en ny instans av[`XmpVersion`](../xmpversion) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Comments](../../groupdocs.metadata.standards.xmp/xmpversion/comments) { get; set; } | Hämtar eller ställer in kommentarer om vad som ändrades. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Event](../../groupdocs.metadata.standards.xmp/xmpversion/event) { get; set; } | Hämtar eller ställer in den formella beskrivningen på hög nivå av vilken operation användaren utförde. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [Modifier](../../groupdocs.metadata.standards.xmp/xmpversion/modifier) { get; set; } | Hämtar eller ställer in personen som modifierade denna version. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp/xmpversion/modifydate) { get; set; } | Hämtar eller ställer in datumet då denna version checkades in. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Hämtar namnområdets URI:er som används i[`XmpComplexType`](../xmpcomplextype) instans. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Hämtar namnutrymmesprefixen som används i[`XmpComplexType`](../xmpcomplextype) instans. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [VersionNumber](../../groupdocs.metadata.standards.xmp/xmpversion/versionnumber) { get; set; } | Hämtar eller ställer in det nya versionsnumret. |

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

### Se även

* class [XmpComplexType](../xmpcomplextype)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
