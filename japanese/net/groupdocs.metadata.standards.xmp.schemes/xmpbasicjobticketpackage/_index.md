---
title: XmpBasicJobTicketPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: Basic JobTicket 名前空間を表します
type: docs
weight: 3080
url: /ja/net/groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/
---
## XmpBasicJobTicketPackage class

Basic Job-Ticket 名前空間を表します。

```csharp
public sealed class XmpBasicJobTicketPackage : XmpPackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpBasicJobTicketPackage](xmpbasicjobticketpackage)() | の新しいインスタンスを初期化します[`XmpBasicJobTicketPackage`](../xmpbasicjobticketpackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Jobs](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicjobticketpackage/jobs) { get; set; } | ジョブを取得または設定します。 |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 名前空間 URI を取得します。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns プレフィックスを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | から継承された値を設定します[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | から継承された値を設定します[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | から継承された値を設定します[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase). |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 関連項目

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 名前空間 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
