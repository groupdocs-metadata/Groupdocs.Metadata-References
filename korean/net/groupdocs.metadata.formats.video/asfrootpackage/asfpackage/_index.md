---
title: AsfPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: ASF 메타데이터 패키지를 가져옵니다.
type: docs
weight: 10
url: /ko/net/groupdocs.metadata.formats.video/asfrootpackage/asfpackage/
---
## AsfRootPackage.AsfPackage property

ASF 메타데이터 패키지를 가져옵니다.

```csharp
public AsfPackage AsfPackage { get; }
```

### 자산 가치

ASF 메타데이터 패키지.

### 비고

**더 알아보기**

* [ASF 파일에서 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### 예

이 코드 샘플은 기본 ASF 메타데이터를 읽는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputAsf))
{
    var root = metadata.GetRootPackage<AsfRootPackage>();

    var package = root.AsfPackage;

    // 기본 속성 표시
    Console.WriteLine("Creation date: {0}", package.CreationDate);
    Console.WriteLine("File id: {0}", package.FileID);
    Console.WriteLine("Flags: {0}", package.Flags);

    // ASF 코덱 정보 표시
    foreach (var codecInfo in package.CodecInformation)
    {
        Console.WriteLine("Codec type: {0}", codecInfo.CodecType);
        Console.WriteLine("Description: {0}", codecInfo.Description);
        Console.WriteLine("Codec information: {0}", codecInfo.Information);
        Console.WriteLine(codecInfo.Name);
    }

    // 메타데이터 설명자 표시
    foreach (AsfBaseDescriptor descriptor in package.MetadataDescriptors)
    {
        Console.WriteLine("Name: {0}", descriptor.Name);
        Console.WriteLine("Value: {0}", descriptor.Value);
        Console.WriteLine("Content type: {0}", descriptor.AsfContentType);
        AsfMetadataDescriptor metadataDescriptor = descriptor as AsfMetadataDescriptor;
        if (metadataDescriptor != null)
        {
            Console.WriteLine("Language: {0}", metadataDescriptor.Language);
            Console.WriteLine("Stream number: {0}", metadataDescriptor.StreamNumber);
            Console.WriteLine("Original name: {0}", metadataDescriptor.OriginalName);
        }
    }

    //기본 스트림 속성 표시
    foreach (AsfBaseStreamProperty property in package.StreamProperties)
    {
        Console.WriteLine("Alternate bitrate: {0}", property.AlternateBitrate);
        Console.WriteLine("Average bitrate: {0}", property.AverageBitrate);
        Console.WriteLine("Average time per frame: {0}", property.AverageTimePerFrame);
        Console.WriteLine("Bitrate: {0}", property.Bitrate);
        Console.WriteLine("Stream end time: {0}", property.EndTime);
        Console.WriteLine("Stream flags: {0}", property.Flags);
        Console.WriteLine("Stream language: {0}", property.Language);
        Console.WriteLine("Stream start time: {0}", property.StartTime);
        Console.WriteLine("Stream number: {0}", property.StreamNumber);
        Console.WriteLine("Stream type: {0}", property.StreamType);

        //오디오 스트림 속성 표시
        AsfAudioStreamProperty audioStreamProperty = property as AsfAudioStreamProperty;
        if (audioStreamProperty != null)
        {
            Console.WriteLine("Audio bits per sample: {0}", audioStreamProperty.BitsPerSample);
            Console.WriteLine("Audio channels: {0}", audioStreamProperty.Channels);
            Console.WriteLine("Audio format tag: {0}", audioStreamProperty.FormatTag);
            Console.WriteLine("Audio samples per second: {0}", audioStreamProperty.SamplesPerSecond);
        }

        //비디오 스트림 속성 표시
        AsfVideoStreamProperty videoStreamProperty = property as AsfVideoStreamProperty;
        if (videoStreamProperty != null)
        {
            Console.WriteLine("Video bits per pixels: {0}", videoStreamProperty.BitsPerPixels);
            Console.WriteLine("Compression: {0}", videoStreamProperty.Compression);
            Console.WriteLine("Image height: {0}", videoStreamProperty.ImageHeight);
            Console.WriteLine("Image width: {0}", videoStreamProperty.ImageWidth);
        }
    }
}
```

### 또한보십시오

* class [AsfPackage](../../asfpackage)
* class [AsfRootPackage](../../asfrootpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Video](../../asfrootpackage)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->