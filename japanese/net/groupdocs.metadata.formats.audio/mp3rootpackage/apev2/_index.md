---
title: ApeV2
second_title: GroupDocs.Metadata for .NET API リファレンス
description: APE v2 メタデータを取得します
type: docs
weight: 10
url: /ja/net/groupdocs.metadata.formats.audio/mp3rootpackage/apev2/
---
## MP3RootPackage.ApeV2 property

APE v2 メタデータを取得します。

```csharp
public ApePackage ApeV2 { get; }
```

### プロパティ値

APE v2 メタデータ。

### 例

この例は、MP3 ファイル内の APEv2 タグを読み取る方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### 関連項目

* class [ApePackage](../../apepackage)
* class [MP3RootPackage](../../mp3rootpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Audio](../../mp3rootpackage)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->