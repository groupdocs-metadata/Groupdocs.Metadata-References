---
title: SpreadsheetPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: スプレッドシート内のネイティブ メタデータ パッケージを表します
type: docs
weight: 1200
url: /ja/net/groupdocs.metadata.formats.document/spreadsheetpackage/
---
## SpreadsheetPackage class

スプレッドシート内のネイティブ メタデータ パッケージを表します。

```csharp
public class SpreadsheetPackage : DocumentPackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/spreadsheetpackage/author) { get; set; } | ドキュメントの作成者を取得または設定します。 |
| [Category](../../groupdocs.metadata.formats.document/spreadsheetpackage/category) { get; set; } | カテゴリを取得または設定します。 |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetpackage/comments) { get; set; } | コメントを取得または設定します。 |
| [Company](../../groupdocs.metadata.formats.document/spreadsheetpackage/company) { get; set; } | 会社を取得または設定します。 |
| [ContentStatus](../../groupdocs.metadata.formats.document/spreadsheetpackage/contentstatus) { get; set; } | コンテンツのステータスを取得または設定します。 |
| [ContentType](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttype) { get; set; } | コンテンツ タイプを取得または設定します。 |
| [ContentTypeProperties](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttypeproperties) { get; } | コンテンツ タイプ プロパティを含むメタデータ パッケージを取得します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [CreatedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/createdtime) { get; set; } | ドキュメントの作成日を取得または設定します。 |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/spreadsheetpackage/hyperlinkbase) { get; set; } | ハイパーリンク ベースを取得または設定します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Keywords](../../groupdocs.metadata.formats.document/spreadsheetpackage/keywords) { get; set; } | キーワードを取得または設定します。 |
| [Language](../../groupdocs.metadata.formats.document/spreadsheetpackage/language) { get; set; } | ドキュメントの言語を取得または設定します。 |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastprinteddate) { get; set; } | UTC で最後に印刷された日付を取得または設定します。 |
| [LastSavedBy](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedby) { get; set; } | 最後の作成者の名前を取得または設定します。 |
| [LastSavedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedtime) { get; set; } | UTC で最後に保存した時刻を取得または設定します。 |
| [Manager](../../groupdocs.metadata.formats.document/spreadsheetpackage/manager) { get; set; } | マネージャを取得または設定します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [NameOfApplication](../../groupdocs.metadata.formats.document/spreadsheetpackage/nameofapplication) { get; set; } | アプリケーションの名前を取得または設定します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Revision](../../groupdocs.metadata.formats.document/spreadsheetpackage/revision) { get; set; } | ドキュメントのリビジョン番号を取得または設定します。 |
| [Subject](../../groupdocs.metadata.formats.document/spreadsheetpackage/subject) { get; set; } | 件名を取得または設定します。 |
| [Template](../../groupdocs.metadata.formats.document/spreadsheetpackage/template) { get; set; } | ドキュメント テンプレート名を取得または設定します。 |
| [Title](../../groupdocs.metadata.formats.document/spreadsheetpackage/title) { get; set; } | ドキュメントのタイトルを取得または設定します。 |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/totaleditingtime) { get; set; } | 合計編集時間を分単位で取得または設定します。 |
| [Version](../../groupdocs.metadata.formats.document/spreadsheetpackage/version) { get; set; } | ドキュメントを作成したアプリケーションのバージョン番号を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | 書き込み可能なすべてのメタデータ プロパティをパッケージから削除します。 |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | 組み込みのメタデータ プロパティをすべて削除します。 |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | すべてのカスタム メタデータ プロパティを削除します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | 指定された名前で書き込み可能なメタデータ プロパティを削除します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set)(string, bool) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_3)(string, DateTime) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_1)(string, double) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_2)(string, int) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_4)(string, string) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

**もっと詳しく知る**

* [スプレッドシートでのメタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### 例

この例は、スプレッドシートの組み込みメタデータ プロパティを更新する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputXlsx);
}
```

### 関連項目

* class [DocumentPackage](../documentpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
