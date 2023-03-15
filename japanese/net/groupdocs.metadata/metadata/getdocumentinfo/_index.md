---
title: GetDocumentInfo
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 読み込まれたドキュメントに関する共通情報を取得します
type: docs
weight: 70
url: /ja/net/groupdocs.metadata/metadata/getdocumentinfo/
---
## Metadata.GetDocumentInfo method

読み込まれたドキュメントに関する共通情報を取得します。

```csharp
public IDocumentInfo GetDocumentInfo()
```

### 戻り値

共通の文書情報を表すオブジェクト。

### 備考

**もっと詳しく知る**

* [ドキュメント情報を取得する](https://docs.groupdocs.com/display/metadatanet/Get+document+info)

### 例

この例は、ファイルから基本的なフォーマット情報を抽出する方法を示しています.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    if (metadata.FileFormat != FileFormat.Unknown)
    {
        IDocumentInfo info = metadata.GetDocumentInfo();
        Console.WriteLine("File format: {0}", info.FileType.FileFormat);
        Console.WriteLine("File extension: {0}", info.FileType.Extension);
        Console.WriteLine("MIME Type: {0}", info.FileType.MimeType);
        Console.WriteLine("Number of pages: {0}", info.PageCount);
        Console.WriteLine("Document size: {0} bytes", info.Size);
        Console.WriteLine("Is document encrypted: {0}", info.IsEncrypted);
    }
}
```

### 関連項目

* interface [IDocumentInfo](../../../groupdocs.metadata.common/idocumentinfo)
* class [Metadata](../../metadata)
* 名前空間 [GroupDocs.Metadata](../../metadata)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->