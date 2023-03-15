---
title: Item
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 指定された ID を持つ TIFF タグを取得します
type: docs
weight: 10
url: /ja/net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/item/
---
## ExifDictionaryBasePackage indexer

指定された ID を持つ TIFF タグを取得します。

```csharp
public TiffTag this[TiffTagID tagId] { get; }
```

| パラメータ | 説明 |
| --- | --- |
| tagId | 取得するタグの ID。 |

### 戻り値

の[`TiffTag`](../../../groupdocs.metadata.formats.image/tifftag)指定されたタグ ID を持つ。

### 例

この例は、特定の TIFF/EXIF タグをその識別子で読み取る方法を示しています.

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null && root.ExifPackage != null)
    {
        TiffAsciiTag software = (TiffAsciiTag)root.ExifPackage[TiffTagID.Software];
        if (software != null)
        {
            Console.WriteLine("Software: {0}", software.Value);
        }
    }
}
```

### 関連項目

* class [TiffTag](../../../groupdocs.metadata.formats.image/tifftag)
* enum [TiffTagID](../../../groupdocs.metadata.formats.image/tifftagid)
* class [ExifDictionaryBasePackage](../../exifdictionarybasepackage)
* 名前空間 [GroupDocs.Metadata.Standards.Exif](../../exifdictionarybasepackage)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->