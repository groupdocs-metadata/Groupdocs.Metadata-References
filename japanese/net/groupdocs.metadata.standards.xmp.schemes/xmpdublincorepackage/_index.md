---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ダブリン コア スキームを表します
type: docs
weight: 3120
url: /ja/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

ダブリン コア スキームを表します。

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | の新しいインスタンスを初期化します[`XmpDublinCorePackage`](../xmpdublincorepackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | コントリビューターの配列を取得または設定します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | リソースのエクステントまたはスコープを取得または設定します。 |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | 作成者の配列を取得または設定します。 |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | リソースのライフ サイクルのイベントに関連付けられた日付の配列を取得または設定します。 |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | さまざまな言語で指定された、リソースのコンテンツのテキスト記述の配列を取得または設定します。 |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | リソースの MIME タイプを取得または設定します。 |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | 特定のコンテキスト内のリソースへの明確な参照を表す文字列値を取得または設定します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | リソースのコンテンツで使用される言語の配列を取得または設定します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 名前空間 URI を取得します。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns プレフィックスを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | リソースを利用可能にしたパブリッシャーの配列を取得または設定します。 |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | 関連するリソースの配列を取得または設定します。 |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | さまざまな言語で指定された、非公式の権利ステートメントの配列を取得または設定します。 |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | 記述されたリソースの派生元である関連リソースを取得または設定します。 |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | リソースのコンテンツを指定する説明的な語句またはキーワードの配列を取得または設定します。 |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | さまざまな言語で指定された、リソースのタイトルまたは名前を取得または設定します。 |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | リソースの性質またはジャンルを表す文字列値の配列を取得または設定します。 |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | 文字列プロパティを設定します。 |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | から継承された値を設定します[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | から継承された値を設定します[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | から継承された値を設定します[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase). |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | リソースの単一の貢献者を設定します。 |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | リソースの単一作成者を設定します。 |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | リソースに関連付けられた単一の日付を設定します。 |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | 単一の言語で指定されたリソースの説明を設定します。 |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | リソースに関連付けられた単一の言語を設定します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | リソースの単一のパブリッシャーを設定します。 |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | 単一の関連リソースを設定します。 |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | 単一言語で指定されたリソース権限を設定します。 |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | リソースの単一のサブジェクトを設定します。 |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | 単一の言語で指定されたリソースのタイトルを設定します。 |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | リソースの単一タイプを設定します。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

詳細については、http://dublincore.org/documents/usageguide/elements.shtml. を参照してください。

### 関連項目

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 名前空間 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
