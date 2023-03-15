---
title: AviHeader
second_title: .NET API 참조용 GroupDocs.Metadata
description: AVI 비디오의 AVIMAINHEADER 구조를 나타냅니다.
type: docs
weight: 2380
url: /ko/net/groupdocs.metadata.formats.video/aviheader/
---
## AviHeader class

AVI 비디오의 AVIMAINHEADER 구조를 나타냅니다.

```csharp
public sealed class AviHeader : CustomPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AviHeader](aviheader)() | 의 새 인스턴스를 초기화합니다.[`AviHeader`](../aviheader) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AviHeaderFlags](../../groupdocs.metadata.formats.video/aviheader/aviheaderflags) { get; } | 0개 이상의 AVI 플래그의 비트 조합을 가져옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [Height](../../groupdocs.metadata.formats.video/aviheader/height) { get; } | AVI 파일의 높이를 픽셀 단위로 가져옵니다. |
| [InitialFrames](../../groupdocs.metadata.formats.video/aviheader/initialframes) { get; } | 인터리브 파일의 초기 프레임을 가져옵니다.  비인터리브 파일은 0을 지정해야 합니다. 인터리브 파일을 생성하는 경우 이 멤버에서 AVI 시퀀스의 초기 프레임 이전 파일에서 프레임 수 를 지정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [MaxBytesPerSec](../../groupdocs.metadata.formats.video/aviheader/maxbytespersec) { get; } | 파일의 대략적인 최대 데이터 속도를 가져옵니다.  이 값은 메인 헤더 및 스트림 헤더 청크에 포함된 다른 매개변수에 의해 지정된 로 AVI 시퀀스를 표시하기 위해 시스템이 처리해야 하는 초당 바이트 수를 나타냅니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [MicroSecPerFrame](../../groupdocs.metadata.formats.video/aviheader/microsecperframe) { get; } | 프레임 사이의 마이크로초 수를 가져옵니다. 이 값은 파일의 전체 타이밍을 나타냅니다. |
| [PaddingGranularity](../../groupdocs.metadata.formats.video/aviheader/paddinggranularity) { get; } | 데이터 정렬을 바이트 단위로 가져옵니다. 데이터를 이 값의 배수로 채웁니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Streams](../../groupdocs.metadata.formats.video/aviheader/streams) { get; } | 파일의 스트림 수를 가져옵니다. 예를 들어 오디오와 비디오가 있는 파일에는 두 개의 스트림이 있습니다. |
| [SuggestedBufferSize](../../groupdocs.metadata.formats.video/aviheader/suggestedbuffersize) { get; } | 파일을 읽기 위해 제안된 버퍼 크기를 가져옵니다.  일반적으로 이 크기는 파일에서 가장 큰 청크를 포함할 수 있을 만큼 충분히 커야 합니다. 0으로 설정하거나 너무 작은 경우 재생 소프트웨어는 재생 중에 메모리를 재할당해야 하므로 성능이 저하됩니다. 인터리브된 파일의 경우 버퍼 크기는 청크만이 아니라 전체 레코드를 읽을 수 있을 만큼 충분히 커야 합니다. |
| [TotalFrames](../../groupdocs.metadata.formats.video/aviheader/totalframes) { get; } | 파일에 있는 데이터의 총 프레임 수를 가져옵니다. |
| [Width](../../groupdocs.metadata.formats.video/aviheader/width) { get; } | AVI 파일의 너비를 픽셀 단위로 가져옵니다. |

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

* [AVI 파일의 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+AVI+files)

### 또한보십시오

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->