---
title: XmpBasicPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: XMP 기본 네임스페이스를 나타냅니다.
type: docs
weight: 3090
url: /ko/net/groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/
---
## XmpBasicPackage class

XMP 기본 네임스페이스를 나타냅니다.

```csharp
public sealed class XmpBasicPackage : XmpPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage)() | 의 새 인스턴스를 초기화합니다.[`XmpBasicPackage`](../xmpbasicpackage) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaseUrl](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/baseurl) { get; set; } | 문서 내용의 상대 URL에 대한 기본 URL을 가져오거나 설정합니다. 이 문서에 인터넷 링크가 포함되어 있고 해당 링크가 상대적인 경우 이 기본 URL에 상대적입니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [CreateDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/createdate) { get; set; } | 리소스가 생성된 날짜와 시간을 가져오거나 설정합니다. |
| [CreatorTool](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/creatortool) { get; set; } | 리소스를 만드는 데 사용되는 도구의 이름을 가져오거나 설정합니다. |
| [Identifiers](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/identifiers) { get; set; } | 지정된 컨텍스트 내에서 리소스를 명확하게 식별하는 정렬되지 않은 텍스트 문자열 배열을 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Label](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/label) { get; set; } | 리소스를 사용자 정의 컬렉션의 구성원으로 식별하는 단어나 짧은 구를 가져오거나 설정합니다. |
| [MetadataDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/metadatadate) { get; set; } | 이 리소스에 대한 메타데이터가 마지막으로 변경된 날짜와 시간을 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [ModifyDate](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/modifydate) { get; set; } | 리소스가 마지막으로 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 네임스페이스 URI를 가져옵니다. |
| [Nickname](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/nickname) { get; set; } | 리소스에 대한 짧은 비공식 이름을 가져오거나 설정합니다. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns 접두사를 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Rating](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/rating) { get; set; } | 이 파일에 대한 사용자 지정 등급을 가져오거나 설정합니다. 값은 -1 또는 [0..5] 범위에 있어야 합니다. 여기서 -1은 "거부됨"을 나타내고 0은 "등급 없음"을 나타냅니다. |
| [Thumbnails](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/thumbnails) { get; set; } | 크기나 이미지 인코딩과 같은 특성이 다를 수 있는 파일의 축소판 이미지 배열을 가져오거나 설정합니다. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | XML 네임스페이스를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | 모든 XMP 속성을 제거합니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | XMP 값을 XML 표현으로 변환합니다. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | 지정된 이름을 가진 속성을 제거합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | 부울 속성을 설정합니다. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | 세트DateTime 속성. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | 이중 속성을 설정합니다. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | 정수 속성을 설정합니다. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/set#set_7)(string, string) | 문자열 속성을 추가합니다. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | 에서 상속된 값을 설정합니다.[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | 에서 상속된 값을 설정합니다.[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | 에서 상속된 값을 설정합니다.[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [RatingMax](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmax) | 정격 최대값. |
| const [RatingMin](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingmin) | 등급 최소값. |
| const [RatingRejected](../../groupdocs.metadata.standards.xmp.schemes/xmpbasicpackage/ratingrejected) | 등급 거부 값. |

### 또한보십시오

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
