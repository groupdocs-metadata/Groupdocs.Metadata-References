---
title: XmpCameraRawPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: Camera Raw 스키마를 나타냅니다.
type: docs
weight: 3100
url: /ko/net/groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/
---
## XmpCameraRawPackage class

Camera Raw 스키마를 나타냅니다.

```csharp
public sealed class XmpCameraRawPackage : XmpPackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpCameraRawPackage](xmpcamerarawpackage)() | 의 새 인스턴스를 초기화합니다.[`XmpCameraRawPackage`](../xmpcamerarawpackage) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoBrightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autobrightness) { get; set; } | AutoBrightness 값을 가져오거나 설정합니다. 사실일 때,[`Brightness`](./brightness) 자동으로 조정됩니다. |
| [AutoContrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autocontrast) { get; set; } | AutoContrast 값을 가져오거나 설정합니다. true인 경우 "대비"가 자동으로 조정됩니다. |
| [AutoExposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoexposure) { get; set; } | AutoExposure 값을 가져오거나 설정합니다. true인 경우 "노출"이 자동으로 조정됩니다. |
| [AutoShadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/autoshadows) { get; set; } | AutoShadows 값을 가져오거나 설정합니다. 참이면 "그림자"가 자동으로 조정됩니다. |
| [BlueHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluehue) { get; set; } | BlueHue 값을 가져오거나 설정합니다. 정의되지 않은 경우 null입니다. |
| [BlueSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/bluesaturation) { get; set; } | BlueSaturation을 가져오거나 설정합니다. 정의되지 않은 경우 null입니다. |
| [Brightness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/brightness) { get; set; } | 밝기 값을 가져오거나 설정합니다. 정의되지 않은 경우 null입니다. |
| [CameraProfile](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cameraprofile) { get; set; } | CameraProfile 값을 가져오거나 설정합니다. |
| [ChromaticAberrationB](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationb) { get; set; } | "Chromatic Aberration, Fix Blue/Yellow Fringe" 설정을 가져오거나 설정합니다. 정의되지 않은 경우 null입니다. |
| [ChromaticAberrationR](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/chromaticaberrationr) { get; set; } | "Chromatic Aberration, Fix Red/Cyan Fringe" 설정을 가져오거나 설정합니다. 정의되지 않은 경우 null입니다. |
| [ColorNoiseReduction](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/colornoisereduction) { get; set; } | 색상 노이즈 감소 설정을 가져오거나 설정합니다. 범위 0 ~ 100. |
| [Contrast](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/contrast) { get; set; } | 대비 설정을 가져오거나 설정합니다. 범위 -50 ~ 100. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [CropAngle](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropangle) { get; set; } | CropAngle 설정을 가져오거나 설정합니다. HasCrop이 참일 때 자르기 직사각형의 각도. |
| [CropBottom](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropbottom) { get; set; } | CropBottom 설정을 가져오거나 설정합니다. HasCrop이 참이면 자르기 직사각형의 하단. |
| [CropHeight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropheight) { get; set; } | 결과 잘린 이미지의 높이를 가져오거나 설정합니다.[`CropUnits`](./cropunits) 단위. |
| [CropLeft](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropleft) { get; set; } | CropLeft 설정을 가져오거나 설정합니다. HasCrop이 참일 때 자르기 직사각형의 왼쪽. |
| [CropRight](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropright) { get; set; } | CropRight 설정을 가져오거나 설정합니다. HasCrop이 true인 경우 자르기 직사각형 오른쪽. |
| [CropTop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/croptop) { get; set; } | CropTop 설정을 가져오거나 설정합니다. HasCrop이 참이면 자르기 직사각형의 상단. |
| [CropUnits](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropunits) { get; set; } | 단위를 가져오거나 설정합니다.[`CropWidth`](./cropwidth) 그리고[`CropHeight`](./cropheight) . |
| [CropWidth](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/cropwidth) { get; set; } | 결과 잘린 이미지의 너비를 가져오거나 설정합니다.[`CropUnits`](./cropunits) 단위. |
| [Exposure](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/exposure) { get; set; } | 노출 설정을 가져오거나 설정합니다. |
| [GreenHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greenhue) { get; set; } | 녹색 색조 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [GreenSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/greensaturation) { get; set; } | 녹색 채도 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [HasCrop](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hascrop) { get; set; } | HasCrop 값을 가져오거나 설정합니다. true인 경우 이미지에 자르기 사각형이 있습니다. |
| [HasSettings](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/hassettings) { get; set; } | HasSettings 값을 가져오거나 설정합니다. true인 경우 기본이 아닌 Camera Raw 설정입니다. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | 가져오기[`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) 지정된 이름으로. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [LuminanceSmoothing](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/luminancesmoothing) { get; set; } | LuminanceSmoothing 설정을 가져오거나 설정합니다. 범위 0 ~ 100. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | 네임스페이스 URI를 가져옵니다. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | xmlns 접두사를 가져옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [RawFileName](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/rawfilename) { get; set; } | 원시 파일의 파일 이름을 가져오거나 설정합니다(완전한 경로 아님). |
| [RedHue](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redhue) { get; set; } | Red Hue 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [RedSaturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/redsaturation) { get; set; } | 빨간색 채도 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [Saturation](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/saturation) { get; set; } | 채도 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [Shadows](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadows) { get; set; } | 그림자 설정을 가져오거나 설정합니다. 범위 0 ~ 100. |
| [ShadowTint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/shadowtint) { get; set; } | ShadowTint 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [Sharpness](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/sharpness) { get; set; } | 선명도 설정을 가져오거나 설정합니다. 범위 0 ~ 100. |
| [Temperature](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/temperature) { get; set; } | 온도 설정을 가져오거나 설정합니다. 범위 2000 ~ 50000. |
| [Tint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/tint) { get; set; } | 색조 설정을 가져오거나 설정합니다. 범위 -150 ~ 150. |
| [Version](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/version) { get; set; } | Camera Raw 플러그인의 버전을 가져오거나 설정합니다. |
| [VignetteAmount](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignetteamount) { get; set; } | 비네트 양 설정을 가져오거나 설정합니다. 범위 -100 ~ 100. |
| [VignetteMidpoint](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/vignettemidpoint) { get; set; } | Vignetting Midpoint 설정을 가져오거나 설정합니다. 범위 0 ~ 100. |
| [WhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/whitebalance) { get; } | 화이트 밸런스 설정을 가져옵니다. 사용[`SetWhiteBalance`](./setwhitebalance) 화이트 밸런스 값을 설정합니다. |
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
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/set#set_7)(string, string) | 문자열 속성을 추가합니다. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpArray) | 에서 상속된 값을 설정합니다.[`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | 에서 상속된 값을 설정합니다.[`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | 에서 상속된 값을 설정합니다.[`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [SetWhiteBalance](../../groupdocs.metadata.standards.xmp.schemes/xmpcamerarawpackage/setwhitebalance)(XmpWhiteBalance) | 화이트 밸런스를 설정합니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 또한보십시오

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* 네임스페이스 [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
