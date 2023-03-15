---
title: DiagramPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 다이어그램 형식의 기본 메타데이터 패키지를 나타냅니다.
type: docs
weight: 890
url: /ko/net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

다이어그램 형식의 기본 메타데이터 패키지를 나타냅니다.

```csharp
public class DiagramPackage : DocumentPackage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | 문서의 대체 이름을 가져오거나 설정합니다. VDX 및 VSX 형식으로만 업데이트할 수 있습니다. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | 문서를 만드는 데 사용된 인스턴스의 전체 빌드 번호를 가져옵니다. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | 문서를 편집하는 데 마지막으로 사용된 인스턴스의 빌드 번호를 가져옵니다. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | 순서도 또는 사무실 레이아웃과 같은 드로잉 유형에 대한 설명 텍스트를 가져오거나 설정합니다. 이 텍스트는 속성 대화 상자의 범주 상자에 있는 Microsoft Visio 사용자 인터페이스에 입력할 수도 있습니다. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | 도면을 작성하는 회사 또는 도면을 작성할 회사를 식별하는 사용자 입력 정보를 가져오거나 설정합니다. 최대 길이는 63자입니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | 파일을 생성하거나 마지막으로 업데이트한 사람을 가져오거나 설정합니다. 최대 길이는 63자입니다.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | 문서에 대한 설명 텍스트 문자열을 가져오거나 설정합니다. 이 요소를 사용하여 목적, 최근 변경 사항 또는 보류 중인 변경 사항과 같은 문서에 대한 중요한 정보를 저장합니다. 최대 191자입니다. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | 상대 하이퍼링크(Microsoft Visio 다이어그램과 관련하여 연결된 파일 위치가 설명된 하이퍼링크)에 사용할 경로를 가져오거나 설정합니다. 기본적으로 하이퍼링크 경로는 다른 경로가 지정되지 않는 한 현재 문서에 상대적입니다. 이 요소에서. 최대 길이는 256자입니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | 프로젝트 이름, 클라이언트 이름 또는 버전 번호와 같은 파일에 대한 항목 또는 기타 중요한 정보를 식별하는 텍스트 문자열을 가져오거나 설정합니다. 최대 문자열 길이는 63자입니다. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | 문서의 언어를 가져오거나 설정합니다. VSD 및 VSDX 형식으로만 업데이트할 수 있습니다. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | 프로젝트 또는 부서의 담당자를 식별하는 사용자 입력 텍스트 문자열을 가져오거나 설정합니다. 최대 길이는 63자입니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | 미리보기 그림을 가져오거나 설정합니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | 문서의 내용을 설명하는 사용자 정의 텍스트 문자열을 가져오거나 설정합니다. 최대 길이는 63자입니다. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | 문서가 생성된 템플릿의 파일 이름을 지정하는 문자열 값을 가져오거나 설정합니다. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | 문서가 생성된 날짜 및 시간 값을 가져오거나 설정합니다. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | 문서가 마지막으로 편집된 시간을 나타내는 날짜 및 시간 값을 가져옵니다. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | 문서가 마지막으로 인쇄된 시간을 나타내는 날짜 및 시간 값을 가져옵니다. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | 문서가 마지막으로 저장된 시간을 나타내는 날짜 및 시간 값을 가져옵니다. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | 문서에 대한 설명 제목 역할을 하는 사용자 정의 텍스트 문자열을 가져오거나 설정합니다. 최대 길이는 63자입니다. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | 메타데이터 속성을 지정된 이름으로 추가하거나 바꿉니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [다이어그램에서 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### 예

이 코드 샘플은 다이어그램에서 기본 제공 메타데이터 속성을 추출하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### 또한보십시오

* class [DocumentPackage](../documentpackage)
* 네임스페이스 [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
