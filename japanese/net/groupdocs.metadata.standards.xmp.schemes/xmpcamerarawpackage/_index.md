---
title: XmpCameraRawPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: Camera Raw スキーマを表します
type: docs
weight: 3100
url: /ja/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Camera Raw スキーマを表します。

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | の新しいインスタンスを初期化します[`XmpCameraRawPackage`](../xmpcamerarawpackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | AutoBrightness 値を取得または設定します。本当の場合、[`Brightness`](./brightness)自動的に調整されます. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | AutoContrast 値を取得または設定します。 true の場合、「コントラスト」が自動的に調整されます。 |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | AutoExposure 値を取得または設定します。 true の場合、「露出」は自動的に調整されます。 |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | AutoShadows 値を取得または設定します。 true の場合、「影」は自動的に調整されます。 |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | BlueHue 値を取得または設定します。未定義の場合は null. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | BlueSaturation を取得または設定します。未定義の場合は null. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | 明るさの値を取得または設定します。未定義の場合は null. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | CameraProfile 値を取得または設定します。 |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | 「色収差、ブルー/イエロー フリンジを修正」設定を取得または設定します。未定義の場合は null. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | 「色収差、赤/シアン フリンジを修正」設定を取得または設定します。未定義の場合は null. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | 色ノイズ低減設定を取得または設定します。範囲 0 ～ 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | コントラスト設定を取得または設定します。範囲 -50 ～ 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | CropAngle 設定を取得または設定します。 HasCrop が true の場合、切り抜く四角形の角度. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | CropBottom 設定を取得または設定します。 HasCrop が true の場合、切り抜く四角形の下部. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | 結果のトリミングされた画像の高さを取得または設定します[`CropUnits`](./cropunits)units. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | CropLeft 設定を取得または設定します。 HasCrop が true の場合、切り抜き四角形の左。 |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | CropRight 設定を取得または設定します。 HasCrop が true の場合、トリミング四角形の右側。 |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | CropTop 設定を取得または設定します。 HasCrop が true の場合、切り抜き四角形の上部. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | の単位を取得または設定します[`CropWidth`](./cropwidth)と[`CropHeight`](./cropheight). |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | 結果のトリミングされた画像の幅を取得または設定します[`CropUnits`](./cropunits)units. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | 露出設定を取得または設定します。 |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | 緑の色相設定を取得または設定します。範囲 -100 ～ 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | 緑の彩度設定を取得または設定します。範囲 -100 ～ 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | HasCrop 値を取得または設定します。 true の場合、画像にトリミング用の四角形が含まれます。 |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | HasSettings 値を取得または設定します。 true の場合、デフォルト以外の Camera Raw 設定. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | を取得します[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)指定された名前で. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | LuminanceSmoothing 設定を取得または設定します。範囲 0 ～ 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 名前空間 URI を取得します。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns プレフィックスを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | 生ファイルのファイル名を取得または設定します (完全なパスではありません). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | 赤の色相設定を取得または設定します。範囲 -100 ～ 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | 赤の彩度設定を取得または設定します。範囲 -100 ～ 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | 彩度設定を取得または設定します。範囲 -100 ～ 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | シャドウ設定を取得または設定します。範囲 0 ～ 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | ShadowTint 設定を取得または設定します。範囲 -100 ～ 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | シャープネス設定を取得または設定します。範囲 0 ～ 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | 温度設定を取得または設定します。範囲 2000 ～ 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | 色合いの設定を取得または設定します。範囲 -150 ～ 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Camera Raw プラグインのバージョンを取得または設定します。 |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | ビネット量設定を取得または設定します。範囲 -100 ～ 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | 口径食の中点設定を取得または設定します。範囲 0 ～ 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | ホワイトバランス設定を取得します。使用[`SetWhiteBalance`](./setwhitebalance)ホワイトバランス値を設定します. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | XML 名前空間を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを追加します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | すべての XMP プロパティを削除します。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 指定した名前のメタデータ プロパティがパッケージに含まれているかどうかを判断します。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを検索します。 検索は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | XMP 値を XML 表現に変換します。 |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | 指定した名前のプロパティを削除します。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 指定された述語を満たすメタデータ プロパティを削除します。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 書き込み可能なメタデータ プロパティをパッケージから削除します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | ブール値のプロパティを設定します。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | セットDateTimeプロパティ. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | double プロパティを設定します。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | 整数プロパティを設定します。 |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | 文字列プロパティを追加します。 |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | から継承された値を設定します[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | から継承された値を設定します[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | から継承された値を設定します[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase). |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを設定します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 このメソッドは、[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)と[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 既存のプロパティが述語を満たす場合、その値が更新されます。 述語を満たす既知のプロパティがパッケージにない場合、それがパッケージに追加されます。 |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | ホワイトバランスを設定します。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 指定された述語を満たす既知のメタデータ プロパティを更新します。 操作は再帰的であるため、ネストされたすべてのパッケージにも影響します。 |

### 関連項目

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 名前空間 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
