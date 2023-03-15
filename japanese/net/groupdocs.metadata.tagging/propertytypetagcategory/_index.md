---
title: PropertyTypeTagCategory
second_title: GroupDocs.Metadata for .NET API リファレンス
description: プロパティの目的ではなくタイプに関する追加情報を含むタグを提供します これらのタグを使用すると外部リソースへの URL リンクを含むメタデータ プロパティフォント色地理位置情報などを説明する プロパティを検出できます
type: docs
weight: 3710
url: /ja/net/groupdocs.metadata.tagging/propertytypetagcategory/
---
## PropertyTypeTagCategory class

プロパティの目的ではなくタイプに関する追加情報を含むタグを提供します。 これらのタグを使用すると、外部リソースへの URL リンクを含むメタデータ プロパティ、フォント、色、地理位置情報などを説明する プロパティを検出できます。

```csharp
public class PropertyTypeTagCategory : TagCategory
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../groupdocs.metadata.tagging/propertytypetagcategory/color) { get; } | 色を説明するプロパティにラベルを付けるタグを取得します. |
| [DigitalSignature](../../groupdocs.metadata.tagging/propertytypetagcategory/digitalsignature) { get; } | デジタル署名にラベルを付けるタグを取得します。 |
| [Font](../../groupdocs.metadata.tagging/propertytypetagcategory/font) { get; } | フォントの特性を記述するプロパティを示すタグを取得します。 |
| [Hash](../../groupdocs.metadata.tagging/propertytypetagcategory/hash) { get; } | ファイル コンテンツのハッシュを保持するプロパティにラベルを付けるタグを取得します。 |
| [Identifier](../../groupdocs.metadata.tagging/propertytypetagcategory/identifier) { get; } | コンテンツの識別子を含むプロパティにラベルを付けるタグを取得します。 |
| [Link](../../groupdocs.metadata.tagging/propertytypetagcategory/link) { get; } | プロパティが外部リソースへのリンクであることを示すタグを取得します。 |
| [Location](../../groupdocs.metadata.tagging/propertytypetagcategory/location) { get; } | プロパティが地理的位置への参照であることを示すタグを取得します。 プロパティには、都市の名前、完全な住所、GPS 座標などを含めることができます. |
| [Measure](../../groupdocs.metadata.tagging/propertytypetagcategory/measure) { get; } | コンテンツの測定された特性であるプロパティを示すタグを取得します。 ファイル サイズ、ページ数、ページ サイズなどです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../groupdocs.metadata.tagging/tagcategory/tostring)() | 現在のオブジェクトを表す文字列を返します。 |

### 関連項目

* class [TagCategory](../tagcategory)
* 名前空間 [GroupDocs.Metadata.Tagging](../../groupdocs.metadata.tagging)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->