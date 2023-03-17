---
title: MpegAudioPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Vertegenwoordigt MPEGaudiometadata.
type: docs
weight: 2150
url: /nl/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

Vertegenwoordigt MPEG-audiometadata.

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | Initialiseert een nieuw exemplaar van het[`MpegAudioPackage`](../mpegaudiopackage) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | Krijgt de bitsnelheid. |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | Krijgt de kanaalmodus. |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | Krijgt de copyright-bit. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Haalt het aantal metadata-eigenschappen op. |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | Krijgt de nadruk. |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | Haalt de frequentie op. |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | Haalt de header-offset op. |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | Krijgt de originele bit. |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | Krijgt`WAAR` indien beveiligd. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Krijgt de[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) met de opgegeven naam. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Haalt een verzameling van de metadata-eigenschapsnamen op. |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | Haalt de laagbeschrijving op. Voor een MP3-audio is het '3'. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Haalt het metadatatype op. |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | Haalt de modusuitbreidingsbits op. |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | Haalt de MPEG-audioversie op. Kan MPEG-1, MPEG-2 etc. zijn |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | Haalt het opvulbit op. |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | Krijgt een waarde die aangeeft of [private bit]. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Haalt een verzameling descriptors op die informatie bevatten over eigenschappen die toegankelijk zijn via de GroupDocs.Metadata-zoekmachine. |

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

### Voorbeelden

Dit voorbeeld laat zien hoe u MPEG-audiometagegevens van een MP3-bestand kunt lezen.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    Console.WriteLine(root.MpegAudioPackage.Bitrate);
    Console.WriteLine(root.MpegAudioPackage.ChannelMode);
    Console.WriteLine(root.MpegAudioPackage.Emphasis);
    Console.WriteLine(root.MpegAudioPackage.Frequency);
    Console.WriteLine(root.MpegAudioPackage.HeaderPosition);
    Console.WriteLine(root.MpegAudioPackage.Layer);

    // ...
}
```

### Zie ook

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* naamruimte [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* montage [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
