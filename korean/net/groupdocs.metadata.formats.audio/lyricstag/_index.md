---
title: LyricsTag
second_title: .NET API 참조용 GroupDocs.Metadata
description: Lyrics3 v2.00 메타데이터를 나타냅니다. 자세한 내용은 다음을 참조하십시오.http//id3.org/Lyrics3v2 .
type: docs
weight: 570
url: /ko/net/groupdocs.metadata.formats.audio/lyricstag/
---
## LyricsTag class

Lyrics3 v2.00 메타데이터를 나타냅니다. 자세한 내용은 다음을 참조하십시오.http://id3.org/Lyrics3v2 .

```csharp
public sealed class LyricsTag : CustomPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [LyricsTag](lyricstag)() | 의 새 인스턴스를 초기화합니다.[`LyricsTag`](../lyricstag) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdditionalInfo](../../groupdocs.metadata.formats.audio/lyricstag/additionalinfo) { get; set; } | 추가 정보를 가져오거나 설정합니다. 이 값은 INF 필드로 표시됩니다. |
| [Album](../../groupdocs.metadata.formats.audio/lyricstag/album) { get; set; } | 앨범 이름을 가져오거나 설정합니다. 이 값은 EAL 필드로 표시됩니다. |
| [Artist](../../groupdocs.metadata.formats.audio/lyricstag/artist) { get; set; } | 아티스트 이름을 가져오거나 설정합니다. 이 값은 EAR 필드로 표시됩니다. |
| [Author](../../groupdocs.metadata.formats.audio/lyricstag/author) { get; set; } | 작성자를 가져오거나 설정합니다. 이 값은 AUT 필드로 표시됩니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Lyrics](../../groupdocs.metadata.formats.audio/lyricstag/lyrics) { get; set; } | 가사를 가져오거나 설정합니다. 이 값은 LYR 필드로 표시됩니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Track](../../groupdocs.metadata.formats.audio/lyricstag/track) { get; set; } | 트랙 제목을 가져오거나 설정합니다. 이 값은 ETT 필드로 표시됩니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Get](../../groupdocs.metadata.formats.audio/lyricstag/get)(string) | 지정된 id를 가진 필드의 값을 가져옵니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Remove](../../groupdocs.metadata.formats.audio/lyricstag/remove)(string) | 지정된 id를 가진 필드를 제거합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Set](../../groupdocs.metadata.formats.audio/lyricstag/set)(LyricsField) | 지정된 Lyrics3 필드를 추가하거나 바꿉니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [ToList](../../groupdocs.metadata.formats.audio/lyricstag/tolist)() | 패키지에서 목록을 만듭니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

Lyrics3 v2.00은 필드를 사용하여 정보를 나타냅니다. 필드의 데이터는 표준에 따라 01에서 254 범위의 ASCII 문자로 구성될 수 있습니다. ASCII 문자 맵은 00에서 128까지만 정의되므로 ISO-8859- 1로 추정할 수 있습니다. 숫자 필드는 위치에 따라 길이가 5자 또는 6자이며 0으로 채워집니다.

**더 알아보기**

* [가사 태그 처리](https://docs.groupdocs.com/display/metadatanet/Handling+the+Lyrics+tag)

### 예

이 코드 샘플은 MP3 파일에서 가사 태그를 읽는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithLyrics))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.Lyrics3V2 != null)
    {
        Console.WriteLine(root.Lyrics3V2.Lyrics);
        Console.WriteLine(root.Lyrics3V2.Album);
        Console.WriteLine(root.Lyrics3V2.Artist);
        Console.WriteLine(root.Lyrics3V2.Track);

        // ...

        // 또는 태그 필드의 전체 목록을 반복할 수 있습니다.
        foreach (var field in root.Lyrics3V2.ToList())
        {
            Console.WriteLine("{0} = {1}", field.ID, field.Data);
        }
    }
}
```

### 또한보십시오

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
