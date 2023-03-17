---
title: XmpResourceRef
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een meerdelige verwijzing naar een resource. Wordt gebruikt om eerdere versies originelen van weergaven originelen van afgeleide documenten enzovoort aan te duiden.
type: docs
weight: 3550
url: /nl/net/groupdocs.metadata.standards.xmp/xmpresourceref/
---
## XmpResourceRef class

Vertegenwoordigt een meerdelige verwijzing naar een resource. Wordt gebruikt om eerdere versies, originelen van weergaven, originelen van afgeleide documenten, enzovoort aan te duiden.

```csharp
public sealed class XmpResourceRef : XmpComplexType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpResourceRef](xmpresourceref)() | Initialiseert een nieuw exemplaar van het[`XmpResourceRef`](../xmpresourceref) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternatePaths](../../groupdocs.metadata.standards.xmp/xmpresourceref/alternatepaths) { get; set; } | Haalt of stelt de fallback-bestandspaden of URL's van de bron waarnaar wordt verwezen in. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [DocumentID](../../groupdocs.metadata.standards.xmp/xmpresourceref/documentid) { get; set; } | Haalt de waarde op van de eigenschap xmpMM:DocumentID van de bron waarnaar wordt verwezen of stelt deze in. |
| [FilePath](../../groupdocs.metadata.standards.xmp/xmpresourceref/filepath) { get; set; } | Hiermee wordt het bestandspad of de URL van de bron waarnaar wordt verwezen, opgehaald of ingesteld. |
| [InstanceID](../../groupdocs.metadata.standards.xmp/xmpresourceref/instanceid) { get; set; } | Haalt de waarde op van de eigenschap xmpMM:InstanceID van de bron waarnaar wordt verwezen of stelt deze in. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [LastModifyDate](../../groupdocs.metadata.standards.xmp/xmpresourceref/lastmodifydate) { get; set; } | Haalt of stelt de waarde in van stEvt:when voor de laatste keer dat het bestand werd geschreven. |
| [Manager](../../groupdocs.metadata.standards.xmp/xmpresourceref/manager) { get; set; } | Haalt de xmpMM:Manager van de resource waarnaar wordt verwezen op of stelt deze in. |
| [ManagerVariant](../../groupdocs.metadata.standards.xmp/xmpresourceref/managervariant) { get; set; } | Haalt de xmpMM:Manager van de resource waarnaar wordt verwezen op of stelt deze in. |
| [ManageTo](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageto) { get; set; } | Hiermee wordt xmpMM:ManageTo van de bron waarnaar wordt verwezen, opgehaald of ingesteld. |
| [ManageUI](../../groupdocs.metadata.standards.xmp/xmpresourceref/manageui) { get; set; } | Haalt de xmpMM:ManageUI. van de resource waarnaar wordt verwezen op of stelt deze in |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Haalt de naamruimte-URI's op die worden gebruikt in de[`XmpComplexType`](../xmpcomplextype) instantie. |
| [PartMapping](../../groupdocs.metadata.standards.xmp/xmpresourceref/partmapping) { get; set; } | Haalt of stelt de naam of URI in van een toewijzingsfunctie die wordt gebruikt om de fromPart toe te wijzen aan de toPart. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Haalt de naamruimtevoorvoegsels op die worden gebruikt in de[`XmpComplexType`](../xmpcomplextype) instantie. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [RenditionClass](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionclass) { get; set; } | Haalt de waarde van de eigenschap xmpMM:RenditionClass op uit de bron waarnaar wordt verwezen. |
| [RenditionParams](../../groupdocs.metadata.standards.xmp/xmpresourceref/renditionparams) { get; set; } | Haalt de waarde op van de eigenschap xmpMM:RenditionParams van de bron waarnaar wordt verwezen of stelt deze in. |
| [VersionID](../../groupdocs.metadata.standards.xmp/xmpresourceref/versionid) { get; set; } | Haalt de waarde op van de eigenschap xmpMM:RenditionParams van de bron waarnaar wordt verwezen of stelt deze in. |

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
