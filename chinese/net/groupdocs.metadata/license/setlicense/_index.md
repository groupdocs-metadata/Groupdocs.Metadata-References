---
title: SetLicense
second_title: GroupDocs.Metadata for .NET API 参考
description: 许可组件
type: docs
weight: 20
url: /zh/net/groupdocs.metadata/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

许可组件。

```csharp
public void SetLicense(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 许可证文件的绝对路径。 |

### 例子

此示例演示如何设置许可证。

```csharp
// 初始化许可证类
License license = new License();

// 设置 .lic 文件的路径
license.SetLicense(@"C:\\GroupDocs.Metadata.lic");    
```

### 也可以看看

* class [License](../../license)
* 命名空间 [GroupDocs.Metadata](../../license)
* 部件 [GroupDocs.Metadata](../../../)

---

## SetLicense(Stream) {#setlicense}

许可组件。

```csharp
public void SetLicense(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 许可证流。 |

### 也可以看看

* class [License](../../license)
* 命名空间 [GroupDocs.Metadata](../../license)
* 部件 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->