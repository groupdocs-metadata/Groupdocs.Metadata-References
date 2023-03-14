---
title: MatroskaPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Matroska meta veri paketini alır.
type: docs
weight: 10
url: /tr/net/groupdocs.metadata.formats.video/matroskarootpackage/matroskapackage/
---
## MatroskaRootPackage.MatroskaPackage property

Matroska meta veri paketini alır.

```csharp
public MatroskaPackage MatroskaPackage { get; }
```

### Mülk değeri

Matroska meta veri paketi.

### Notlar

**Daha fazla bilgi edin**

* [Matroska (MKV) dosyalarında meta verilerle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### Örnekler

Bu örnek, Matroska biçimine özgü meta veri özelliklerinin nasıl okunacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMkv))
{
    var root = metadata.GetRootPackage<MatroskaRootPackage>();

    // EBML başlığını oku
    Console.WriteLine("DocType: {0}", root.MatroskaPackage.EbmlHeader.DocType);
    Console.WriteLine("DocTypeReadVersion: {0}", root.MatroskaPackage.EbmlHeader.DocTypeReadVersion);
    Console.WriteLine("DocTypeVersion: {0}", root.MatroskaPackage.EbmlHeader.DocTypeVersion);
    Console.WriteLine("ReadVersion: {0}", root.MatroskaPackage.EbmlHeader.ReadVersion);
    Console.WriteLine("Version: {0}", root.MatroskaPackage.EbmlHeader.Version);

    // Matroska segment bilgilerini oku
    foreach (var segment in root.MatroskaPackage.Segments)
    {
        Console.WriteLine("DateUtc: {0}", segment.DateUtc);
        Console.WriteLine("Duration: {0}", segment.Duration);
        Console.WriteLine("MuxingApp: {0}", segment.MuxingApp);
        Console.WriteLine("SegmentFilename: {0}", segment.SegmentFilename);
        Console.WriteLine("SegmentUid: {0}", segment.SegmentUid);
        Console.WriteLine("TimecodeScale: {0}", segment.TimecodeScale);
        Console.WriteLine("Title: {0}", segment.Title);
        Console.WriteLine("WritingApp: {0}", segment.WritingApp);
    }

    // Matroska etiketi meta verilerini oku
    foreach (var tag in root.MatroskaPackage.Tags)
    {
        Console.WriteLine("TargetType: {0}", tag.TargetType);
        Console.WriteLine("TargetTypeValue: {0}", tag.TargetTypeValue);
        Console.WriteLine("TagTrackUid: {0}", tag.TagTrackUid);
        foreach (var simpleTag in tag.SimpleTags)
        {
            Console.WriteLine("Name: {0}", simpleTag.Name);
            Console.WriteLine("Value: {0}", simpleTag.Value);
        }
    }

    // Matroska parça meta verilerini oku
    foreach (var track in root.MatroskaPackage.Tracks)
    {
        Console.WriteLine("CodecId: {0}", track.CodecID);
        Console.WriteLine("CodecName: {0}", track.CodecName);
        Console.WriteLine("DefaultDuration: {0}", track.DefaultDuration);
        Console.WriteLine("FlagEnabled: {0}", track.FlagEnabled);
        Console.WriteLine("Language: {0}", track.Language);
        Console.WriteLine("LanguageIetf: {0}", track.LanguageIetf);
        Console.WriteLine("Name: {0}", track.Name);
        Console.WriteLine("TrackNumber: {0}", track.TrackNumber);
        Console.WriteLine("TrackType: {0}", track.TrackType);
        Console.WriteLine("TrackUid: {0}", track.TrackUid);

        var audioTrack = track as MatroskaAudioTrack;
        if (audioTrack != null)
        {
            Console.WriteLine("SamplingFrequency: {0}", audioTrack.SamplingFrequency);
            Console.WriteLine("OutputSamplingFrequency: {0}", audioTrack.OutputSamplingFrequency);
            Console.WriteLine("Channels: {0}", audioTrack.Channels);
            Console.WriteLine("BitDepth: {0}", audioTrack.BitDepth);
        }

        var videoTrack = track as MatroskaVideoTrack;
        if (videoTrack != null)
        {
            Console.WriteLine("FlagInterlaced: {0}", videoTrack.FlagInterlaced);
            Console.WriteLine("FieldOrder: {0}", videoTrack.FieldOrder);
            Console.WriteLine("StereoMode: {0}", videoTrack.StereoMode);
            Console.WriteLine("AlphaMode: {0}", videoTrack.AlphaMode);
            Console.WriteLine("PixelWidth: {0}", videoTrack.PixelWidth);
            Console.WriteLine("PixelHeight: {0}", videoTrack.PixelHeight);
            Console.WriteLine("PixelCropBottom: {0}", videoTrack.PixelCropBottom);
            Console.WriteLine("PixelCropTop: {0}", videoTrack.PixelCropTop);
            Console.WriteLine("PixelCropLeft: {0}", videoTrack.PixelCropLeft);
            Console.WriteLine("PixelCropRight: {0}", videoTrack.PixelCropRight);
            Console.WriteLine("DisplayWidth: {0}", videoTrack.DisplayWidth);
            Console.WriteLine("DisplayHeight: {0}", videoTrack.DisplayHeight);
            Console.WriteLine("DisplayUnit: {0}", videoTrack.DisplayUnit);
        }
    }
}
```

### Ayrıca bakınız

* class [MatroskaPackage](../../matroskapackage)
* class [MatroskaRootPackage](../../matroskarootpackage)
* ad alanı [GroupDocs.Metadata.Formats.Video](../../matroskarootpackage)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->