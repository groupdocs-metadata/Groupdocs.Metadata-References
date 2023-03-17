---
title: ID3V2UserDefinedUrlLinkFrame
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt een WXXXframe in eenID3V2Tag./id3v2tag .
type: docs
weight: 550
url: /nl/net/groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/
---
## ID3V2UserDefinedUrlLinkFrame class

Vertegenwoordigt een WXXX-frame in een[`ID3V2Tag`](../id3v2tag) .

```csharp
public sealed class ID3V2UserDefinedUrlLinkFrame : ID3V2TagFrame
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ID3V2UserDefinedUrlLinkFrame](id3v2userdefinedurllinkframe#constructor_1)(string, string) | Initialiseert een nieuw exemplaar van het[`ID3V2UserDefinedUrlLinkFrame`](../id3v2userdefinedurllinkframe) klasse. |
| [ID3V2UserDefinedUrlLinkFrame](id3v2userdefinedurllinkframe#constructor)(ID3V2EncodingType, string, string) | Initialiseert een nieuw exemplaar van het[`ID3V2UserDefinedUrlLinkFrame`](../id3v2userdefinedurllinkframe) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Data](../../groupdocs.metadata.formats.audio/id3v2tagframe/data) { get; } | Haalt de framegegevens op. |
| [Description](../../groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/description) { get; } | Krijgt de beschrijving. |
| [Encoding](../../groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/encoding) { get; } | Haalt de codering van het frame op. |
| [Flags](../../groupdocs.metadata.formats.audio/id3v2tagframe/flags) { get; } | Haalt de framevlaggen op. |
| [Id](../../groupdocs.metadata.formats.audio/id3v2tagframe/id) { get; } | Haalt de id van het frame op (vier tekens die overeenkomen met het patroon [A-Z0-9]). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |
| [Url](../../groupdocs.metadata.formats.audio/id3v2userdefinedurllinkframe/url) { get; } | Krijgt de URL. |

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

**Kom meer te weten**

* [Omgaan met de ID3v2-tag](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### Zie ook

* class [ID3V2TagFrame](../id3v2tagframe)
* naamruimte [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
