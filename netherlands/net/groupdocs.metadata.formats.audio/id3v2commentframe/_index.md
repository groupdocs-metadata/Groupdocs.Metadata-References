---
title: ID3V2CommentFrame
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een COMMframe in eenID3V2Tag./id3v2tag .
type: docs
weight: 440
url: /nl/net/groupdocs.metadata.formats.audio/id3v2commentframe/
---
## ID3V2CommentFrame class

Vertegenwoordigt een COMM-frame in een[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2CommentFrame : ID3V2TagFrame
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ID3V2CommentFrame](id3v2commentframe)(ID3V2EncodingType, string, string, string) | Initialiseert een nieuw exemplaar van het[`ID3V2CommentFrame`](../id3v2commentframe) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CommentEncoding](../../groupdocs.metadata.formats.audio/id3v2commentframe/commentencoding) { get; } | Haalt de codering van de opmerking op. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Haalt de framegegevens op. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Haalt de framevlaggen op. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Haalt de id van het frame op (vier tekens die overeenkomen met het patroon [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Language](../../groupdocs.metadata.formats.audio/id3v2commentframe/language) { get; } | Krijgt de taal van de opmerking (3 tekens). |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [ShortContentDescription](../../groupdocs.metadata.formats.audio/id3v2commentframe/shortcontentdescription) { get; } | Krijgt de korte inhoudsbeschrijving. |
| [Text](../../groupdocs.metadata.formats.audio/id3v2commentframe/text) { get; } | Haalt de tekst van de opmerking op. |

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

### Opmerkingen

Dit frame is bedoeld voor alle soorten volledige tekstinformatie die niet in een ander frame past.

**Kom meer te weten**

* [Omgaan met de ID3v2-tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Zie ook

* class [ID3V2TagFrame](../id3v2tagframe)
* naamruimte [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
