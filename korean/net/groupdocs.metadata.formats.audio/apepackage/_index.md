---
title: ApePackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: APE v2 메타데이터 패키지를 나타냅니다. 자세한 내용은 다음을 참조하십시오.http//wiki.hydrogenaud.io/index.phptitleAPE_keyhttp//wiki.hydrogenaud.io/index.phptitleAPE_key .
type: docs
weight: 380
url: /ko/net/groupdocs.metadata.formats.audio/apepackage/
---
## ApePackage class

APE v2 메타데이터 패키지를 나타냅니다. 자세한 내용은 다음을 참조하십시오.[http://wiki.hydrogenaud.io/index.php?title=APE_key](http://wiki.hydrogenaud.io/index.php?title=APE_key) .

```csharp
public sealed class ApePackage : CustomPackage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Abstract](../../groupdocs.metadata.formats.audio/apepackage/abstract) { get; } | 추상 링크를 가져옵니다. |
| [Album](../../groupdocs.metadata.formats.audio/apepackage/album) { get; } | 앨범을 가져옵니다. |
| [Artist](../../groupdocs.metadata.formats.audio/apepackage/artist) { get; } | 아티스트를 가져옵니다. |
| [Bibliography](../../groupdocs.metadata.formats.audio/apepackage/bibliography) { get; } | 참고문헌을 가져옵니다. |
| [Comment](../../groupdocs.metadata.formats.audio/apepackage/comment) { get; } | 댓글을 가져옵니다. |
| [Composer](../../groupdocs.metadata.formats.audio/apepackage/composer) { get; } | 작곡가를 가져옵니다. |
| [Conductor](../../groupdocs.metadata.formats.audio/apepackage/conductor) { get; } | 도체를 가져옵니다. |
| [Copyright](../../groupdocs.metadata.formats.audio/apepackage/copyright) { get; } | 저작권을 얻습니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DebutAlbum](../../groupdocs.metadata.formats.audio/apepackage/debutalbum) { get; } | 데뷔 앨범을 받습니다. |
| [File](../../groupdocs.metadata.formats.audio/apepackage/file) { get; } | 파일을 가져옵니다. |
| [Genre](../../groupdocs.metadata.formats.audio/apepackage/genre) { get; } | 장르를 가져옵니다. |
| [Isbn](../../groupdocs.metadata.formats.audio/apepackage/isbn) { get; } | 검사 숫자가 있는 ISBN 번호를 가져옵니다. 더 보기: https://en.wikipedia.org/wiki/International_Standard_Book_Number. |
| [Isrc](../../groupdocs.metadata.formats.audio/apepackage/isrc) { get; } | 국제 표준 기록 번호를 가져옵니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Language](../../groupdocs.metadata.formats.audio/apepackage/language) { get; } | 언어를 가져옵니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [PublicationRight](../../groupdocs.metadata.formats.audio/apepackage/publicationright) { get; } | 게시 권한을 얻습니다. |
| [Publisher](../../groupdocs.metadata.formats.audio/apepackage/publisher) { get; } | 게시자를 가져옵니다. |
| [RecordLocation](../../groupdocs.metadata.formats.audio/apepackage/recordlocation) { get; } | 레코드 위치를 가져옵니다. |
| [Subtitle](../../groupdocs.metadata.formats.audio/apepackage/subtitle) { get; } | 자막을 가져옵니다. |
| [Title](../../groupdocs.metadata.formats.audio/apepackage/title) { get; } | 제목을 가져옵니다. |
| [Track](../../groupdocs.metadata.formats.audio/apepackage/track) { get; } | 트랙 번호를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [APEv2 태그 처리](https://docs.groupdocs.com/display/metadatanet/Handling+the+APEv2+tag)

### 예

이 예는 MP3 파일에서 APEv2 태그를 읽는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithApe))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ApeV2 != null)
    {
        Console.WriteLine(root.ApeV2.Album);
        Console.WriteLine(root.ApeV2.Title);
        Console.WriteLine(root.ApeV2.Artist);
        Console.WriteLine(root.ApeV2.Composer);
        Console.WriteLine(root.ApeV2.Copyright);
        Console.WriteLine(root.ApeV2.Genre);
        Console.WriteLine(root.ApeV2.Language);

        // ...
    }
}
```

### 또한보십시오

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
