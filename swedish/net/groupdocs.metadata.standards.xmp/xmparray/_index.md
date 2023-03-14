---
title: XmpArray
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar basabstraktion för XMParray.
type: docs
weight: 3250
url: /sv/net/groupdocs.metadata.standards.xmp/xmparray/
---
## XmpArray class

Representerar basabstraktion för XMP-array.

```csharp
public class XmpArray : XmpValueBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpArray](xmparray#constructor)(XmpArrayType, XmpComplexType[]) | Initierar en ny instans av[`XmpArray`](../xmparray) class. |
| [XmpArray](xmparray#constructor_1)(XmpArrayType, XmpValueBase[]) | Initierar en ny instans av[`XmpArray`](../xmparray) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | Hämtar typen av XMP-array. |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Får råvärdet. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Får[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_2)(DateTime[], XmpArrayType) | Skapar en[`XmpArray`](../xmparray) instans bildar en datummatris. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from)(double[], XmpArrayType) | Skapar en[`XmpArray`](../xmparray) instans bildar en dubbel array. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_1)(int[], XmpArrayType) | Skapar en[`XmpArray`](../xmparray) instans bildar en heltalsmatris. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_3)(string[], XmpArrayType) | Skapar en[`XmpArray`](../xmparray) instans bildar en strängarray. |
| static [From&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/from#from_4)(T[], XmpArrayType) | Skapar en[`XmpArray`](../xmparray)instans bildar en matris av[`XmpComplexType`](../xmpcomplextype) . |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Extraherar egenskapsvärdet med en anpassad[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmparray/getxmprepresentation)() | Konverterar XMP-värdet till xml-representationen. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Konverterar egenskapsvärdet till en array av den angivna typen. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Konverterar egenskapsvärdet till en referenstyp. |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | Konverterar[`XmpArray`](../xmparray) till en plattformsspecifik array. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Returnerar en sträng som representerar egenskapsvärdet. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Konverterar egenskapsvärdet till en värdetyp. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Konverterar egenskapsvärdet till en värdetyp. |

### Se även

* class [XmpValueBase](../xmpvaluebase)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->