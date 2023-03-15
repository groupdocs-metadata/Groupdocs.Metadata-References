---
title: VCardCard
second_title: .NET API 참조용 GroupDocs.Metadata
description: VCard 파일에서 추출한 단일 카드를 나타냅니다.
type: docs
weight: 650
url: /ko/net/groupdocs.metadata.formats.businesscard/vcardcard/
---
## VCardCard class

VCard 파일에서 추출한 단일 카드를 나타냅니다.

```csharp
public class VCardCard : VCardRecordset
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CalendarRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/calendarrecordset) { get; } | 달력 레코드를 가져옵니다. |
| [CommunicationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/communicationrecordset) { get; } | 통신 기록을 가져옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DeliveryAddressingRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/deliveryaddressingrecordset) { get; } | 배달 주소 레코드를 가져옵니다. |
| [ExplanatoryRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/explanatoryrecordset) { get; } | 설명 레코드를 가져옵니다. |
| [ExtensionRecords](../../groupdocs.metadata.formats.businesscard/vcardcard/extensionrecords) { get; } | 개인 확장 레코드를 가져옵니다. |
| [GeneralRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/generalrecordset) { get; } | 일반 레코드를 가져옵니다. |
| [GeographicalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/geographicalrecordset) { get; } | 지리적 레코드를 가져옵니다. |
| [IdentificationRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/identificationrecordset) { get; } | 식별 레코드를 가져옵니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [OrganizationalRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/organizationalrecordset) { get; } | 조직 레코드를 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [SecurityRecordset](../../groupdocs.metadata.formats.businesscard/vcardcard/securityrecordset) { get; } | 보안 레코드를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| [FilterByGroup](../../groupdocs.metadata.formats.businesscard/vcardcard/filterbygroup)(string) | 매개변수로 전달된 그룹 이름으로 모든 vCard 레코드를 필터링합니다. 자세한 내용은 다음을 참조하십시오. 방법. |
| [FilterHomeTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterhometags)() | HOME 태그로 표시된 모든 vCard 레코드를 필터링합니다. |
| [FilterPreferred](../../groupdocs.metadata.formats.businesscard/vcardcard/filterpreferred)() | 기본 레코드를 필터링합니다. |
| [FilterWorkTags](../../groupdocs.metadata.formats.businesscard/vcardcard/filterworktags)() | WORK 태그로 표시된 모든 vCard 레코드를 필터링합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetAvailableGroups](../../groupdocs.metadata.formats.businesscard/vcardcard/getavailablegroups)() | 사용 가능한 그룹 이름을 가져옵니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [vCard 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### 예

이 예는 vCard 속성 필터를 사용하는 방법을 보여줍니다.

```csharp
public static void Run()
{
    using (Metadata metadata = new Metadata(Constants.InputVcf))
    {
        var root = metadata.GetRootPackage<VCardRootPackage>();

        foreach (var vCard in root.VCardPackage.Cards)
        {
            // 가장 선호하는 직장 전화번호 및 직장 이메일 출력
            var filtered = vCard.FilterWorkTags().FilterPreferred();
            PrintArray(filtered.CommunicationRecordset.Telephones);
            PrintArray(filtered.CommunicationRecordset.Emails);
        }
    }
}

private static void PrintArray(string[] values)
{
    if (values != null)
    {
        foreach (string value in values)
        {
            Console.WriteLine(value);
        }
    }
}
```

### 또한보십시오

* class [VCardRecordset](../vcardrecordset)
* 네임스페이스 [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
