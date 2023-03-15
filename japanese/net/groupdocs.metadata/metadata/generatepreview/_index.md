---
title: GeneratePreview
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 指定したページのプレビュー画像を作成します
type: docs
weight: 60
url: /ja/net/groupdocs.metadata/metadata/generatepreview/
---
## Metadata.GeneratePreview method

指定したページのプレビュー画像を作成します。

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| previewOptions | PreviewOptions | プレビュー生成の一連のオプション。 |

### 備考

**もっと詳しく知る**

* [ドキュメントのプレビューを生成](https://docs.groupdocs.com/display/metadatanet/Generate+document+preview)

### 例

このコード スニペットは、ドキュメント ページの画像プレビューを作成する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    PreviewOptions previewOptions = new PreviewOptions(pageNumber => File.Create($"{Constants.OutputPath}\\result_{pageNumber}.png"));
    previewOptions.PreviewFormat = PreviewOptions.PreviewFormats.PNG;
    previewOptions.PageNumbers = new int[] { 1 };

    metadata.GeneratePreview(previewOptions);
}
```

### 関連項目

* class [PreviewOptions](../../../groupdocs.metadata.options/previewoptions)
* class [Metadata](../../metadata)
* 名前空間 [GroupDocs.Metadata](../../metadata)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->