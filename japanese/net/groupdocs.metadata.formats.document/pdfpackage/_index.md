---
title: PdfPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: PDF ドキュメントのネイティブ メタデータを表します
type: docs
weight: 1030
url: /ja/net/groupdocs.metadata.formats.document/pdfpackage/
---
## PdfPackage class

PDF ドキュメントのネイティブ メタデータを表します。

```csharp
public class PdfPackage : DocumentPackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/pdfpackage/author) { get; set; } | ドキュメントの作成者を取得または設定します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [CreatedDate](../../groupdocs.metadata.formats.document/pdfpackage/createddate) { get; set; } | ドキュメントの作成日を取得または設定します。 |
| [Creator](../../groupdocs.metadata.formats.document/pdfpackage/creator) { get; } | ドキュメントの作成者を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Keywords](../../groupdocs.metadata.formats.document/pdfpackage/keywords) { get; set; } | キーワードを取得または設定します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [ModifiedDate](../../groupdocs.metadata.formats.document/pdfpackage/modifieddate) { get; set; } | 最終変更日を取得または設定します。 |
| [Producer](../../groupdocs.metadata.formats.document/pdfpackage/producer) { get; } | ドキュメント プロデューサーを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Subject](../../groupdocs.metadata.formats.document/pdfpackage/subject) { get; set; } | ドキュメントの件名を取得または設定します。 |
| [Title](../../groupdocs.metadata.formats.document/pdfpackage/title) { get; set; } | ドキュメントのタイトルを取得または設定します。 |
| [TrappedFlag](../../groupdocs.metadata.formats.document/pdfpackage/trappedflag) { get; set; } | トラップ フラグを取得または設定します。 |

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
| [Set](../../groupdocs.metadata.formats.document/pdfpackage/set)(string, string) | メタデータ プロパティを指定された名前で追加または置換します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

**もっと詳しく知る**

* [PDF ドキュメントのメタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### 例

このコード スニペットは、PDF ドキュメントの組み込みメタデータ プロパティを更新する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedDate = DateTime.Now;
    root.DocumentProperties.Title = "test title";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPdf);
}
```

### 関連項目

* class [DocumentPackage](../documentpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
