---
title: FileFormat
second_title: .NET API 참조용 GroupDocs.Metadata
description: 로드된 파일의 인식된 형식을 나타냅니다.
type: docs
weight: 40
url: /ko/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

로드된 파일의 인식된 형식을 나타냅니다.

```csharp
public enum FileFormat
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Unknown | `0` | 파일 형식이 인식되지 않습니다. |
| Presentation | `1` | 프리젠테이션 파일. Microsoft PowerPoint로 작업하려면 PPTX 및 PPT 확장 파일에 익숙해야 합니다. 슬라이드, 도형, 텍스트, 애니메이션, 비디오, 오디오 및 포함 개체. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/) . |
| Spreadsheet | `2` | 스프레드시트 파일입니다. 스프레드시트 파일에는 행과 열 형식의 데이터가 포함되어 있습니다. 이제 Windows 및 MacOS 운영 체제 모두에서 사용할 수 있는 Microsoft Excel과 같은 스프레드시트 소프트웨어 응용 프로그램을 사용하여 이러한 파일을 열고 보고 편집할 수 있습니다. 마찬가지로 Google 스프레드시트는 모든 웹 브라우저에서 작동하는 무료 온라인 스프레드시트 작성 및 편집 도구입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/) . |
| WordProcessing | `3` | 워드 프로세싱 파일입니다. 워드 프로세싱 파일에는 일반 텍스트 또는 리치 텍스트 형식의 사용자 정보가 들어 있습니다. 일반 텍스트 파일 형식 에는 서식이 지정되지 않은 텍스트가 포함되어 있으며 글꼴이나 페이지 설정 등을 적용할 수 없습니다. 반대로 서식 있는 텍스트 파일 형식은 글꼴 유형, 스타일(굵게, 기울임꼴, 밑줄 등) 설정과 같은 서식 옵션을 허용합니다. 페이지 여백, 제목, 글머리 기호 및 숫자, 기타 여러 서식 기능. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/) . |
| Diagram | `4` | 다이어그램 파일. |
| Note | `5` | 전자 메모 파일입니다. Microsoft OneNote와 같은 메모 작성 프로그램을 사용하면 메모를 저장하기 위한 섹션과 페이지가 포함된 메모 파일을 만들고 열고 편집할 수 있습니다. 메모 문서는 텍스트 문서만큼 간단할 뿐만 아니라 더 자세하게 디지털 이미지, 오디오/비디오 클립, 손으로 스케치한 그림으로 구성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/note-taking/) . |
| ProjectManagement | `6` | 프로젝트 관리 형식입니다. MPP 파일이 무엇인지 또는 파일을 여는 방법에 대해 궁금한 적이 있습니까? MPP 및 기타 유사한 파일은 Microsoft Project와 같은 프로젝트 관리 소프트웨어에서 생성되는 프로젝트 파일 형식입니다. 프로젝트 파일은 형태나 제품 또는 서비스에서 측정 가능한 출력을 얻기 위한 작업, 리소스 및 일정의 모음입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/project-management/) . |
| Pdf | `7` | PDF 파일. PDF(Portable Document Format)는 Adobe에서 1990년대에 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식인 문서 및 기타 참조 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/view/pdf/) . |
| Tiff | `8` | TIFF 이미지. TIFF 또는 TIF, Tagged Image File Format은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기 [여기](https://wiki.fileformat.com/image/tiff/) . |
| Jpeg | `9` | JPEG 이미지. JPEG는 손실 압축 방법을 사용하여 저장되는 이미지 형식 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg/) . |
| Psd | `10` | PSD 이미지. Photoshop 문서인 PSD는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop의 기본 파일 형식을 나타냅니다. PSD 파일에는 이미지 레이어, 조정 레이어, 레이어 마스크, 주석, 파일 정보, 키워드 및 기타 Photoshop 관련 요소가 포함될 수 있습니다. . 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/psd/) . |
| Jpeg2000 | `11` | Jpeg2000 이미지. JPEG 2000(JPX)은 이미지 코딩 시스템이자 최신 이미지 압축 표준입니다. 설계 웨이블릿 기술 사용 JPEG 2000은 한 번에 모든 품질의 무손실 콘텐츠를 코딩할 수 있습니다. about 이 파일 형식 자세히 알아보기[여기](https://wiki.fileformat.com/image/jp2/) . |
| Gif | `12` | GIF 이미지. GIF 또는 Graphical Interchange Format은 고도로 압축된 이미지 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/gif/) . |
| Png | `13` | PNG 이미지. PNG(Portable Network Graphics)는 무손실 압축을 사용하는 래스터 이미지 파일 형식 유형을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/png/) . |
| Bmp | `14` | BMP 이미지. 확장자가 .BMP인 파일은 비트맵 디지털 이미지를 저장하는 데 사용되는 비트맵 이미지 파일을 나타냅니다. 이러한 이미지는 그래픽 어댑터와 독립적이며 DIB(장치 독립적 비트맵) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/bmp/) . |
| Dicom | `15` | DICOM 이미지. DICOM은 Digital Imaging and Communications in Medicine의 약어이며 Medical Informatics 분야와 관련이 있습니다. DICOM은 파일 형식 정의와 네트워크 통신 프로토콜의 조합입니다. 이 파일 형식에 대해 자세히 알아보기[ 여기](https://wiki.fileformat.com/image/dicom/) . |
| WebP | `16` | WEBP 이미지. Google에서 소개한 WebP는 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 크기를 상당히 줄이면서 동일한 이미지 품질을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/webp/) . |
| Emf | `17` | EMF 이미지입니다. 향상된 메타파일 형식(EMF)은 장치 독립적으로 그래픽 이미지를 저장합니다. EMF의 메타파일은 모든 출력 장치에서 구문 분석한 후 저장된 이미지를 렌더링할 수 있는 시간순의 가변 길이 레코드로 구성됩니다. 이에 대해 자세히 알아보기 파일 형식[여기](https://wiki.fileformat.com/image/emf/) . |
| Wmf | `18` | WMF 이미지. WMF 확장자를 가진 파일은 벡터 및 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows 메타파일(WMF)을 나타냅니다. 독립. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/wmf/) . |
| DjVu | `19` | DjVu 파일. DjVu는 특히 텍스트, 그림, 이미지 및 사진의 조합을 포함하는 스캔 문서 및 책용 그래픽 파일 형식입니다. AT&amp;T 연구소에서 개발했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/djvu/) . |
| Wav | `20` | WAV 오디오 파일입니다. WAVE(Waveform Audio File Format)로 알려진 WAV는 디지털 오디오 파일을 저장하기 위한 Microsoft의 RIFF(Resource Interchange File Format) 사양의 하위 집합입니다. 이 형식은 비트스트림에 압축을 적용하지 않습니다. 다양한 샘플링 속도와 비트 전송률로 오디오 녹음을 저장합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/audio/wav/) . |
| Mp3 | `21` | Mp3 오디오 파일입니다. 확장자가 MP3인 파일은 MPEG-1 Audio Layer III 또는 MPEG-2 Audio Layer III를 기반으로 하는 오디오 파일용 디지털 인코딩 파일 형식입니다. 동영상 전문가 그룹( MPEG) 레이어 3 오디오 압축을 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/audio/mp3/) . |
| Avi | `22` | AVI 비디오. AVI 파일 형식은 Microsoft에서 도입한 오디오 비디오 멀티미디어 컨테이너 파일 형식입니다. Xvid 및 DivX와 같은 여러 코덱(코더/디코더)을 사용하여 생성되고 압축된 오디오 및 비디오 데이터를 보유합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/video/avi/) . |
| Flv | `23` | FLV 비디오. |
| Asf | `24` | ASF 비디오. ASF(Advanced Systems Format)는 주로 미디어 스트림을 저장하고 전송하기 위해 설계된 디지털 멀티미디어 컨테이너입니다. Microsoft Windows Media Video(WMV)는 압축된 비디오 형식이고 Microsoft Windows Media Audio(WMA)는 Microsoft에서 개발한 ASF 컨테이너의 추가 메타데이터와 함께 압축된 오디오 형식 . 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/video/wmv/) . |
| Mov | `25` | QuickTime 비디오. Mov 또는 QuickTime 파일 형식은 Apple에서 개발한 멀티미디어 컨테이너입니다. 하나 이상의 트랙을 포함하고 각 트랙은 비디오, 오디오, 텍스트 등과 같은 특정 유형의 데이터를 보유합니다. Mov 형식은 Windows 및 Macintosh 시스템. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/video/mov/) . |
| Matroska | `26` | Matroska 멀티미디어 컨테이너로 인코딩된 비디오. |
| Zip | `27` | ZIP 아카이브. ZIP 파일 확장자는 하나 이상의 파일 또는 디렉토리를 보유할 수 있는 아카이브를 나타냅니다. 아카이브는 ZIP 파일 크기를 줄이기 위해 포함된 파일에 압축을 적용할 수 있습니다. ZIP 파일 형식은 1989년 2월 Phil Katz가 파일 및 폴더 보관을 달성했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/zip/) . |
| VCard | `28` | VCard 파일. VCF(가상 카드 형식) 또는 vCard는 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. 이 형식은 널리 사용되는 정보 교환 응용 프로그램 간의 데이터 교환에 널리 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/vcf/) . |
| Epub | `29` | EPUB 전자책. 확장자가 .EPUB인 파일은 발행인과 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 지금까지 매우 보편화되어 많은 e-reader 및 소프트웨어 애플리케이션. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/ebook/epub/) . |
| OpenType | `30` | OpenType 글꼴입니다. |
| Dxf | `31` | DXF(Drawing Exchange Format) 도면. DXF, 도면 교환 형식 또는 도면 교환 형식은 AutoCAD 도면 파일의 태그가 지정된 데이터 표현입니다. 파일의 각 요소에는 그룹 코드라는 접두어 정수가 있습니다. 학습 이 파일 형식에 대한 추가 정보[여기](https://wiki.fileformat.com/cad/dxf/) . |
| Dwg | `32` | DWG 도면. DWG 확장자를 가진 파일은 2D 및 3D 설계 데이터를 포함하는 데 사용되는 전용 바이너리 파일을 나타냅니다. ASCII 파일인 DXF와 마찬가지로 DWG는 CAD(Computer Aided Design) 도면용 바이너리 파일 형식을 나타냅니다. 자세히 알아보기 이 파일 형식에 대해[여기](https://wiki.fileformat.com/cad/dwg/) . |
| Eml | `33` | EML 이메일 메시지. EML 파일 형식은 Outlook 및 기타 관련 응용 프로그램을 사용하여 저장된 이메일 메시지를 나타냅니다. 거의 모든 이메일 클라이언트는 RFC-822 인터넷 메시지 형식 표준을 준수하기 위해 이 파일 형식을 지원합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/eml/) . |
| Msg | `34` | MSG 전자 메일 메시지. MSG는 전자 메일 메시지, 연락처, 약속 또는 기타 작업을 저장하기 위해 Microsoft Outlook 및 Exchange에서 사용하는 파일 형식입니다. 이러한 메시지에는 보낸 사람, 받는 사람, 제목, date, 및 메시지 본문 또는 연락처 정보, 약속 세부 사항 및 하나 이상의 작업 사양. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/msg/) . |
| Torrent | `35` | 배포할 파일 및 폴더에 대한 메타데이터가 포함된 토렌트 파일. |
| Heif | `36` | HEIF/HEIC 이미지. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
