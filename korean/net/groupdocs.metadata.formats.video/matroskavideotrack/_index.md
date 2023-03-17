---
title: MatroskaVideoTrack
second_title: .NET API 참조용 GroupDocs.Metadata
description: Matroska 비디오의 비디오 메타데이터를 나타냅니다.
type: docs
weight: 2610
url: /ko/net/groupdocs.metadata.formats.video/matroskavideotrack/
---
## MatroskaVideoTrack class

Matroska 비디오의 비디오 메타데이터를 나타냅니다.

```csharp
public class MatroskaVideoTrack : MatroskaTrack
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlphaMode](../../groupdocs.metadata.formats.video/matroskavideotrack/alphamode) { get; } | 알파 비디오 모드를 가져옵니다. 이 요소의 존재는 BlockAdditional 요소가 알파 데이터를 포함할 수 있음을 나타냅니다. |
| [CodecID](../../groupdocs.metadata.formats.video/matroskatrack/codecid) { get; } | 코덱에 해당하는 ID를 가져옵니다. |
| [CodecName](../../groupdocs.metadata.formats.video/matroskatrack/codecname) { get; } | 코덱을 지정하는 사람이 읽을 수 있는 문자열을 가져옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DefaultDuration](../../groupdocs.metadata.formats.video/matroskatrack/defaultduration) { get; } | 나노초 수를 가져옵니다(통해 조정되지 않음).[`TimecodeScale`](../matroskasegment/timecodescale) ) 프레임당. |
| [DisplayHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/displayheight) { get; } | 표시할 비디오 프레임의 높이를 가져옵니다. 자르기 후 비디오 프레임에 적용됩니다(PixelCrop* 요소). |
| [DisplayUnit](../../groupdocs.metadata.formats.video/matroskavideotrack/displayunit) { get; } | 방법을 가져옵니다.[`DisplayWidth`](./displaywidth) 그리고[`DisplayHeight`](./displayheight) 해석됩니다. |
| [DisplayWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/displaywidth) { get; } | 표시할 비디오 프레임의 너비를 가져옵니다. 자르기 후 비디오 프레임에 적용됩니다(PixelCrop* 요소). |
| [FieldOrder](../../groupdocs.metadata.formats.video/matroskavideotrack/fieldorder) { get; } | 비디오의 필드 순서를 선언합니다. FlagInterlaced가 1로 설정되지 않은 경우 이 요소는 무시되어야 합니다. |
| [FlagEnabled](../../groupdocs.metadata.formats.video/matroskatrack/flagenabled) { get; } | 활성화된 플래그를 가져옵니다. 트랙을 사용할 수 있으면 true입니다. |
| [FlagInterlaced](../../groupdocs.metadata.formats.video/matroskavideotrack/flaginterlaced) { get; } | 비디오가 프로그레시브 또는 인터레이스로 알려진 경우 선언할 플래그를 가져오고 적용 가능한 경우 인터레이스에 대한 세부 정보를 선언합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Language](../../groupdocs.metadata.formats.video/matroskatrack/language) { get; } | Matroska 언어 형식으로 트랙의 언어를 가져옵니다. 이 요소는 다음과 같은 경우 무시해야 합니다.[`LanguageIetf`](../matroskatrack/languageietf) 요소는 동일한 TrackEntry. 에서 사용됩니다. |
| [LanguageIetf](../../groupdocs.metadata.formats.video/matroskatrack/languageietf) { get; } | BCP 47에 따라 IANA 언어 하위 태그 레지스트리를 사용하여 트랙의 언어를 가져옵니다. 이 요소가 사용되면 모든[`Language`](../matroskatrack/language) 동일한 TrackEntry에 사용된 요소는 무시해야 합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [Name](../../groupdocs.metadata.formats.video/matroskatrack/name) { get; } | 사람이 읽을 수 있는 트랙 이름을 가져옵니다. |
| [PixelCropBottom](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropbottom) { get; } | 이미지 하단에서 제거할 비디오 픽셀 수를 가져옵니다. |
| [PixelCropLeft](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropleft) { get; } | 이미지 왼쪽에서 제거할 비디오 픽셀 수를 가져옵니다. |
| [PixelCropRight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcropright) { get; } | 이미지 오른쪽에서 제거할 비디오 픽셀 수를 가져옵니다. |
| [PixelCropTop](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelcroptop) { get; } | 이미지 상단에서 제거할 비디오 픽셀 수를 가져옵니다. |
| [PixelHeight](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelheight) { get; } | 인코딩된 비디오 프레임의 높이를 픽셀 단위로 가져옵니다. |
| [PixelWidth](../../groupdocs.metadata.formats.video/matroskavideotrack/pixelwidth) { get; } | 인코딩된 비디오 프레임의 너비를 픽셀 단위로 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [StereoMode](../../groupdocs.metadata.formats.video/matroskavideotrack/stereomode) { get; } | 스테레오 3D 비디오 모드를 가져옵니다. |
| [TrackNumber](../../groupdocs.metadata.formats.video/matroskatrack/tracknumber) { get; } | 블록 헤더에 사용된 트랙 번호를 가져옵니다. 127개 이상의 트랙을 사용하는 것은 권장되지 않지만 설계상 무제한으로 허용됩니다. |
| [TrackType](../../groupdocs.metadata.formats.video/matroskatrack/tracktype) { get; } | 트랙의 유형을 가져옵니다. |
| [TrackUid](../../groupdocs.metadata.formats.video/matroskatrack/trackuid) { get; } | 트랙을 식별하기 위한 고유 ID를 가져옵니다. 이것은 트랙을 다른 파일로 직접 스트림 복사할 때 동일하게 유지해야 합니다. |

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

* [Matroska(MKV) 파일의 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Matroska+%28MKV%29+files)

### 또한보십시오

* class [MatroskaTrack](../matroskatrack)
* 네임스페이스 [GroupDocs.Metadata.Formats.Video](../../groupdocs.metadata.formats.video)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
