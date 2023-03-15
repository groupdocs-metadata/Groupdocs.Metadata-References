---
title: WordProcessingInspectionPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 경우에 따라 메타데이터로 간주될 수 있는 문서 부분에 대한 정보를 포함합니다.
type: docs
weight: 1270
url: /ko/net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
---
## WordProcessingInspectionPackage class

경우에 따라 메타데이터로 간주될 수 있는 문서 부분에 대한 정보를 포함합니다.

```csharp
public sealed class WordProcessingInspectionPackage : CustomPackage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments) { get; } | 사용자 댓글의 배열을 가져옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digitalsignatures) { get; } | 문서에 표시된 디지털 서명 배열을 가져옵니다. |
| [Fields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields) { get; } | 문서 필드의 배열을 가져옵니다. |
| [HiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hiddentext) { get; } | 문서에서 추출된 숨겨진 텍스트 조각의 배열을 가져옵니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Revisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions) { get; } | 문서에 표시된 디지털 서명 배열을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AcceptAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/acceptallrevisions)() | 문서에서 감지된 모든 개정을 승인합니다. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [ClearComments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearcomments)() | 문서에서 감지된 모든 사용자 댓글을 제거합니다. |
| [ClearFields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearfields)() | 문서에서 감지된 모든 필드를 제거합니다. |
| [ClearHiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearhiddentext)() | 문서에서 숨겨진 텍스트 조각을 모두 제거합니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [RejectAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/rejectallrevisions)() | 문서에서 감지된 모든 개정을 거부합니다. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| override [Sanitize](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [WordProcessing 문서에서 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### 예

이 코드 샘플은 WordProcessing 문서에서 검사 속성을 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.AcceptAllRevisions();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearHiddenText();

    metadata.Save(Constants.OutputDoc);
}
```

### 또한보십시오

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
