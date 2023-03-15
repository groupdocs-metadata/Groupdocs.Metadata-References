---
title: XmpMeta
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt xmpmeta. Optioneel. Het doel van dit element is om XMPmetadata te identificeren in algemene XMLtekst die mogelijk ander nietXMPgebruik van RDF. bevat
type: docs
weight: 3460
url: /nl/net/groupdocs.metadata.standards.xmp/xmpmeta/
---
## XmpMeta class

Vertegenwoordigt xmpmeta. Optioneel. Het doel van dit element is om XMP-metadata te identificeren in algemene XML-tekst die mogelijk ander niet-XMP-gebruik van RDF. bevat

```csharp
public sealed class XmpMeta : XmpElementBase, IXmpType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpMeta](xmpmeta)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AdobeXmpToolkit](../../groupdocs.metadata.standards.xmp/xmpmeta/adobexmptoolkit) { get; } | Krijgt Adobe XMP-toolkitversie. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [ClearAttributes](../../groupdocs.metadata.standards.xmp/xmpelementbase/clearattributes)() | Verwijdert alle attributen. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| [ContainsAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/containsattribute)(string) | Bepaalt of het element een specifiek attribuut bevat. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetAttribute](../../groupdocs.metadata.standards.xmp/xmpelementbase/getattribute)(string) | Krijgt het attribuut. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpmeta/getxmprepresentation)() | Converteert XMP-waarde naar de xml-representatie. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| override [SetAttribute](../../groupdocs.metadata.standards.xmp/xmpmeta/setattribute)(string, string) | Voegt een attribuut toe. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Zie ook

* class [XmpElementBase](../xmpelementbase)
* interface [IXmpType](../ixmptype)
* naamruimte [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
