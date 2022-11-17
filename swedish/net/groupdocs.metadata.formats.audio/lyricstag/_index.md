---
title: LyricsTag
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar Lyrics3 v2.00 metadata. Mer information finns påhttp//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /sv/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Representerar Lyrics3 v2.00 metadata. Mer information finns påhttp://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LyricsTag](lyricstag)() | Initierar en ny instans av[`LyricsTag`](../lyricstag) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | Hämtar eller ställer in ytterligare information. Detta värde representeras av INF-fältet. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | Hämtar eller ställer in albumnamnet. Detta värde representeras av EAL-fältet. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | Hämtar eller ställer in artistnamnet. Detta värde representeras av EAR-fältet. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | Hämtar eller ställer in författaren. Detta värde representeras av AUT-fältet. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | Hämtar eller ställer in sångtexten. Detta värde representeras av LYR-fältet. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | Hämtar eller ställer in spårtiteln. Detta värde representeras av ETT-fältet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | Hämtar värdet på fältet med angivet id. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | Tar bort fältet med angivet id. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | Lägger till eller ersätter det angivna fältet Lyrics3. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | Skapar en lista från paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

Lyrics3 v2.00 använder fält för att representera information. Datan i ett fält kan bestå av ASCII-tecken i intervallet 01 till 254 enligt standarden. Eftersom ASCII-teckenkartan endast är definierad från 00 till 128 ISO-8859- 1 kan antas. Numeriska fält är 5 eller 6 tecken långa, beroende på plats, och är utfyllda med nollor.

**Läs mer**

* [Hantera Lyrics-taggen](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### Exempel

Detta kodexempel visar hur man läser Lyrics-taggen från en MP3-fil.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // Alternativt kan du gå igenom en fullständig lista med taggfält
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
