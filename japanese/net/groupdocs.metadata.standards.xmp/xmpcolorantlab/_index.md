---
title: XmpColorantLab
second_title: GroupDocs.Metadata for .NET API リファレンス
description: LAB 着色剤を表します
type: docs
weight: 3330
url: /ja/net/groupdocs.metadata.standards.xmp/xmpcolorantlab/
---
## XmpColorantLab class

LAB 着色剤を表します。

```csharp
public sealed class XmpColorantLab : XmpColorantBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpColorantLab](xmpcolorantlab#constructor)() | の新しいインスタンスを初期化します[`XmpColorantLab`](../xmpcolorantlab)class. |
| [XmpColorantLab](xmpcolorantlab#constructor_1)(sbyte, sbyte, double) | の新しいインスタンスを初期化します[`XmpColorantLab`](../xmpcolorantlab)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/a) { get; set; } | A コンポーネントを取得または設定します。 |
| [B](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/b) { get; set; } | B コンポーネントを取得または設定します。 |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | 色の種類を取得または設定します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [L](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/l) { get; set; } | L コンポーネントを取得または設定します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | 色が定義されている色空間を取得します。次のいずれか: CMYK、RGB、LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | で使用される名前空間 URI を取得します[`XmpComplexType`](../xmpcomplextype)インスタンス. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | で使用される名前空間プレフィックスを取得します[`XmpComplexType`](../xmpcomplextype)インスタンス. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | スウォッチの名前を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | 指定されたプレフィックスに関連付けられた名前空間 URI を取得します。 |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | 文字列に含まれる値を XMP 形式で返します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | を返しますStringこのインスタンスを表す. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [MaxL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/maxl) | コンポーネント L の最大値. |
| const [MinL](../../groupdocs.metadata.standards.xmp/xmpcolorantlab/minl) | コンポーネント L 最小値. |

### 関連項目

* class [XmpColorantBase](../xmpcolorantbase)
* 名前空間 [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->