---
title: ImageResourceID
second_title: .NET API 참조용 GroupDocs.Metadata
description: 이미지 리소스 표준 ID 번호. 모든 파일 형식이 모든 ID를 사용하는 것은 아닙니다. 일부 정보는 파일의 다른 섹션에 저장될 수 있습니다.
type: docs
weight: 1750
url: /ko/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

이미지 리소스 표준 ID 번호. 모든 파일 형식이 모든 ID를 사용하는 것은 아닙니다. 일부 정보는 파일의 다른 섹션에 저장될 수 있습니다.

```csharp
public enum ImageResourceID
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ResolutionInfo | `1005` | ResolutionInfo 구조. Photoshop API 가이드 PDF 문서의 부록 A를 참조하십시오. |
| NamesOfAlphaChannels | `1006` | 일련의 파스칼 문자열로 된 알파 채널의 이름입니다. |
| Caption | `1008` | 파스칼 문자열로 된 캡션. |
| BorderInformation | `1009` | 테두리 정보. 테두리 너비에 대한 고정 숫자(2바이트 실수, 2바이트 분수), 및 테두리 단위에 대한 2바이트(1 = 인치, 2 = cm, 3 = 포인트, 4 = 파이카, 5 = 열)를 포함합니다. |
| BackgroundColor | `1010` | 배경색. [더보기.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | 플래그를 인쇄합니다. 일련의 1바이트 부울 값(페이지 설정 대화 상자 참조): 레이블, 자르기 표시, 색상 막대, 등록 표시, 음수, 뒤집기, 보간, 캡션, 인쇄 플래그. |
| Grayscale | `1012` | 그레이스케일 및 다중 채널 하프톤 정보. |
| ColorHalftoning | `1013` | 색상 하프톤 정보. |
| DuotoneHalftoning | `1014` | 이중톤 하프톤 정보. |
| GrayscaleFunction | `1015` | 그레이스케일 및 다중 채널 전송 기능. |
| ColorTransferFunctions | `1016` | 색상 전송 기능. |
| DuotoneTransferFunctions | `1017` | 이중톤 전송 함수. |
| DuotoneImageInformation | `1018` | 이중톤 이미지 정보. |
| EPSOptions | `1021` | EPS 옵션. |
| QuickMaskInformation | `1022` | 빠른 마스크 정보. Quick Mask 채널 ID를 포함하는 2바이트; 마스크가 초기에 비어 있는지 여부를 나타내는 1바이트 부울. |
| LayerStateInformation | `1024` | 레이어 상태 정보. 대상 레이어의 인덱스를 포함하는 2바이트(0 = 맨 아래 레이어). |
| WorkingPath | `1025` | 작업 경로(저장되지 않음). 경로 리소스 형식 참조 참조. |
| LayersGroupInformation | `1026` | 레이어 그룹 정보. 드래그 그룹에 대한 그룹 ID를 포함하는 레이어당 2바이트. 그룹의 레이어는 동일한 그룹 ID를 가집니다. |
| Iptc | `1028` | IPTC-NAA 레코드. 파일 정보... 정보를 포함합니다. Documentation 폴더의 IPTC 폴더에 있는 설명서를 참조하십시오. |
| ImageModeForRawFormat | `1029` | 원시 형식 파일용 이미지 모드. |
| JpegQuality | `1030` | JPEG 품질. 비공개. |
| GridAndGuidesInfoPhotoshop4 | `1032` | 그리드 및 가이드 정보. |
| ThumbnailResourcePhotoshop4 | `1033` | Photoshop 4.0 전용 축소판 리소스. |
| CopyrightFlagPhotoshop4 | `1034` | 저작권 플래그. 이미지에 저작권이 있는지 여부를 나타내는 부울입니다. 속성 제품군을 통해 또는 파일 정보... 에서 사용자가 설정할 수 있습니다. |
| UrlPhotoshop4 | `1035` | URL. 균일한 리소스 로케이터가 있는 텍스트 문자열의 핸들입니다. 속성 제품군을 통해 또는 파일 정보... 에서 사용자가 설정할 수 있습니다. |
| ThumbnailResourcePhotoshop5 | `1036` | 썸네일 리소스(리소스 1033을 대체함). 썸네일 리소스 형식 참조 참조. |
| GlobalAnglePhotoshop5 | `1037` | 전역 각도. 효과 레이어의 전역 조명 각도인 0에서 359 사이의 정수를 포함하는 4바이트. 존재하지 않는 경우 30. 로 간주됩니다. |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC 프로파일. ICC(International Color Consortium) 형식 프로필의 원시 바이트입니다. Documentation 폴더의 ICC1v42_2006-05.pdf 및 Sample Code\Common\Includes. 의 icProfileHeader.h를 참조하십시오. |
| WatermarkPhotoshop5 | `1040` | 워터마크. 1바이트. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC 태그가 지정되지 않은 프로필. 파일을 열 때 가정된 프로필 처리를 비활성화하는 1바이트. 1 = 의도적으로 태그를 지정하지 않았습니다. |
| TransparencyIndexPhotoshop6 | `1047` | 투명도 지수. 있는 경우 투명 색상 인덱스용 2바이트. |
| GlobalAltitudePhotoshop6 | `1049` | 글로벌 고도. 고도를 위한 4바이트 항목. |
| SlicesPhotoshop6 | `1050` | 슬라이스(Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | 워크플로우 URL. 유니코드 문자열. 포토샵 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | 알파 식별자. 길이 4바이트, 모든 알파 식별자에 대해 각각 4바이트. |
| UrlListPhotoshop6 | `1054` | URL 내부 목록. URL의 4바이트 수, 4바이트 길이, 4바이트 ID 및 각 수에 대한 유니코드 문자열이 뒤따릅니다. |
| VersionInfoPhotoshop6 | `1057` | 버전 정보. 4바이트 버전, 1바이트 hasRealMergedData , 유니코드 문자열: 작성자 이름, 유니코드 문자열: 리더 이름, 4바이트 파일 버전. |
| ExifData1Photoshop7 | `1058` | EXIF 데이터 1,[더보기](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ EXIF 데이터 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP 메타데이터. 파일 정보를 XML 설명으로,[더보기](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | 캡션 다이제스트. 16바이트: RSA 데이터 보안, MD5 메시지 다이제스트 알고리즘. |
| PrintScalePhotoshop7 | `1062` | 인쇄 배율. 2바이트 스타일(0 = 중앙 맞춤, 1 = 맞춤 크기, 2 = 사용자 정의). 4바이트 x 위치(부동 소수점). 4바이트 y 위치(부동 소수점). 4바이트 스케일(부동 소수점). |
| PixelAspectRatio | `1064` | 픽셀 종횡비. 4바이트(버전 = 1 또는 2), 8바이트 더블, 픽셀의 x/y. 버전 2, NTSC 및 PAL에 대한 값을 수정하려고 합니다. 5%. |
| LayerComps | `1065` | 레이어 구성 요소. 4바이트(설명자 버전 = 16), 설명자. |
| LayerSelectionIds | `1069` | 레이어 선택 ID. 2바이트 카운트, 다음은 각 카운트에 대해 반복됩니다: 4바이트 레이어 ID. |
| PrintInfoCS2 | `1071` | 인쇄 정보(Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | 레이어 그룹 활성화 ID. 문서의 각 레이어에 대해 1바이트, 리소스 길이만큼 반복됩니다. 참고: 레이어 그룹에는 시작 및 끝 마커가 있습니다(Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | 색상 샘플러 자원. 이전 형식에 대해서는 ID 1038도 참조하십시오. |
| MeasurementScaleCS3 | `1074` | 측정 척도. 4바이트(설명자 버전 = 16), 설명자. |
| TimelineInformationCS3 | `1075` | 타임라인 정보. 4바이트(설명자 버전 = 16), 설명자. |
| SheetDisclosureCS3 | `1076` | 시트 공개. 4바이트(설명자 버전 = 16), 설명자. |
| PrintInformationCS5 | `1082` | 인쇄 정보(Photoshop CS5). |
| PrintStyleCS5 | `1083` | 인쇄 스타일(Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | 매킨토시 NSPrintInfo. Macintosh용 가변 OS 특정 정보. NSPrintInfo. 이 데이터를 해석하거나 사용하지 않는 것이 좋습니다. (포토샵 CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Windows용 가변 OS 특정 정보. DEVMODE. 이 데이터를 해석하거나 사용하지 않는 것이 좋습니다. (포토샵 CS5). |
| AutoSaveFilePathCS6 | `1086` | 자동 저장 파일 경로. 유니코드 문자열. (포토샵 CS6). |
| AutoSaveFormatCS6 | `1087` | 자동 저장 형식. 유니코드 문자열. (포토샵 CS6). |
| PathSelectionStateCC | `1088` | 경로 선택 상태. (포토샵 CC). |
| ImageReadyVariables | `7000` | 이미지 준비 변수. 변수 정의의 XML 표현. |
| ImageReadyDatasets | `7001` | 이미지 준비 데이터 세트. |
| PrintFlagsInformation | `10000` | 플래그 정보를 인쇄합니다. 2바이트 버전( = 1), 1바이트 중앙 자르기 표시, 1바이트( = 0), 4바이트 블리드 너비 값, 2바이트 블리드 너비 스케일. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
