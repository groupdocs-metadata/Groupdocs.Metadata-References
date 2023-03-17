---
title: TiffTagID
second_title: GroupDocs.Metadata for .NET API リファレンス
description: TIFF タグの ID を定義します
type: docs
weight: 2100
url: /ja/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

TIFF タグの ID を定義します。

```csharp
public enum TiffTagID : ushort
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| GpsVersionID | `0` | GPSInfoIFD のバージョンを示します。 |
| GpsLatitudeRef | `1` | 緯度が北緯か南緯かを示します。 |
| GpsLatitude | `2` | 緯度を示します。 |
| GpsLongitudeRef | `3` | 経度が東経か西経かを示します。 |
| GpsLongitude | `4` | 経度を示します。 |
| GpsAltitudeRef | `5` | 基準高度として使用される高度を示します。 |
| GpsAltitude | `6` | GPSAltitudeRef. の参照に基づく高度を示します。 |
| GpsTimeStamp | `7` | 時刻を UTC (協定世界時) で示します。 |
| GpsSatellites | `8` | は、測定に使用された GPS 衛星を示します。 |
| GpsStatus | `9` | 画像が記録されたときの GPS 受信機のステータスを示します。 |
| GpsMeasureMode | `10` | GPS 測定モードを示します。 |
| GpsDop | `11` | GPS DOP (データの精度) を示します。 |
| GpsSpeedRef | `12` | GPS受信機の移動速度を表す単位を示します |
| GpsSpeed | `13` | GPS 受信機の移動速度を示します。 |
| GpsTrackRef | `14` | GPS 受信機の移動方向を示す基準を示します。 |
| GpsTrack | `15` | GPS 受信機の移動方向を示します。 |
| GpsImgDirectionRef | `16` | 撮影時の画像の方向を示すための基準を示します。 |
| GpsImgDirection | `17` | キャプチャされたときの画像の方向を示します。 |
| GpsMapDatum | `18` | GPS 受信機が使用する測地データを示します。 |
| GpsDestLatitudeRef | `19` | 目的地点の緯度が北緯か南緯かを示します。 |
| GpsDestLatitude | `20` | 目的地の緯度を示します。 |
| GpsDestLongitudeRef | `21` | 目的地の経度が東経か西経かを示します。 |
| GpsDestLongitude | `22` | 目的地の経度を示します。 |
| GpsDestBearingRef | `23` | 目的地点に方位を与えるために使用される参照を示します。 |
| GpsDestBearing | `24` | 目的地までの方位を示します。 |
| GpsDestDistanceRef | `25` | 目的地までの距離を表す単位を示します。 |
| GpsDestDistance | `26` | 目的地までの距離を示します。 |
| GpsProcessingMethod | `27` | 位置検索に使用した方法の名前を記録した文字列。 |
| GpsAreaInformation | `28` | GPSエリアの名前を記録した文字列. |
| GpsDateStamp | `29` | UTC (協定世界時) を基準とした日時情報を記録する文字列。 |
| GpsDifferential | `30` | 差分補正が GPS 受信機に適用されているかどうかを示します。 |
| GpsHPositioningError | `31` | このタグは、水平位置の誤差をメートル単位で示します。 |
| NewSubfileType | `254` | このサブファイルに含まれるデータの種類の一般的な指標. |
| SubfileType | `255` | このサブファイルに含まれるデータの種類の一般的な指標。 このフィールドは非推奨です。代わりに NewSubfileType フィールドを使用する必要があります |
| ImageWidth | `256` | 画像の列数、つまりスキャン ラインあたりのピクセル数. |
| ImageLength | `257` | イメージ内の行数 (スキャン ラインと呼ばれることもあります)。 |
| BitsPerSample | `258` | コンポーネントあたりのビット数. |
| Compression | `259` | 画像データで使用される圧縮スキーム. |
| PhotometricInterpretation | `262` | 画像データの色空間. |
| Threshholding | `263` | グレーの陰影を表す白黒の TIFF ファイルの場合、グレーから白黒のピクセルに変換するために使用される技術. |
| CellWidth | `264` | ディザリングまたは ハーフトーン 2 値ファイルの作成に使用されるディザリングまたはハーフトーン マトリックスの幅。 |
| CellLength | `265` | ディザ処理または ハーフトーン処理されたバイレベル ファイルを作成するために使用されるディザ処理またはハーフトーン処理マトリックスの長さ. |
| FillOrder | `266` | バイト内のビットの論理順序。 |
| DocumentName | `269` | この画像がスキャンされたドキュメントの名前. |
| ImageDescription | `270` | 画像の主題を説明する文字列. |
| Make | `271` | スキャナの製造元。 |
| Model | `272` | スキャナのモデル名または番号. |
| StripOffsets | `273` | 各ストリップの、そのストリップのバイト オフセット。 |
| Orientation | `274` | 行と列に対する画像の向き。 |
| SamplesPerPixel | `277` | ピクセルあたりのコンポーネント数。 |
| RowsPerStrip | `278` | ストリップあたりの行数。 |
| StripByteCounts | `279` | 各ストリップについて、圧縮後のストリップ内のバイト数. |
| MinSampleValue | `280` | 使用される最小コンポーネント値。 |
| MaxSampleValue | `281` | 使用される最大コンポーネント値。 |
| XResolution | `282` | ImageWidth 方向の ResolutionUnit あたりのピクセル数. |
| YResolution | `283` | ImageLength 方向の ResolutionUnit あたりのピクセル数. |
| PlanarConfiguration | `284` | 各ピクセルのコンポーネントの格納方法. |
| PageName | `285` | この画像がスキャンされたページの名前. |
| XPosition | `286` | 画像の X 位置。 |
| YPosition | `287` | 画像の Y 位置。 |
| FreeOffsets | `288` | TIFF ファイル内の連続する未使用バイトの文字列ごとに、文字列のバイト オフセット。 |
| FreeByteCounts | `289` | TIFF ファイル内の連続する未使用バイトの文字列ごとに、文字列内のバイト数. |
| GrayResponseUnit | `290` | GrayResponseCurve に含まれる情報の精度。 |
| GrayResponseCurve | `291` | グレースケール データの場合、可能な各ピクセル値の光学濃度。 |
| T4Options | `292` | T4 エンコード オプション。 |
| T6Options | `293` | T6 エンコード オプション。 |
| ResolutionUnit | `296` | XResolution および YResolution の測定単位。 |
| PageNumber | `297` | この画像がスキャンされたページのページ番号. |
| TransferFunction | `301` | 画像の伝達関数を表形式で記述します。ピクセル コンポーネントは、 ガンマ補正、圧伸、不均一な量子化、またはその他の方法での コーディングが可能です。 TransferFunction は、ピクセル コンポーネントを non-linear BitsPerSample (例: 8 ビット) 形式から 16 ビット線形形式にマッピングします。 |
| Software | `305` | イメージの作成に使用されたソフトウェア パッケージの名前とバージョン番号. |
| DateTime | `306` | イメージ作成日時. |
| Artist | `315` | 画像を作成した人. |
| HostComputer | `316` | イメージの作成時に使用されていたコンピューターおよび/またはオペレーティング システム. |
| Predictor | `317` | このセクションでは、一部の画像の圧縮率を大幅に改善する Predictor を定義します。 |
| WhitePoint | `318` | 画像の白色点の色度. |
| PrimaryChromaticities | `319` | 画像の原色の色度. |
| ColorMap | `320` | パレットカラー画像のカラーマップ. |
| HalftoneHints | `321` | HalftoneHints フィールドの目的は、 色調の詳細を保持する測色的に指定された画像内の グレー レベルの範囲をハーフトーン関数に伝えることです。 |
| TileWidth | `322` | ピクセル単位のタイル幅。これは各タイルの列数です. |
| TileLength | `323` | ピクセル単位のタイルの長さ (高さ)。これは、各タイルの行数です. |
| TileOffsets | `324` | タイルごとに、圧縮されてディスクに格納されたタイルのバイト オフセット。 オフセットは、TIFF ファイルの先頭に対して指定されます。 これは、各タイルが他のタイルの位置とは独立した位置を持つことを意味することに注意してください. |
| TileByteCounts | `325` | 各タイルの、そのタイルの (圧縮された) バイト数。 |
| InkSet | `332` | 分離された (PhotometricInterpretation=5) 画像で使用されるインクのセット. |
| InkNames | `333` | 分離された (PhotometricInterpretation=5) 画像で使用される各インクの名前、 連結された NUL で終わる ASCII 文字列のリストとして書き込まれます。 |
| NumberOfInks | `334` | インクの数。余分なサンプルがない限り、通常は SamplesPerPixel と同じです。 |
| DotRange | `336` | 0% ドットと 100% ドットに対応するコンポーネント値。 DotRange[0] は 0% ドットに対応し、DotRange[1] は 100% ドットに対応します。 |
| ExtraSamples | `338` | 追加コンポーネントの説明. |
| SampleFormat | `339` | このフィールドは、ピクセル内の各データ サンプルを解釈する方法を指定します。 |
| SMinSampleValue | `340` | このフィールドは最小サンプル値を指定します。 |
| SMaxSampleValue | `341` | この新しいフィールドは、最大サンプル値を指定します。 |
| TransferRange | `342` | TransferFunction の範囲を拡張します。 |
| JpegProc | `512` | このフィールドは、圧縮データの生成に使用される JPEG プロセスを示します。 |
| JpegInterchangeFormat | `513` | このフィールドは、TIFF ファイルに JPEG 交換フォーマット ビットストリームが存在するかどうかを示します。 |
| JpegInterchangeFormatLength | `514` | このフィールドは、JPEG 交換フォーマットのバイト単位の長さを示します |
| JpegRestartInterval | `515` | このフィールドは、圧縮された画像データで使用される再起動間隔の長さを示します。 |
| JpegLosslessPredictors | `517` | このフィールドは、コンポーネントごとに 1 つずつ、無損失予測子選択値のリストを指します。 |
| JpegPointTransforms | `518` | このフィールドは、コンポーネントごとに 1 つの点変換値のリストを指します。 |
| JpegQTables | `519` | このフィールドは、コンポーネントごとに 1 つの量子化テーブルへのオフセットのリストを指します。 |
| JpegDCTables | `520` | このフィールドは、コンポーネントごとに 1 つの DC ハフマン テーブルまたは lossless ハフマン テーブルへのオフセットのリストを指します。 |
| JpegACTables | `521` | このフィールドは、コンポーネントごとに 1 つ、Huffman AC テーブルへのオフセットのリストを指します。 |
| YCbCrCoefficients | `529` | RGB から YCbCr 画像データへの変換の行列係数. |
| YCbCrSubSampling | `530` | 輝度成分に対するクロミナンス成分のサンプリング比. |
| YCbCrPositioning | `531` | 輝度サンプルに対するサブサンプリングされたクロミナンス コンポーネントの位置を指定します。 |
| ReferenceBlackWhite | `532` | 各ピクセル コンポーネントのヘッドルームとフットルームの画像データ値 (コード) のペアを指定します。 |
| Copyright | `33432` | 著作権表示. |
| UserComment | `37510` | 画像のキーワードまたはコメント。 ImageDescription. を補完します |
| Xmp | `700` | XMP メタデータへのポインター。 |
| ImageID | `32781` | OPI 関連. |
| Iptc | `33723` | IPTC (International Press Telecommunications Council) メタデータ. 多くの場合、データ型が誤って LONG として指定されています. |
| Photoshop | `34377` | Photoshop の「画像リソース ブロック」のコレクション。 |
| ImageLayer | `34732` | 画像レイヤー. |
| IccProfile | `34675` | カラープロファイルデータ. |
| ExifIfd | `34665` | すべての EXIF メタデータのコレクションへのポインター。 EXIF はタグではなくフィールド名を使用して、フィールドの内容を示します。 |
| GpsIfd | `34853` | GPS データへのポインター。 |
| Makernotes | `37500` | makernotes データへのポインタ. |
| InteroperabilityIfd | `40965` | Exif 関連の相互運用性 IFD. |
| CameraOwnerName | `42032` | ASCII 文字列としてのカメラ所有者名. |
| BodySerialNumber | `42033` | ASCII 文字列としてのカメラ本体のシリアル番号. |
| CfaPattern | `41730` | は、ワンチップカラーエリアセンサー使用時のイメージセンサーのカラーフィルターアレイ(CFA)の幾何学模様を示します。すべてのセンシング方法に適用されるわけではありません. |
| ExifVersion | `36864` | サポートされている EXIF 標準のバージョン. |
| ComponentsConfiguration | `37121` | 圧縮データ固有の情報。各コンポーネントのチャネルは、1 番目のコンポーネントから 4 番目のコンポーネントまで順番に配置されています。 |
| FlashpixVersion | `40960` | FPXR ファイルでサポートされている Flashpix 形式のバージョン。 FPXR機能がFlashpixフォーマットVer. 1.0 では、ExifVersion と同様に 4 バイトの ASCII として「0100」を記録することで示されます。 |
| ColorSpace | `40961` | 色空間情報タグ(ColorSpace)は必ず色空間指定子として記録されます。 通常、sRGB (=1) は、PC モニターの条件と環境に基づいて色空間を定義するために使用されます。 sRGB 以外の色空間を使用する場合、Uncalibrated (=FFFF.H) が設定されます。 |
| PixelXDimension | `40962` | 圧縮データ固有の情報。圧縮ファイルが記録されるとき、 パディング データまたはリスタート マーカーがあるかどうかに関係なく、意味のある画像の有効な幅がこのタグに記録されます。 |
| PixelYDimension | `40963` | 圧縮データ固有の情報。圧縮ファイルが記録されるとき、 パディング データまたはリスタート マーカーがあるかどうかに関係なく、意味のある画像の有効な高さがこのタグに記録されます。 |
| SceneCaptureType | `41990` | このタグは、撮影されたシーンのタイプを示します。また、画像が撮影されたモードを記録するために使用することもできます. |
| Gamma | `42240` | 係数ガンマの値を示します。 |
| CompressedBitsPerPixel | `37122` | 圧縮データ固有の情報。圧縮画像に使用される圧縮モードは、単位ビット/ピクセルで示されます。 |
| RelatedSoundFile | `40964` | このタグは、画像データに関連する音声ファイルの名前を記録するために使用されます。 ここに記録される関連情報は、Exif オーディオ ファイル名と拡張子 (8 文字 + '.' + 3 文字からなる ASCII 文字列) のみです。 |
| DateTimeOriginal | `36867` | 元の画像データが生成された日時。 DSC の場合、写真が撮影された日時が記録されます。 形式は「YYYY:MM:DD HH:MM:SS」で、時刻は 24 時間形式で表示され、日付と時刻は 1 つの空白文字で区切られます。 |
| DateTimeDigitized | `36868` | 画像がデジタルデータとして保存された日時。 たとえば、画像が DSC によってキャプチャされ、同時にファイルが記録された場合、DateTimeOriginal と DateTimeDigitized は同じ内容になります。 形式は「YYYY:MM:DD HH:MM:SS」で、時刻は 24 時間形式で表示され、日付と時刻は 1 つの空白文字で区切られます。 |
| OffsetTime | `36880` | DateTime タグの時刻の UTC (協定世界時との時差) からのオフセットを記録するタグです。 オフセットを記録する際のフォーマットは「±HH:MM」です。 「±」の部分は「+」または「-」として記録するものとする. |
| OffsetTimeOriginal | `36881` | DateTimeOriginalタグの時刻のUTC(協定世界時との時差)からのオフセットを記録するタグです。 オフセットを記録する際のフォーマットは「±HH:MM」です。 「±」の部分は「+」または「-」として記録するものとする. |
| OffsetTimeDigitized | `36882` | DateTimeDigitized タグの時刻の UTC (協定世界時との時差) からのオフセットを記録するタグです。 オフセットを記録する際のフォーマットは「±HH:MM」です。 「±」の部分は「+」または「-」として記録するものとする. |
| SubsecTime | `37520` | DateTime タグの秒の端数を記録するために使用されるタグ。 |
| SubsecTimeOriginal | `37521` | DateTimeOriginal タグの秒の端数を記録するために使用されるタグ。 |
| SubsecTimeDigitized | `37522` | DateTimeDigitized タグの秒の端数を記録するために使用されるタグ. |
| ExposureTime | `33434` | 秒単位の露出時間 (sec). |
| FNumber | `33437` | Fナンバー. |
| ExposureProgram | `34850` | 写真撮影時に露出を設定するためにカメラが使用するプログラムのクラス。 |
| SpectralSensitivity | `34852` | 使用するカメラの各チャンネルの分光感度を示します。 タグ値は、ASTM 技術委員会によって開発された標準と互換性のある ASCII 文字列です。 |
| PhotographicSensitivity | `34855` | このタグは、画像が撮影されたときのカメラまたは入力デバイスの感度を示します。 |
| Oecf | `34856` | ISO 14524 で指定されている光電気変換関数 (OECF) を示します。 OECF は、カメラの光入力と画像値の関係です。 |
| SensitivityType | `34864` | SensitivityType タグは、ISO12232 のどのパラメータが PhotographicSensitivity タグであるかを示します。 任意のタグですが、PhotographicSensitivity タグを記録する際に記録する必要があります。 |
| StandardOutputSensitivity | `34865` | このタグは、ISO 12232 で定義されたカメラまたは入力デバイスの標準出力感度値を示します。 このタグを記録する場合、PhotographicSensitivity および SensitivityType タグも記録する必要があります。 |
| RecommendedExposureIndex | `34866` | このタグは、ISO 12232 で定義されたカメラまたは入力デバイスの推奨露出指標値を示します。 このタグを記録する場合、PhotographicSensitivity および SensitivityType タグも記録する必要があります。 |
| IsoSpeed | `34867` | このタグは、ISO 12232 で定義されているカメラまたは入力デバイスの ISO 速度値を示します。 このタグを記録する場合、PhotographicSensitivity および SensitivityType タグも記録する必要があります。 |
| ISOSpeedLatitudeYyy | `34868` | このタグは、ISO 12232 で定義されているカメラまたは入力デバイスの ISO 速度緯度 yyy 値を示します。 |
| ISOSpeedLatitudeZzz | `34869` | このタグは、ISO 12232 で定義されているカメラまたは入力デバイスの ISO スピード ラティチュード zzz 値を示します。 |
| ShutterSpeedValue | `37377` | シャッター速度。単位は APEX (Additive System of Photographic Exposure) 設定です。 |
| ApertureValue | `37378` | レンズの絞り。単位はAPEX値です. |
| BrightnessValue | `37379` | 明るさの値。単位は APEX 値です。 |
| ExposureBiasValue | `37380` | 露出バイアス。単位はAPEX値です. |
| MaxApertureValue | `37381` | レンズの最小 F 値。単位はAPEX値です. |
| SubjectDistance | `37382` | 被写体までの距離 (メートル単位)。 |
| MeteringMode | `37383` | 測光モード. |
| LightSource | `37384` | 光源の種類. |
| Flash | `37385` | このタグは、画像が撮影されたときのフラッシュの状態を示します。 ビット 0 はフラッシュ発光ステータスを示し、ビット 1 と 2 はフラッシュ リターン ステータスを示し、 ビット 3 と 4 はフラッシュ モードを示し、ビット 5 はフラッシュ機能が存在するかどうかを示し、ビット 6 は「赤目」モードを示します。 |
| SubjectArea | `37396` | このタグは、シーン全体における主な被写体の位置と範囲を示します。 |
| FocalLength | `37386` | レンズの実際の焦点距離 (mm)。 35mmフィルムカメラの焦点距離への換算は行いません。 |
| FlashEnergy | `41483` | ビーム キャンドル パワー秒 (BCPS) で測定された、画像がキャプチャされた時点のストロボ エネルギーを示します。 |
| SpatialFrequencyResponse | `41484` | このタグは、ISO 12233 で指定されているように、カメラまたは入力デバイスの空間周波数テーブルと、画像幅方向、 画像高さ、および対角方向の SFR 値を記録します。 |
| FocalPlaneXResolution | `41486` | カメラの焦点面の FocalPlaneResolutionUnit あたりの画像幅 (X) 方向のピクセル数を示します。 |
| FocalPlaneYResolution | `41487` | カメラの焦点面の FocalPlaneResolutionUnit あたりの像の高さ (Y) 方向のピクセル数を示します。 |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution および FocalPlaneYResolution を測定するための単位を示します。この値は、ResolutionUnit. と同じです。 |
| SubjectLocation | `41492` | シーン内の主被写体の位置を示します。 このタグの値は、Rotation タグによる回転処理の前に、左端を基準とした主被写体の中心のピクセルを表します。 最初の値は X 列番号を示し、2 番目の値は Y 行番号を示します。 |
| ExposureIndex | `41493` | 画像のキャプチャ時にカメラまたは入力デバイスで選択された露出インデックスを示します。 |
| SensingMethod | `41495` | カメラまたは入力デバイスのイメージ センサーの種類を示します。 |
| FileSource | `41728` | 画像ソースを示します。 DSC が画像を記録した場合、このタグ値は常に 3. に設定されます。 |
| SceneType | `41729` | シーンの種類を示します。 DSC が画像を記録した場合、このタグ値は常に 1 に設定され、画像が直接撮影されたことを示します。 |
| CustomRendered | `41985` | このタグは、出力に合わせてレンダリングするなど、画像データに対する特別な処理の使用を示します。 |
| ExposureMode | `41986` | このタグは、画像が撮影されたときに設定された露出モードを示します。自動ブラケット モードでは、 カメラは同じシーンの一連のフレームを異なる露出設定で撮影します。 |
| WhiteBalance | `41987` | このタグは、画像が撮影されたときに設定されたホワイトバランスモードを示します. |
| DigitalZoomRatio | `41988` | このタグは、画像が撮影されたときのデジタル ズーム倍率を示します。 記録された値の分子が 0 の場合、デジタル ズームが使用されなかったことを示します。 |
| FocalLengthIn35mmFilm | `41989` | このタグは、35mm フィルム カメラを想定した等価焦点距離を mm 単位で示します。 値 0 は、焦点距離が不明であることを意味します。このタグは FocalLength タグとは異なることに注意してください。 |
| GainControl | `41991` | このタグは、全体的なイメージ ゲイン調整の度合いを示します。 |
| Contrast | `41992` | このタグは、画像が撮影されたときにカメラによって適用されたコントラスト処理の方向を示します. |
| Saturation | `41993` | このタグは、画像が撮影されたときにカメラによって適用された飽和処理の方向を示します. |
| Sharpness | `41994` | このタグは、画像が撮影されたときにカメラによって適用されたシャープネス処理の方向を示します. |
| DeviceSettingDescription | `41995` | このタグは、特定のカメラ モデルの撮影条件に関する情報を示します。 |
| SubjectDistanceRange | `41996` | 被写体までの距離を表すタグです。 |
| CompositeImage | `42080` | 記録画像が合成画像※かどうかを示すタグです。 |
| SourceImageNumberOfCompositeImage | `42081` | このタグは、合成画像のためにキャプチャされたソース画像 (仮に記録された画像) の数を示します。 |
| SourceExposureTimesOfCompositeImage | `42082` | 合成画像の場合、このタグは、キャプチャされたソース画像 (仮に記録された画像) のそれぞれの露光時間など、 合成画像を生成するための露光の露光時間に関連するパラメータを記録します。 |
| Temperature | `37888` | 撮影時の周囲の状況としての温度。たとえば、写真家がカメラを持っていた部屋の温度。単位は℃です。 |
| Humidity | `37889` | 撮影時の周囲の状況としての湿度。たとえば、写真家がカメラを持っていた部屋の湿度。単位は%です。 |
| Pressure | `37890` | 撮影時の周囲の状況としての圧力。 たとえば、写真家がカメラを持っていた部屋の雰囲気または海の下の水圧。 単位はhPa. |
| WaterDepth | `37891` | 水中撮影時のカメラの水深など、撮影時の周囲の状況としての水深。単位は m. |
| Acceleration | `37892` | 撮影時の周囲の状況としての加速度 (方向に関係なくスカラー)。たとえば、写真家が撮影時に乗った車両の運転加速度。 単位は mGal (10-5 m/s2). |
| CameraElevationAngle | `37893` | 高低。撮影時の周囲の状況として、カメラの向き（撮影光軸）の角度。単位は度(°). |
| ImageUniqueID | `42016` | このタグは、各画像に一意に割り当てられた識別子を示します。 |
| LensSpecification | `42034` | このタグには、撮影に使用されたレンズの仕様情報である、最短焦点距離、最長焦点距離、最短焦点距離における最小 F 値、 、および最大焦点距離における最小 F 値が記述されています。 |
| LensMake | `42035` | このタグは、レンズの製造元を ASCII 文字列として記録します。 |
| LensModel | `42036` | このタグは、レンズのモデル名とモデル番号を ASCII 文字列として記録します。 |
| LensSerialNumber | `42037` | 撮影に使用した交換レンズのシリアルナンバーをASCII文字列で記録したタグです。 |

### 関連項目

* 名前空間 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
