---
title: ExifPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 获取或设置 EXIF 元数据包
type: docs
weight: 10
url: /zh/net/groupdocs.metadata.formats.image/heifrootpackage/exifpackage/
---
## HeifRootPackage.ExifPackage property

获取或设置 EXIF 元数据包。

```csharp
public ExifPackage ExifPackage { get; set; }
```

### 适当的价值

EXIF 元数据包。

### 评论

**了解更多**

* [使用 EXIF 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### 例子

此代码示例演示了如何提取基本的 EXIF 元数据属性。

```csharp
using (Metadata metadata = new Metadata(Constants.HeifWithExif))
{
    var root = metadata.GetRootPackage<HeifRootPackage>();
    if (root.ExifPackage != null)
    {
        Console.WriteLine(root.ExifPackage.Artist);
        Console.WriteLine(root.ExifPackage.Copyright);
        Console.WriteLine(root.ExifPackage.ImageDescription);
        Console.WriteLine(root.ExifPackage.Make);
        Console.WriteLine(root.ExifPackage.Model);
        Console.WriteLine(root.ExifPackage.Software);
        Console.WriteLine(root.ExifPackage.ImageWidth);
        Console.WriteLine(root.ExifPackage.ImageLength);

        // ...

        Console.WriteLine(root.ExifPackage.ExifIfdPackage.BodySerialNumber);
        Console.WriteLine(root.ExifPackage.ExifIfdPackage.CameraOwnerName);
        Console.WriteLine(root.ExifPackage.ExifIfdPackage.UserComment);

        // ...

        Console.WriteLine(root.ExifPackage.GpsPackage.Altitude);
        Console.WriteLine(root.ExifPackage.GpsPackage.LatitudeRef);
        Console.WriteLine(root.ExifPackage.GpsPackage.LongitudeRef);

        // ...
    }
}
```

### 也可以看看

* class [ExifPackage](../../../groupdocs.metadata.standards.exif/exifpackage)
* class [HeifRootPackage](../../heifrootpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Image](../../heifrootpackage)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
