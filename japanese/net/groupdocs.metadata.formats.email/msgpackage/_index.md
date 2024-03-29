---
title: MsgPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: MSG メッセージのメタデータを表します
type: docs
weight: 1400
url: /ja/net/groupdocs.metadata.formats.email/msgpackage/
---
## MsgPackage class

MSG メッセージのメタデータを表します。

```csharp
public class MsgPackage : EmailPackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AttachedFileNames](../../groupdocs.metadata.formats.email/emailpackage/attachedfilenames) { get; } | 添付ファイルの名前の配列を取得します。 |
| [BlindCarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/blindcarboncopyrecipients) { get; set; } | 電子メール メッセージの BCC (ブラインド カーボン コピー) 受信者の配列を取得または設定します。 |
| [Body](../../groupdocs.metadata.formats.email/msgpackage/body) { get; } | 電子メール メッセージのテキストを取得します。 |
| [CarbonCopyRecipients](../../groupdocs.metadata.formats.email/emailpackage/carboncopyrecipients) { get; set; } | 電子メール メッセージの CC (カーボン コピー) 受信者の配列を取得または設定します。 |
| [Categories](../../groupdocs.metadata.formats.email/msgpackage/categories) { get; } | カテゴリまたはキーワードの配列を取得します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [DeliveryTime](../../groupdocs.metadata.formats.email/msgpackage/deliverytime) { get; } | メッセージが配信された日時を取得します。 |
| [Headers](../../groupdocs.metadata.formats.email/emailpackage/headers) { get; } | 電子メール ヘッダーを含むメタデータ パッケージを取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Recipients](../../groupdocs.metadata.formats.email/emailpackage/recipients) { get; set; } | 電子メール受信者の配列を取得または設定します。 |
| [Sender](../../groupdocs.metadata.formats.email/emailpackage/sender) { get; } | 送信者のメールアドレスを取得します。 |
| [Subject](../../groupdocs.metadata.formats.email/emailpackage/subject) { get; set; } | メールの件名を取得または設定します。 |

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

* [保存したメールの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+saved+Emails)

### 関連項目

* class [EmailPackage](../emailpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Email](../../groupdocs.metadata.formats.email)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
