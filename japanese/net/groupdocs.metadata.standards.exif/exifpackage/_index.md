---
title: ExifPackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: EXIF メタデータ パッケージ Exchangeable Image File Format を表します
type: docs
weight: 2790
url: /ja/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

EXIF メタデータ パッケージ (Exchangeable Image File Format) を表します。

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ExifPackage](exifpackage)() | の新しいインスタンスを初期化します[`ExifPackage`](../exifpackage)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | カメラの所有者、写真家、または画像作成者の名前を取得または設定します。 |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | 著作権表示を取得または設定します。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | メタデータ プロパティの数を取得します。 |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | イメージの作成日時を取得または設定します。 EXIF 規格では、ファイルが変更された日時です。 |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | EXIF IFD データを取得します。 |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | GPS データを取得します。 |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | 画像のタイトルを与える文字列を取得または設定します. 「1988年の会社のピクニック」などのコメントでもかまいません. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | 画像データの行数を取得または設定します。 |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | 1 行あたりのピクセル数に等しい、画像データの列数を取得または設定します。 |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 指定された ID を持つ TIFF タグを取得します。 (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | メタデータ プロパティ名のコレクションを取得します。 |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | 記録機器のメーカーを取得または設定します。 これは、画像を生成した DSC、スキャナー、ビデオ デジタイザー、またはその他の機器のメーカーです。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | メタデータ タイプを取得します。 |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | 機器のモデル名またはモデル番号を取得または設定します。 これは、画像を生成した DSC、スキャナー、ビデオ デジタイザー、またはその他の機器のモデル名または番号です。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 検索エンジンを介してアクセス可能なプロパティに関する情報を含む記述子のコレクションを取得します。 |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | 画像の生成に使用されるカメラまたは画像入力デバイスのソフトウェアまたはファームウェアの名前とバージョンを取得または設定します。 |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | バイトの配列として表される画像のサムネイルを取得します。 |

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

### 例

このコード サンプルは、一般的な EXIF プロパティを更新する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // EXIF パッケージがない場合は設定します
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### 関連項目

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* 名前空間 [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* 組み立て [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
