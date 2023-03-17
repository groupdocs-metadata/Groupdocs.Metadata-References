---
title: XmpJob
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt Job.
type: docs
weight: 3440
url: /nl/net/groupdocs.metadata.standards.xmp/xmpjob/
---
## XmpJob class

Vertegenwoordigt Job.

```csharp
public sealed class XmpJob : XmpComplexType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpJob](xmpjob)() | Initialiseert een nieuw exemplaar van het[`XmpJob`](../xmpjob) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [ID](../../groupdocs.metadata.standards.xmp/xmpjob/id) { get; set; } | Krijgt of stelt unieke id voor de taak in. Dit veld is een verwijzing naar een extern taakbeheersysteem. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [Name](../../groupdocs.metadata.standards.xmp/xmpjob/name) { get; set; } | Krijgt of stelt de informele naam van de taak in. Deze naam is voor gebruikersweergave en informele systemen. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Haalt de naamruimte-URI's op die worden gebruikt in de[`XmpComplexType`](../xmpcomplextype) instantie. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Haalt de naamruimtevoorvoegsels op die worden gebruikt in de[`XmpComplexType`](../xmpcomplextype) instantie. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Url](../../groupdocs.metadata.standards.xmp/xmpjob/url) { get; set; } | Haalt een bestands-URL op of stelt deze in die verwijst naar een extern taakbeheerbestand. |

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
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Zie ook

* class [XmpComplexType](../xmpcomplextype)
* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
