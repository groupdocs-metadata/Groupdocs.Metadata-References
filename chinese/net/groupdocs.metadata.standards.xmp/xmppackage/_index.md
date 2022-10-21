---
title: XmpPackage
second_title: GroupDocs.Metadata for .NET API 参考
description: 表示 XMP 包的基本抽象
type: docs
weight: 3490
url: /zh/net/groupdocs.metadata.standards.xmp/xmppackage/
---
## XmpPackage class

表示 XMP 包的基本抽象。

```csharp
public class XmpPackage : XmpMetadataContainer
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XmpPackage](xmppackage)(string, string) | 初始化[`XmpPackage`](../xmppackage)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 获取元数据属性的数量。 |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 获取[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty)具有指定的名称。 |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 获取元数据属性名称的集合。 |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 获取元数据类型。 |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 获取命名空间 URI。 |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | 获取 xmlns 前缀。 |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | 获取描述符集合，其中包含有关可通过 GroupDocs.Metadata 搜索引擎访问的属性的信息。 |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | 获取 XML 命名空间。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | 删除所有 XMP 属性。 |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 确定包是否包含具有指定名称的元数据属性。 |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 返回一个遍历集合的枚举器。 |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | 将 XMP 值转换为 XML 表示形式。 |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | 删除具有指定名称的属性。 |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 从包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set)(string, bool) | 设置布尔属性。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_6)(string, DateTime) | 套DateTime属性. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_1)(string, double) | 设置双重属性。 |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_5)(string, int) | 设置整数属性。 |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_7)(string, string) | 设置字符串属性。 |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_2)(string, XmpArray) | 设置继承自的值[`XmpArray`](../xmparray). |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_3)(string, XmpComplexType) | 设置继承自的值[`XmpComplexType`](../xmpcomplextype). |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set#set_4)(string, XmpValueBase) | 设置继承自的值[`XmpValueBase`](../xmpvaluebase). |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties)和[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 评论

**学到更多**

* [使用 XMP 元数据](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### 例子

此示例演示如何将自定义 XMP 包添加到任何受支持格式的文件中。

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        var packet = new XmpPacketWrapper();

        var custom = new XmpPackage("gd", "https://groupdocs.com");
        custom.Set("gd:Copyright", "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.");
        custom.Set("gd:CreationDate", DateTime.Today);
        custom.Set("gd:Company", XmpArray.From(new [] { "Aspose", "GroupDocs" }, XmpArrayType.Ordered));

        packet.AddPackage(custom);
        root.XmpPackage = packet;

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### 也可以看看

* class [XmpMetadataContainer](../xmpmetadatacontainer)
* 命名空间 [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
