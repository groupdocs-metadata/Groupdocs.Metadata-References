---
title: WordProcessingFormat
second_title: GroupDocs.Metadata for .NET API リファレンス
description: さまざまなワード プロセッシング ドキュメントのサブフォーマットを定義します
type: docs
weight: 1260
url: /ja/net/groupdocs.metadata.formats.document/wordprocessingformat/
---
## WordProcessingFormat enumeration

さまざまなワード プロセッシング ドキュメントのサブフォーマットを定義します。

```csharp
public enum WordProcessingFormat
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Unknown | `0` | フォーマットが認識されていません。 |
| Doc | `1` | .DOC Word 形式を表します。 拡張子が .doc のファイルは、Microsoft Word またはその他のワード プロセッシング アプリケーションによってバイナリ ファイル形式で生成されたドキュメントを表します。画像、 形式のデータ、プレーン テキスト、グラフ、チャート、埋め込みオブジェクト、リンク、ページ、ページの書式設定、印刷設定など、さまざまな種類のデータを含めることができます. このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/doc/). |
| Docm | `2` | .DOCM Word 形式を表します。 DOCM ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 DOCX ファイル形式に似ていますが、マクロを実行できるため、DOCX とは異なります。 DOCX と同様に、DOCM ファイルには、テキスト、画像、 表、図形、グラフ、その他のコンテンツを保存できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docm/). |
| Docx | `3` | .DOCX Word 形式を表します。 DOCX は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年から Microsoft Office 2007 のリリースとともに導入され、この新しいドキュメント形式の構造は、 プレーン バイナリから XML の組み合わせに変更されました。およびバイナリ ファイル. Docx ファイルは、Word 2007 およびラテラル バージョンで開くことができますが、DOC ファイル拡張子をサポートする以前のバージョンの MS Word では開くことができません. このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docx/). |
| Dot | `4` | .DOT Word 形式を表します。 .DOT 拡張子を持つファイルは、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOC または DOCX ファイルを生成するための設定が事前にフォーマットされています。 テンプレート ファイルは、特定のユーザー設定を持つために作成されます。これらから作成される後続のファイルに適用する必要があります。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dot/). |
| Dotx | `5` | .DOTX Word 形式を表します。 DOTX 拡張子を持つファイルは、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOCX ファイルを生成するための設定が事前にフォーマットされています。 テンプレート ファイルは、適用する必要がある特定のユーザー設定を持つために作成されます。これらから作成された後続のフライに. このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotx/). |
| Dotm | `6` | .DOTM Word 形式を表します。 DOTM 拡張子を持つファイルは、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 新しいファイルを作成する場合に再利用するためにユーザー定義の設定を保持すること以外は、一般的な DOCX ファイル形式に似ています。 documents. このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotm/). |
| Odt | `7` | .ODT 形式を表します。 ODT ファイルは、OpenDocument テキスト ファイル形式に基づくワード プロセッシング アプリケーションで作成されたドキュメントのタイプです。 これらは、無料の OpenOffice Writer などのワード プロセッサ アプリケーションで作成され、テキスト、画像などのコンテンツを保持できます。 、オブジェクト、スタイル. このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/odt/). |

### 関連項目

* 名前空間 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->