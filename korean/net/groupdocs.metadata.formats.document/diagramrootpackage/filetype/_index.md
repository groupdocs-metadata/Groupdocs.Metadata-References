---
title: FileType
second_title: .NET API 참조용 GroupDocs.Metadata
description: 파일 형식 메타데이터 패키지를 가져옵니다.
type: docs
weight: 20
url: /ko/net/groupdocs.metadata.formats.document/diagramrootpackage/filetype/
---
## DiagramRootPackage.FileType property

파일 형식 메타데이터 패키지를 가져옵니다.

```csharp
public DiagramTypePackage FileType { get; }
```

### 자산 가치

파일 형식 메타데이터 패키지입니다.

### 예

이 코드 샘플은 로드된 다이어그램의 정확한 유형을 감지하고 일부 추가 파일 형식 정보를 추출하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.FileType.FileFormat);
    Console.WriteLine(root.FileType.DiagramFormat);
    Console.WriteLine(root.FileType.MimeType);
    Console.WriteLine(root.FileType.Extension);
}
```

### 또한보십시오

* class [DiagramTypePackage](../../diagramtypepackage)
* class [DiagramRootPackage](../../diagramrootpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Document](../../diagramrootpackage)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->