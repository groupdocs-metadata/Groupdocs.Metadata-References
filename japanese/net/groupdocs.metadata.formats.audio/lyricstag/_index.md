---
title: LyricsTag
second_title: GroupDocs.Metadata for .NET API リファレンス
description: Lyrics3 v2.00 メタデータを表します 詳細についてはhttp//id3.org/Lyrics3v2.
type: docs
weight: 570
url: /ja/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Lyrics3 v2.00 メタデータを表します。 詳細については、http://id3.org/Lyrics3v2.

```csharp
public sealed class LyricsTag : CustomPackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LyricsTag](lyricstag)() | の新しいインスタンスを初期化します[`LyricsTag`](../lyricstag)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | 追加情報を取得または設定します。 この値は、INF フィールドによって表されます。 |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | アルバム名を取得または設定します。 この値は EAL フィールドによって表されます。 |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | アーティスト名を取得または設定します。 この値は EAR フィールドによって表されます。 |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | 作成者を取得または設定します。 この値は AUT フィールドで表されます。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | 歌詞を取得または設定します。 この値は LYR フィールドによって表されます。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | トラック タイトルを取得または設定します。 この値は ETT フィールドによって表されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | 指定された id を持つフィールドの値を取得します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | 指定された ID を持つフィールドを削除します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | 指定した Lyrics3 フィールドを追加または置換します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | パッケージからリストを作成します。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

Lyrics3 v2.00 はフィールドを使用して情報を表します. フィールド内のデータは、標準に従って 01 から 254 の範囲の ASCII 文字で構成できます. ASCII 文字マップは 00 から 128 までしか定義されていないため、ISO-8859- 1 と考えられます。数値フィールドは、場所に応じて 5 文字または 6 文字の長さで、ゼロが埋め込まれます。

**もっと詳しく知る**

* [歌詞タグの扱い](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### 例

このコード サンプルは、MP3 ファイルから歌詞タグを読み取る方法を示しています。

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

        // または、タグ フィールドの完全なリストをループすることもできます
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### 関連項目

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 名前空間 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
