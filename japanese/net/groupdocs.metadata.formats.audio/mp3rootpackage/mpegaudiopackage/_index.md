---
title: MpegAudioPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: MPEG オーディオ メタデータ パッケージを取得します
type: docs
weight: 50
url: /ja/net/groupdocs.metadata.formats.audio/mp3rootpackage/mpegaudiopackage/
---
## MP3RootPackage.MpegAudioPackage property

MPEG オーディオ メタデータ パッケージを取得します。

```csharp
public MpegAudioPackage MpegAudioPackage { get; }
```

### プロパティ値

MPEG オーディオ メタデータ パッケージ。

### 例

この例では、MP3 ファイルから MPEG オーディオ メタデータを読み取る方法を示します。

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

### 関連項目

* class [MpegAudioPackage](../../../groupdocs.metadata.formats.mpeg/mpegaudiopackage)
* class [MP3RootPackage](../../mp3rootpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Audio](../../mp3rootpackage)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
