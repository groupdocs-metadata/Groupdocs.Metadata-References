---
title: XmpResourceRef
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar en referens med flera delar till en resurs. Används för att indikera tidigare versioner original av återgivningar original för härledda dokument och så vidare.
type: docs
weight: 3550
url: /sv/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Representerar en referens med flera delar till en resurs. Används för att indikera tidigare versioner, original av återgivningar, original för härledda dokument och så vidare.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Initierar en ny instans av[`XmpResourceRef`](../xmpresourceref) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Hämtar eller ställer in den refererade resursens reservfilsökvägar eller webbadresser. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Hämtar eller ställer in värdet för egenskapen xmpMM:DocumentID från den refererade resursen. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Hämtar eller ställer in den refererade resursens filsökväg eller URL. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Hämtar eller ställer in värdet för egenskapen xmpMM:InstanceID från den refererade resursen. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Hämtar eller ställer in värdet för stEvt:när filen skrevs för sista gången. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Hämtar eller ställer in den refererade resursens xmpMM:Manager. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Hämtar eller ställer in den refererade resursens xmpMM:Manager. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Hämtar eller ställer in den refererade resursens xmpMM:ManageTo. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Hämtar eller ställer in den refererade resursens xmpMM:ManageUI. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Hämtar namnområdets URI:er som används i[`XmpComplexType`](../xmpcomplextype) instans. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | Hämtar eller ställer in namnet eller URI för en mappningsfunktion som används för att mappa fromPart till toPart. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Hämtar namnutrymmesprefixen som används i[`XmpComplexType`](../xmpcomplextype) instans. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Hämtar eller ställer in värdet för egenskapen xmpMM:RenditionClass från den refererade resursen. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Hämtar eller ställer in värdet för egenskapen xmpMM:RenditionParams från den refererade resursen. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Hämtar eller ställer in värdet för egenskapen xmpMM:RenditionParams från den refererade resursen. |

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
