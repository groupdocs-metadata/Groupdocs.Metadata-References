---
title: XmpRightsManagementPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: XMP 권한 관리 네임스페이스를 나타냅니다.
type: docs
weight: 3220
url: /ko/net/groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/
---
## XmpRightsManagementPackage class

XMP 권한 관리 네임스페이스를 나타냅니다.

```csharp
public sealed class XmpRightsManagementPackage : XmpPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpRightsManagementPackage](xmprightsmanagementpackage)() | 의 새 인스턴스를 초기화합니다.[`XmpRightsManagementPackage`](../xmprightsmanagementpackage) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Certificate](../../groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/certificate) { get; set; } | 권한 관리 인증서의 웹 URL을 가져오거나 설정합니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Marked](../../groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/marked) { get; set; } | 권한 관리 리소스인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 네임스페이스 URI를 가져옵니다. |
| [Owners](../../groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/owners) { get; set; } | 법적 소유자를 가져오거나 설정합니다. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns 접두사를 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [UsageTerms](../../groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/usageterms) { get; set; } | 리소스를 합법적으로 사용할 수 있는 방법에 대한 지침을 다양한 언어로 가져오거나 설정합니다. |
| [WebStatement](../../groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/webstatement) { get; set; } | 이 리소스에 대한 소유권 및 사용 권한에 대한 설명의 웹 URL을 가져오거나 설정합니다. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmprightsmanagementpackage/set#set_7)(string, string) | 문자열 속성을 설정합니다. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | 에서 상속된 값을 설정합니다.[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | 에서 상속된 값을 설정합니다.[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | 에서 상속된 값을 설정합니다.[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 또한보십시오

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
