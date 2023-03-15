---
title: RiffInfoPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt het metadatapakket met eigenschappen die zijn geëxtraheerd uit het RIFF INFOblok.
type: docs
weight: 2220
url: /nl/net/groupdocs.metadata.formats.riff/riffinfopackage/
---
## RiffInfoPackage class

Vertegenwoordigt het metadatapakket met eigenschappen die zijn geëxtraheerd uit het RIFF INFO-blok.

```csharp
public sealed class RiffInfoPackage : CustomPackage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Artist](../../groupdocs.metadata.formats.riff/riffinfopackage/artist) { get; } | Krijgt de artiest van het originele onderwerp van het bestand. |
| [Comment](../../groupdocs.metadata.formats.riff/riffinfopackage/comment) { get; } | Krijgt de opmerking over het bestand of het onderwerp van het bestand. |
| [Copyright](../../groupdocs.metadata.formats.riff/riffinfopackage/copyright) { get; } | Haalt de copyrightinformatie op voor het bestand. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [CreationDate](../../groupdocs.metadata.formats.riff/riffinfopackage/creationdate) { get; } | Krijgt de datum waarop het onderwerp van het bestand is gemaakt. |
| [Engineer](../../groupdocs.metadata.formats.riff/riffinfopackage/engineer) { get; } | Krijgt de naam van de technicus die aan het bestand heeft gewerkt. |
| [Genre](../../groupdocs.metadata.formats.riff/riffinfopackage/genre) { get; } | Krijgt het genre van het originele werk. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Keywords](../../groupdocs.metadata.formats.riff/riffinfopackage/keywords) { get; } | Haalt de trefwoorden op die verwijzen naar het bestand of het onderwerp van het bestand. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [Name](../../groupdocs.metadata.formats.riff/riffinfopackage/name) { get; } | Krijgt de titel van het onderwerp van het bestand. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Software](../../groupdocs.metadata.formats.riff/riffinfopackage/software) { get; } | Haalt de naam op van het softwarepakket dat is gebruikt om het bestand te maken. |
| [Source](../../groupdocs.metadata.formats.riff/riffinfopackage/source) { get; } | Krijgt de naam van de persoon of organisatie die het oorspronkelijke onderwerp van het bestand heeft aangeleverd. |
| [Subject](../../groupdocs.metadata.formats.riff/riffinfopackage/subject) { get; } | Krijgt een beschrijving van de bestandsinhoud, zoals "Luchtfoto van Seattle." |
| [Technician](../../groupdocs.metadata.formats.riff/riffinfopackage/technician) { get; } | Haalt de technicus op die het onderwerpbestand heeft gedigitaliseerd. |

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
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Werkt bekende metadata-eigenschappen bij die voldoen aan het opgegeven predikaat. De bewerking is recursief, dus het is ook van invloed op alle geneste pakketten. |

### Zie ook

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Formats.Riff](../../groupdocs.metadata.formats.riff)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
