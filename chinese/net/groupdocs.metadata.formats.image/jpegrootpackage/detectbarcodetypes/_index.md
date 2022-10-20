---
title: DetectBarcodeTypes
second_title: GroupDocs.Metadata for .NET API 参考
description: 提取图像中显示的条形码类型
type: docs
weight: 60
url: /zh/net/groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes/
---
## JpegRootPackage.DetectBarcodeTypes method

提取图像中显示的条形码类型。

```csharp
public string[] DetectBarcodeTypes()
```

### 返回值

条码类型数组。

### 评论

**学到更多**

* [处理 JPEG 图像中的元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### 例子

此代码段演示如何检测 JPEG 图像中的条形码。

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithBarcodes))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    var barcodeTypes = root.DetectBarcodeTypes();

    foreach (var barcodeType in barcodeTypes)
    {
        Console.WriteLine(barcodeType);
    }
}
```

### 也可以看看

* class [JpegRootPackage](../../jpegrootpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->