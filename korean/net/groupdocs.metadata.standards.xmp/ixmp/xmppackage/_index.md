---
title: XmpPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: XMP 메타데이터 패키지를 가져오거나 설정합니다.
type: docs
weight: 10
url: /ko/net/groupdocs.metadata.standards.xmp/ixmp/xmppackage/
---
## IXmp.XmpPackage property

XMP 메타데이터 패키지를 가져오거나 설정합니다.

```csharp
public XmpPacketWrapper XmpPackage { get; set; }
```

### 자산 가치

XMP 메타데이터 패키지.

### 비고

**더 알아보기**

* [XMP 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### 예

이 코드 샘플은 파일에서 XMP 메타데이터를 제거하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null)
    {
        root.XmpPackage = null;
        metadata.Save(Constants.OutputJpeg);
    }
}
```

### 또한보십시오

* class [XmpPacketWrapper](../../xmppacketwrapper)
* interface [IXmp](../../ixmp)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp](../../ixmp)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->