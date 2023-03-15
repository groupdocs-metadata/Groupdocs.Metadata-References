---
title: XmpDublinCorePackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: 더블린 코어 체계를 나타냅니다.
type: docs
weight: 3120
url: /ko/net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

더블린 코어 체계를 나타냅니다.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | 의 새 인스턴스를 초기화합니다.[`XmpDublinCorePackage`](../xmpdublincorepackage) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | 기여자의 배열을 가져오거나 설정합니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | 리소스의 범위 또는 범위를 가져오거나 설정합니다. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | 생성자의 배열을 가져오거나 설정합니다. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | 리소스 수명 주기의 이벤트와 관련된 날짜 배열을 가져오거나 설정합니다. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | 다양한 언어로 제공되는 리소스 내용의 텍스트 설명 배열을 가져오거나 설정합니다. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | 리소스의 MIME 유형을 가져오거나 설정합니다. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | 지정된 컨텍스트 내에서 리소스에 대한 명확한 참조를 나타내는 문자열 값을 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | 리소스 내용에 사용된 언어 배열을 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 네임스페이스 URI를 가져옵니다. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns 접두사를 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | 리소스를 사용할 수 있도록 만든 게시자 배열을 가져오거나 설정합니다. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | 관련 리소스의 배열을 가져오거나 설정합니다. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | 다양한 언어로 제공된 비공식적 권리 진술의 배열을 가져오거나 설정합니다. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | 설명된 리소스가 파생된 관련 리소스를 가져오거나 설정합니다. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | 리소스의 내용을 지정하는 설명 문구 또는 키워드의 배열을 가져오거나 설정합니다. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | 다양한 언어로 제공되는 리소스의 제목 또는 이름을 가져오거나 설정합니다. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | 리소스의 특성 또는 장르를 나타내는 문자열 값의 배열을 가져오거나 설정합니다. |
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
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | 문자열 속성을 설정합니다. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | 에서 상속된 값을 설정합니다.[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | 에서 상속된 값을 설정합니다.[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | 에서 상속된 값을 설정합니다.[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | 리소스의 단일 기여자를 설정합니다. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | 리소스의 단일 생성자를 설정합니다. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | 리소스와 관련된 단일 날짜를 설정합니다. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | 단일 언어로 주어진 리소스 설명을 설정합니다. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | 리소스와 관련된 단일 언어를 설정합니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | 리소스의 단일 게시자를 설정합니다. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | 단일 관련 리소스를 설정합니다. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | 단일 언어로 주어진 리소스 권한을 설정합니다. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | 리소스의 단일 주제를 설정합니다. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | 단일 언어로 주어진 리소스 제목을 설정합니다. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | 리소스의 단일 유형을 설정합니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

자세한 내용은 다음을 참조하십시오. http://dublincore.org/documents/usageguide/elements.shtml.

### 또한보십시오

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
