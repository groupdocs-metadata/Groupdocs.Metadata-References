---
title: XmpPhotoshopPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar Adobe Photoshopnamnrymden.
type: docs
weight: 3210
url: /sv/net/groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/
---
## XmpPhotoshopPackage class

Representerar Adobe Photoshop-namnrymden.

```csharp
public sealed class XmpPhotoshopPackage : XmpPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpPhotoshopPackage](xmpphotoshoppackage)() | Initierar en ny instans av[`XmpPhotoshopPackage`](../xmpphotoshoppackage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AuthorsPosition](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/authorsposition) { get; set; } | Hämtar eller ställer in by-line titel. |
| [CaptionWriter](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/captionwriter) { get; set; } | Hämtar eller ställer in författaren/redigeraren. |
| [Category](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/category) { get; set; } | Hämtar eller ställer in kategorin. Begränsat till 3 7-bitars ASCII-tecken. |
| [City](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/city) { get; set; } | Får eller ställer in staden. |
| [ColorMode](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/colormode) { get; set; } | Hämtar eller ställer in färgläget. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Country](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/country) { get; set; } | Hämtar eller ställer in landet. |
| [Credit](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/credit) { get; set; } | Får eller sätter krediten. |
| [DateCreated](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/datecreated) { get; set; } | Hämtar eller ställer in datumet då det intellektuella innehållet i dokumentet skapades. |
| [Headline](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/headline) { get; set; } | Får eller sätter rubriken. |
| [History](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/history) { get; set; } | Hämtar eller ställer in historiken som visas i FileInfo-panelen, om den är aktiverad i programinställningarna. |
| [IccProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/iccprofile) { get; set; } | Hämtar eller ställer in färgprofilen, som AppleRGB, AdobeRGB1998. |
| [Instructions](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/instructions) { get; set; } | Hämtar eller ställer in specialinstruktionerna. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Hämtar namnutrymmets URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Hämtar xmlns-prefixet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/source) { get; set; } | Hämtar eller ställer in källan. |
| [State](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/state) { get; set; } | Hämtar eller ställer in provinsen/staten. |
| [SupplementalCategories](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/supplementalcategories) { get; set; } | Hämtar eller ställer in de kompletterande kategorierna. |
| [TransmissionReference](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/transmissionreference) { get; set; } | Hämtar eller ställer in den ursprungliga överföringsreferensen. |
| [Urgency](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgency) { get; set; } | Hämtar eller ställer in brådska. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/set#set_7)(string, string) | Anger strängegenskap. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Ställer in värdet som ärvs från[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Ställer in värdet som ärvs från[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Ställer in värdet som ärvs från[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [UrgencyMax](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgencymax) | Brådskande maxvärde. |
| const [UrgencyMin](../../groupdocs.metadata.standards.xmp.schemes/xmpphotoshoppackage/urgencymin) | Minsta brådskande värde. |

### Se även

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
