---
title: ApePackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: APE v2 メタデータ パッケージを表します 詳細については次を参照してくださいhttp//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key.
type: docs
weight: 380
url: /ja/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

APE v2 メタデータ パッケージを表します。 詳細については、次を参照してください。[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key).

```csharp
public sealed class ApePackage : CustomPackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | 抽象リンクを取得します。 |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | アルバムを取得します。 |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | アーティストを取得します。 |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | 参考文献を取得します。 |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | コメントを取得します。 |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | コンポーザを取得します。 |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | 導体を取得します. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | 著作権を取得します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | デビュー アルバムを取得します。 |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | ファイルを取得します。 |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | ジャンルを取得します. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | チェックデジット付きISBN番号を取得します。詳細: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | 国際標準記録番号を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | 言語を取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | 公開権を取得します。 |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | パブリッシャーを取得します。 |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | レコードの場所を取得します。 |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | サブタイトルを取得します。 |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | タイトルを取得します。 |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | トラック番号を取得します。 |

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

* [APEv2 タグの処理](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

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

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 名前空間 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
