---
title: ExifPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 获取或设置与文件关联的 EXIF 元数据包
type: docs
weight: 10
url: /zh/net/groupdocs.metadata.standards.exif/iexif/exifpackage/
---
## IExif.ExifPackage property

获取或设置与文件关联的 EXIF 元数据包。

```csharp
public ExifPackage ExifPackage { get; set; }
```

### 适当的价值

与文件关联的 EXIF 元数据包。

### 评论

**了解更多**

* [使用 EXIF 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### 例子

此代码示例展示了如何从文件中删除 EXIF 元数据。

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        root.ExifPackage = null;

        metadata.Save(Constants.OutputJpeg);
     }
}
```

### 也可以看看

* class [ExifPackage](../../exifpackage)
* interface [IExif](../../iexif)
* 命名空间 [GroupDocs.Metadata.Standards.Exif](../../iexif)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
