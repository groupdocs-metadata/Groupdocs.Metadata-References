---
title: IptcApplicationRecord
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een IPTCtoepassingsrecord.
type: docs
weight: 2880
url: /nl/net/groupdocs.metadata.standards.iptc/iptcapplicationrecord/
---
## IptcApplicationRecord class

Vertegenwoordigt een IPTC-toepassingsrecord.

```csharp
public sealed class IptcApplicationRecord : IptcRecord
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [IptcApplicationRecord](iptcapplicationrecord)() | Initialiseert een nieuw exemplaar van het[`IptcApplicationRecord`](../iptcapplicationrecord) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllKeywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/allkeywords) { get; set; } | Haalt of stelt de trefwoorden in. |
| [ByLine](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/byline) { get; set; } | Haalt of stelt de naam in van de maker van het object, bijvoorbeeld schrijver, fotograaf of grafisch kunstenaar. |
| [ByLines](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylines) { get; set; } | Haalt of stelt de namen in van de makers van het object, bijvoorbeeld schrijver, fotograaf of graficus. |
| [ByLineTitle](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitle) { get; set; } | Haalt of stelt de titel in van de maker of makers van het object. |
| [ByLineTitles](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/bylinetitles) { get; set; } | Haalt of stelt de titels in van de maker of makers van het object. |
| [CaptionAbstract](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/captionabstract) { get; set; } | Haalt een tekstuele beschrijving van het object op of stelt deze in, met name wanneer het object geen tekst is. |
| [City](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/city) { get; set; } | Haalt of stelt de stad in. |
| [Contact](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contact) { get; set; } | Krijgt of stelt informatie in over de persoon of organisatie die verdere achtergrondinformatie over het object kan geven. |
| [Contacts](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contacts) { get; set; } | Krijgt of stelt informatie in over de persoon of organisatie die verdere achtergrondinformatie over het object kan geven. |
| [ContentLocationCode](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcode) { get; set; } | Haalt de inhoudslocatiecode op of stelt deze in. |
| [ContentLocationCodes](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationcodes) { get; set; } | Haalt de locatiecodes van de inhoud op of stelt deze in. |
| [ContentLocationName](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationname) { get; set; } | Haalt de locatienaam van de inhoud op of stelt deze in. |
| [ContentLocationNames](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/contentlocationnames) { get; set; } | Haalt of stelt de locatienamen van de inhoud in. |
| [CopyrightNotice](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/copyrightnotice) { get; set; } | Krijgt of stelt de copyrightmelding in. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Credit](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/credit) { get; set; } | Krijgt of stelt informatie in over de aanbieder van het object, niet noodzakelijkerwijs de eigenaar/maker. |
| [DateCreated](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/datecreated) { get; set; } | Haalt of stelt de datum in waarop de intellectuele inhoud van het object is gemaakt. |
| [Headline](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/headline) { get; set; } | Hiermee wordt een publiceerbaar item opgehaald of ingesteld met een samenvatting van de inhoud van het object. |
| [Item](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/item) { get; } | Krijgt de[`IptcDataSet`](../iptcdataset) met het opgegeven nummer. (3 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Keywords](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/keywords) { get; set; } | Haalt of stelt de trefwoorden in. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [ProgramVersion](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/programversion) { get; set; } | Haalt of stelt de programmaversie in. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcrecord/recordnumber) { get; } | Krijgt het recordnummer. |
| [ReferenceDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedate) { get; set; } | Haalt of stelt de datum in van een eerdere enveloppe waarnaar het huidige object verwijst. |
| [ReferenceDates](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/referencedates) { get; } | Haalt de datums op van een eerdere envelop waarnaar het huidige object verwijst. |
| [ReleaseDate](../../groupdocs.metadata.standards.iptc/iptcapplicationrecord/releasedate) { get; set; } | Haalt of stelt de releasedatum in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Voegt bekende metadata-eigenschappen toe die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bepaalt of het pakket een metadata-eigenschap bevat met de opgegeven naam. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Zoekt de metadata-eigenschappen die voldoen aan het opgegeven predikaat. De zoekopdracht is recursief, dus het heeft ook invloed op alle geneste pakketten. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Retourneert een enumerator die de verzameling herhaalt. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Verwijdert metadata-eigenschappen die voldoen aan het opgegeven predikaat. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Verwijdert beschrijfbare metadata-eigenschappen uit het pakket. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Stelt bekende metadata-eigenschappen in die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. Deze methode is een combinatie van[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) En[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Als een bestaande eigenschap voldoet aan het predikaat, wordt de waarde bijgewerkt. Als er een bekende eigenschap ontbreekt in het pakket die voldoet aan het predikaat, wordt deze aan het pakket toegevoegd. |
| [ToList](../../groupdocs.metadata.standards.iptc/iptcrecord/tolist)() | Maakt een lijst van het pakket. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Opmerkingen

**Kom meer te weten**

* [Werken met IPTC IIM-metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### Zie ook

* class [IptcRecord](../iptcrecord)
* naamruimte [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
