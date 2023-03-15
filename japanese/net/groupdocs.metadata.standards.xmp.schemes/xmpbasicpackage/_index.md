---
title: XmpBasicPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: XMP 基本名前空間を表します
type: docs
weight: 3090
url: /ja/net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
---
## XmpBasicPackage class

XMP 基本名前空間を表します。

```csharp
public sealed class XmpBasicPackage : XmpPackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage)() | の新しいインスタンスを初期化します[`XmpBasicPackage`](../xmpbasicpackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaseUrl](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/baseurl) { get; set; } | ドキュメント コンテンツ内の相対 URL のベース URL を取得または設定します。 このドキュメントにインターネット リンクが含まれていて、それらのリンクが相対リンクである場合、それらはこのベース URL に対して相対的です。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [CreateDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/createdate) { get; set; } | リソースが作成された日時を取得または設定します。 |
| [CreatorTool](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creatortool) { get; set; } | リソースの作成に使用されるツールの名前を取得または設定します。 |
| [Identifiers](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) { get; set; } | 指定されたコンテキスト内のリソースを明確に識別するテキスト文字列の順序付けられていない配列を取得または設定します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Label](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) { get; set; } | リソースをユーザー定義コレクションのメンバーとして識別する単語または短い語句を取得または設定します。 |
| [MetadataDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadatadate) { get; set; } | このリソースのメタデータが最後に変更された日時を取得または設定します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [ModifyDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modifydate) { get; set; } | リソースが最後に変更された日時を取得または設定します。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 名前空間 URI を取得します。 |
| [Nickname](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) { get; set; } | リソースの略称を取得または設定します。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns プレフィックスを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Rating](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) { get; set; } | このファイルにユーザーが割り当てた評価を取得または設定します。 値は -1 または範囲 [0..5] で、-1 は「拒否」を示し、0 は「評価なし」を示します。 |
| [Thumbnails](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) { get; set; } | ファイルのサムネイル画像の配列を取得または設定します。サイズや画像のエンコードなどの特性が異なる場合があります。 |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | XML 名前空間を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | すべての XMP プロパティを削除します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | XMP 値を XML 表現に変換します。 |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | 指定した名前のプロパティを削除します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | ブール値のプロパティを設定します。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | セットDateTimeプロパティ. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | double プロパティを設定します。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | 整数プロパティを設定します。 |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set#set_7)(string, string) | 文字列プロパティを追加します。 |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | から継承された値を設定します[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | から継承された値を設定します[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | から継承された値を設定します[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase). |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [RatingMax](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmax) | レーティング最大値. |
| const [RatingMin](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmin) | 評価の最小値. |
| const [RatingRejected](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingrejected) | 評価が拒否された値. |

### 関連項目

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 名前空間 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
