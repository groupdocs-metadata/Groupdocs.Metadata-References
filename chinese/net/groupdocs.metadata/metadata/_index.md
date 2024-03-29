---
title: Metadata
second_title: GroupDocs.Metadata for .NET API 参考
description: 提供访问所有支持格式的元数据的主类
type: docs
weight: 2660
url: /zh/net/groupdocs.metadata/metadata/
---
## Metadata class

提供访问所有支持格式的元数据的主类。

```csharp
public sealed class Metadata : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Metadata](metadata#constructor)(Stream) | 初始化一个新的实例[`Metadata`](../metadata)类. |
| [Metadata](metadata#constructor_2)(string) | 初始化一个新的实例[`Metadata`](../metadata)类. |
| [Metadata](metadata#constructor_1)(Stream, LoadOptions) | 初始化一个新的实例[`Metadata`](../metadata)类. |
| [Metadata](metadata#constructor_3)(string, LoadOptions) | 初始化一个新的实例[`Metadata`](../metadata)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FileFormat](../../groupdocs.metadata/metadata/fileformat) { get; } | 获取加载文件的类型（如果识别）。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata/metadata/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 添加满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Dispose](../../groupdocs.metadata/metadata/dispose)() | 执行与释放、释放或重置非托管资源相关的应用程序定义的任务。 |
| [FindProperties](../../groupdocs.metadata/metadata/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。 |
| [GeneratePreview](../../groupdocs.metadata/metadata/generatepreview)(PreviewOptions) | 为指定页面创建预览图像。 |
| [GetDocumentInfo](../../groupdocs.metadata/metadata/getdocumentinfo)() | 获取有关已加载文档的公共信息。 |
| [GetRootPackage](../../groupdocs.metadata/metadata/getrootpackage#getrootpackage)() | 获取根包，提供对从文件中提取的所有元数据属性的访问权限。 |
| [GetRootPackage&lt;TRoot&gt;](../../groupdocs.metadata/metadata/getrootpackage#getrootpackage_1)() | 获取根包，提供对从文件中提取的所有元数据属性的访问权限。 |
| [RemoveProperties](../../groupdocs.metadata/metadata/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 删除满足指定谓词的元数据属性。 |
| [Sanitize](../../groupdocs.metadata/metadata/sanitize)() | 如果可能，从所有检测到的包或整个包中删除可写元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |
| [Save](../../groupdocs.metadata/metadata/save#save)() | 保存在加载文档中所做的所有更改。 |
| [Save](../../groupdocs.metadata/metadata/save#save_1)(Stream) | 将文档内容保存到流中。 |
| [Save](../../groupdocs.metadata/metadata/save#save_2)(string) | 将文档内容保存到指定文件中。 |
| [SetProperties](../../groupdocs.metadata/metadata/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 设置满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 此方法是以下方法的组合[`AddProperties`](./addproperties)和[`UpdateProperties`](./updateproperties) 如果现有属性满足谓词，则更新其值。 如果包中缺少满足谓词的已知属性，则将其添加到包中。 |
| [UpdateProperties](../../groupdocs.metadata/metadata/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 更新满足指定谓词的已知元数据属性。 该操作是递归的，因此它也会影响所有嵌套包。 |

### 也可以看看

* 命名空间 [GroupDocs.Metadata](../../groupdocs.metadata)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
