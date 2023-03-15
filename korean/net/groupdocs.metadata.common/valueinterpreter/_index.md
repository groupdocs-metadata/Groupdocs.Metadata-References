---
title: ValueInterpreter
second_title: .NET API 참조용 GroupDocs.Metadata
description: 메타데이터 속성 값을 해석하는 데 필요한 작업을 정의합니다.
type: docs
weight: 260
url: /ko/net/groupdocs.metadata.common/valueinterpreter/
---
## ValueInterpreter class

메타데이터 속성 값을 해석하는 데 필요한 작업을 정의합니다.

```csharp
public abstract class ValueInterpreter
```

## 속성

| 이름 | 설명 |
| --- | --- |
| abstract [InterpretedValueType](../../groupdocs.metadata.common/valueinterpreter/interpretedvaluetype) { get; } | 해석된 값의 유형을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [ToInterpretedValue](../../groupdocs.metadata.common/valueinterpreter/tointerpretedvalue)(PropertyValue) | 제공된 속성 값을 해석합니다. |
| [ToSourceValue](../../groupdocs.metadata.common/valueinterpreter/tosourcevalue)(PropertyValue) | 해석된 값을 다시 원래 형식으로 변환합니다. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->