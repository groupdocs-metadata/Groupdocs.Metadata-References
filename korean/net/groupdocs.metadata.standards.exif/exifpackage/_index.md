---
title: ExifPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: EXIF 메타데이터 패키지Exchangeable Image File Format를 나타냅니다.
type: docs
weight: 2790
url: /ko/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

EXIF 메타데이터 패키지(Exchangeable Image File Format)를 나타냅니다.

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ExifPackage](exifpackage)() | 의 새 인스턴스를 초기화합니다.[`ExifPackage`](../exifpackage) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | 카메라 소유자, 사진가 또는 이미지 작성자의 이름을 가져오거나 설정합니다. |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | 저작권 표시를 가져오거나 설정합니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | 이미지 생성 날짜 및 시간을 가져오거나 설정합니다. EXIF 표준에서는 파일이 변경된 날짜 및 시간입니다. |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | EXIF IFD 데이터를 가져옵니다. |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | GPS 데이터를 가져옵니다. |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | 이미지의 제목을 나타내는 문자열을 가져오거나 설정합니다. "1988 회사 소풍"과 같은 주석일 수 있습니다. |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | 이미지 데이터의 행 수를 가져오거나 설정합니다. |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | 행당 픽셀 수와 같은 이미지 데이터의 열 수를 가져오거나 설정합니다. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 지정된 id를 가진 TIFF 태그를 가져옵니다. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | 기록 장비의 제조업체를 가져오거나 설정합니다. 이미지를 생성한 DSC, 스캐너, 비디오 디지타이저 또는 기타 장비의 제조업체입니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | 장비의 모델명이나 모델 번호를 가져오거나 설정합니다. 이미지를 생성한 DSC, 스캐너, 비디오 디지타이저 또는 기타 장비의 모델명 또는 번호입니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | 이미지를 생성하는 데 사용되는 카메라 또는 이미지 입력 장치의 소프트웨어 또는 펌웨어의 이름과 버전을 가져오거나 설정합니다. |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | 바이트 배열로 표시된 이미지 축소판을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 조건자를 만족하는 알려진 메타데이터 속성을 추가합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | 패키지에 저장된 모든 TIFF 태그를 제거합니다. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | 패키지에 지정된 이름의 메타데이터 속성이 포함되어 있는지 확인합니다. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 찾습니다. 검색은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | 지정된 id를 가진 속성을 제거합니다. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | 지정된 조건자를 만족하는 메타데이터 속성을 제거합니다. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | 패키지에서 쓰기 가능한 메타데이터 속성을 제거합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | 지정된 태그를 추가하거나 바꿉니다. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 설정합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. 이 방법은[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) 그리고[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) 기존 속성이 술어를 충족하면 해당 값이 업데이트됩니다. 조건자를 충족하는 패키지에 알려진 속성이 누락된 경우 패키지에 추가됩니다. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | 패키지에서 목록을 만듭니다. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | 지정된 술어를 만족하는 알려진 메타데이터 속성을 업데이트합니다. 이 작업은 재귀적이므로 중첩된 모든 패키지에도 영향을 미칩니다. |

### 비고

**더 알아보기**

* [EXIF 메타데이터 작업](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### 예

이 코드 샘플은 일반적인 EXIF 속성을 업데이트하는 방법을 보여줍니다.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // 없는 경우 EXIF 패키지를 설정합니다.
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### 또한보십시오

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* 네임스페이스 [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
