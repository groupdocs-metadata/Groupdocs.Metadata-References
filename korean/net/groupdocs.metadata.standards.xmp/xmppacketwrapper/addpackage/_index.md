---
title: AddPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 패키지를 추가합니다.
type: docs
weight: 80
url: /ko/net/groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage/
---
## XmpPacketWrapper.AddPackage method

패키지를 추가합니다.

```csharp
public void AddPackage(XmpPackage package)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| package | XmpPackage | 패키지. |

### 예

이 예는 지원되는 형식의 파일에 사용자 정의 XMP 패키지를 추가하는 방법을 보여줍니다.

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

### 또한보십시오

* class [XmpPackage](../../xmppackage)
* class [XmpPacketWrapper](../../xmppacketwrapper)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp](../../xmppacketwrapper)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
