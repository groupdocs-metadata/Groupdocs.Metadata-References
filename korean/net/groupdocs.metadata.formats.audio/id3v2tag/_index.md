---
title: ID3V2Tag
second_title: .NET API 참조용 GroupDocs.Metadata
description: 는 ID3v2 태그를 나타냅니다. 자세한 내용은 다음을 참조하십시오.https//en.wikipedia.org/wiki/ID3ID3v2https//en.wikipedia.org/wiki/ID3ID3v2 .
type: docs
weight: 490
url: /ko/net/groupdocs.metadata.formats.audio/id3v2tag/
---
## ID3V2Tag class

는 ID3v2 태그를 나타냅니다. 자세한 내용은 다음을 참조하십시오.[https://en.wikipedia.org/wiki/ID3#ID3v2](https://en.wikipedia.org/wiki/ID3#ID3v2) .

```csharp
public sealed class ID3V2Tag : ID3Tag
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ID3V2Tag](id3v2tag)() | 의 새 인스턴스를 초기화합니다.[`ID3V2Tag`](../id3v2tag) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Album](../../groupdocs.metadata.formats.audio/id3v2tag/album) { get; set; } | 앨범/영화/쇼 제목을 가져오거나 설정합니다. 이 값은 TALB 프레임으로 표시됩니다. |
| [Artist](../../groupdocs.metadata.formats.audio/id3v2tag/artist) { get; set; } | 리드 아티스트/리드 연주자/솔로이스트/퍼포밍 그룹을 가져오거나 설정합니다. 이 값은 TPE1 프레임으로 표시됩니다. |
| [AttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/attachedpictures) { get; set; } | 오디오 파일과 직접 관련된 첨부된 그림을 가져오거나 설정합니다. 이 값은 APIC 프레임으로 표시됩니다. |
| [Band](../../groupdocs.metadata.formats.audio/id3v2tag/band) { get; set; } | 밴드/오케스트라/반주를 가져오거나 설정합니다. 이 값은 TPE2 프레임으로 표시됩니다. |
| [BitsPerMinute](../../groupdocs.metadata.formats.audio/id3v2tag/bitsperminute) { get; set; } | 오디오 주요 부분의 분당 비트 수를 가져오거나 설정합니다. 이 값은 TBPM 프레임으로 표시됩니다. |
| [Comments](../../groupdocs.metadata.formats.audio/id3v2tag/comments) { get; set; } | 사용자 설명을 가져오거나 설정합니다. 이 값은 COMM 프레임으로 표시됩니다. 프레임은 다른 프레임에 맞지 않는 모든 종류의 전체 텍스트 정보를 위한 것입니다. |
| [Composers](../../groupdocs.metadata.formats.audio/id3v2tag/composers) { get; set; } | 작성기를 가져오거나 설정합니다. 이름은 "/" 문자로 구분됩니다. 이 값은 TCOM 프레임으로 표시됩니다. |
| [ContentType](../../groupdocs.metadata.formats.audio/id3v2tag/contenttype) { get; set; } | 콘텐츠 유형을 가져오거나 설정합니다. 이 값은 TCON 프레임으로 표시됩니다. |
| [Copyright](../../groupdocs.metadata.formats.audio/id3v2tag/copyright) { get; set; } | 저작권 메시지를 가져오거나 설정합니다. 이 값은 TCOP 프레임으로 표시됩니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [Date](../../groupdocs.metadata.formats.audio/id3v2tag/date) { get; set; } | 녹화 날짜가 포함된 DDMM 형식의 숫자 문자열을 가져오거나 설정합니다. 이 필드는 항상 4자 길이입니다. 이 값은 TDAT 프레임으로 표시됩니다. |
| [EncodedBy](../../groupdocs.metadata.formats.audio/id3v2tag/encodedby) { get; set; } | 오디오 파일을 인코딩한 사람 또는 조직의 이름을 가져오거나 설정합니다. 이 값은 TENC 프레임으로 표시됩니다. |
| [Isrc](../../groupdocs.metadata.formats.audio/id3v2tag/isrc) { get; set; } | ISRC(International Standard Recording Code)(12자)를 가져오거나 설정합니다. 이 값은 TSRC 프레임으로 표시됩니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [LengthInMilliseconds](../../groupdocs.metadata.formats.audio/id3v2tag/lengthinmilliseconds) { get; set; } | 숫자 문자열로 표시되는 오디오 파일의 길이를 밀리초 단위로 가져오거나 설정합니다. 이 값은 TLEN 프레임으로 표시됩니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [MusicalKey](../../groupdocs.metadata.formats.audio/id3v2tag/musicalkey) { get; set; } | 사운드가 시작되는 음악 키를 가져오거나 설정합니다. 이 값은 TKEY 프레임으로 표시됩니다. |
| [OriginalAlbum](../../groupdocs.metadata.formats.audio/id3v2tag/originalalbum) { get; set; } | 원본 앨범/영화/프로그램 제목을 가져오거나 설정합니다. 이 값은 TOAL 프레임으로 표시됩니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Publisher](../../groupdocs.metadata.formats.audio/id3v2tag/publisher) { get; set; } | 레이블 또는 게시자의 이름을 가져오거나 설정합니다. 이 값은 TPUB 프레임으로 표시됩니다. |
| [SizeInBytes](../../groupdocs.metadata.formats.audio/id3v2tag/sizeinbytes) { get; set; } | 숫자 문자열로 표시되는 ID3v2 태그를 제외한 오디오 파일의 크기를 바이트 단위로 가져오거나 설정합니다. 이 값은 TSIZ 프레임으로 표시됩니다. |
| [SoftwareHardware](../../groupdocs.metadata.formats.audio/id3v2tag/softwarehardware) { get; set; } | 파일이 인코딩되었을 때 사용된 오디오 인코더 및 해당 설정을 가져오거나 설정합니다. 이 값은 TSSE 프레임으로 표시됩니다. |
| [Subtitle](../../groupdocs.metadata.formats.audio/id3v2tag/subtitle) { get; set; } | 자막/설명 개선을 가져오거나 설정합니다. 이 값은 TIT3 프레임으로 표시됩니다. |
| [TagSize](../../groupdocs.metadata.formats.audio/id3v2tag/tagsize) { get; } | 태그의 크기를 가져옵니다. |
| [Time](../../groupdocs.metadata.formats.audio/id3v2tag/time) { get; set; } | 기록 시간을 포함하는 HHMM 형식의 숫자 문자열을 가져오거나 설정합니다. 이 필드는 항상 4자 길이입니다. 이 값은 TIME 프레임으로 표시됩니다. |
| [Title](../../groupdocs.metadata.formats.audio/id3v2tag/title) { get; set; } | 제목/노래 이름/내용 설명을 가져오거나 설정합니다. 이 값은 TIT2 프레임으로 표시됩니다. |
| [TrackNumber](../../groupdocs.metadata.formats.audio/id3v2tag/tracknumber) { get; set; } | 원본 녹음에서 오디오 파일의 순서 번호를 포함하는 숫자 문자열을 가져오거나 설정합니다. 이 값은 TRCK 프레임으로 표시됩니다. |
| [TrackPlayCounter](../../groupdocs.metadata.formats.audio/id3v2tag/trackplaycounter) { get; } | 파일이 재생된 횟수를 가져옵니다. 이 값은 PCNT 프레임으로 표시됩니다. |
| override [Version](../../groupdocs.metadata.formats.audio/id3v2tag/version) { get; } | ID3 버전을 가져옵니다. |
| [Year](../../groupdocs.metadata.formats.audio/id3v2tag/year) { get; set; } | 녹음 연도가 포함된 숫자 문자열을 가져오거나 설정합니다. 이 프레임은 항상 4자 길이입니다(10000년까지). 이 값은 TYER 프레임으로 표시됩니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Add](../../groupdocs.metadata.formats.audio/id3v2tag/add)(ID3V2TagFrame) | 태그에 프레임을 추가합니다. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Clear](../../groupdocs.metadata.formats.audio/id3v2tag/clear)(string) | 지정된 id를 가진 모든 프레임을 제거합니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Get](../../groupdocs.metadata.formats.audio/id3v2tag/get)(string) | 지정된 id를 가진 프레임 배열을 가져옵니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Remove](../../groupdocs.metadata.formats.audio/id3v2tag/remove)(ID3V2TagFrame) | 태그에서 지정된 프레임을 제거합니다. |
| [RemoveAttachedPictures](../../groupdocs.metadata.formats.audio/id3v2tag/removeattachedpictures)() | APIC 프레임에 저장된 모든 첨부 사진을 제거합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Set](../../groupdocs.metadata.formats.audio/id3v2tag/set)(ID3V2TagFrame) | 지정된 프레임과 동일한 id를 가진 모든 프레임을 제거하고 새 프레임을 태그에 추가합니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [ToList](../../groupdocs.metadata.formats.audio/id3v2tag/tolist)() | 패키지에서 목록을 만듭니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [ID3v2 태그 처리](https://docs.groupdocs.com/display/metadatanet/Handling+the+ID3v2+tag)

### 예

이 예는 MP3 파일에서 ID3v2 태그를 읽는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 != null)
    {
        Console.WriteLine(root.ID3V2.Album);
        Console.WriteLine(root.ID3V2.Artist);
        Console.WriteLine(root.ID3V2.Band);
        Console.WriteLine(root.ID3V2.Title);
        Console.WriteLine(root.ID3V2.Composers);
        Console.WriteLine(root.ID3V2.Copyright);
        Console.WriteLine(root.ID3V2.Publisher);
        Console.WriteLine(root.ID3V2.OriginalAlbum);
        Console.WriteLine(root.ID3V2.MusicalKey);

        if (root.ID3V2.AttachedPictures != null)
        {
            foreach (var attachedPicture in root.ID3V2.AttachedPictures)
            {
                Console.WriteLine(attachedPicture.AttachedPictureType);
                Console.WriteLine(attachedPicture.MimeType);
                Console.WriteLine(attachedPicture.Description);

                // ...
            }
        }

        // ...
    }
}
```

### 또한보십시오

* class [ID3Tag](../id3tag)
* 네임스페이스 [GroupDocs.Metadata.Formats.Audio](../../groupdocs.metadata.formats.audio)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
