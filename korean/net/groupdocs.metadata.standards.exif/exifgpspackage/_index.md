---
title: ExifGpsPackage
second_title: .NET API 참조용 GroupDocs.Metadata
description: EXIF 메타데이터 패키지의 GPS 메타데이터를 나타냅니다.
type: docs
weight: 2770
url: /ko/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

EXIF 메타데이터 패키지의 GPS 메타데이터를 나타냅니다.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | 의 새 인스턴스를 초기화합니다.[`ExifGpsPackage`](../exifgpspackage) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | 의 참조를 기반으로 고도를 가져오거나 설정합니다.[`AltitudeRef`](./altituderef) . 참조 단위는 미터입니다. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | 기준 고도로 사용되는 고도를 가져오거나 설정합니다. 기준이 해수면이고 고도가 해수면보다 높으면 0이 주어진다. 고도가 해수면보다 낮으면 1의 값이 주어지고 그 고도는[`Altitude`](./altitude) 태그. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | GPS 영역의 이름을 기록한 문자열을 가져오거나 설정합니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며 그 뒤에 GPS 영역의 이름이 옵니다. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | 메타데이터 속성의 수를 가져옵니다. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | GPS DOP(데이터 정밀도)를 가져오거나 설정합니다. HDOP 값은 2차원 측정 시 기록되고 PDOP는 3차원 측정 시 기록됩니다. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | UTC(Coordinated Universal Time)를 기준으로 한 문자열 녹화 날짜 및 시간 정보를 가져오거나 설정합니다. 형식은 YYYY:MM:DD. 입니다. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | 목적지 지점까지의 GPS 방위를 가져오거나 설정합니다. 값의 범위는 0.00에서 359.99까지입니다. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | 목적지 지점까지 방위를 제공하는 데 사용되는 GPS 참조를 가져오거나 설정합니다. 'T'는 실제 방향을 나타내고 'M'은 자기 방향을 나타냅니다. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | 목적지까지의 GPS 거리를 가져오거나 설정합니다. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | 목적지까지의 거리를 나타내는 데 사용되는 GPS 단위를 가져오거나 설정합니다. 'K', 'M' 및 'N'은 킬로미터, 마일 및 노트를 나타냅니다. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | 목적지 지점의 GPS 위도를 가져오거나 설정합니다. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | 목적지의 위도가 북위인지 남위인지를 나타내는 GPS 값을 가져오거나 설정합니다. ASCII 값 'N'은 북위를 나타내고 'S'는 남위를 나타냅니다. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | 목적지 지점의 GPS 경도를 가져오거나 설정합니다. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | 목적지의 경도가 동경인지 서경인지를 나타내는 GPS 값을 가져오거나 설정합니다. ASCII 'E'는 동경을 나타내고 'W'는 서경을 나타냅니다. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | GPS 수신기에 차분 보정이 적용되었는지 여부를 나타내는 GPS 값을 가져오거나 설정합니다. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | GPS 수신기 이동 방향을 가져오거나 설정합니다. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | 이미지가 캡처되었을 때 이미지의 GPS 방향을 가져오거나 설정합니다. 값의 범위는 0.00에서 359.99까지입니다. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | 이미지가 캡처될 때 이미지의 방향을 제공하기 위한 GPS 참조를 가져오거나 설정합니다. 'T'는 실제 방향을 나타내고 'M'은 자기 방향을 나타냅니다. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | 지정된 id를 가진 TIFF 태그를 가져옵니다. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | 메타데이터 속성 이름의 컬렉션을 가져옵니다. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | GPS 위도를 가져오거나 설정합니다. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | 위도가 북위인지 남위인지 나타내는 GPS 값을 가져오거나 설정합니다. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | GPS 경도를 가져오거나 설정합니다. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | 경도가 동경인지 서경인지 나타내는 GPS 값을 가져오거나 설정합니다. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | GPS 수신기에서 사용하는 측지 측량 데이터를 가져오거나 설정합니다. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | GPS 측정 모드를 가져오거나 설정합니다. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | 메타데이터 유형을 가져옵니다. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | 위치 찾기에 사용된 메서드 이름을 기록한 문자열을 가져오거나 설정합니다. 첫 번째 바이트는 사용된 문자 코드를 나타내며 그 뒤에 메서드 이름이 옵니다. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata 검색 엔진을 통해 액세스할 수 있는 속성에 대한 정보가 포함된 설명자 모음을 가져옵니다. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | 측정에 사용되는 GPS 위성을 가져오거나 설정합니다. 이 태그는 위성의 수, 위성의 ID 번호, 고도각, 방위각, SNR 및 ASCII 표기법의 기타 정보를 설명하는 데 사용할 수 있습니다. 형식이 not 지정되었습니다. GPS 수신기가 측정을 수행할 수 없는 경우 태그 값은 NULL로 설정되어야 합니다. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | GPS 수신기 이동 속도를 가져오거나 설정합니다. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | GPS 수신기 이동 속도를 표현하는 데 사용되는 단위를 가져오거나 설정합니다. 'K' 'M' 및 'N'은 시간당 킬로미터, 시간당 마일 및 노트를 나타냅니다. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | 이미지가 기록될 때 GPS 수신기의 상태를 가져오거나 설정합니다. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | 시간을 UTC(Coordinated Universal Time)로 가져오거나 설정합니다. TimeStamp는 시, 분, 초를 나타내는 3개의 RATIONAL 값으로 표현됩니다. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | GPS 수신기 이동 방향을 제공하기 위한 참조를 가져오거나 설정합니다. 'T'는 실제 방향을 나타내고 'M'은 자기 방향을 나타냅니다. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | GPS IFD의 버전을 가져오거나 설정합니다. |

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

### 또한보십시오

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* 네임스페이스 [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* 집회 [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
