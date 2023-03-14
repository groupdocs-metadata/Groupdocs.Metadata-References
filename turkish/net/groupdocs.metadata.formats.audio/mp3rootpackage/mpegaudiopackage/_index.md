---
title: MpegAudioPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: MPEG ses meta veri paketini alır.
type: docs
weight: 50
url: /tr/net/groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage/
---
## MP3RootPackage.MpegAudioPackage property

MPEG ses meta veri paketini alır.

```csharp
public MpegAudioPackage MpegAudioPackage { get; }
```

### Mülk değeri

MPEG ses meta veri paketi.

### Örnekler

Bu örnek, MPEG ses meta verilerinin bir MP3 dosyasından nasıl okunacağını gösterir.

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

### Ayrıca bakınız

* class [MpegAudioPackage](../../../groupdocs.metadata.formats.mpeg/mpegaudiopackage)
* class [MP3RootPackage](../../mp3rootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Audio](../../mp3rootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->