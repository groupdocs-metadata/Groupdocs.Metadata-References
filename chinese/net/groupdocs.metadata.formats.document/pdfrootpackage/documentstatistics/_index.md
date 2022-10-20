---
title: DocumentStatistics
second_title: GroupDocs.Metadata for .NET API 参考
description: 获取文档统计包
type: docs
weight: 10
url: /zh/net/groupdocs.metadata.formats.document/pdfrootpackage/documentstatistics/
---
## PdfRootPackage.DocumentStatistics property

获取文档统计包。

```csharp
public DocumentStatistics DocumentStatistics { get; }
```

### 适当的价值

文档统计包。

### 评论

**学到更多**

* [使用 PDF 文档中的元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### 例子

此代码示例演示如何获取 PDF 文档的文本统计信息。

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

        Console.WriteLine(root.DocumentStatistics.CharacterCount);
        Console.WriteLine(root.DocumentStatistics.PageCount);
        Console.WriteLine(root.DocumentStatistics.WordCount);
}
```

### 也可以看看

* class [DocumentStatistics](../../documentstatistics)
* class [PdfRootPackage](../../pdfrootpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Document](../../pdfrootpackage)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->