---
title: OpenTypeFlags
second_title: .NET API 참조용 GroupDocs.Metadata
description: OpenType 글꼴 헤더 플래그를 나타냅니다.
type: docs
weight: 1450
url: /ko/net/groupdocs.metadata.formats.font/opentypeflags/
---
## OpenTypeFlags enumeration

OpenType 글꼴 헤더 플래그를 나타냅니다.

```csharp
[Flags]
public enum OpenTypeFlags : ushort
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 정의되지 않음, 플래그 없음. |
| BaselineAtY0 | `1` | y=0. 에서 글꼴의 기준선 |
| LeftSidebearingAtX0 | `2` | x=0의 왼쪽 측면 방위점(TrueType 래스터라이저에만 해당). |
| DependOnPointSize | `4` | 명령어는 포인트 크기에 따라 달라질 수 있습니다. |
| ForceToInteger | `8` | 모든 내부 스케일러 수학에 대해 ppm을 정수 값으로 강제합니다. 이 비트가 명확한 경우 분수 ppm 크기를 사용할 수 있습니다. |
| AlterAdvanceWidth | `10` | 명령은 전진 너비를 변경할 수 있습니다(전진 너비는 선형으로 확장되지 않을 수 있음). |
| Lossless | `1000` | 글꼴 데이터는 최적화된 변환 및/또는 압축을 거친 결과 "무손실"입니다. |
| Converted | `2000` | 글꼴 변환됨(호환 메트릭 생성). |
| Optimized | `4000` | ClearType™에 최적화된 글꼴. |
| Resort | `8000` | 최후의 수단 글꼴. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->