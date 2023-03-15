---
title: PresentationFormat
second_title: GroupDocs.Metadata for .NET API リファレンス
description: さまざまなプレゼンテーション サブフォーマットを定義します
type: docs
weight: 1070
url: /ja/net/groupdocs.metadata.formats.document/presentationformat/
---
## PresentationFormat enumeration

さまざまなプレゼンテーション サブフォーマットを定義します。

```csharp
public enum PresentationFormat
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Unknown | `0` | フォーマットが認識されていません。 |
| Ppt | `1` | .PPT PowerPoint 形式を表します。 PPT 拡張子を持つファイルは、SlideShow として表示するスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 PPT ファイルには、テキスト、 箇条書き、画像、マルチメディア、その他の埋め込み OLE オブジェクトなど、さまざまな種類の情報を含めることができます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppt/). |
| Pptx | `2` | .PPTX PowerPoint 形式を表します。 拡張子が PPTX のファイルは、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。 バイナリであった以前のバージョンのプレゼンテーション ファイル形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint オープン XML プレゼンテーション ファイルに基づいています。 format. このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptx/). |
| Potm | `3` | .POTM PowerPoint 形式を表します。 POTM 拡張子の付いたファイルは、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。 POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するために使用できるデフォルト設定が含まれています。 詳しくはこちらこのファイル形式について[ここ](https://wiki.fileformat.com/presentation/potm/). |
| Potx | `4` | .POTX PowerPoint 形式を表します。 拡張子が .POTX のファイルは、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。 この形式は、バイナリ ファイル形式に基づく POT ファイル形式を置き換えるために作成されました。 PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potx/). |
| Pptm | `5` | .PPTM PowerPoint 形式を表します。 PPTM 拡張子を持つファイルは、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応のプレゼンテーション ファイルです。 これらは PPTX ファイルに似ていますが、ラテラルではマクロを実行できないという違いがあります。マクロを含めることができます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptm/). |
| Pps | `6` | .PPS PowerPoint 形式を表します。 PPS、PowerPoint スライド ショー、ファイルは、スライド ショーの目的で Microsoft PowerPoint を使用して作成されます。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pps/). |
| Ppsx | `7` | .PPSX PowerPoint 形式を表します。 PPSX、Power Point スライド ショー、ファイルは Microsoft PowerPoint 2007 以降を使用してスライド ショー用に作成されます。 Microsoft PowerPoint 97-2003 バージョンでサポートされていた PPS ファイル形式の更新です。 . このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsx/). |
| Ppsm | `8` | .PPSM PowerPoint 形式を表します。 PPSM 拡張子を持つファイルは、Microsoft PowerPoint 2007 以降で作成されたマクロ対応のスライド ショー ファイル形式を表します。 別の同様のファイル形式は PPTM です。 Slide Show このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsm/). |
| Pot | `9` | .POT PowerPoint 形式を表します。 拡張子が .POT のファイルは、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 これらのバージョンの Microsoft PowerPoint で作成されたファイルは、Office OpenXML ファイル形式で作成されたものと比較して、バイナリ形式です。 PowerPoint の上位バージョンを使用してください。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pot/). |

### 関連項目

* 名前空間 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->