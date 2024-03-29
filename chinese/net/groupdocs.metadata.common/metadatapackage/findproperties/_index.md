---
title: FindProperties
second_title: GroupDocs.Metadata for .NET API 参考
description: 查找满足指定谓词的元数据属性 搜索是递归的因此它也会影响所有嵌套包
type: docs
weight: 80
url: /zh/net/groupdocs.metadata.common/metadatapackage/findproperties/
---
## MetadataPackage.FindProperties method

查找满足指定谓词的元数据属性。 搜索是递归的，因此它也会影响所有嵌套包。

```csharp
public virtual IEnumerable<MetadataProperty> FindProperties(Func<MetadataProperty, bool> predicate)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| predicate | Func`2 | 用于测试条件的每个元数据属性的函数。 |

### 返回值

一个IEnumerable包含包中满足条件的属性。

### 评论

**了解更多**

* 更多示例演示此方法的用法： [提取元数据](https://docs.groupdocs.com/display/metadatanet/Extracting+metadata)

### 也可以看看

* class [MetadataProperty](../../metadataproperty)
* delegate [Func&lt;T,TResult&gt;](../../func-2)
* class [MetadataPackage](../../metadatapackage)
* 命名空间 [GroupDocs.Metadata.Common](../../metadatapackage)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
