---
title: SpreadsheetPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 스프레드시트의 기본 메타데이터 패키지를 나타냅니다.
type: docs
weight: 1200
url: /ko/net/groupdocs.metadata.formats.document/spreadsheetpackage/
---
## SpreadsheetPackage class

스프레드시트의 기본 메타데이터 패키지를 나타냅니다.

```csharp
public class SpreadsheetPackage : DocumentPackage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/spreadsheetpackage/author) { get; set; } | 문서 작성자를 가져오거나 설정합니다. |
| [Category](../../groupdocs.metadata.formats.document/spreadsheetpackage/category) { get; set; } | 범주를 가져오거나 설정합니다. |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetpackage/comments) { get; set; } | 설명을 가져오거나 설정합니다. |
| [Company](../../groupdocs.metadata.formats.document/spreadsheetpackage/company) { get; set; } | 회사를 가져오거나 설정합니다. |
| [ContentStatus](../../groupdocs.metadata.formats.document/spreadsheetpackage/contentstatus) { get; set; } | 콘텐츠 상태를 가져오거나 설정합니다. |
| [ContentType](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttype) { get; set; } | 콘텐츠 유형을 가져오거나 설정합니다. |
| [ContentTypeProperties](../../groupdocs.metadata.formats.document/spreadsheetpackage/contenttypeproperties) { get; } | 콘텐츠 유형 속성을 포함하는 메타데이터 패키지를 가져옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [CreatedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/createdtime) { get; set; } | 문서 생성 날짜를 가져오거나 설정합니다. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/spreadsheetpackage/hyperlinkbase) { get; set; } | 하이퍼링크 기준을 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Keywords](../../groupdocs.metadata.formats.document/spreadsheetpackage/keywords) { get; set; } | 키워드를 가져오거나 설정합니다. |
| [Language](../../groupdocs.metadata.formats.document/spreadsheetpackage/language) { get; set; } | 문서 언어를 가져오거나 설정합니다. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastprinteddate) { get; set; } | UTC로 마지막 인쇄 날짜를 가져오거나 설정합니다. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedby) { get; set; } | 마지막 작성자의 이름을 가져오거나 설정합니다. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/lastsavedtime) { get; set; } | 마지막 저장 시간을 UTC로 가져오거나 설정합니다. |
| [Manager](../../groupdocs.metadata.formats.document/spreadsheetpackage/manager) { get; set; } | 관리자를 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/spreadsheetpackage/nameofapplication) { get; set; } | 응용 프로그램의 이름을 가져오거나 설정합니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Revision](../../groupdocs.metadata.formats.document/spreadsheetpackage/revision) { get; set; } | 문서 개정 번호를 가져오거나 설정합니다. |
| [Subject](../../groupdocs.metadata.formats.document/spreadsheetpackage/subject) { get; set; } | 제목을 가져오거나 설정합니다. |
| [Template](../../groupdocs.metadata.formats.document/spreadsheetpackage/template) { get; set; } | 문서 템플릿 이름을 가져오거나 설정합니다. |
| [Title](../../groupdocs.metadata.formats.document/spreadsheetpackage/title) { get; set; } | 문서의 제목을 가져오거나 설정합니다. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/spreadsheetpackage/totaleditingtime) { get; set; } | 총 편집 시간을 분 단위로 가져오거나 설정합니다. |
| [Version](../../groupdocs.metadata.formats.document/spreadsheetpackage/version) { get; set; } | 문서를 만든 응용 프로그램의 버전 번호를 가져오거나 설정합니다. |

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
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set)(string, bool) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_3)(string, DateTime) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_1)(string, double) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_2)(string, int) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/spreadsheetpackage/set#set_4)(string, string) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [스프레드시트에서 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### 예

이 예는 스프레드시트에서 기본 제공 메타데이터 속성을 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputXlsx);
}
```

### 또한보십시오

* class [DocumentPackage](../documentpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
