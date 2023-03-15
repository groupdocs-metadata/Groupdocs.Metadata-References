---
title: FileType
second_title: GroupDocs.Metadata for .NET API リファレンス
description: ファイルの種類のメタデータ パッケージを取得します
type: docs
weight: 20
url: /ja/net/groupdocs.metadata.formats.document/spreadsheetrootpackage/filetype/
---
## SpreadsheetRootPackage.FileType property

ファイルの種類のメタデータ パッケージを取得します。

```csharp
public SpreadsheetTypePackage FileType { get; }
```

### プロパティ値

ファイルの種類のメタデータ パッケージ.

### 例

この例は、ロードされたスプレッドシートの正確なタイプを検出し、いくつかの追加のファイル形式情報を抽出する方法を示しています.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.SpreadsheetFormat);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### 関連項目

* class [SpreadsheetTypePackage](../../spreadsheettypepackage)
* class [SpreadsheetRootPackage](../../spreadsheetrootpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Document](../../spreadsheetrootpackage)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->