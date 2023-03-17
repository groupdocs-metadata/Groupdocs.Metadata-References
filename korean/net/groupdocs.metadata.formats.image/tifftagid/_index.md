---
title: TiffTagID
second_title: .NET API 참조용 GroupDocs.Metadata
description: TIFF 태그의 ID를 정의합니다.
type: docs
weight: 2100
url: /ko/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

TIFF 태그의 ID를 정의합니다.

```csharp
public enum TiffTagID : ushort
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| GpsVersionID | `0` | GPSInfoIFD의 버전을 나타냅니다. |
| GpsLatitudeRef | `1` | 위도가 북위인지 남위인지 나타냅니다. |
| GpsLatitude | `2` | 위도를 나타냅니다. |
| GpsLongitudeRef | `3` | 경도가 동경인지 서경인지를 나타냅니다. |
| GpsLongitude | `4` | 경도를 나타냅니다. |
| GpsAltitudeRef | `5` | 기준 고도로 사용되는 고도를 나타냅니다. |
| GpsAltitude | `6` | GPSAltitudeRef. 의 참조를 기반으로 고도를 나타냅니다. |
| GpsTimeStamp | `7` | 시간을 UTC(Coordinated Universal Time)로 나타냅니다. |
| GpsSatellites | `8` | 는 측정에 사용되는 GPS 위성을 나타냅니다. |
| GpsStatus | `9` | 이미지가 기록될 때 GPS 수신기의 상태를 나타냅니다. |
| GpsMeasureMode | `10` | GPS 측정 모드를 나타냅니다. |
| GpsDop | `11` | GPS DOP(데이터 정밀도)를 나타냅니다. |
| GpsSpeedRef | `12` | 이동 의 GPS 수신기 속도를 표현하는 데 사용되는 단위를 나타냅니다. |
| GpsSpeed | `13` | GPS 수신기 이동 속도를 나타냅니다. |
| GpsTrackRef | `14` | GPS 수신기 이동 방향을 알려주는 기준을 나타냅니다. |
| GpsTrack | `15` | GPS 수신기 이동 방향을 나타냅니다. |
| GpsImgDirectionRef | `16` | 이미지를 촬영할 때 이미지의 방향을 알려주는 기준을 나타냅니다. |
| GpsImgDirection | `17` | 이미지가 캡처되었을 때의 방향을 나타냅니다. |
| GpsMapDatum | `18` | GPS 수신기에서 사용하는 측지 측량 데이터를 나타냅니다. |
| GpsDestLatitudeRef | `19` | 목적지의 위도가 북위인지 남위인지를 나타냅니다. |
| GpsDestLatitude | `20` | 목적지 지점의 위도를 나타냅니다. |
| GpsDestLongitudeRef | `21` | 목적지 지점의 경도가 동경인지 서경인지를 나타냅니다. |
| GpsDestLongitude | `22` | 목적지 지점의 경도를 나타냅니다. |
| GpsDestBearingRef | `23` | 목적지 지점에 방위를 부여하는 데 사용되는 참조를 나타냅니다. |
| GpsDestBearing | `24` | 목적지까지의 방위를 나타냅니다. |
| GpsDestDistanceRef | `25` | 목적지까지의 거리를 나타내는 단위를 나타냅니다. |
| GpsDestDistance | `26` | 목적지까지의 거리를 나타냅니다. |
| GpsProcessingMethod | `27` | 위치 찾기 방법의 이름을 기록한 문자열. |
| GpsAreaInformation | `28` | GPS 영역의 이름을 기록한 문자열. |
| GpsDateStamp | `29` | UTC(Coordinated Universal Time)를 기준으로 날짜 및 시간 정보를 기록한 문자열. |
| GpsDifferential | `30` | GPS 수신기에 차분 보정 적용 여부를 나타냅니다. |
| GpsHPositioningError | `31` | 이 태그는 수평 위치 오류를 미터 단위로 나타냅니다. |
| NewSubfileType | `254` | 이 하위 파일에 포함된 데이터 종류의 일반적인 표시입니다. |
| SubfileType | `255` | 이 서브파일에 포함된 데이터 종류의 일반적인 표시. 이 필드는 더 이상 사용되지 않습니다. 대신 NewSubfileType 필드를 사용해야 합니다 |
| ImageWidth | `256` | 이미지의 열 수, 즉 스캔 라인당 픽셀 수입니다. |
| ImageLength | `257` | 이미지의 행 수(주사선이라고도 함)입니다. |
| BitsPerSample | `258` | 구성 요소당 비트 수. |
| Compression | `259` | 이미지 데이터에 사용된 압축 방식입니다. |
| PhotometricInterpretation | `262` | 이미지 데이터의 색 공간입니다. |
| Threshholding | `263` | 회색 음영을 나타내는 흑백 TIFF 파일의 경우 회색에서 흑백 픽셀로 변환하는 데 사용되는 기술입니다. |
| CellWidth | `264` | 디더링 또는 하프톤 이중 레벨 파일을 만드는 데 사용되는 디더링 또는 하프톤 매트릭스의 폭입니다. |
| CellLength | `265` | 디더링 또는 하프톤 이중 레벨 파일을 만드는 데 사용되는 디더링 또는 하프톤 매트릭스의 길이입니다. |
| FillOrder | `266` | 바이트 내 비트의 논리적 순서. |
| DocumentName | `269` | 이 이미지가 스캔된 문서의 이름입니다. |
| ImageDescription | `270` | 이미지의 주제를 설명하는 문자열입니다. |
| Make | `271` | 스캐너 제조업체입니다. |
| Model | `272` | 스캐너 모델 이름 또는 번호. |
| StripOffsets | `273` | 각 스트립에 대해 해당 스트립의 바이트 오프셋. |
| Orientation | `274` | 행과 열에 대한 이미지의 방향입니다. |
| SamplesPerPixel | `277` | 픽셀당 구성 요소 수입니다. |
| RowsPerStrip | `278` | 스트립당 행 수입니다. |
| StripByteCounts | `279` | 각 스트립에 대해 압축 후 스트립의 바이트 수입니다. |
| MinSampleValue | `280` | 사용된 최소 구성 요소 값입니다. |
| MaxSampleValue | `281` | 사용된 최대 구성 요소 값입니다. |
| XResolution | `282` | ImageWidth 방향에서 ResolutionUnit당 픽셀 수입니다. |
| YResolution | `283` | ImageLength 방향에서 ResolutionUnit당 픽셀 수입니다. |
| PlanarConfiguration | `284` | 각 픽셀의 구성요소가 저장되는 방식. |
| PageName | `285` | 이 이미지가 스캔된 페이지의 이름입니다. |
| XPosition | `286` | 이미지의 X 위치. |
| YPosition | `287` | 이미지의 Y 위치. |
| FreeOffsets | `288` | TIFF 파일에서 사용되지 않은 연속 바이트의 각 문자열에 대해 문자열의 바이트 오프셋입니다. |
| FreeByteCounts | `289` | TIFF 파일에서 사용되지 않은 연속 바이트의 각 문자열에 대해 문자열의 바이트 수입니다. |
| GrayResponseUnit | `290` | GrayResponseCurve. 에 포함된 정보의 정밀도 |
| GrayResponseCurve | `291` | 그레이스케일 데이터의 경우 가능한 각 픽셀 값의 광학 밀도입니다. |
| T4Options | `292` | T4 인코딩 옵션. |
| T6Options | `293` | T6 인코딩 옵션. |
| ResolutionUnit | `296` | XResolution 및 YResolution의 측정 단위입니다. |
| PageNumber | `297` | 이 이미지가 스캔된 페이지의 페이지 번호입니다. |
| TransferFunction | `301` | 표 형식의 이미지에 대한 전달 함수를 설명합니다. 픽셀 구성 요소 can 감마 보정, 압축, 비균일 양자화 또는 some 다른 방식으로 코딩할 수 있습니다. TransferFunction은 non-linear BitsPerSample(예: 8비트) 형식의 픽셀 구성 요소를 감지할 수 있는 정확도 손실 없이 16비트 선형 형식으로 매핑합니다. |
| Software | `305` | 이미지 생성에 사용된 소프트웨어 패키지의 이름 및 버전 번호. |
| DateTime | `306` | 이미지 생성 날짜 및 시간. |
| Artist | `315` | 이미지를 만든 사람입니다. |
| HostComputer | `316` | 이미지 생성 시 사용 중인 컴퓨터 및/또는 운영 체제입니다. |
| Predictor | `317` | 이 섹션은 일부 이미지의 압축률을 크게 향상시키는 예측자를 정의합니다. |
| WhitePoint | `318` | 이미지의 흰색 점의 색도입니다. |
| PrimaryChromaticities | `319` | 이미지 원색의 색도. |
| ColorMap | `320` | 팔레트 컬러 이미지용 컬러 맵. |
| HalftoneHints | `321` | HalftoneHints 필드의 목적은 색조 세부 사항을 유지해야 하는 비색 지정 이미지 내에서 그레이 레벨 범위를 하프톤 함수에 전달하는 것입니다. |
| TileWidth | `322` | 타일 너비(픽셀)입니다. 이것은 각 타일의 열 수입니다. |
| TileLength | `323` | 타일 길이(높이)(픽셀 단위). 이것은 각 타일의 행 수입니다. |
| TileOffsets | `324` | 각 타일에 대해 디스크에 압축 및 저장된 타일의 바이트 오프셋입니다. 오프셋은 TIFF 파일의 시작과 관련하여 지정됩니다. 이것은 각 타일이 다른 타일의 위치와 독립적인 위치를 가짐을 의미합니다. |
| TileByteCounts | `325` | 각 타일에 대해 해당 타일의 (압축된) 바이트 수입니다. |
| InkSet | `332` | 분리된(PhotometricInterpretation=5) 이미지에 사용된 잉크 세트입니다. |
| InkNames | `333` | 분리된(PhotometricInterpretation=5) 이미지에 사용된 각 잉크의 이름, 는 연결된 NUL 종료 ASCII 문자열 목록으로 작성됩니다. |
| NumberOfInks | `334` | 잉크 수. 추가 샘플이 없는 한 일반적으로 SamplesPerPixel과 같습니다. |
| DotRange | `336` | 0% 도트와 100% 도트에 해당하는 구성 요소 값입니다. DotRange[0] 는 0% 도트에 해당하고 DotRange[1]은 100% 도트에 해당합니다. |
| ExtraSamples | `338` | 추가 구성 요소에 대한 설명. |
| SampleFormat | `339` | 이 필드는 픽셀의 각 데이터 샘플을 해석하는 방법을 지정합니다. |
| SMinSampleValue | `340` | 이 필드는 최소 샘플 값을 지정합니다. |
| SMaxSampleValue | `341` | 이 새 필드는 최대 샘플 값을 지정합니다. |
| TransferRange | `342` | TransferFunction의 범위를 확장합니다. |
| JpegProc | `512` | 이 필드는 압축 데이터를 생성하는 데 사용되는 JPEG 프로세스를 나타냅니다. |
| JpegInterchangeFormat | `513` | 이 필드는 TIFF 파일에 JPEG 교환 형식 비트스트림이 있는지 여부를 나타냅니다. |
| JpegInterchangeFormatLength | `514` | 이 필드는 JPEG 교환 형식 bitstream 의 바이트 길이를 나타냅니다. |
| JpegRestartInterval | `515` | 이 필드는 압축된 이미지 데이터에 사용되는 재시작 간격의 길이를 나타냅니다. |
| JpegLosslessPredictors | `517` | 이 필드는 구성 요소당 하나의 무손실 예측자 선택 값 목록을 가리킵니다. |
| JpegPointTransforms | `518` | 이 필드는 구성 요소당 하나씩 포인트 변환 값 목록을 가리킵니다. |
| JpegQTables | `519` | 이 필드는 구성 요소당 하나씩 양자화 테이블에 대한 오프셋 목록을 가리킵니다. |
| JpegDCTables | `520` | 이 필드는 구성 요소당 하나씩 DC Huffman 테이블 또는 lossless Huffman 테이블에 대한 오프셋 목록을 가리킵니다. |
| JpegACTables | `521` | 이 필드는 구성 요소당 하나씩 Huffman AC 테이블에 대한 오프셋 목록을 가리킵니다. |
| YCbCrCoefficients | `529` | RGB에서 YCbCr 이미지 데이터로 변환하기 위한 매트릭스 계수. |
| YCbCrSubSampling | `530` | 휘도 성분에 대한 색차 성분의 샘플링 비율. |
| YCbCrPositioning | `531` | 휘도 샘플을 기준으로 서브샘플링된 색차 구성 요소의 위치를 지정합니다. |
| ReferenceBlackWhite | `532` | 각 픽셀 구성 요소에 대한 헤드룸 및 풋룸 이미지 데이터 값(코드) 쌍을 지정합니다. |
| Copyright | `33432` | 저작권 고지. |
| UserComment | `37510` | 이미지에 대한 키워드 또는 설명; ImageDescription. 를 보완합니다. |
| Xmp | `700` | XMP 메타데이터에 대한 포인터입니다. |
| ImageID | `32781` | OPI 관련. |
| Iptc | `33723` | IPTC(International Press Telecommunications Council) 메타데이터. 종종 데이터 유형이 LONG. 로 잘못 지정됩니다. |
| Photoshop | `34377` | Photoshop '이미지 리소스 블록' 컬렉션. |
| ImageLayer | `34732` | 이미지 레이어. |
| IccProfile | `34675` | 색상 프로필 데이터. |
| ExifIfd | `34665` | 모든 EXIF 메타데이터의 컬렉션을 가리키는 포인터. EXIF는 태그가 아닌 필드 이름을 사용하여 필드 내용을 나타냅니다. |
| GpsIfd | `34853` | GPS 데이터에 대한 포인터. |
| Makernotes | `37500` | 메이커노트 데이터에 대한 포인터. |
| InteroperabilityIfd | `40965` | Exif 관련 상호 운용성 IFD. |
| CameraOwnerName | `42032` | 카메라 소유자 이름(ASCII 문자열). |
| BodySerialNumber | `42033` | ASCII 문자열로 된 카메라 본체 일련 번호. |
| CfaPattern | `41730` | 는 원칩 컬러 영역 센서를 사용할 때 이미지 센서의 CFA(Color Filter Array) 기하학적 패턴을 나타냅니다. 모든 센싱 방식에 적용되는 것은 아닙니다. |
| ExifVersion | `36864` | 지원되는 EXIF 표준 버전입니다. |
| ComponentsConfiguration | `37121` | 압축 데이터 관련 정보. 각 구성 요소의 채널은 첫 번째 구성 요소부터 네 번째 구성 요소까지 순서대로 배열됩니다. |
| FlashpixVersion | `40960` | FPXR 파일에서 지원하는 Flashpix 형식 버전입니다. FPXR 기능이 Flashpix 형식을 지원하는 경우 Ver. 1.0인 경우 ExifVersion과 유사하게 "0100"을 4바이트 ASCII로 기록하여 표시합니다. |
| ColorSpace | `40961` | 색 공간 정보 태그(ColorSpace)는 항상 색 공간 지정자로 기록됩니다. 일반적으로 sRGB(=1)는 PC 모니터 조건 및 환경에 따라 색 공간을 정의하는 데 사용됩니다. sRGB 이외의 색 공간을 사용하는 경우 Uncalibrated(=FFFF.H)로 설정됩니다. |
| PixelXDimension | `40962` | 압축 데이터 관련 정보. 압축 파일을 기록할 때 패딩 데이터나 재시작 마커가 있든 없든 이 태그에는 의미 있는 이미지의 유효한 너비가 기록됩니다. |
| PixelYDimension | `40963` | 압축 데이터 관련 정보. 압축 파일을 기록할 때 패딩 데이터나 재시작 마커가 있든 없든 의미 있는 이미지의 유효한 높이를 이 태그에 기록해야 합니다. |
| SceneCaptureType | `41990` | 이 태그는 촬영된 장면의 유형을 나타냅니다. 이미지가 촬영된 모드를 기록하는 데에도 사용할 수 있습니다. |
| Gamma | `42240` | 계수 감마의 값을 나타냅니다. |
| CompressedBitsPerPixel | `37122` | 압축 데이터 관련 정보. 압축된 이미지에 사용되는 압축 모드는 픽셀당 단위 비트로 표시됩니다. |
| RelatedSoundFile | `40964` | 이 태그는 이미지 데이터와 관련된 오디오 파일의 이름을 기록하는 데 사용됩니다. 여기에 기록된 유일한 관계 정보는 Exif 오디오 파일 이름과 확장자 (8자 + '.' + 3자로 구성된 ASCII 문자열)입니다. |
| DateTimeOriginal | `36867` | 원본 이미지 데이터가 생성된 날짜와 시간입니다. DSC의 경우 사진을 찍은 날짜와 시간이 기록됩니다. 형식은 "YYYY:MM:DD HH:MM:SS"이며 시간은 24시간 형식으로 표시되고 날짜와 시간은 하나의 공백 문자로 구분됩니다. |
| DateTimeDigitized | `36868` | 이미지가 디지털 데이터로 저장된 날짜와 시간. 예를 들어 이미지가 DSC에 의해 캡처되고 동시에 파일이 기록된 경우 DateTimeOriginal 및 DateTimeDigitized는 동일한 내용을 갖게 됩니다. 형식은 "YYYY:MM:DD HH:MM:SS"이며 시간은 24시간 형식으로 표시되고 날짜와 시간은 하나의 공백 문자로 구분됩니다. |
| OffsetTime | `36880` | DateTime 태그의 시간의 UTC(일광 절약 시간을 포함한 협정 세계시와의 시차)와의 오프셋을 기록하는 데 사용되는 태그입니다. 오프셋을 기록할 때 형식은 "±HH:MM"입니다. "±" 부분은 "+" 또는 "-"로 기록한다. |
| OffsetTimeOriginal | `36881` | DateTimeOriginal 태그의 시간의 UTC(일광 절약 시간을 포함한 협정 세계시와의 시차)와의 오프셋을 기록하는 데 사용되는 태그입니다. 오프셋을 기록할 때 형식은 "±HH:MM"입니다. "±" 부분은 "+" 또는 "-"로 기록한다. |
| OffsetTimeDigitized | `36882` | DateTimeDigitized 태그의 시간의 UTC(일광 절약 시간을 포함한 협정 세계시와의 시차)와의 오프셋을 기록하는 데 사용되는 태그입니다. 오프셋을 기록할 때 형식은 "±HH:MM"입니다. "±" 부분은 "+" 또는 "-"로 기록한다. |
| SubsecTime | `37520` | DateTime 태그의 초 단위를 기록하는 데 사용되는 태그입니다. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal 태그의 초 단위를 기록하는 데 사용되는 태그입니다. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized 태그의 초 단위를 기록하는 데 사용되는 태그입니다. |
| ExposureTime | `33434` | 노출 시간, 초(초). |
| FNumber | `33437` | F 번호. |
| ExposureProgram | `34850` | 사진을 찍을 때 노출을 설정하기 위해 카메라에서 사용하는 프로그램 클래스입니다. |
| SpectralSensitivity | `34852` | 사용된 카메라의 각 채널의 스펙트럼 감도를 나타냅니다. 태그 값은 ASTM 기술 위원회에서 개발한 표준과 호환되는 ASCII 문자열입니다. |
| PhotographicSensitivity | `34855` | 이 태그는 이미지가 촬영되었을 때 카메라 또는 입력 장치의 감도를 나타냅니다. |
| Oecf | `34856` | ISO 14524에 지정된 광전기 변환 함수(OECF)를 나타냅니다. OECF는 카메라 광학 입력과 이미지 값 간의 관계입니다. |
| SensitivityType | `34864` | SensitivityType 태그는 ISO12232의 매개변수 중 어느 것이 PhotographicSensitivity 태그인지를 나타냅니다. 선택적 태그이지만 PhotographicSensitivity 태그가 기록될 때 함께 기록되어야 합니다. |
| StandardOutputSensitivity | `34865` | 이 태그는 ISO 12232에 정의된 카메라 또는 입력 장치의 표준 출력 감도 값을 나타냅니다. 이 태그를 기록할 때 PhotographicSensitivity 및 SensitivityType 태그도 기록되어야 합니다. |
| RecommendedExposureIndex | `34866` | 이 태그는 ISO 12232에서 정의된 카메라 또는 입력 장치의 권장 노출 지수 값을 나타냅니다. 이 태그를 기록할 때 PhotographicSensitivity 및 SensitivityType 태그도 기록되어야 합니다. |
| IsoSpeed | `34867` | 이 태그는 ISO 12232에 정의된 카메라 또는 입력 장치의 ISO 감도 값을 나타냅니다. 이 태그를 기록할 때 PhotographicSensitivity 및 SensitivityType 태그도 기록됩니다. |
| ISOSpeedLatitudeYyy | `34868` | 이 태그는 ISO 12232에 정의된 카메라 또는 입력 장치의 ISO 감도 위도 yyy 값을 나타냅니다. |
| ISOSpeedLatitudeZzz | `34869` | 이 태그는 ISO 12232에 정의된 카메라 또는 입력 장치의 ISO 속도 관용도 zzz 값을 나타냅니다. |
| ShutterSpeedValue | `37377` | 셔터 속도. 단위는 APEX(Additive System of Photographic Exposure) 설정입니다. |
| ApertureValue | `37378` | 렌즈 조리개입니다. 단위는 APEX 값입니다. |
| BrightnessValue | `37379` | 밝기 값입니다. 단위는 APEX 값입니다. |
| ExposureBiasValue | `37380` | 노출 바이어스. 단위는 APEX 값입니다. |
| MaxApertureValue | `37381` | 렌즈의 가장 작은 F 번호. 단위는 APEX 값입니다. |
| SubjectDistance | `37382` | 피사체까지의 거리(미터 단위). |
| MeteringMode | `37383` | 측광 모드입니다. |
| LightSource | `37384` | 광원의 종류. |
| Flash | `37385` | 이 태그는 이미지가 촬영되었을 때 플래시 상태를 나타냅니다. 비트 0은 플래시 발광 상태를 나타내고, 비트 1 및 2는 플래시 복귀 상태를 나타내고, 비트 3 및 4는 플래시 모드를 나타내고, 비트 5는 플래시 기능이 있는지 여부를 나타내고, 비트 6은 "적목 현상" 모드를 나타냅니다. |
| SubjectArea | `37396` | 이 태그는 전체 장면에서 주요 피사체의 위치와 영역을 나타냅니다. |
| FocalLength | `37386` | 렌즈의 실제 초점 거리(mm)입니다. 35mm 필름 카메라의 초점 거리로 변환되지 않습니다. |
| FlashEnergy | `41483` | BCPS(Beam Candle Power Seconds) 단위로 측정된 이미지 캡처 시간의 스트로브 에너지를 나타냅니다. |
| SpatialFrequencyResponse | `41484` | 이 태그는 ISO 12233. 에 지정된 이미지 너비, 이미지 높이 및 대각선 방향의 카메라 또는 입력 장치 공간 주파수 테이블 및 SFR 값을 기록합니다. |
| FocalPlaneXResolution | `41486` | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 너비(X) 방향의 픽셀 수를 나타냅니다. |
| FocalPlaneYResolution | `41487` | 카메라 초점면에서 FocalPlaneResolutionUnit당 이미지 높이(Y) 방향의 픽셀 수를 나타냅니다. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution 및 FocalPlaneYResolution 측정 단위를 나타냅니다. 이 값은 ResolutionUnit. 와 동일합니다. |
| SubjectLocation | `41492` | 장면에서 주 피사체의 위치를 나타냅니다. 이 태그의 값은 회전 태그에 따라 회전 처리하기 전에 왼쪽 가장자리를 기준으로 주 피사체의 중심에 있는 픽셀을 나타냅니다. 첫 번째 값은 X 열 번호를 나타내고 두 번째 값은 Y 행 번호를 나타냅니다. |
| ExposureIndex | `41493` | 이미지 촬영 시 카메라 또는 입력 장치에서 선택한 노출 지수를 나타냅니다. |
| SensingMethod | `41495` | 카메라 또는 입력 장치의 이미지 센서 유형을 나타냅니다. |
| FileSource | `41728` | 이미지 소스를 나타냅니다. DSC가 이미지를 기록한 경우 이 태그 값은 항상 3. 로 설정됩니다. |
| SceneType | `41729` | 장면 유형을 나타냅니다. DSC가 이미지를 기록했다면 이 태그 값은 항상 1로 설정되어 이미지가 직접 촬영되었음을 나타냅니다. |
| CustomRendered | `41985` | 이 태그는 출력에 맞춘 렌더링과 같이 이미지 데이터에 대한 특수 처리 사용을 나타냅니다. |
| ExposureMode | `41986` | 이 태그는 이미지가 촬영될 때 설정된 노출 모드를 나타냅니다. 자동 브라케팅 모드에서 카메라는 서로 다른 노출 설정에서 동일한 장면의 일련의 프레임을 촬영합니다. |
| WhiteBalance | `41987` | 이 태그는 이미지를 촬영할 때 설정한 화이트 밸런스 모드를 나타냅니다. |
| DigitalZoomRatio | `41988` | 이 태그는 이미지가 촬영되었을 때의 디지털 줌 비율을 나타냅니다. 기록된 값의 분자가 0이면 디지털 줌을 사용하지 않은 것입니다. |
| FocalLengthIn35mmFilm | `41989` | 이 태그는 35mm 필름 카메라를 가정하여 해당 초점 거리를 mm 단위로 나타냅니다. 값 0은 초점 거리를 알 수 없음을 의미합니다. 이 태그는 FocalLength 태그와 다릅니다. |
| GainControl | `41991` | 이 태그는 전반적인 이미지 게인 조정 정도를 나타냅니다. |
| Contrast | `41992` | 이 태그는 이미지가 촬영될 때 카메라가 적용한 대비 처리의 방향을 나타냅니다. |
| Saturation | `41993` | 이 태그는 이미지가 촬영될 때 카메라가 적용한 채도 처리 방향을 나타냅니다. |
| Sharpness | `41994` | 이 태그는 이미지가 촬영될 때 카메라가 적용한 선명도 처리 방향을 나타냅니다. |
| DeviceSettingDescription | `41995` | 이 태그는 특정 카메라 모델의 촬영 조건에 대한 정보를 나타냅니다. |
| SubjectDistanceRange | `41996` | 이 태그는 피사체까지의 거리를 나타냅니다. |
| CompositeImage | `42080` | 이 태그는 녹화된 이미지가 합성 이미지*인지 여부를 나타냅니다. |
| SourceImageNumberOfCompositeImage | `42081` | 이 태그는 합성 이미지에 대해 캡처된 원본 이미지(임시 녹화 이미지)의 수를 나타냅니다. |
| SourceExposureTimesOfCompositeImage | `42082` | 합성 이미지의 경우 이 태그는 해당 합성 이미지를 생성하기 위한 노출의 노출 시간과 관련된 매개변수를 기록합니다. |
| Temperature | `37888` | 촬영 시 주변 상황으로서의 온도(예: 사진가가 카메라를 들고 있는 실내 온도). 단위는 °C입니다. |
| Humidity | `37889` | 촬영 시 주변 상황으로서의 습도(예: 사진가가 카메라를 들고 있는 실내 습도). 단위는 %입니다. |
| Pressure | `37890` | 촬영 시 주변 상황으로서의 압력, 예를 들어 사진가가 카메라를 들고 있는 실내 분위기 또는 해저 수압. 단위는 hPa입니다. |
| WaterDepth | `37891` | 촬영 시 주변 상황으로서의 수심(예: 수중 촬영 시 카메라의 수심). 단위는 m. 입니다. |
| Acceleration | `37892` | 촬영 시 주변 상황으로서의 가속도(방향에 상관없는 스칼라), 예를 들어 촬영 시 사진사가 탔던 차량의 주행 가속도. 단위는 mGal(10-5m/s2)입니다. |
| CameraElevationAngle | `37893` | 상승/하강. 촬영 시 주변 상황에 따른 카메라 방향(영상 광축)의 각도. 단위는 도(°). |
| ImageUniqueID | `42016` | 이 태그는 각 이미지에 고유하게 할당된 식별자를 나타냅니다. |
| LensSpecification | `42034` | 이 태그는 최소 초점 거리, 최대 초점 거리, 최소 초점 거리의 최소 F 번호, 및 최대 초점 거리의 최소 F 번호를 기록하며 사진에 사용된 렌즈에 대한 사양 정보입니다. |
| LensMake | `42035` | 이 태그는 렌즈 제조업체를 ASCII 문자열로 기록합니다. |
| LensModel | `42036` | 이 태그는 렌즈의 모델명과 모델 번호를 ASCII 문자열로 기록합니다. |
| LensSerialNumber | `42037` | 이 태그는 사진에 사용된 교환식 렌즈의 일련 번호를 ASCII 문자열로 기록합니다. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
