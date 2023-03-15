---
title: XmpArray
second_title: GroupDocs.Metadata for .NET API リファレンス
description: XMP 配列の基本抽象化を表します
type: docs
weight: 3250
url: /ja/net/groupdocs.metadata.standards.xmp/xmparray/
---
## XmpArray class

XMP 配列の基本抽象化を表します。

```csharp
public class XmpArray : XmpValueBase
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpArray](xmparray#constructor)(XmpArrayType, XmpComplexType[]) | の新しいインスタンスを初期化します[`XmpArray`](../xmparray)class. |
| [XmpArray](xmparray#constructor_1)(XmpArrayType, XmpValueBase[]) | の新しいインスタンスを初期化します[`XmpArray`](../xmparray)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArrayType](../../groupdocs.metadata.standards.xmp/xmparray/arraytype) { get; } | XMP 配列のタイプを取得します。 |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | 生の値を取得します。 |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | を取得します[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_2)(DateTime[], XmpArrayType) | を作成します[`XmpArray`](../xmparray)インスタンスは日付配列を形成します. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from)(double[], XmpArrayType) | を作成します[`XmpArray`](../xmparray)インスタンスは double 配列を形成します。 |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_1)(int[], XmpArrayType) | を作成します[`XmpArray`](../xmparray)インスタンス形式の整数配列. |
| static [From](../../groupdocs.metadata.standards.xmp/xmparray/from#from_3)(string[], XmpArrayType) | を作成します[`XmpArray`](../xmparray)インスタンスは文字列配列を形成します. |
| static [From&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/from#from_4)(T[], XmpArrayType) | を作成します[`XmpArray`](../xmparray)の配列からのインスタンス[`XmpComplexType`](../xmpcomplextype). |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | カスタムを使用してプロパティ値を抽出します[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor). |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmparray/getxmprepresentation)() | XMP 値を xml 表現に変換します。 |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | プロパティ値を指定された型の配列に変換します。 |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | プロパティ値を参照型に変換します。 |
| [ToPlatformArray&lt;T&gt;](../../groupdocs.metadata.standards.xmp/xmparray/toplatformarray)() | は[`XmpArray`](../xmparray)プラットフォーム固有の配列に. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | プロパティ値を表す文字列を返します。 |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | プロパティ値を値型に変換します。 |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | プロパティ値を値型に変換します。 |

### 関連項目

* class [XmpValueBase](../xmpvaluebase)
* 名前空間 [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->