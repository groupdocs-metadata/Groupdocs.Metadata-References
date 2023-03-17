---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt het Dublin Coreschema.
type: docs
weight: 3120
url: /nl/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

Vertegenwoordigt het Dublin Core-schema.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | Initialiseert een nieuw exemplaar van het[`XmpDublinCorePackage`](../xmpdublincorepackage) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | Haalt of stelt een array van de bijdragers in. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | Haalt of stelt de omvang of reikwijdte van de bron in. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | Haalt of stelt een array van de makers in. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | Hiermee wordt een reeks datums opgehaald of ingesteld die zijn gekoppeld aan een gebeurtenis in de levenscyclus van de bron. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | Haalt of stelt een reeks tekstuele beschrijvingen van de inhoud van de bron op, gegeven in verschillende talen. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | Haalt het MIME-type van de bron op of stelt het in. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | Hiermee wordt een tekenreekswaarde opgehaald of ingesteld die een ondubbelzinnige verwijzing naar de bron vertegenwoordigt binnen een bepaalde context. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | Haalt of stelt een reeks talen in die worden gebruikt in de inhoud van de bron. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Haalt de naamruimte-URI op. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Haalt het xmlns-voorvoegsel op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | Haalt of stelt een reeks uitgevers in die de bron beschikbaar hebben gemaakt. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | Haalt of stelt een array van de gerelateerde bronnen in. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | Haalt of stelt een reeks van de informele rechtenverklaringen op, gegeven in verschillende talen. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | Haalt of stelt de gerelateerde bron in waarvan de beschreven bron is afgeleid. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | Haalt of stelt een reeks beschrijvende zinnen of trefwoorden in die de inhoud van de bron specificeren. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | Haalt of stelt de titel of naam van de bron in, gegeven in verschillende talen. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | Hiermee wordt een reeks tekenreekswaarden opgehaald of ingesteld die de aard of het genre van de bron vertegenwoordigt. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Haalt de XML-naamruimte op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Verwijdert alle XMP-eigenschappen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converteert de XMP-waarde naar de XML-weergave. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Verwijdert de eigenschap met de opgegeven naam. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Stelt booleaanse eigenschap in. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | setsDateTime eigendom. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Stelt dubbele eigenschap in. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Stelt integer-eigenschap in. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Stelt tekenreekseigenschap in. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | Stelt de waarde in die is overgenomen van[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Stelt de waarde in die is overgenomen van[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Stelt de waarde in die is overgenomen van[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | Stelt een enkele bijdrager van de bron in. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | Stelt een enkele maker van de bron in. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | Stelt een enkele datum in die aan de bron is gekoppeld. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | Stelt de bronbeschrijving in, gegeven in een enkele taal. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | Stelt een enkele taal in die aan de bron is gekoppeld. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | Stelt een enkele uitgever van de bron in. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | Stelt een enkele gerelateerde bron in. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | Stelt de bronrechten in, gegeven in een enkele taal. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | Stelt een enkel onderwerp van de bron in. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | Stelt de brontitel in, gegeven in een enkele taal. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | Stelt een enkel type van de bron in. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

Zie voor meer informatie: http://dublincore.org/documents/usageguide/elements.shtml.

### Zie ook

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* naamruimte [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
