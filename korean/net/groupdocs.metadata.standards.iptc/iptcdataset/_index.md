---
title: IptcDataSet
second_title: .NET API 참조용 GroupDocs.Metadata
description: IPTC DataSet메타데이터 속성을 나타냅니다.
type: docs
weight: 2900
url: /ko/net/groupdocs.metadata.standards.iptc/iptcdataset/
---
## IptcDataSet class

IPTC DataSet(메타데이터 속성)을 나타냅니다.

```csharp
public sealed class IptcDataSet : MetadataProperty
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [IptcDataSet](iptcdataset#constructor)(byte, byte, byte[]) | 의 새 인스턴스를 초기화합니다.[`IptcDataSet`](../iptcdataset) 클래스. |
| [IptcDataSet](iptcdataset#constructor_2)(byte, byte, DateTime) | 의 새 인스턴스를 초기화합니다.[`IptcDataSet`](../iptcdataset) 클래스. |
| [IptcDataSet](iptcdataset#constructor_1)(byte, byte, int) | 의 새 인스턴스를 초기화합니다.[`IptcDataSet`](../iptcdataset) 클래스. |
| [IptcDataSet](iptcdataset#constructor_3)(byte, byte, string) | 의 새 인스턴스를 초기화합니다.[`IptcDataSet`](../iptcdataset) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternativeName](../../groupdocs.metadata.standards.iptc/iptcdataset/alternativename) { get; } | 데이터 세트의 대체 이름을 가져옵니다. |
| [DataSetNumber](../../groupdocs.metadata.standards.iptc/iptcdataset/datasetnumber) { get; } | 데이터 세트 번호를 가져옵니다. |
| [Descriptor](../../groupdocs.metadata.common/metadataproperty/descriptor) { get; } | 메타데이터 속성과 연결된 설명자를 가져옵니다. |
| [InterpretedValue](../../groupdocs.metadata.common/metadataproperty/interpretedvalue) { get; } | 사용 가능한 경우 해석된 속성 값을 가져옵니다. 해석된 값은 원래 속성 값의 사용자에게 친숙한 형식입니다. 예를 들어, 숫자 플래그 및 ID 대신 사람이 읽을 수 있는 문자열을 반환하고, 필요한 경우 는 바이트 배열을 텍스트로 변환하는 등의 작업을 수행합니다. |
| [Name](../../groupdocs.metadata.common/metadataproperty/name) { get; } | 속성 이름을 가져옵니다. |
| [RecordNumber](../../groupdocs.metadata.standards.iptc/iptcdataset/recordnumber) { get; } | 레코드 번호를 가져옵니다. |
| [Tags](../../groupdocs.metadata.common/metadataproperty/tags) { get; } | 속성과 연결된 태그 모음을 가져옵니다. |
| [Value](../../groupdocs.metadata.common/metadataproperty/value) { get; } | 속성 값을 가져옵니다. |

### 비고

**더 알아보기**

* [IPTC IIM 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+IPTC+IIM+metadata)

### 또한보십시오

* class [MetadataProperty](../../groupdocs.metadata.common/metadataproperty)
* 네임스페이스 [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->