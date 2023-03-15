---
title: SonyMakerNotePackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: SONY MakerNote メタデータを表します
type: docs
weight: 2860
url: /ja/net/groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/
---
## SonyMakerNotePackage class

SONY MakerNote メタデータを表します。

```csharp
public sealed class SonyMakerNotePackage : MakerNotePackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AFIlluminator](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/afilluminator) { get; } | AFイルミネーターの種類を取得します。 |
| [Brightness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/brightness) { get; } | 明るさを取得します。 |
| [ColorMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colormode) { get; } | カラーモードを取得します. |
| [ColorTemperature](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/colortemperature) { get; } | 色温度を取得します。 |
| [Contrast](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/contrast) { get; } | コントラストを取得します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [CreativeStyle](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/creativestyle) { get; } | クリエイティブ スタイルを取得します。 |
| [ExposureMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/exposuremode) { get; } | 露出モードを取得します. |
| [FlashLevel](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/flashlevel) { get; } | フラッシュレベルを取得します。 |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/focusmode) { get; } | フォーカスモードを取得します. |
| [Header](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/header) { get; } | MakerNote ヘッダーを取得します。 |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 指定された ID を持つ TIFF タグを取得します。 (2 indexers) |
| [JpegQuality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/jpegquality) { get; } | JPEG 品質を取得します。 |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Macro](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/macro) { get; } | マクロを取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [MultiBurstImageHeight](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimageheight) { get; } | マルチバースト画像の高さを取得します。 |
| [MultiBurstImageWidth](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstimagewidth) { get; } | マルチバースト画像の幅を取得します。 |
| [MultiBurstMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/multiburstmode) { get; } | マルチバーストモードがオンかどうかを示す値を取得します。 |
| [PictureEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/pictureeffect) { get; } | 画像効果を取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Quality](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/quality) { get; } | 画質を取得します。 |
| [Rating](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/rating) { get; } | 評価を取得します。 |
| [ReleaseMode](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/releasemode) { get; } | リリースモードを取得します。 |
| [Saturation](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/saturation) { get; } | 彩度を取得します。 |
| [Sharpness](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sharpness) { get; } | シャープネスを取得します。 |
| [SoftSkinEffect](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/softskineffect) { get; } | ソフトスキン効果を取得します。 |
| [SonyModelID](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/sonymodelid) { get; } | ソニーのモデル ID を取得します。 |
| [Teleconverter](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/teleconverter) { get; } | テレコンバーターの種類を取得します。 |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/sonymakernotepackage/whitebalance) { get; } | ホワイトバランスを取得します。 |

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

### 関連項目

* class [MakerNotePackage](../makernotepackage)
* 名前空間 [GroupDocs.Metadata.Standards.Exif.MakerNote](../../groupdocs.metadata.standards.exif.makernote)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
