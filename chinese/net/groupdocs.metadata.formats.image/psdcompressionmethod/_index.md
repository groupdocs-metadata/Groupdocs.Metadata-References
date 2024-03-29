---
title: PsdCompressionMethod
second_title: GroupDocs.Metadata for .NET API 参考
description: 定义用于图像数据的压缩方法
type: docs
weight: 1890
url: /zh/net/groupdocs.metadata.formats.image/psdcompressionmethod/
---
## PsdCompressionMethod enumeration

定义用于图像数据的压缩方法。

```csharp
public enum PsdCompressionMethod
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Raw | `0` | 无压缩。以 RGBA 平面顺序存储为原始字节的图像数据。 这意味着首先写入所有 R 数据，然后写入所有 G，然后写入所有 B，最后写入所有 A 数据。 |
| Rle | `1` | RLE 已压缩。图像数据以所有扫描线（行 * 通道）的字节计数开始，每个 计数存储为两个字节值。随后是 RLE 压缩数据，每个扫描线单独压缩。 RLE 压缩与 Macintosh ROM 例程 PackBits 和 TIFF 标准使用的压缩算法相同。 |
| ZipWithoutPrediction | `2` | 没有预测的 ZIP. |
| ZipWithPrediction | `3` | 带预测的 ZIP. |

### 也可以看看

* 命名空间 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 部件 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
