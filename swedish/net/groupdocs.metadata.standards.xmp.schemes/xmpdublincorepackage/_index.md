---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar Dublin Coreschemat.
type: docs
weight: 3120
url: /sv/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

Representerar Dublin Core-schemat.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | Initierar en ny instans av[`XmpDublinCorePackage`](../xmpdublincorepackage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | Hämtar eller ställer in en uppsättning av bidragsgivarna. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | Hämtar eller ställer in omfattningen eller omfattningen av resursen. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | Får eller ställer in en uppsättning av skaparna. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | Hämtar eller ställer in en array av datum associerade med en händelse i resursens livscykel. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | Hämtar eller ställer in en rad textbeskrivningar av innehållet i resursen, givna på olika språk. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | Hämtar eller ställer in MIME-typen för resursen. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | Hämtar eller ställer in ett strängvärde som representerar en entydig referens till resursen inom ett givet sammanhang. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | Hämtar eller ställer in en rad språk som används i innehållet i resursen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Hämtar namnutrymmets URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Hämtar xmlns-prefixet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | Hämtar eller ställer in en rad utgivare som gjort resursen tillgänglig. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | Hämtar eller ställer in en array av relaterade resurser. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | Hämtar eller ställer in en rad informella rättighetsförklaringar, givna på olika språk. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | Hämtar eller ställer in den relaterade resursen som den beskrivna resursen härrör från. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | Hämtar eller ställer in en rad beskrivande fraser eller nyckelord som anger innehållet i resursen. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | Hämtar eller ställer in titeln eller namnet på resursen, givet på olika språk. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | Hämtar eller ställer in en matris med strängvärden som representerar resursens natur eller genre. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Hämtar XML-namnutrymmet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Tar bort alla XMP-egenskaper. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Konverterar XMP-värdet till XML-representationen. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Tar bort egenskapen med det angivna namnet. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Ställer in boolesk egenskap. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | SetsDateTime egenskap. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Ställer in dubbel egenskap. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Ställer in heltalsegenskapen. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Anger strängegenskap. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | Ställer in värdet som ärvs från[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Ställer in värdet som ärvs från[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Ställer in värdet som ärvs från[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | Anger en enskild bidragsgivare till resursen. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | Ställer in en enda skapare av resursen. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | Ställer in ett enda datum kopplat till resursen. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | Ställer in resursbeskrivningen på ett enda språk. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | Ställer in ett enda språk som är associerat med resursen. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | Anger en enda utgivare av resursen. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | Anger en enskild relaterad resurs. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | Anger resursrättigheterna, givna på ett enda språk. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | Anger ett enda ämne för resursen. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | Ställer in resurstiteln, angiven på ett enda språk. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | Ställer in en enda typ av resursen. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

För mer information se: http://dublincore.org/documents/usageguide/elements.shtml.

### Se även

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
