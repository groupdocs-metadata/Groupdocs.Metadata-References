---
title: ImageResourceID
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 画像リソースの標準 ID 番号すべてのファイル形式がすべての ID を使用するわけではありません一部の情報はファイルの他のセクションに保存される場合があります.
type: docs
weight: 1750
url: /ja/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

画像リソースの標準 ID 番号。すべてのファイル形式がすべての ID を使用するわけではありません。一部の情報は、ファイルの他のセクションに保存される場合があります.

```csharp
public enum ImageResourceID
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo 構造体。 Photoshop API ガイド PDF ドキュメントの付録 A を参照してください。 |
| NamesOfAlphaChannels | `1006` | 一連の Pascal 文字列としてのアルファ チャネルの名前。 |
| Caption | `1008` | Pascal 文字列としてのキャプション。 |
| BorderInformation | `1009` | ボーダー情報。 ボーダー幅の固定数 (実数 2 バイト、端数 2 バイト)、 およびボーダー単位の 2 バイト (1 = インチ、2 = cm、3 = ポイント、4 = パイカ、5 = 列) が含まれます。 |
| BackgroundColor | `1010` | 背景色. [続きを見る。](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | フラグを出力します。 一連の 1 バイトのブール値 ([ページ設定] ダイアログを参照): ラベル、トリミング マーク、カラー バー、レジストレーション マーク、ネガ、反転、補間、キャプション、印刷フラグ。 |
| Grayscale | `1012` | グレースケールおよびマルチチャネル ハーフトーン情報。 |
| ColorHalftoning | `1013` | カラーハーフトーン情報. |
| DuotoneHalftoning | `1014` | ダブルトーンハーフトーン情報. |
| GrayscaleFunction | `1015` | グレースケールおよびマルチチャネル伝達関数. |
| ColorTransferFunctions | `1016` | 色伝達関数. |
| DuotoneTransferFunctions | `1017` | ダブルトーン伝達関数. |
| DuotoneImageInformation | `1018` | ダブルトーン画像情報. |
| EPSOptions | `1021` | EPS オプション. |
| QuickMaskInformation | `1022` | クイック マスク情報。クイック マスク チャネル ID を含む 2 バイト。マスクが最初に空であったかどうかを示す 1 バイトのブール値. |
| LayerStateInformation | `1024` | 層状態情報。ターゲット レイヤーのインデックスを含む 2 バイト (0 = 一番下のレイヤー). |
| WorkingPath | `1025` | 作業パス (保存されません)。参照 参照 パス リソース形式. |
| LayersGroupInformation | `1026` | レイヤーグループ情報。 ドラッグするグループのグループ ID を含むレイヤーごとに 2 バイト。グループ内のレイヤーは、同じグループ ID. を持っています。 |
| Iptc | `1028` | IPTC-NAA レコード。ファイル情報... 情報が含まれます。 Documentation フォルダの IPTC フォルダにあるドキュメントを参照してください。 |
| ImageModeForRawFormat | `1029` | raw 形式ファイルの画像モード。 |
| JpegQuality | `1030` | JPEG 品質。プライベート. |
| GridAndGuidesInfoPhotoshop4 | `1032` | グリッドとガイドの情報。 |
| ThumbnailResourcePhotoshop4 | `1033` | Photoshop 4.0 専用のサムネイル リソース。 |
| CopyrightFlagPhotoshop4 | `1034` | 著作権フラグ。画像が著作権で保護されているかどうかを示すブール値。プロパティ スイートを介して、またはファイル情報でユーザーが設定できます... |
| UrlPhotoshop4 | `1035` | URL。 Uniform Resource Locator を持つテキスト文字列のハンドル。プロパティ スイートを介して、またはファイル情報でユーザーが設定できます... |
| ThumbnailResourcePhotoshop5 | `1036` | サムネイル リソース (リソース 1033 に代わるもの)。参照 参照 サムネイル リソース形式. |
| GlobalAnglePhotoshop5 | `1037` | グローバル角度。 0 ～ 359 の整数を含む 4 バイト。これはエフェクト レイヤーのグローバルな照明角度です。存在しない場合は、30. と見なされます |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC プロファイル。 ICC (International Color Consortium) 形式のプロファイルの raw バイト。 Documentation フォルダの ICC1v42_2006-05.pdf と Sample Code\Common\Includes. の icProfileHeader.h を参照してください。 |
| WatermarkPhotoshop5 | `1040` | 透かし。 1バイト. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC タグなしプロファイル。ファイルを開くときに想定されるプロファイル処理を無効にする 1 バイト。 1 = 意図的にタグ付けされていません。 |
| TransparencyIndexPhotoshop6 | `1047` | 透明度インデックス。透明色のインデックスの 2 バイト (存在する場合)。 |
| GlobalAltitudePhotoshop6 | `1049` | グローバル高度。高度の 4 バイト エントリ。 |
| SlicesPhotoshop6 | `1050` | スライス (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | ワークフロー URL。ユニコード文字列。フォトショップ 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | アルファ識別子。 4 バイトの長さの後に、アルファ識別子ごとにそれぞれ 4 バイトが続きます。 |
| UrlListPhotoshop6 | `1054` | URL 内部リスト。 URL の 4 バイト カウント。その後に、各カウントの 4 バイト長、4 バイト ID、および Unicode 文字列が続きます。 |
| VersionInfoPhotoshop6 | `1057` | バージョン情報。 4 バイト バージョン、1 バイト hasRealMergedData 、Unicode 文字列: ライター名、Unicode 文字列: リーダー名、4 バイト ファイル バージョン. |
| ExifData1Photoshop7 | `1058` | EXIF データ 1、[続きを見る](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf). |
| ExifData3Photoshop7 | `1059` | [EXIF データ 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP メタデータ。 XML 記述としてのファイル情報、[続きを見る](http://www.adobe.com/devnet/xmp). |
| CaptionDigestPhotoshop7 | `1061` | キャプション ダイジェスト。 16 バイト: RSA データ セキュリティ、MD5 メッセージ ダイジェスト アルゴリズム. |
| PrintScalePhotoshop7 | `1062` | スケールを印刷します。 2 バイト スタイル (0 = 中央揃え、1 = 収まるサイズ、2 = ユーザー定義)。 4 バイト x 位置 (浮動小数点)。 4 バイトの y 位置 (浮動小数点)。 4 バイト スケール (浮動小数点). |
| PixelAspectRatio | `1064` | ピクセルの縦横比。 4 バイト (バージョン = 1 または 2)、倍精度 8 バイト、ピクセルの x / y。 バージョン 2、NTSC と PAL の値を修正しようとしていますが、以前は約 1 倍オフでした。 5%. |
| LayerComps | `1065` | レイヤー構成。 4 バイト (記述子バージョン = 16)、Descriptor. |
| LayerSelectionIds | `1069` | レイヤー選択 ID。 2 バイト カウント、カウントごとに以下が繰り返されます: 4 バイト レイヤー ID. |
| PrintInfoCS2 | `1071` | 印刷情報 (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | レイヤ グループの有効な ID。 ドキュメント内のレイヤーごとに 1 バイト。リソースの長さだけ繰り返されます。 注: レイヤー グループには開始マーカーと終了マーカーがあります (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | カラー サンプラー リソース。古い形式の ID 1038 も参照してください。 |
| MeasurementScaleCS3 | `1074` | 測定スケール。 4 バイト (記述子バージョン = 16)、Descriptor. |
| TimelineInformationCS3 | `1075` | タイムライン情報。 4 バイト (記述子バージョン = 16)、Descriptor. |
| SheetDisclosureCS3 | `1076` | シート開示。 4 バイト (記述子バージョン = 16)、Descriptor. |
| PrintInformationCS5 | `1082` | 印刷情報 (Photoshop CS5). |
| PrintStyleCS5 | `1083` | 印刷スタイル (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. 変数 Macintosh の OS 固有の情報。 NSPrintInfo. このデータを解釈または使用しないことをお勧めします。 (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE。 変数 Windows の OS 固有の情報。 DEVMODE。 このデータを解釈または使用しないことをお勧めします。 (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | 自動保存ファイルのパス。ユニコード文字列。 (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | 自動保存形式。ユニコード文字列。 (Photoshop CS6). |
| PathSelectionStateCC | `1088` | パス選択状態。 (Photoshop CC). |
| ImageReadyVariables | `7000` | Image Ready 変数。変数定義の XML 表現. |
| ImageReadyDatasets | `7001` | Image Ready データセット. |
| PrintFlagsInformation | `10000` | フラグ情報を出力します。 2 バイト バージョン ( = 1)、 1 バイト センター クロップ マーク、 1 バイト ( = 0)、4 バイト ブリード幅値、2 バイト ブリード幅スケール。 |

### 関連項目

* 名前空間 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
