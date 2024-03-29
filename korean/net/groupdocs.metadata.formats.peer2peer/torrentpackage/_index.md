---
title: TorrentPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 토렌트 설명자 파일 메타데이터를 나타냅니다. 자세한 내용은 다음을 참조하십시오.https//en.wikipedia.org/wiki/Torrent_filehttps//en.wikipedia.org/wiki/Torrent_file .
type: docs
weight: 2190
url: /ko/net/groupdocs.metadata.formats.peer2peer/torrentpackage/
---
## TorrentPackage class

토렌트 설명자 파일 메타데이터를 나타냅니다. 자세한 내용은 다음을 참조하십시오.[https://en.wikipedia.org/wiki/Torrent_file](https://en.wikipedia.org/wiki/Torrent_file) .

```csharp
public sealed class TorrentPackage : CustomPackage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Announce](../../groupdocs.metadata.formats.peer2peer/torrentpackage/announce) { get; set; } | 추적기의 URL을 가져오거나 설정합니다. |
| [Comment](../../groupdocs.metadata.formats.peer2peer/torrentpackage/comment) { get; set; } | 작성자의 설명을 가져오거나 설정합니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [CreatedBy](../../groupdocs.metadata.formats.peer2peer/torrentpackage/createdby) { get; set; } | 토렌트를 만드는 데 사용되는 프로그램의 이름과 버전을 가져오거나 설정합니다. |
| [CreationDate](../../groupdocs.metadata.formats.peer2peer/torrentpackage/creationdate) { get; set; } | 토렌트 생성 날짜를 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [PieceLength](../../groupdocs.metadata.formats.peer2peer/torrentpackage/piecelength) { get; } | 각 부분의 바이트 수를 가져옵니다. 자세한 내용은 다음을 참조하십시오. . |
| [Pieces](../../groupdocs.metadata.formats.peer2peer/torrentpackage/pieces) { get; } | 조각당 하나씩 모든 20바이트 SHA1 해시 값의 연결로 구성된 바이트 배열을 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [SharedFiles](../../groupdocs.metadata.formats.peer2peer/torrentpackage/sharedfiles) { get; } | 공유 파일 정보 항목이 포함된 배열을 가져옵니다. |

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

* [TORRENT 파일 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+TORRENT+files)

### 또한보십시오

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Peer2Peer](../../groupdocs.metadata.formats.peer2peer)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
