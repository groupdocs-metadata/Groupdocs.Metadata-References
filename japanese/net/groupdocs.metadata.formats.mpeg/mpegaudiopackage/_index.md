---
title: MpegAudioPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: MPEG オーディオ メタデータを表します
type: docs
weight: 2150
url: /ja/net/groupdocs.metadata.formats.mpeg/mpegaudiopackage/
---
## MpegAudioPackage class

MPEG オーディオ メタデータを表します。

```csharp
public sealed class MpegAudioPackage : CustomPackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MpegAudioPackage](mpegaudiopackage)() | の新しいインスタンスを初期化します[`MpegAudioPackage`](../mpegaudiopackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bitrate](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/bitrate) { get; } | ビットレートを取得します。 |
| [ChannelMode](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/channelmode) { get; } | チャネル モードを取得します。 |
| [Copyright](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/copyright) { get; } | 著作権ビットを取得します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Emphasis](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/emphasis) { get; } | 強調を取得します。 |
| [Frequency](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/frequency) { get; } | 周波数を取得します。 |
| [HeaderPosition](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/headerposition) { get; } | ヘッダーのオフセットを取得します。 |
| [IsOriginal](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isoriginal) { get; } | 元のビットを取得します。 |
| [IsProtected](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/isprotected) { get; } | 取得`真実`保護されている場合. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Layer](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/layer) { get; } | レイヤーの説明を取得します。 MP3 オーディオの場合は「3」です。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [ModeExtensionBits](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/modeextensionbits) { get; } | モード拡張ビットを取得します。 |
| [MpegAudioVersion](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/mpegaudioversion) { get; } | MPEG オーディオ バージョンを取得します。 MPEG-1、MPEG-2など |
| [PaddingBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/paddingbit) { get; } | パディング ビットを取得します。 |
| [PrivateBit](../../groupdocs.metadata.formats.mpeg/mpegaudiopackage/privatebit) { get; } | [プライベートビット]かどうかを示す値を取得します. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

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

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 名前空間 [GroupDocs.Metadata.Formats.Mpeg](../../groupdocs.metadata.formats.mpeg)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
