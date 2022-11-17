---
title: XmpPdfPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Anger egenskaper som används med Adobe PDFdokument.
type: docs
weight: 3190
url: /sv/net/groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/
---
## XmpPdfPackage class

Anger egenskaper som används med Adobe PDF-dokument.

```csharp
public sealed class XmpPdfPackage : XmpPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpPdfPackage](xmppdfpackage)() | Initierar en ny instans av[`XmpPdfPackage`](../xmppdfpackage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [IsTrapped](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/istrapped) { get; set; } | Hämtar eller ställer in ett värde som anger om dokumentet har fångats. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Keywords](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/keywords) { get; set; } | Hämtar eller ställer in sökorden. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Hämtar namnutrymmets URI. |
| [PdfVersion](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/pdfversion) { get; set; } | Hämtar eller ställer in PDF-filversionen. Till exempel 1.0, 1.3 och så vidare. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Hämtar xmlns-prefixet. |
| [Producer](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/producer) { get; set; } | Hämtar eller ställer in namnet på verktyget som skapade PDF-dokumentet. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmppdfpackage/set#set_7)(string, string) | Anger strängegenskap. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | Ställer in värdet som ärvs från[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Ställer in värdet som ärvs från[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Ställer in värdet som ärvs från[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Se även

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
