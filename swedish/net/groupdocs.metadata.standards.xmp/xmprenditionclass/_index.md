---
title: XmpRenditionClass
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar XMP RenditionClass.
type: docs
weight: 3530
url: /sv/net/groupdocs.metadata.standards.xmp/xmprenditionclass/
---
## XmpRenditionClass class

Representerar XMP RenditionClass.

```csharp
public sealed class XmpRenditionClass : XmpText
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpRenditionClass](xmprenditionclass)(params string[]) | Initierar en ny instans av[`XmpRenditionClass`](../xmprenditionclass) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Får råvärdet. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Får[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |
| [Value](../../groupdocs.metadata.standards.xmp/xmptext/value) { get; } | Hämtar värdet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Extraherar egenskapsvärdet med en anpassad[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptext/getxmprepresentation)() | Returnerar stränginnehållet värde i XMP-format. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Konverterar egenskapsvärdet till en array av den angivna typen. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Konverterar egenskapsvärdet till en referenstyp. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Returnerar en sträng som representerar egenskapsvärdet. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Konverterar egenskapsvärdet till en värdetyp. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Konverterar egenskapsvärdet till en värdetyp. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [Default](../../groupdocs.metadata.standards.xmp/xmprenditionclass/default) | Huvudresursen; inga ytterligare tokens tillåtna. |
| const [Draft](../../groupdocs.metadata.standards.xmp/xmprenditionclass/draft) | En recensionsversion. |
| const [LowRes](../../groupdocs.metadata.standards.xmp/xmprenditionclass/lowres) | En lågupplöst, full storlek stand-in. |
| const [Proof](../../groupdocs.metadata.standards.xmp/xmprenditionclass/proof) | Ett recensionsbevis. |
| const [Screen](../../groupdocs.metadata.standards.xmp/xmprenditionclass/screen) | Skärmupplösning eller webbåtergivning. |
| const [Thumbnail](../../groupdocs.metadata.standards.xmp/xmprenditionclass/thumbnail) | En förenklad eller reducerad förhandsvisning. Ytterligare tokens kan ge egenskaper. Den rekommenderade ordningen är thumbnail:format:size:colorspace. |

### Se även

* class [XmpText](../xmptext)
* namnutrymme [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
