---
title: ExifPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 EXIF 元数据包可交换图像文件格式
type: docs
weight: 2790
url: /zh/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

表示 EXIF 元数据包（可交换图像文件格式）。

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ExifPackage](exifpackage)() | 初始化[`ExifPackage`](../exifpackage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | 获取或设置相机所有者、摄影师或图像创建者的名称。 |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | 获取或设置版权声明。 |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | 获取或设置图像创建的日期和时间。 在EXIF标准中，是文件被更改的日期和时间。 |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | 获取 EXIF IFD 数据。 |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | 获取 GPS 数据。 |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | 获取或设置一个字符串，给出图像的标题。 可能是“1988 公司野餐”之类的注释。 |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | 获取或设置图像数据的行数。 |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | 获取或设置图像数据的列数，等于每行的像素数。 |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 获取具有指定 id 的 TIFF 标签。 (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | 获取或设置记录设备的制造商。 这是生成图像的DSC、扫描仪、视频数字化仪或其他设备的制造商。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | 获取或设置设备的型号名称或型号。 这是生成图像的 DSC、扫描仪、视频数字化仪或其他设备的型号名称或编号。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | 获取或设置用于生成图像的相机或图像输入设备的软件或固件的名称和版本。 |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | 获取表示为字节数组的图像缩略图。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | 删除存储在包中的所有 TIFF 标签。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | 删除具有指定 id 的属性。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | 添加或替换指定的标签。 |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | 从包中创建一个列表。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**学到更多**

* [使用 EXIF 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### 例子

此代码示例演示如何更新常见的 EXIF 属性。

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // 如果 EXIF 包丢失，则设置它
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

### 也可以看看

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* 命名空间 [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
