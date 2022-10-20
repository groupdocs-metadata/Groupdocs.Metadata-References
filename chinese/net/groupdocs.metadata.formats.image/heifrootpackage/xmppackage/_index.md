---
title: XmpPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 获取或设置 XMP 元数据包
type: docs
weight: 20
url: /zh/net/groupdocs.metadata.formats.image/heifrootpackage/xmppackage/
---
## HeifRootPackage.XmpPackage property

获取或设置 XMP 元数据包。

```csharp
public XmpPacketWrapper XmpPackage { get; set; }
```

### 适当的价值

XMP 元数据包。

### 评论

**学到更多**

* [使用 XMP 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### 例子

此示例演示如何从文件中提取 XMP 元数据。

```csharp
using (Metadata metadata = new Metadata(Constants.HeifWithXmp))
{
    var root = metadata.GetRootPackage<HeifRootPackage>();
    if (root.XmpPackage != null)
    {
        if (root.XmpPackage.Schemes.XmpBasic != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreatorTool);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.CreateDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.ModifyDate);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Label);
            Console.WriteLine(root.XmpPackage.Schemes.XmpBasic.Nickname);

            // ...
        }

        if (root.XmpPackage.Schemes.DublinCore != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Format);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Coverage);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Identifier);
            Console.WriteLine(root.XmpPackage.Schemes.DublinCore.Source);

            // ...
        }

        if (root.XmpPackage.Schemes.Photoshop != null)
        {
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.ColorMode);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.IccProfile);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.Country);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.City);
            Console.WriteLine(root.XmpPackage.Schemes.Photoshop.DateCreated);

            // ... 
        }

        // ...
    }
}
```

### 也可以看看

* class [XmpPacketWrapper](../../../groupdocs.metadata.standards.xmp/xmppacketwrapper)
* class [HeifRootPackage](../../heifrootpackage)
* 命名空间 [GroupDocs.Metadata.Formats.Image](../../heifrootpackage)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->