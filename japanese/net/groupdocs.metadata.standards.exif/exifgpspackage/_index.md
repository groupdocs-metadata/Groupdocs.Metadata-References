---
title: ExifGpsPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: EXIF メタデータ パッケージ内の GPS メタデータを表します
type: docs
weight: 2770
url: /ja/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

EXIF メタデータ パッケージ内の GPS メタデータを表します。

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | の新しいインスタンスを初期化します[`ExifGpsPackage`](../exifgpspackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | の参照に基づいて高度を取得または設定します[`AltitudeRef`](./altituderef). 基準単位はメートルです. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | 基準高度として使用される高度を取得または設定します。基準が海抜で高度が海抜の場合は 0 が与えられます。 高度が海抜の場合は 1 が与えられ、高度は絶対値として[`Altitude`](./altitude)tag. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | GPS エリアの名前を記録する文字列を取得または設定します。最初のバイトは使用される文字コードを示し、これに GPS エリアの名前が続きます. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | GPS DOP (データ精度の度合い) を取得または設定します。 2 次元測定では HDOP 値が書き込まれ、3 次元測定では PDOP 値が書き込まれます。 |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | UTC (協定世界時) を基準とした日時情報を記録する文字列を取得または設定します。形式は YYYY:MM:DD. です。 |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | 目的地の GPS 方位を取得または設定します。 値の範囲は 0.00 ～ 359.99 です。 |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | 目的地への方位を示すために使用される GPS 基準を取得または設定します. 「T」は真の方向を表し、「M」は磁気方向を表します. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | 目的地までの GPS 距離を取得または設定します。 |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | 目的地までの距離を表すために使用される GPS 単位を取得または設定します。 「K」、「M」、および「N」はキロメートル、マイル、ノットを表します。 |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | 目的地の GPS 緯度を取得または設定します。 |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | 目的地の緯度が北緯か南緯かを示す GPS 値を取得または設定します。 ASCII 値の「N」は北緯を示し、「S」は南緯を示します。 |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | 目的地の GPS 経度を取得または設定します。 |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | 目的地の経度が東経か西経かを示す GPS 値を取得または設定します. ASCII 'E' は東経を示し、'W' は西経を示します. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | 差分補正が GPS 受信機に適用されているかどうかを示す GPS 値を取得または設定します。 |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | GPS 受信機の移動方向を取得または設定します。 |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | 画像がキャプチャされたときの GPS 方向を取得または設定します。 値の範囲は 0.00 ～ 359.99 です。 |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | 画像がキャプチャされたときの方向を示すための GPS 参照を取得または設定します。 「T」は真の方向を表し、「M」は磁気方向です。 |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 指定された ID を持つ TIFF タグを取得します。 (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | GPS 緯度を取得または設定します。 |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | 緯度が北緯か南緯かを示す GPS 値を取得または設定します。 |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | GPS 経度を取得または設定します。 |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | 経度が東経か西経かを示す GPS 値を取得または設定します。 |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | GPS 受信機が使用する測地データを取得または設定します。 |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | GPS 測定モードを取得または設定します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | 位置検索に使用したメソッドの名前を記録した文字列を取得または設定します。 1 バイト目は使用した文字コードを示し、その後にメソッドの名前が続きます。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | 測定に使用される GPS 衛星を取得または設定します。 このタグは、衛星の数、 ID 番号、仰角、方位角、SNR およびその他の情報を ASCII 表記で記述するために使用できます。フォーマットは指定されていません。 GPS 受信機が測定できない場合、タグの値は NULL. に設定されます。 |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | GPS 受信機の移動速度を取得または設定します。 |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | GPS 受信機の移動速度を表すために使用される単位を取得または設定します。 'K''M' および 'N' は時速キロメートル、時速マイル、ノットを表します。 |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | 画像が記録されたときの GPS 受信機のステータスを取得または設定します。 |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | 時刻を UTC (協定世界時) として取得または設定します。 TimeStamp は、時、分、および秒を示す 3 つの RATIONAL 値として表されます。 |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | GPS 受信機の移動方向を示す基準を取得または設定します。 「T」は真の方向を表し、「M」は磁気方向を表します。 |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | GPS IFD のバージョンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | パッケージに保存されているすべての TIFF タグを削除します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | 指定された ID のプロパティを削除します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | 指定したタグを追加または置換します。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | パッケージからリストを作成します。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 備考

**もっと詳しく知る**

* [EXIF メタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### 関連項目

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* 名前空間 [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
