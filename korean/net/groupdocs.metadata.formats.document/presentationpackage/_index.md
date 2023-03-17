---
title: PresentationPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 프레젠테이션의 기본 메타데이터 패키지를 나타냅니다.
type: docs
weight: 1090
url: /ko/net/groupdocs.metadata.formats.document/presentationpackage/
---
## PresentationPackage class

프레젠테이션의 기본 메타데이터 패키지를 나타냅니다.

```csharp
public class PresentationPackage : DocumentPackage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ApplicationTemplate](../../groupdocs.metadata.formats.document/presentationpackage/applicationtemplate) { get; set; } | 응용 프로그램 템플릿을 가져오거나 설정합니다. |
| [Author](../../groupdocs.metadata.formats.document/presentationpackage/author) { get; set; } | 문서 작성자를 가져오거나 설정합니다. |
| [Category](../../groupdocs.metadata.formats.document/presentationpackage/category) { get; set; } | 범주를 가져오거나 설정합니다. |
| [Comments](../../groupdocs.metadata.formats.document/presentationpackage/comments) { get; set; } | 설명을 가져오거나 설정합니다. |
| [Company](../../groupdocs.metadata.formats.document/presentationpackage/company) { get; set; } | 회사를 가져오거나 설정합니다. |
| [ContentStatus](../../groupdocs.metadata.formats.document/presentationpackage/contentstatus) { get; set; } | 콘텐츠 상태를 가져오거나 설정합니다. PPTX 문서에서만 업데이트할 수 있습니다. |
| [ContentType](../../groupdocs.metadata.formats.document/presentationpackage/contenttype) { get; set; } | 콘텐츠 형식을 가져오거나 설정합니다. PPTX 문서에서만 업데이트할 수 있습니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [CreatedTime](../../groupdocs.metadata.formats.document/presentationpackage/createdtime) { get; set; } | 문서 생성 날짜를 가져오거나 설정합니다. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/presentationpackage/hyperlinkbase) { get; set; } | 하이퍼링크 기준을 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Keywords](../../groupdocs.metadata.formats.document/presentationpackage/keywords) { get; set; } | 키워드를 가져오거나 설정합니다. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/presentationpackage/lastprinteddate) { get; set; } | 마지막으로 인쇄된 날짜를 가져오거나 설정합니다. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedby) { get; set; } | 마지막 작성자의 이름을 가져오거나 설정합니다. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/presentationpackage/lastsavedtime) { get; } | 프레젠테이션이 마지막으로 수정된 날짜와 시간을 가져옵니다. |
| [Manager](../../groupdocs.metadata.formats.document/presentationpackage/manager) { get; set; } | 관리자를 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/presentationpackage/nameofapplication) { get; } | 문서를 만든 응용 프로그램의 이름을 가져옵니다. |
| [PresentationFormat](../../groupdocs.metadata.formats.document/presentationpackage/presentationformat) { get; } | 프레젠테이션 형식을 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/presentationpackage/revisionnumber) { get; set; } | 개정 번호를 가져오거나 설정합니다. |
| [SharedDoc](../../groupdocs.metadata.formats.document/presentationpackage/shareddoc) { get; set; } | 여러 사람이 프레젠테이션을 공유하는지 여부를 나타내는 값을 가져오거나 설정합니다. PPTX 문서에서만 업데이트할 수 있습니다. |
| [Subject](../../groupdocs.metadata.formats.document/presentationpackage/subject) { get; set; } | 제목을 가져오거나 설정합니다. |
| [Title](../../groupdocs.metadata.formats.document/presentationpackage/title) { get; set; } | 문서의 제목을 가져오거나 설정합니다. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/presentationpackage/totaleditingtime) { get; set; } | 문서의 총 편집 시간을 가져오거나 설정합니다. |
| [Version](../../groupdocs.metadata.formats.document/presentationpackage/version) { get; } | 애플리케이션 버전을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | 패키지에서 쓰기 가능한 모든 메타데이터 속성을 제거합니다. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | 모든 내장 메타데이터 속성을 제거합니다. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | 모든 사용자 지정 메타데이터 속성을 제거합니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | 지정된 이름으로 쓰기 가능한 메타데이터 속성을 제거합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set)(string, bool) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_3)(string, DateTime) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_1)(string, double) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_2)(string, int) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/presentationpackage/set#set_4)(string, string) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [프레젠테이션에서 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Presentations)

### 예

이 예는 프레젠테이션에서 기본 제공 메타데이터 속성을 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPptx))
{
    var root = metadata.GetRootPackage<PresentationRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPptx);
}
```

### 또한보십시오

* class [DocumentPackage](../documentpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
