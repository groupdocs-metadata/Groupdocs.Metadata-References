---
title: DublinCorePackage
second_title: GroupDocs.Metadata for .NET API リファレンス
description: 電子書籍から抽出された Dublin Core メタデータ パッケージを取得します
type: docs
weight: 10
url: /ja/net/groupdocs.metadata.formats.ebook/epubrootpackage/dublincorepackage/
---
## EpubRootPackage.DublinCorePackage property

電子書籍から抽出された Dublin Core メタデータ パッケージを取得します。

```csharp
public DublinCorePackage DublinCorePackage { get; }
```

### プロパティ値

e-book から抽出された Dublin Core メタデータ パッケージ。

### 備考

**もっと詳しく知る**

* [EPUB 電子書籍でのメタデータの操作](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+EPUB+E-Books)

### 例

この例は、EPUB ファイルから Dublin Core メタデータを抽出する方法を示しています。

```csharp
using (Metadata metadata = new Metadata(Constants.InputEpub))
{
    var root = metadata.GetRootPackage<EpubRootPackage>();

    if (root.DublinCorePackage != null)
    {
        Console.WriteLine(root.DublinCorePackage.Rights);
        Console.WriteLine(root.DublinCorePackage.Publisher);
        Console.WriteLine(root.DublinCorePackage.Title);
        Console.WriteLine(root.DublinCorePackage.Creator);
        Console.WriteLine(root.DublinCorePackage.Language);
        Console.WriteLine(root.DublinCorePackage.Date);

        // ...
    }
}
```

### 関連項目

* class [DublinCorePackage](../../../groupdocs.metadata.standards.dublincore/dublincorepackage)
* class [EpubRootPackage](../../epubrootpackage)
* 名前空間 [GroupDocs.Metadata.Formats.Ebook](../../epubrootpackage)
* 組み立て [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->