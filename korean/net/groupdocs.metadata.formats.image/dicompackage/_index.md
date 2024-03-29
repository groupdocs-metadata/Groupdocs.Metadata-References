---
title: DicomPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 네이티브 DICOM 메타데이터를 나타냅니다.
type: docs
weight: 1670
url: /ko/net/groupdocs.metadata.formats.image/dicompackage/
---
## DicomPackage class

네이티브 DICOM 메타데이터를 나타냅니다.

```csharp
public sealed class DicomPackage : CustomPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DicomPackage](dicompackage)() | 의 새 인스턴스를 초기화합니다.[`Metadata`](../../groupdocs.metadata/metadata) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BitsAllocated](../../groupdocs.metadata.formats.image/dicompackage/bitsallocated) { get; } | 할당된 비트 값을 가져옵니다. |
| [Blues](../../groupdocs.metadata.formats.image/dicompackage/blues) { get; } | 파란색의 배열 색상을 가져옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DicomInfo](../../groupdocs.metadata.formats.image/dicompackage/dicominfo) { get; } | DICOM 파일의 헤더 정보를 가져옵니다. |
| [Greens](../../groupdocs.metadata.formats.image/dicompackage/greens) { get; } | 녹색의 배열 색상을 가져옵니다. |
| [HeaderBytes](../../groupdocs.metadata.formats.image/dicompackage/headerbytes) { get; } | 헤더 정보를 바이트 단위로 가져옵니다. |
| [HeaderOffset](../../groupdocs.metadata.formats.image/dicompackage/headeroffset) { get; } | 헤더 오프셋을 가져옵니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [NumberOfFrames](../../groupdocs.metadata.formats.image/dicompackage/numberofframes) { get; } | 프레임 수를 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Reds](../../groupdocs.metadata.formats.image/dicompackage/reds) { get; } | 빨간색의 배열 색상을 가져옵니다. |

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

* [DICOM 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+DICOM+metadata)

### 또한보십시오

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
