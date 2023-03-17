---
title: XmpTimecode
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een tijdcodewaarde in een video.
type: docs
weight: 3600
url: /nl/net/groupdocs.metadata.standards.xmp/xmptimecode/
---
## XmpTimecode class

Vertegenwoordigt een tijdcodewaarde in een video.

```csharp
public sealed class XmpTimecode : XmpComplexType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpTimecode](xmptimecode#constructor)() | Initialiseert een nieuw exemplaar van het[`XmpTimecode`](../xmptimecode) klasse. |
| [XmpTimecode](xmptimecode#constructor_1)(XmpTimeFormat, string) | Initialiseert een nieuw exemplaar van het[`XmpTimecode`](../xmptimecode) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Haalt de naamruimte-URI's op die worden gebruikt in de[`XmpComplexType`](../xmpcomplextype) instantie. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Haalt de naamruimtevoorvoegsels op die worden gebruikt in de[`XmpComplexType`](../xmpcomplextype) instantie. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [TimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/timeformat) { get; set; } | Haalt of stelt het formaat in dat wordt gebruikt in de tijdswaarde. |
| [TimeValue](../../groupdocs.metadata.standards.xmp/xmptimecode/timevalue) { get; set; } | Haalt de tijdwaarde op of stelt deze in in het opgegeven formaat. Tijdwaarden gebruiken een dubbele punt als scheidingsteken in alle notaties behalve 2997drop en 5994drop, die een puntkomma gebruiken. De vier velden geven uren, minuten, seconden en frames aan: hh:mm:ss:ff |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Haalt de naamruimte-URI op die is gekoppeld aan het opgegeven voorvoegsel. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Retourneert een tekenreeks die een waarde bevat in XMP-indeling. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [SetTimeFormat](../../groupdocs.metadata.standards.xmp/xmptimecode/settimeformat)(XmpTimeFormat) | Stelt het tijdformaat in. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Zie ook

* class [XmpComplexType](../xmpcomplextype)
* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
