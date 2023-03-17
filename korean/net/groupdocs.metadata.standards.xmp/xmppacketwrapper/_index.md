---
title: XmpPacketWrapper
second_title: .NET API 참조용 GroupDocs.Metadata
description: 헤더와 트레일러를 포함하여 직렬화된 XMP 패키지를 포함합니다. 한 쌍의 XML 처리 명령PI으로 구성된 래퍼는 rdfRDF 요소 주위에 배치될 수 있습니다.
type: docs
weight: 3500
url: /ko/net/groupdocs.metadata.standards.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

헤더와 트레일러를 포함하여 직렬화된 XMP 패키지를 포함합니다. 한 쌍의 XML 처리 명령(PI)으로 구성된 래퍼는 rdf:RDF 요소 주위에 배치될 수 있습니다.

```csharp
public class XmpPacketWrapper : MetadataPackage, IXmpType
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | 의 새 인스턴스를 초기화합니다.[`XmpPacketWrapper`](../xmppacketwrapper) 클래스. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPI, XmpTrailerPI, XmpMeta) | 의 새 인스턴스를 초기화합니다.[`XmpPacketWrapper`](../xmppacketwrapper) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [HeaderPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/headerpi) { get; set; } | 헤더 처리 명령을 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Meta](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/meta) { get; set; } | XMP 메타를 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [PackageCount](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packagecount) { get; } | XMP 구조 내부의 패키지 수를 가져옵니다. |
| [Packages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/packages) { get; } | 배열 가져오기[`XmpPackage`](../xmppackage) 내부 XMP. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Schemes](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/schemes) { get; } | 알려진 XMP 스키마에 대한 액세스를 제공합니다. |
| [TrailerPI](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/trailerpi) { get; set; } | 트레일러 처리 명령을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/addpackage)(XmpPackage) | 패키지를 추가합니다. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [ClearPackages](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/clearpackages)() | 모두 제거[`XmpPackage`](../xmppackage) 내부 XMP. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| [ContainsPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/containspackage)(string) | 패키지가 XMP 래퍼에 있는지 여부를 결정합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [GetPackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getpackage)(string) | 네임스페이스 uri로 패키지를 가져옵니다. |
| [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/getxmprepresentation)() | XMP 형식의 값이 포함된 문자열을 반환합니다. |
| [RemovePackage](../../groupdocs.metadata.standards.xmp/xmppacketwrapper/removepackage)(XmpPackage) | 지정된 패키지를 제거합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [XMP 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+XMP+metadata)

### 예

이 예는 XMP 메타데이터 속성을 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.GifWithXmp))
{
    IXmp root = metadata.GetRootPackage() as IXmp;
    if (root != null && root.XmpPackage != null)
    {
        // XMP 패키지에 그러한 스키마가 없으면 생성해야 합니다.
        if (root.XmpPackage.Schemes.DublinCore == null)
        {
            root.XmpPackage.Schemes.DublinCore = new XmpDublinCorePackage();
        }
        root.XmpPackage.Schemes.DublinCore.Format = "image/gif";
        root.XmpPackage.Schemes.DublinCore.SetRights("Copyright (C) 2011-2022 GroupDocs. All Rights Reserved");
        root.XmpPackage.Schemes.DublinCore.SetSubject("test");

        if (root.XmpPackage.Schemes.CameraRaw == null)
        {
            root.XmpPackage.Schemes.CameraRaw = new XmpCameraRawPackage();
        }
        root.XmpPackage.Schemes.CameraRaw.Shadows = 50;
        root.XmpPackage.Schemes.CameraRaw.AutoBrightness = true;
        root.XmpPackage.Schemes.CameraRaw.AutoExposure = true;
        root.XmpPackage.Schemes.CameraRaw.CameraProfile = "test";
        root.XmpPackage.Schemes.CameraRaw.Exposure = 0.0001;

        // 이전 값을 유지하지 않으려면 전체 구성표를 바꾸십시오.
        root.XmpPackage.Schemes.XmpBasic = new XmpBasicPackage();
        root.XmpPackage.Schemes.XmpBasic.CreateDate = DateTime.Today;
        root.XmpPackage.Schemes.XmpBasic.BaseUrl = "https://groupdocs.com";
        root.XmpPackage.Schemes.XmpBasic.Rating = 5;

        root.XmpPackage.Schemes.BasicJobTicket = new XmpBasicJobTicketPackage();

        // 복합 유형 속성 설정
        root.XmpPackage.Schemes.BasicJobTicket.Jobs = new[]
        {
            new XmpJob
            {
                ID = "1",
                Name = "test job",
                Url = "https://groupdocs.com"
            },
        };

        // ... 

        metadata.Save(Constants.OutputGif);
    }
}
```

### 또한보십시오

* class [MetadataPackage](../../groupdocs.metadata.common/metadatapackage)
* interface [IXmpType](../ixmptype)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
