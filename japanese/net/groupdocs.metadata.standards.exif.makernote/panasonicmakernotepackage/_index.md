---
title: PanasonicMakerNotePackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: PANASONIC MakerNote メタデータを表します
type: docs
weight: 2850
url: /ja/net/groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/
---
## PanasonicMakerNotePackage class

PANASONIC MakerNote メタデータを表します。

```csharp
public class PanasonicMakerNotePackage : MakerNotePackage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AccessorySerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessoryserialnumber) { get; } | アクセサリのシリアル番号を取得します。 |
| [AccessoryType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/accessorytype) { get; } | アクセサリのタイプを取得します。 |
| [AFMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/afmode) { get; } | AF モードを取得します。 |
| [Audio](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/audio) { get; } | オーディオモードを取得します. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [FirmwareVersion](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/firmwareversion) { get; } | ファームウェアのバージョンを取得します。 |
| [FocusMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/focusmode) { get; } | フォーカスモードを取得します. |
| [ImageQuality](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagequality) { get; } | 画質を取得します。 |
| [ImageStabilization](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/imagestabilization) { get; } | 手ぶれ補正モードを取得します。 |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 指定された ID を持つ TIFF タグを取得します。 (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [LensSerialNumber](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lensserialnumber) { get; } | レンズのシリアル番号を取得します。 |
| [LensType](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/lenstype) { get; } | レンズの種類を取得します。 |
| [MacroMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/macromode) { get; } | マクロモードを取得します。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [ShootingMode](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/shootingmode) { get; } | 撮影モードを取得します。 |
| [WhiteBalance](../../groupdocs.metadata.standards.exif.makernote/panasonicmakernotepackage/whitebalance) { get; } | ホワイトバランスを取得します。 |

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
