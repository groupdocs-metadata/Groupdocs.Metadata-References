---
title: FileFormat
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 読み込まれたファイルの認識された形式を表します
type: docs
weight: 40
url: /ja/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

読み込まれたファイルの認識された形式を表します。

```csharp
public enum FileFormat
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Unknown | `0` | ファイルの種類が認識されません. |
| Presentation | `1` | プレゼンテーション ファイル. Microsoft PowerPoint で作業する場合、PPTX および PPT 拡張ファイルに精通している必要があります。 audio and embedded objects. このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/). |
| Spreadsheet | `2` | スプレッドシート ファイル。 スプレッドシート ファイルには、行と列の形式でデータが含まれています。 Windows と MacOS オペレーティング システムの両方で利用できるようになった Microsoft Excel などのスプレッドシート ソフトウェア アプリケーションを使用して、そのようなファイルを開いて表示し、編集できます。 同様に、Google スプレッドシートは無料のオンライン スプレッドシート作成および編集ツールで、任意の Web ブラウザから使用できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/). |
| WordProcessing | `3` | ワープロ ファイル。 ワープロ ファイルには、ユーザー情報がプレーン テキストまたはリッチ テキスト形式で含まれています。プレーン テキスト ファイル format には書式設定されていないテキストが含まれており、フォントやページ設定などを適用することはできません。 ページ余白、見出し、箇条書き、数字、およびその他の書式設定機能. このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/). |
| Diagram | `4` | ダイアグラム ファイル. |
| Note | `5` | 電子メモ ファイル。 Microsoft OneNote などのメモ作成プログラムを使用すると、メモを保存するためのセクションとページを含むメモ ファイルを作成、開いて、編集できます。 メモ ドキュメントは、テキスト ドキュメントのように単純なものから、より詳細なものまであります。デジタル画像、オーディオ/ビデオ クリップ、手描きスケッチで構成されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/note-taking/). |
| ProjectManagement | `6` | プロジェクト管理形式. MPP ファイルとは何か、またはその開き方を考えたことはありますか? MPP およびその他の同様のファイルは、Microsoft Project などのプロジェクト管理ソフトウェアによって作成されるプロジェクト ファイル形式です。 プロジェクトファイルは、フォームまたは製品またはサービスで測定可能な出力を取得するためのタスク、リソース、およびそれらのスケジューリングのコレクションです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/project-management/). |
| Pdf | `7` | PDF ファイル. Portable Document Format (PDF) は、1990 年代に Adobe によって作成されたドキュメントの一種です。この ファイル形式の目的は、アプリケーション ソフトウェア、ハードウェア、およびオペレーティング システムに依存しない 形式でドキュメントやその他の参照資料を表現するための標準を導入することでした。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/view/pdf/). |
| Tiff | `8` | TIFF 画像。 TIFF または TIF、タグ付き画像ファイル形式は、このファイル形式標準に準拠するさまざまな デバイスでの使用を意図したラスター画像を表します。このファイル形式の詳細 [ここ](https://wiki.fileformat.com/image/tiff/). |
| Jpeg | `9` | JPEG 画像。 JPEG は、非可逆圧縮方式を使用して保存される画像形式の一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg/). |
| Psd | `10` | PSD 画像。 PSD、Photoshop ドキュメントは、グラフィックスの設計と開発に使用される Adobe Photoshop のネイティブ ファイル形式を表します。 PSD ファイルには、画像レイヤー、調整レイヤー、レイヤー マスク、注釈、ファイル情報、キーワード、その他の Photoshop 固有の要素が含まれる場合があります。 . このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/psd/). |
| Jpeg2000 | `11` | JPEG2000 画像。 JPEG 2000 (JPX) は、画像符号化システムであり、最先端の画像圧縮規格です。ウェーブレット技術を使用して設計された JPEG 2000 は、あらゆる品質のロスレス コンテンツを一度にコーディングできます。詳しくは このファイル形式について[ここ](https://wiki.fileformat.com/image/jp2/). |
| Gif | `12` | GIF 画像。 GIF または Graphical Interchange Format は、高度に圧縮された画像の一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/gif/). |
| Png | `13` | PNG 画像。 PNG、Portable Network Graphics は、可逆圧縮を使用するラスター画像ファイル形式の一種を指します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/png/). |
| Bmp | `14` | BMP イメージ。 拡張子が .BMP のファイルは、ビットマップ デジタル イメージの保存に使用されるビットマップ イメージ ファイルを表します。 これらのイメージは、グラフィック アダプタに依存せず、デバイス非依存ビットマップ (DIB) file 形式とも呼ばれます。このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/bmp/). |
| Dicom | `15` | DICOM 画像。 DICOM は Digital Imaging and Communications in Medicine の頭字語で、医療情報学の分野に関連しています。 DICOM は、ファイル形式定義とネットワーク通信プロトコルの組み合わせです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/dicom/). |
| WebP | `16` | WEBP 画像。 Google によって導入された WebP は、ロスレスおよび ロッシー圧縮に基づく最新のラスター Web 画像ファイル形式です。画像サイズを大幅に縮小しながら、同じ画質を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/webp/). |
| Emf | `17` | EMF 画像。 拡張メタファイル形式 (EMF) は、グラフィック画像をデバイスに依存せずに保存します。 EMF のメタファイルは、任意の出力デバイスで解析後に保存された画像をレンダリングできる、時系列の可変長レコードで構成されます。 詳細については、こちらをご覧ください。ファイル形式[ここ](https://wiki.fileformat.com/image/emf/). |
| Wmf | `18` | WMF 画像。 WMF 拡張子を持つファイルは、ベクターおよびビットマップ形式の画像データを格納するための Microsoft Windows メタファイル (WMF) を表します。 より正確には、WMF はデバイスであるグラフィックス ファイル形式のベクター ファイル形式カテゴリに属しますindependent. このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/wmf/). |
| DjVu | `19` | DjVu ファイル. DjVu は、スキャンした文書や書籍、特にテキスト、 図面、画像、写真の組み合わせを含むものを対象としたグラフィック ファイル形式です。 AT&amp;T Labs によって開発されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/djvu/). |
| Wav | `20` | WAV オーディオ ファイル。 WAVE (Waveform Audio File Format) で知られる WAV は、デジタル オーディオ ファイルを格納するための Microsoft の Resource Interchange File Format (RIFF) 仕様のサブセットです。 この形式はビットストリームに圧縮を適用しません。さまざまなサンプリング レートとビットレートでオーディオ録音を保存します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/audio/wav/). |
| Mp3 | `21` | Mp3 オーディオ ファイル。 MP3 拡張子を持つファイルは、MPEG-1 オーディオ レイヤー III または MPEG-2 オーディオ レイヤー III に正式に基づくオーディオ ファイル用にデジタル エンコードされたファイル形式です。 これは、Moving Picture Experts Group (レイヤ 3 オーディオ圧縮を使用する MPEG)。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/audio/mp3/). |
| Avi | `22` | AVI ビデオ。 AVI ファイル形式は、Microsoft によって導入されたオーディオ ビデオ マルチメディア コンテナー ファイル形式です。 Xvid や DivX などのいくつかのコーデック (コーダー/デコーダー) を使用して作成および圧縮されたオーディオおよびビデオ データを保持します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/video/avi/). |
| Flv | `23` | FLV ビデオ。 |
| Asf | `24` | ASF ビデオ。 Advanced Systems Format (ASF) は、主にメディア ストリームの保存と送信を目的として設計されたデジタル マルチメディア コンテナです。圧縮されたオーディオ形式 と、Microsoft が開発した ASF コンテナー内の追加のメタデータ. このファイル形式の詳細[ここ](https://wiki.fileformat.com/video/wmv/). |
| Mov | `25` | QuickTime ビデオ。 Mov または QuickTime ファイル形式は、Apple によって開発されたマルチメディア コンテナです。1 つまたは複数のトラックが含まれます。 各トラックには、ビデオ、オーディオ、テキストなどの特定のタイプのデータが含まれます。 Mov 形式は、両方で互換性があります。 Windows および Macintosh システム. このファイル形式の詳細[ここ](https://wiki.fileformat.com/video/mov/). |
| Matroska | `26` | Matroska マルチメディア コンテナーでエンコードされたビデオ。 |
| Zip | `27` | ZIP アーカイブ。 ZIP ファイル拡張子は、1 つ以上のファイルまたはディレクトリを保持できるアーカイブを表します。 アーカイブは、ZIP ファイルのサイズを縮小するために、含まれるファイルに圧縮を適用できます。 ZIP ファイル形式は、2000 年に公開されました。 1989 年 2 月、ファイルとフォルダーのアーカイブを達成するために Phil Katz によって作成されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/zip/). |
| VCard | `28` | VCard ファイル。 VCF (Virtual Card Format) または vCard は、連絡先情報を保存するためのデジタル ファイル形式です。 この形式は、一般的な情報交換アプリケーション間のデータ交換に広く使用されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/vcf/). |
| Epub | `29` | EPUB 電子書籍。 拡張子が .EPUB のファイルは、発行者と消費者に標準のデジタル出版形式を提供する電子書籍ファイル形式です。 この形式は現在では非常に一般的になっているため、多くの電子書籍リーダーや電子書籍リーダーでサポートされています。 software applications. このファイル形式の詳細[ここ](https://wiki.fileformat.com/ebook/epub/). |
| OpenType | `30` | OpenType フォント。 |
| Dxf | `31` | DXF (Drawing Exchange Format) 図面。 DXF、Drawing Interchange Format、または Drawing Exchange Format は、AutoCAD 図面ファイルのタグ付きデータ表現です。 ファイル内の各要素には、グループ コードと呼ばれるプレフィックス整数番号があります。 学習このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dxf/). |
| Dwg | `32` | DWG 図面。 DWG 拡張子を持つファイルは、2D および 3D 設計データを格納するために使用される独自のバイナリ ファイルを表します。 ASCII ファイルである DXF と同様に、DWG は CAD (コンピュータ支援設計) 図面のバイナリ ファイル形式を表します。 詳細このファイル形式について[ここ](https://wiki.fileformat.com/cad/dwg/). |
| Eml | `33` | EML 電子メール メッセージ。 EML ファイル形式は、Outlook およびその他の関連アプリケーションを使用して保存された電子メール メッセージを表します。 RFC-822 Internet Message Format Standard に準拠するために、ほとんどすべての電子メール クライアントがこのファイル形式をサポートしています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/eml/). |
| Msg | `34` | MSG 電子メール メッセージ。 MSG は、電子メール メッセージ、連絡先、予定、またはその他のタスクを保存するために Microsoft Outlook および Exchange で使用されるファイル形式です。 このようなメッセージには、送信者、受信者、件名、日付、 とメッセージ本文、または連絡先情報、予定の詳細、および 1 つ以上のタスク仕様. このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/msg/). |
| Torrent | `35` | 配布するファイルとフォルダーに関するメタデータを含む torrent ファイル。 |
| Heif | `36` | HEIF/HEIC 画像。 |

### 関連項目

* 名前空間 [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
