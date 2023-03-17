---
title: OpenTypeFont
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ファイルから抽出された単一のフォントを表します.
type: docs
weight: 1460
url: /ja/net/groupdocs.metadata.formats.font/opentypefont/
---
## OpenTypeFont class

ファイルから抽出された単一のフォントを表します.

```csharp
public class OpenTypeFont : CustomPackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Created](../../groupdocs.metadata.formats.font/opentypefont/created) { get; } | 作成日を取得します。 |
| [DirectionHint](../../groupdocs.metadata.formats.font/opentypefont/directionhint) { get; } | 方向ヒントを取得します。 |
| [EmbeddingLicensingRights](../../groupdocs.metadata.formats.font/opentypefont/embeddinglicensingrights) { get; } | 埋め込みライセンス権の種類を取得します。 |
| [Flags](../../groupdocs.metadata.formats.font/opentypefont/flags) { get; } | ヘッダー フラグを取得します。 |
| [FontFamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontfamilyname) { get; } | フォント ファミリの名前を取得します。 |
| [FontRevision](../../groupdocs.metadata.formats.font/opentypefont/fontrevision) { get; } | フォントのリビジョンを取得します。 |
| [FontSubfamilyName](../../groupdocs.metadata.formats.font/opentypefont/fontsubfamilyname) { get; } | フォント サブファミリーの名前を取得します。 |
| [FullFontName](../../groupdocs.metadata.formats.font/opentypefont/fullfontname) { get; } | フォントの完全な名前を取得します。 |
| [GlyphBounds](../../groupdocs.metadata.formats.font/opentypefont/glyphbounds) { get; } | グリフ境界を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [MajorVersion](../../groupdocs.metadata.formats.font/opentypefont/majorversion) { get; } | ヘッダーのメジャー バージョンを取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [MinorVersion](../../groupdocs.metadata.formats.font/opentypefont/minorversion) { get; } | ヘッダーのマイナー バージョンを取得します。 |
| [Modified](../../groupdocs.metadata.formats.font/opentypefont/modified) { get; } | 変更日を取得します。 |
| [Names](../../groupdocs.metadata.formats.font/opentypefont/names) { get; } | 名前レコードを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [SfntVersion](../../groupdocs.metadata.formats.font/opentypefont/sfntversion) { get; } | ヘッダー SFNT バージョンを取得します。 |
| [Style](../../groupdocs.metadata.formats.font/opentypefont/style) { get; } | フォント スタイルを取得します。 |
| [TypographicFamily](../../groupdocs.metadata.formats.font/opentypefont/typographicfamily) { get; } | 文字体裁ファミリを取得します。 |
| [TypographicSubfamily](../../groupdocs.metadata.formats.font/opentypefont/typographicsubfamily) { get; } | 活版印刷サブファミリーを取得します。 |
| [Weight](../../groupdocs.metadata.formats.font/opentypefont/weight) { get; } | フォントの太さを取得します。 |
| [Width](../../groupdocs.metadata.formats.font/opentypefont/width) { get; } | フォント幅を取得します。 |

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

* [OpenType フォントの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+OpenType+fonts)

### 関連項目

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 名前空間 [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
