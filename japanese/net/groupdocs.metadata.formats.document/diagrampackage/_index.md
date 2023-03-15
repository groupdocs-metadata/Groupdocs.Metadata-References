---
title: DiagramPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 図形式でネイティブ メタデータ パッケージを表します
type: docs
weight: 890
url: /ja/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

図形式でネイティブ メタデータ パッケージを表します。

```csharp
public class DiagramPackage : DocumentPackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | ドキュメントの代替名を取得または設定します。 VDX および VSX 形式でのみ更新できます。 |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | ドキュメントの作成に使用されたインスタンスの完全なビルド番号を取得します。 |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | ドキュメントの編集に最後に使用されたインスタンスのビルド番号を取得します。 |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | フローチャートやオフィス レイアウトなど、図面の種類の説明テキストを取得または設定します。 このテキストは、Microsoft Visio ユーザー インターフェイスの [プロパティ] ダイアログ ボックスの [カテゴリ] ボックスにも入力できます。 |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | 図面を作成している会社または図面が作成されている会社を識別するユーザー入力情報を取得または設定します. 最大長は 63 文字です. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | ファイルの作成者または最終更新者を取得または設定します. 最大長は 63 文字です.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | ドキュメントの説明テキスト文字列を取得または設定します。 この要素を使用して、目的、最近の変更、保留中の変更など、ドキュメントに関する重要な情報を保存します。 最大文字数は 191 文字です。 |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | 相対ハイパーリンク (リンクされたファイルの場所が Microsoft Visio ダイアグラムに関連して記述されているハイパーリンク) に使用されるパスを取得または設定します。 最大長は 256 文字です. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | プロジェクト名、クライアント名、バージョン番号など、ファイルに関するトピックやその他の重要な情報を識別するテキスト文字列を取得または設定します。 文字列の最大長は 63 文字です。 |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | ドキュメントの言語を取得または設定します。 VSD および VSDX 形式でのみ更新できます。 |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | プロジェクトまたは部門の担当者を識別するユーザー入力のテキスト文字列を取得または設定します。 最大長は 63 文字です。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | プレビュー画像を取得または設定します. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | ドキュメントの内容を説明するユーザー定義のテキスト文字列を取得または設定します. 最大長は 63 文字です. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | ドキュメントが作成されたテンプレートのファイル名を指定する文字列値を取得または設定します。 |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | ドキュメントがいつ作成されたかを示す日付と時刻の値を取得または設定します。 |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | ドキュメントが最後に編集された日時を示す日付と時刻の値を取得します。 |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | ドキュメントが最後に印刷された日時を示す日付と時刻の値を取得します。 |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | ドキュメントが最後に保存された日時を示す日付と時刻の値を取得します。 |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | ドキュメントの説明的なタイトルとして機能するユーザー定義のテキスト文字列を取得または設定します. 最大長は 63 文字です. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

**もっと詳しく知る**

* [ダイアグラムでのメタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### 例

このコード サンプルは、ダイアグラムから組み込みのメタデータ プロパティを抽出する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### 関連項目

* class [DocumentPackage](../documentpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
