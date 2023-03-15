---
title: Flags
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ZIP エントリ フラグを取得します
type: docs
weight: 30
url: /ja/net/groupdocs.metadata.formats.archive/zipfile/flags/
---
## ZipFile.Flags property

ZIP エントリ フラグを取得します。

```csharp
public int Flags { get; }
```

### プロパティ値

ZIP エントリ フラグ。

### 備考

ビット 00: 暗号化されたファイル。 ビット 01: 圧縮オプション。 ビット 02: 圧縮オプション。 ビット 03: データ記述子。 ビット 04: 強化されたデフレ。 ビット 05: 圧縮されたパッチ データ。 ビット 06: 強力な暗号化。 ビット 07 ～ 10: 未使用。 ビット 11: 言語エンコード。 ビット 12: 予約済み。 ビット 13: ヘッダー値をマスクします。 ビット 14 ～ 15: 予約済み。

### 関連項目

* class [ZipFile](../../zipfile)
* 名前空間 [GroupDocs.Metadata.Formats.Archive](../../zipfile)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->