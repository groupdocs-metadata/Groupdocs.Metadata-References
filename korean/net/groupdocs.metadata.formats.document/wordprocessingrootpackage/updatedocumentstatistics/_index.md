---
title: UpdateDocumentStatistics
second_title: .NET API 참조용 GroupDocs.Metadata
description: 문서의 페이지 단락 단어 줄 문자 수를 다시 계산하고 적절한 메타데이터 패키지를 업데이트합니다.
type: docs
weight: 50
url: /ko/net/groupdocs.metadata.formats.document/wordprocessingrootpackage/updatedocumentstatistics/
---
## WordProcessingRootPackage.UpdateDocumentStatistics method

문서의 페이지, 단락, 단어, 줄, 문자 수를 다시 계산하고 적절한 메타데이터 패키지를 업데이트합니다.

```csharp
public void UpdateDocumentStatistics()
```

### 비고

**더 알아보기**

* [WordProcessing 문서에서 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### 예

이 코드 샘플은 WordProcessing 문서에 대한 문서 통계를 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
   var root = metadata.GetRootPackage<WordProcessingRootPackage>();

   root.UpdateDocumentStatistics();

   metadata.Save(Constants.OutputDoc);
}
```

### 또한보십시오

* class [WordProcessingRootPackage](../../wordprocessingrootpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Document](../../wordprocessingrootpackage)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
