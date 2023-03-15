---
title: VCardPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: VCard 메타데이터 패키지를 가져옵니다.
type: docs
weight: 10
url: /ko/net/groupdocs.metadata.formats.businesscard/vcardrootpackage/vcardpackage/
---
## VCardRootPackage.VCardPackage property

VCard 메타데이터 패키지를 가져옵니다.

```csharp
public VCardPackage VCardPackage { get; }
```

### 자산 가치

VCard 메타데이터 패키지.

### 비고

**더 알아보기**

* [vCard 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### 예

이 코드 샘플은 설명 매개변수와 함께 vCard 필드를 추출하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVcf))
{
    var root = metadata.GetRootPackage<VCardRootPackage>();

    foreach (var vCard in root.VCardPackage.Cards)
    {
        if (vCard.IdentificationRecordset.PhotoUriRecords != null)
        {
            // URI가 나타내는 모든 사진 반복
            foreach (var photoUriRecord in vCard.IdentificationRecordset.PhotoUriRecords)
            {
                // 속성값 출력
                Console.WriteLine(photoUriRecord.Value);

                // 속성의 일부 추가 매개변수를 인쇄합니다.
                Console.WriteLine(photoUriRecord.ContentType);
                Console.WriteLine(photoUriRecord.MediaTypeParameter);
                if (photoUriRecord.TypeParameters != null)
                {
                    foreach (string parameter in photoUriRecord.TypeParameters)
                    {
                        Console.WriteLine(parameter);
                    }
                }
                Console.WriteLine(photoUriRecord.PrefParameter);
            }
        }
    }
}
```

### 또한보십시오

* class [VCardPackage](../../vcardpackage)
* class [VCardRootPackage](../../vcardrootpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.BusinessCard](../../vcardrootpackage)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->