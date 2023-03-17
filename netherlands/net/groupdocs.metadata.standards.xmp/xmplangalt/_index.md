---
title: XmpLangAlt
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt XMPtaalalternatief.
type: docs
weight: 3450
url: /nl/net/groupdocs.metadata.standards.xmp/xmplangalt/
---
## XmpLangAlt class

Vertegenwoordigt XMP-taalalternatief.

Een alternatieve reeks eenvoudige tekstitems. Taalalternatieven vergemakkelijken de selectie van een eenvoudig tekstitem op basis van een gewenste taal. Elk array-item heeft een xml:lang-kwalificatie. Elke xml:lang-waarde zal uniek zijn onder de items.

```csharp
public sealed class XmpLangAlt : XmpArray
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpLangAlt](xmplangalt#constructor)(IDictionary&lt;string, string&gt;) | Initialiseert een nieuw exemplaar van het[`XmpLangAlt`](../xmplangalt) klasse. |
| [XmpLangAlt](xmplangalt#constructor_1)(string) | Initialiseert een nieuw exemplaar van het[`XmpLangAlt`](../xmplangalt) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | Haalt het type van de XMP-array op. |
| [Item](../../groupdocs.metadata.standards.xmp/xmplangalt/item) { get; } | Haalt de waarde op die is gekoppeld aan de opgegeven taal. |
| [Languages](../../groupdocs.metadata.standards.xmp/xmplangalt/languages) { get; } | Haalt een array op van alle talen die zijn geregistreerd in de instantie van[`XmpLangAlt`](../xmplangalt) . |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | Krijgt de ruwe waarde. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | Krijgt de[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | Extraheert de eigenschapswaarde met behulp van een custom[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| [Contains](../../groupdocs.metadata.standards.xmp/xmplangalt/contains)(string) | Bepaalt of de[`XmpLangAlt`](../xmplangalt) bevat de opgegeven taal. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmplangalt/getxmprepresentation)() | Converteert XMP-waarde naar de xml-representatie. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | Converteert de eigenschapswaarde naar een array van het opgegeven type. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | Converteert de eigenschapswaarde naar een referentietype. |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | Converteert de[`XmpArray`](../xmparray) naar een platformspecifieke array. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | Retourneert een tekenreeks die de waarde van de eigenschap vertegenwoordigt. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | Converteert de eigenschapswaarde naar een waardetype. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | Converteert de eigenschapswaarde naar een waardetype. |

### Zie ook

* class [XmpArray](../xmparray)
* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->