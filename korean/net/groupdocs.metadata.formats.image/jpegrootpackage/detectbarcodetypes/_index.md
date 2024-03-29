---
title: DetectBarcodeTypes
second_title: .NET API 참조용 GroupDocs.Metadata
description: 이미지에 나타난 바코드의 종류를 추출합니다.
type: docs
weight: 60
url: /ko/net/groupdocs.metadata.formats.image/jpegrootpackage/detectbarcodetypes/
---
## JpegRootPackage.DetectBarcodeTypes method

이미지에 나타난 바코드의 종류를 추출합니다.

```csharp
public string[] DetectBarcodeTypes()
```

### 반환 값

바코드 유형의 배열입니다.

### 비고

**더 알아보기**

* [JPEG 이미지의 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG+images)

### 예

이 코드 스니펫은 JPEG 이미지에서 바코드를 감지하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.JpegWithBarcodes))
{
    var root = metadata.GetRootPackage<JpegRootPackage>();

    var barcodeTypes = root.DetectBarcodeTypes();

    foreach (var barcodeType in barcodeTypes)
    {
        Console.WriteLine(barcodeType);
    }
}
```

### 또한보십시오

* class [JpegRootPackage](../../jpegrootpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Image](../../jpegrootpackage)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
