---
title: ID3V1
second_title: .NET API 참조용 GroupDocs.Metadata
description: ID3v1 메타데이터 태그를 가져오거나 설정합니다. 자세한 내용은 다음을 참조하십시오.http//id3.org/ID3v1http//id3.org/ID3v1 .
type: docs
weight: 20
url: /ko/net/groupdocs.metadata.formats.audio/mp3rootpackage/id3v1/
---
## MP3RootPackage.ID3V1 property

ID3v1 메타데이터 태그를 가져오거나 설정합니다. 자세한 내용은 다음을 참조하십시오.[http://id3.org/ID3v1](http://id3.org/ID3v1) .

```csharp
public ID3V1Tag ID3V1 { get; set; }
```

### 자산 가치

오디오 파일에 첨부된 ID3v1 메타데이터 태그입니다.

### 비고

ID3(v1) 태그는 MP3 파일 끝에 있는 추가 데이터의 작은 청크입니다.

### 예

이 코드 샘플은 MP3 파일에서 ID3v1 태그를 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V1))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V1 == null)
    {
        root.ID3V1 = new ID3V1Tag();
    }

    root.ID3V1.Album = "test album";
    root.ID3V1.Artist = "test artist";
    root.ID3V1.Title = "test title";
    root.ID3V1.Comment = "test comment";
    root.ID3V1.Year = "2019";

    // ...

    metadata.Save(Constants.OutputMp3);
}
```

### 또한보십시오

* class [ID3V1Tag](../../id3v1tag)
* class [MP3RootPackage](../../mp3rootpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Audio](../../mp3rootpackage)
* 집회 [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->