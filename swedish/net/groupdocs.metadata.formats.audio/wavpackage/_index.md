---
title: WavPackage
second_title: GroupDocs.Metadata for .NET API-referens
description: Representerar ett inbyggt metadatapaket i en WAVljudfil.
type: docs
weight: 590
url: /sv/net/groupdocs.metadata.formats.audio/wavpackage/
---
## WavPackage class

Representerar ett inbyggt metadatapaket i en WAV-ljudfil.

```csharp
public sealed class WavPackage : CustomPackage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WavPackage](wavpackage)() | Initierar en ny instans av[`WavPackage`](../wavpackage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AudioFormat](../../groupdocs.metadata.formats.audio/wavpackage/audioformat) { get; } | Hämtar ljudformatet. PCM = 1 (dvs linjär kvantisering). Andra värden än 1 indikerar någon form av komprimering. |
| [BitsPerSample](../../groupdocs.metadata.formats.audio/wavpackage/bitspersample) { get; } | Hämtar bitarna per sampelvärde. |
| [BlockAlign](../../groupdocs.metadata.formats.audio/wavpackage/blockalign) { get; } | Får blocket align. |
| [ByteRate](../../groupdocs.metadata.formats.audio/wavpackage/byterate) { get; } | Hämtar bytehastigheten. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Hämtar antalet metadataegenskaper. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Får[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) med det angivna namnet. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Hämtar en samling av metadataegenskapsnamnen. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Hämtar metadatatypen. |
| [NumberOfChannels](../../groupdocs.metadata.formats.audio/wavpackage/numberofchannels) { get; } | Hämtar antalet kanaler. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Får en samling beskrivningar som innehåller information om egenskaper som är tillgängliga via sökmotorn GroupDocs.Metadata. |
| [SampleRate](../../groupdocs.metadata.formats.audio/wavpackage/samplerate) { get; } | Hämtar samplingsfrekvensen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Lägger till kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar även alla kapslade paket. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Bestämmer om paketet innehåller en metadataegenskap med det angivna namnet. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Hittar metadataegenskaperna som uppfyller det angivna predikatet. Sökningen är rekursiv så den påverkar också alla kapslade paket. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Tar bort metadataegenskaper som uppfyller det angivna predikatet. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Tar bort skrivbara metadataegenskaper från paketet. Operationen är rekursiv så den påverkar alla kapslade paket också. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Ställer in kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. Denna metod är en kombination av[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) och[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Om en befintlig egenskap uppfyller predikatet uppdateras dess värde. Om det saknas en känd egenskap i paketet som uppfyller predikatet läggs den till i paketet. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Uppdaterar kända metadataegenskaper som uppfyller det angivna predikatet. Operationen är rekursiv så den påverkar också alla kapslade paket. |

### Anmärkningar

**Läs mer**

* [Hantera metadata i WAV-filer](https://docs.groupdocs.com/display/metadatanet/Handling+metadata+in+WAV+files)

### Exempel

Detta kodexempel visar hur man extraherar teknisk ljudinformation från en WAV-fil.

```csharp
using (Metadata metadata = new Metadata(Constants.InputWav))
{
    var root = metadata.GetRootPackage<WavRootPackage>();
    if (root.WavPackage != null)
    {
        Console.WriteLine(root.WavPackage.AudioFormat);
        Console.WriteLine(root.WavPackage.BitsPerSample);
        Console.WriteLine(root.WavPackage.BlockAlign);
        Console.WriteLine(root.WavPackage.ByteRate);
        Console.WriteLine(root.WavPackage.NumberOfChannels);
        Console.WriteLine(root.WavPackage.SampleRate);
    }
}
```

### Se även

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namnutrymme [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* hopsättning [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
