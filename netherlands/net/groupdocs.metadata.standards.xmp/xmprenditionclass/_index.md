---
title: XmpRenditionClass
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt XMP RenditionClass.
type: docs
weight: 3530
url: /nl/net/groupdocs.metadata.standards.xmp/xmprenditionclass/
---
## XmpRenditionClass class

Vertegenwoordigt XMP RenditionClass.

```csharp
public sealed class XmpRenditionClass : XmpText
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpRenditionClass](xmprenditionclass)(params string[]) | Initialiseert een nieuw exemplaar van het[`XmpRenditionClass`](../xmprenditionclass) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Krijgt de ruwe waarde. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Krijgt de[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |
| [Value](../../groupdocs.metadata.standards.xmp/xmptext/value) { get; } | Krijgt de waarde. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Extraheert de eigenschapswaarde met behulp van een custom[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptext/getxmprepresentation)() | Retourneert een tekenreeks die een waarde bevat in XMP-indeling. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Converteert de eigenschapswaarde naar een array van het opgegeven type. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Converteert de eigenschapswaarde naar een referentietype. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Retourneert een tekenreeks die de waarde van de eigenschap vertegenwoordigt. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Converteert de eigenschapswaarde naar een waardetype. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Converteert de eigenschapswaarde naar een waardetype. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [Default](../../groupdocs.metadata.standards.xmp/xmprenditionclass/default) | De hoofdresource; geen extra tokens toegestaan. |
| const [Draft](../../groupdocs.metadata.standards.xmp/xmprenditionclass/draft) | Een weergave van een recensie. |
| const [LowRes](../../groupdocs.metadata.standards.xmp/xmprenditionclass/lowres) | Een full-size stand-in met lage resolutie. |
| const [Proof](../../groupdocs.metadata.standards.xmp/xmprenditionclass/proof) | Een beoordelingsbewijs. |
| const [Screen](../../groupdocs.metadata.standards.xmp/xmprenditionclass/screen) | Schermresolutie of webweergave. |
| const [Thumbnail](../../groupdocs.metadata.standards.xmp/xmprenditionclass/thumbnail) | Een vereenvoudigd of verkleind voorbeeld. Extra tokens kunnen kenmerken geven. De aanbevolen volgorde is thumbnail:format:size:colorspace. |

### Zie ook

* class [XmpText](../xmptext)
* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
