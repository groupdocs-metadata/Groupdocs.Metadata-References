---
title: XmpRenditionClass
second_title: .NET API 참조용 GroupDocs.Metadata
description: 는 XMP RenditionClass를 나타냅니다.
type: docs
weight: 3530
url: /ko/net/groupdocs.metadata.standards.xmp/xmprenditionclass/
---
## XmpRenditionClass class

는 XMP RenditionClass를 나타냅니다.

```csharp
public sealed class XmpRenditionClass : XmpText
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpRenditionClass](xmprenditionclass)(params string[]) | 의 새 인스턴스를 초기화합니다.[`XmpRenditionClass`](../xmprenditionclass) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [RawValue](../../groupdocs.metadata.common/propertyvalue/rawvalue) { get; } | 원시 값을 가져옵니다. |
| [Type](../../groupdocs.metadata.common/propertyvalue/type) { get; } | 가져오기[`MetadataPropertyType`](../../groupdocs.metadata.common/metadatapropertytype) . |
| [Value](../../groupdocs.metadata.standards.xmp/xmptext/value) { get; } | 값을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AcceptValue](../../groupdocs.metadata.common/propertyvalue/acceptvalue)(ValueAcceptor) | 사용자 지정을 사용하여 속성 값을 추출합니다.[`ValueAcceptor`](../../groupdocs.metadata.common/valueacceptor) . |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmptext/getxmprepresentation)() | XMP 형식의 값이 포함된 문자열을 반환합니다. |
| [ToArray&lt;TElement&gt;](../../groupdocs.metadata.common/propertyvalue/toarray)() | 속성 값을 지정된 유형의 배열로 변환합니다. |
| [ToClass&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/toclass)() | 속성 값을 참조 유형으로 변환합니다. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpvaluebase/tostring)() | 속성 값을 나타내는 문자열을 반환합니다. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)() | 속성 값을 값 유형으로 변환합니다. |
| [ToStruct&lt;T&gt;](../../groupdocs.metadata.common/propertyvalue/tostruct)(T) | 속성 값을 값 유형으로 변환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [Default](../../groupdocs.metadata.standards.xmp/xmprenditionclass/default) | 마스터 리소스입니다. 추가 토큰은 허용되지 않습니다. |
| const [Draft](../../groupdocs.metadata.standards.xmp/xmprenditionclass/draft) | 리뷰 번역. |
| const [LowRes](../../groupdocs.metadata.standards.xmp/xmprenditionclass/lowres) | 저해상도 풀 사이즈 stand-in. |
| const [Proof](../../groupdocs.metadata.standards.xmp/xmprenditionclass/proof) | 검토 증거. |
| const [Screen](../../groupdocs.metadata.standards.xmp/xmprenditionclass/screen) | 화면 해상도 또는 웹 표현. |
| const [Thumbnail](../../groupdocs.metadata.standards.xmp/xmprenditionclass/thumbnail) | 단순화되거나 축소된 미리보기. 추가 토큰은 특성을 제공할 수 있습니다. 권장 순서는 thumbnail:format:size:colorspace. 입니다. |

### 또한보십시오

* class [XmpText](../xmptext)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
