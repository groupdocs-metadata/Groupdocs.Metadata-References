---
title: AsfAudioStreamProperty
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ASF メディア コンテナー内のオーディオ ストリーム プロパティのメタデータを表します
type: docs
weight: 2230
url: /ja/net/groupdocs.metadata.formats.video/asfaudiostreamproperty/
---
## AsfAudioStreamProperty class

ASF メディア コンテナー内のオーディオ ストリーム プロパティのメタデータを表します。

```csharp
public class AsfAudioStreamProperty : AsfBaseStreamProperty
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternateBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/alternatebitrate) { get; } | ストリームのデータ部分 を含むリーク バケットのリーク レート RAlt をビット/秒で取得します。オーバーフローすることはありません。すべての ASF データ パケット オーバーヘッドは除外されます。 |
| [AverageBitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagebitrate) { get; } | 平均ビットレートを取得します。 |
| [AverageTimePerFrame](../../groupdocs.metadata.formats.video/asfbasestreamproperty/averagetimeperframe) { get; } | 各フレームの 100 ナノ秒単位で測定された平均継続時間を取得します。 |
| [Bitrate](../../groupdocs.metadata.formats.video/asfbasestreamproperty/bitrate) { get; } | ストリームのデータ部分 を含むリーク バケットのリーク レート R をビット/秒で取得します。オーバーフローすることはありません。すべての ASF データ パケット オーバーヘッドは除外されます。 |
| [BitsPerSample](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/bitspersample) { get; } | モノラル データの 1 サンプルあたりのビット数を取得します。 |
| [Channels](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/channels) { get; } | 音声チャンネル数を取得します. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [EndTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/endtime) { get; } | 最後のオブジェクトの表示時間と再生時間を加えたものを取得し、ASF ファイル全体のタイムラインのコンテキスト内でこのデジタル メディア ストリームが終了する 場所を示します. |
| [Flags](../../groupdocs.metadata.formats.video/asfbasestreamproperty/flags) { get; } | フラグを取得します。 |
| [FormatTag](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/formattag) { get; } | オーディオ データのエンコードに使用されるコーデックの一意の ID を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Language](../../groupdocs.metadata.formats.video/asfbasestreamproperty/language) { get; } | ストリーム言語を取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [SamplesPerSecond](../../groupdocs.metadata.formats.video/asfaudiostreamproperty/samplespersecond) { get; } | オーディオ ストリームのサンプリング レートを表すヘルツ (1 秒あたりのサイクル数) の値を取得します。 |
| [StartTime](../../groupdocs.metadata.formats.video/asfbasestreamproperty/starttime) { get; } | 最初のオブジェクトのプレゼンテーション時間を取得し、このデジタル メディア ストリーム が ASF ファイル全体のタイムラインのコンテキスト内で開始する場所を示します. |
| [StreamNumber](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamnumber) { get; } | このストリームの番号を取得します。 |
| [StreamType](../../groupdocs.metadata.formats.video/asfbasestreamproperty/streamtype) { get; } | このストリームのタイプを取得します。 |

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

### 備考

**もっと詳しく知る**

* [ASF ファイルのメタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+Metadata+in+ASF+Files)

### 関連項目

* class [AsfBaseStreamProperty](../asfbasestreamproperty)
* 名前空間 [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
