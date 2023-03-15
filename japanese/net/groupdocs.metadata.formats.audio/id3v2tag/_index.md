---
title: ID3V2Tag
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ID3v2 タグを表します 詳細についてはhttps//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2.
type: docs
weight: 490
url: /ja/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

ID3v2 タグを表します。 詳細については、[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2).

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | の新しいインスタンスを初期化します[`ID3V2Tag`](../id3v2tag)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | アルバム/ムービー/番組のタイトルを取得または設定します。 この値は TALB フレームによって表されます。 |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | リード アーティスト/リード パフォーマー/ソリスト/パフォーミング グループを取得または設定します。 この値は TPE1 フレームで表されます。 |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | オーディオ ファイルに直接関連する添付画像を取得または設定します. この値は APIC フレームで表されます. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | Band/Orchestra/Accompaniment を取得または設定します。 この値は TPE2 フレームで表されます。 |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | オーディオの主要部分の 1 分あたりのビート数を取得または設定します。 この値は TBPM フレームで表されます。 |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | ユーザー コメントを取得または設定します。 この値は、COMM フレームによって表されます。 フレームは、他のフレームに収まらないあらゆる種類のフル テキスト情報を対象としています。 |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | コンポーザーを取得または設定します。名前は「/」文字で区切ります。 この値は TCOM フレームで表されます。 |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | コンテンツ タイプを取得または設定します。 この値は TCON フレームによって表されます。 |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | 著作権メッセージを取得または設定します. この値は TCOP フレームによって表されます. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | 記録の日付を含む DDMM 形式の数値文字列を取得または設定します。このフィールドは常に 4 文字の長さです. この値は TDAT フレームによって表されます. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | オーディオ ファイルをエンコードした人物または組織の名前を取得または設定します。 この値は、TENC フレームによって表されます。 |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | 国際標準記録コード (ISRC) (12 文字) を取得または設定します。 この値は TSRC フレームによって表されます。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | 数値文字列として表されるオーディオ ファイルの長さをミリ秒単位で取得または設定します。 この値は TLEN フレームによって表されます。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | サウンドが開始する音楽キーを取得または設定します. この値は TKEY フレームによって表されます. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | 元のアルバム/映画/番組のタイトルを取得または設定します。 この値は TOAL フレームで表されます。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | ラベルまたは発行者の名前を取得または設定します。 この値は TPUB フレームによって表されます。 |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | 数値文字列として表される、ID3v2 タグを除くオーディオ ファイルのサイズをバイト単位で取得または設定します。 この値は、TSIZ フレームによって表されます。 |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | ファイルがエンコードされたときに使用されたオーディオ エンコーダーとその設定を取得または設定します。 この値は TSSE フレームによって表されます。 |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | サブタイトル/説明の絞り込みを取得または設定します。 この値は TIT3 フレームによって表されます。 |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | タグのサイズを取得します。 |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | 記録の時間を含む HHMM 形式の数値文字列を取得または設定します。このフィールドは常に 4 文字です。 この値は TIME フレームで表されます。 |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | タイトル/曲名/コンテンツの説明を取得または設定します。 この値は TIT2 フレームによって表されます。 |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | 元の録音のオーディオ ファイルの順序番号を含む数値文字列を取得または設定します。 この値は TRCK フレームで表されます。 |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | ファイルが再生された回数を取得します。 この値は PCNT フレームで表されます。 |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | ID3 バージョンを取得します。 |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | 録音年を含む数値文字列を取得または設定します。このフレームは常に 4 文字の長さです (10000 年まで)。 この値は TYER フレームで表されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | タグにフレームを追加します。 |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | 指定された ID を持つすべてのフレームを削除します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | 指定された id を持つフレームの配列を取得します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | 指定したフレームをタグから削除します。 |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | APIC フレームに保存されているすべての添付画像を削除します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | 指定されたフレームと同じ ID を持つすべてのフレームを削除し、新しいフレームをタグに追加します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | パッケージからリストを作成します。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

**もっと詳しく知る**

* [ID3v2 タグの処理](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### 例

この例は、MP3 ファイル内の ID3v2 タグを読み取る方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### 関連項目

* class [ID3Tag](../id3tag)
* 名前空間 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
