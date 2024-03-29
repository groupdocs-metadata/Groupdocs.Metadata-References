---
title: IIptc
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示用于 IPTC 元数据的基本操作 请在以下位置找到更多信息http//en.wikipedia.org/wiki/International_Press_Telecommunications_Councilhttp//en.wikipedia.org/wiki/International_Press_Telecommunications_Council.
type: docs
weight: 2870
url: /zh/net/groupdocs.metadata.standards.iptc/iiptc/
---
## IIptc interface

表示用于 IPTC 元数据的基本操作。 请在以下位置找到更多信息[http://en.wikipedia.org/wiki/International_Press_Telecommunications_Council](http://en.wikipedia.org/wiki/International_Press_Telecommunications_Council).

```csharp
public interface IIptc
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [IptcPackage](../../groupdocs.metadata.standards.iptc/iiptc/iptcpackage) { get; set; } | 获取或设置与文件关联的 IPTC 元数据包。 |

### 评论

**了解更多**

* [使用 IPTC IIM 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### 例子

此示例显示如何读取基本 IPTC 元数据属性。

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithIptc))
{
    IIptc root = metadata.GetRootPackage() as IIptc;
    if (root != null && root.IptcPackage != null)
    {
        if (root.IptcPackage.EnvelopeRecord != null)
        {
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.DateSent);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.Destination);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.FileFormat);
            Console.WriteLine(root.IptcPackage.EnvelopeRecord.FileFormatVersion);

            // ...
        }

        if (root.IptcPackage.ApplicationRecord != null)
        {
            Console.WriteLine(root.IptcPackage.ApplicationRecord.Headline);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ByLine);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ByLineTitle);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.CaptionAbstract);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.City);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.DateCreated);
            Console.WriteLine(root.IptcPackage.ApplicationRecord.ReleaseDate);

            // ...
        }
    }
}
```

### 也可以看看

* 命名空间 [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
