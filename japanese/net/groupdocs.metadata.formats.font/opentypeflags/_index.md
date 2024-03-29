---
title: OpenTypeFlags
second_title: GroupDocs.Metadata for .NET API リファレンス
description: OpenType フォント ヘッダー フラグを表します
type: docs
weight: 1450
url: /ja/net/groupdocs.metadata.formats.font/opentypeflags/
---
## OpenTypeFlags enumeration

OpenType フォント ヘッダー フラグを表します。

```csharp
[Flags]
public enum OpenTypeFlags : ushort
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | 未定義、フラグなし。 |
| BaselineAtY0 | `1` | y=0. のフォントのベースライン |
| LeftSidebearingAtX0 | `2` | x=0 の左サイドベアリング ポイント (TrueType ラスタライザーにのみ関連). |
| DependOnPointSize | `4` | 命令はポイント サイズによって異なります。 |
| ForceToInteger | `8` | すべての内部スケーラー演算で ppem を整数値に強制します。このビットがクリアされている場合、小数の ppem サイズを使用できます。 |
| AlterAdvanceWidth | `10` | 命令によって、進行幅が変更される場合があります (進行幅は線形にスケーリングされない場合があります). |
| Lossless | `1000` | 最適化変換および/または圧縮を行った結果、フォント データは「ロスレス」です。 |
| Converted | `2000` | フォントが変換されました (互換性のあるメトリックを生成します). |
| Optimized | `4000` | ClearType™ 用に最適化されたフォント。 |
| Resort | `8000` | ラスト リゾート フォント. |

### 関連項目

* 名前空間 [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
