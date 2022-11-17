---
title: TiffTagID
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: TIFF etiketlerinin kimliklerini tanımlar.
type: docs
weight: 2100
url: /tr/net/groupdocs.metadata.formats.image/tifftagid/
---
## TiffTagID enumeration

TIFF etiketlerinin kimliklerini tanımlar.

```csharp
public enum TiffTagID : ushort
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| GpsVersionID | `0` | GPSInfoIFD. sürümünü gösterir |
| GpsLatitudeRef | `1` | Enlemin kuzey mi güney mi olduğunu gösterir. |
| GpsLatitude | `2` | Enlemi gösterir. |
| GpsLongitudeRef | `3` | Boylamın doğu mu yoksa batı boylamı mı olduğunu gösterir. |
| GpsLongitude | `4` | Boylamı gösterir. |
| GpsAltitudeRef | `5` | Referans yükseklik olarak kullanılan yüksekliği gösterir. |
| GpsAltitude | `6` | GPSAltitudeRef. içindeki referansa göre yüksekliği gösterir. |
| GpsTimeStamp | `7` | Saati UTC (Eşgüdümlü Evrensel Saat) olarak gösterir. |
| GpsSatellites | `8` | , ölçümler için kullanılan GPS uydularını gösterir. |
| GpsStatus | `9` | Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir. |
| GpsMeasureMode | `10` | GPS ölçüm modunu gösterir. |
| GpsDop | `11` | GPS DOP'u (veri kesinlik derecesi) gösterir. |
| GpsSpeedRef | `12` | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi belirtir |
| GpsSpeed | `13` | GPS alıcısının hareket hızını gösterir. |
| GpsTrackRef | `14` | GPS alıcı hareketinin yönünü vermek için referansı gösterir. |
| GpsTrack | `15` | GPS alıcısının hareket yönünü gösterir. |
| GpsImgDirectionRef | `16` | Yakalandığında görüntünün yönünü vermek için referansı belirtir. |
| GpsImgDirection | `17` | Yakalandığında görüntünün yönünü belirtir. |
| GpsMapDatum | `18` | GPS alıcısı tarafından kullanılan jeodezik araştırma verilerini gösterir. |
| GpsDestLatitudeRef | `19` | Varış noktasının enleminin kuzey mi yoksa güney enlemi mi olduğunu gösterir. |
| GpsDestLatitude | `20` | Hedef noktanın enlemini gösterir. |
| GpsDestLongitudeRef | `21` | Varış noktasının boylamının doğu mu yoksa batı boylamı mı olduğunu gösterir. |
| GpsDestLongitude | `22` | Hedef noktanın boylamını gösterir. |
| GpsDestBearingRef | `23` | Yönü varış noktasına vermek için kullanılan referansı belirtir. |
| GpsDestBearing | `24` | Hedef noktaya olan yönü gösterir. |
| GpsDestDistanceRef | `25` | Varış noktasına olan mesafeyi ifade etmek için kullanılan birimi belirtir. |
| GpsDestDistance | `26` | Hedef noktaya olan mesafeyi gösterir. |
| GpsProcessingMethod | `27` | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizisi. |
| GpsAreaInformation | `28` | GPS alanının adını kaydeden bir karakter dizisi. |
| GpsDateStamp | `29` | UTC'ye (Koordineli Evrensel Zaman) göre tarih ve saat bilgilerini kaydeden bir karakter dizisi. |
| GpsDifferential | `30` | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösterir. |
| GpsHPositioningError | `31` | Bu etiket, metre cinsinden yatay konumlandırma hatalarını gösterir. |
| NewSubfileType | `254` | Bu alt dosyada bulunan veri türlerinin genel bir göstergesi. |
| SubfileType | `255` | Bu alt dosyada bulunan veri türlerinin genel bir göstergesi. Bu alan kullanımdan kaldırılmıştır. Bunun yerine NewSubfileType alanı kullanılmalıdır |
| ImageWidth | `256` | Görüntüdeki sütun sayısı, yani tarama satırı başına piksel sayısı. |
| ImageLength | `257` | Resimdeki satır sayısı (bazen tarama çizgileri olarak tanımlanır). |
| BitsPerSample | `258` | Bileşen başına bit sayısı. |
| Compression | `259` | Görüntü verilerinde kullanılan sıkıştırma şeması. |
| PhotometricInterpretation | `262` | Görüntü verilerinin renk alanı. |
| Threshholding | `263` | Grinin tonlarını temsil eden siyah beyaz TIFF dosyaları için, griden siyah beyaz piksellere dönüştürmek için kullanılan teknik. |
| CellWidth | `264` | Titreşimli veya yarı tonlu iki düzeyli dosya oluşturmak için kullanılan renk taklidi veya yarı tonlama matrisinin genişliği. |
| CellLength | `265` | Titreşimli veya yarı tonlu iki düzeyli dosya oluşturmak için kullanılan renk taklidi veya yarı tonlama matrisinin uzunluğu. |
| FillOrder | `266` | Bir bayt içindeki bitlerin mantıksal sırası. |
| DocumentName | `269` | Bu görüntünün tarandığı belgenin adı. |
| ImageDescription | `270` | Resmin konusunu açıklayan bir dize. |
| Make | `271` | Tarayıcı üreticisi. |
| Model | `272` | Tarayıcı model adı veya numarası. |
| StripOffsets | `273` | Her şerit için, o şeridin bayt ofseti. |
| Orientation | `274` | Görüntünün satırlara ve sütunlara göre yönü. |
| SamplesPerPixel | `277` | Piksel başına bileşen sayısı. |
| RowsPerStrip | `278` | Şerit başına satır sayısı. |
| StripByteCounts | `279` | Her şerit için, sıkıştırmadan sonra şeritteki bayt sayısı. |
| MinSampleValue | `280` | Kullanılan minimum bileşen değeri. |
| MaxSampleValue | `281` | Kullanılan maksimum bileşen değeri. |
| XResolution | `282` | ImageWidth yönünde ÇözünürlükBirimi başına piksel sayısı. |
| YResolution | `283` | Görüntü Uzunluğu yönünde ÇözünürlükBirimi başına piksel sayısı. |
| PlanarConfiguration | `284` | Her pikselin bileşenleri nasıl depolanır. |
| PageName | `285` | Bu görüntünün tarandığı sayfanın adı. |
| XPosition | `286` | Resmin X konumu. |
| YPosition | `287` | Görüntünün Y konumu. |
| FreeOffsets | `288` | Bir TIFF dosyasındaki her bitişik kullanılmayan bayt dizisi için, dizenin bayt ofseti. |
| FreeByteCounts | `289` | Bir TIFF dosyasındaki her bitişik kullanılmayan bayt dizisi için, dizedeki bayt sayısı. |
| GrayResponseUnit | `290` | GrayResponseCurve. içinde yer alan bilgilerin kesinliği |
| GrayResponseCurve | `291` | Gri tonlamalı veriler için, olası her piksel değerinin optik yoğunluğu. |
| T4Options | `292` | T4 kodlama seçenekleri. |
| T6Options | `293` | T6 kodlama seçenekleri. |
| ResolutionUnit | `296` | XResolution ve YResolution. için ölçüm birimi |
| PageNumber | `297` | Bu görüntünün tarandığı sayfanın sayfa numarası. |
| TransferFunction | `301` | Görüntü için bir aktarım işlevini tablo biçiminde tanımlar. Piksel bileşenleri x000d_ gama telafili, sıkıştırılmış, eşit olmayan şekilde nicelenmiş veya başka bir şekilde x000d_ kodlanmış olabilir. TransferFunction, piksel bileşenlerini lineer olmayan BitsPerSample (örn. 8 bit) formundan, algılanabilir bir doğruluk kaybı olmadan 16 bit lineer forma eşler. |
| Software | `305` | Görüntüyü oluşturmak için kullanılan yazılım paketlerinin adı ve sürüm numarası. |
| DateTime | `306` | Görüntü oluşturma tarihi ve saati. |
| Artist | `315` | Resmi oluşturan kişi. |
| HostComputer | `316` | Görüntü oluşturulurken kullanımda olan bilgisayar ve/veya işletim sistemi. |
| Predictor | `317` | Bu bölüm, bazı görüntüler için sıkıştırma oranlarını büyük ölçüde iyileştiren bir Predictor tanımlar. |
| WhitePoint | `318` | Görüntünün beyaz noktasının renkliliği. |
| PrimaryChromaticities | `319` | Görüntünün ana renklerinin renklilikleri. |
| ColorMap | `320` | Palet renkli görüntüler için bir renk haritası. |
| HalftoneHints | `321` | Yarı Tonlu İpuçları alanının amacı, x000d_ ton detayını tutması gereken kolorimetrik olarak belirlenmiş bir görüntüdeki gri seviyeleri aralığını yarı ton işlevine iletmektir. |
| TileWidth | `322` | Piksel cinsinden döşeme genişliği. Bu, her döşemedeki sütun sayısıdır. |
| TileLength | `323` | Piksel cinsinden karo uzunluğu (yüksekliği). Bu, her döşemedeki satır sayısıdır. |
| TileOffsets | `324` | Her kutucuk için, o kutucuğun sıkıştırılmış ve diskte saklanan bayt ofseti. Ofset, TIFF dosyasının başlangıcına göre belirtilir. Bunun, her döşemenin diğer döşemelerin konumlarından bağımsız bir konuma sahip olduğu anlamına geldiğini unutmayın. |
| TileByteCounts | `325` | Her kutucuk için, o kutucuktaki (sıkıştırılmış) bayt sayısı. |
| InkSet | `332` | Ayrılmış (Fotometrik Yorum=5) bir görüntüde kullanılan mürekkep seti. |
| InkNames | `333` | Ayrılmış (PhotometricInterpretation=5) bir görüntüde kullanılan her bir mürekkebin adı, birleştirilmiş, NUL ile sonlandırılmış ASCII dizilerinin bir listesi olarak yazılır. |
| NumberOfInks | `334` | Mürekkep sayısı. Fazladan sample olmadıkça, genellikle SamplesPerPixel'e eşittir. |
| DotRange | `336` | %0 noktasına ve %100 noktasına karşılık gelen bileşen değerleri. DotRange[0] , %0'lık bir noktaya karşılık gelir ve DotRange[1], %100'lük bir noktaya karşılık gelir. |
| ExtraSamples | `338` | Ekstra bileşenlerin açıklaması. |
| SampleFormat | `339` | Bu alan, her bir veri örneğinin bir pikselde nasıl yorumlanacağını belirtir. |
| SMinSampleValue | `340` | Bu alan minimum numune değerini belirtir. |
| SMaxSampleValue | `341` | Bu yeni alan maksimum numune değerini belirtir. |
| TransferRange | `342` | TransferFonksiyonunun aralığını genişletir. |
| JpegProc | `512` | Bu Alan, sıkıştırılmış verileri üretmek için kullanılan JPEG işlemini belirtir. |
| JpegInterchangeFormat | `513` | Bu Alan, TIFF dosyasında bir JPEG değişim biçimi bit akışının olup olmadığını gösterir. |
| JpegInterchangeFormatLength | `514` | Bu Alan, JPEG değişim formatı bitstream 'nin bayt cinsinden uzunluğunu gösterir. |
| JpegRestartInterval | `515` | Bu Alan, sıkıştırılmış görüntü verilerinde kullanılan yeniden başlatma aralığının uzunluğunu belirtir. |
| JpegLosslessPredictors | `517` | Bu Alan, bileşen başına bir tane olmak üzere, kayıpsız öngörücü seçim değerleri listesine işaret eder. |
| JpegPointTransforms | `518` | Bu Alan, bileşen başına bir nokta dönüştürme değerleri listesine işaret eder. |
| JpegQTables | `519` | Bu Alan, bileşen başına bir tane olmak üzere niceleme tablolarına ofsetler listesine işaret eder. |
| JpegDCTables | `520` | Bu Alan, bileşen başına bir tane olmak üzere DC Huffman tablolarına veya kayıpsız Huffman tablolarına göre ofsetler listesine işaret eder. |
| JpegACTables | `521` | Bu Alan, bileşen başına bir tane olmak üzere Huffman AC tablolarına ofsetler listesine işaret eder. |
| YCbCrCoefficients | `529` | RGB'den YCbCr görüntü verilerine dönüşüm için matris katsayıları. |
| YCbCrSubSampling | `530` | Renk bileşenlerinin parlaklık bileşenine göre örnekleme oranı. |
| YCbCrPositioning | `531` | Alt örneklemeli krominans bileşenlerinin parlaklık örneklerine göre konumunu belirtir. |
| ReferenceBlackWhite | `532` | Her bir piksel bileşeni için bir çift üst ve alt boşluk görüntü veri değeri (kod) belirtir. |
| Copyright | `33432` | Telif hakkı bildirimi. |
| UserComment | `37510` | Resimdeki anahtar kelimeler veya yorumlar; ImageDescription. 'yi tamamlar |
| Xmp | `700` | XMP meta verilerinin işaretçisi. |
| ImageID | `32781` | OPI ile ilgili. |
| Iptc | `33723` | IPTC (Uluslararası Basın Telekomünikasyon Konseyi) metadata. Çoğu zaman, veri türü yanlış bir şekilde LONG. şeklinde belirtilir. |
| Photoshop | `34377` | Photoshop 'Görüntü Kaynak Blokları' Koleksiyonu. |
| ImageLayer | `34732` | Görüntü katmanı. |
| IccProfile | `34675` | Renk profili verileri. |
| ExifIfd | `34665` | Tüm EXIF Meta Verilerinin toplanmasına işaretçi. EXIF, alan içeriğini belirtmek için etiketler yerine alan adlarını kullanır. |
| GpsIfd | `34853` | GPS verilerini işaretçi. |
| Makernotes | `37500` | Makernotes verilerine işaretçi. |
| InteroperabilityIfd | `40965` | Exif ile İlgili Birlikte Çalışabilirlik IFD. |
| CameraOwnerName | `42032` | ASCII dizisi olarak kamera sahibi adı. |
| BodySerialNumber | `42033` | ASCII dizisi olarak kamera gövde seri numarası. |
| CfaPattern | `41730` | , tek çipli bir renk alanı sensörü kullanıldığında görüntü sensörünün renk filtresi dizisi (CFA) geometrik modelini belirtir. Tüm algılama yöntemleri için geçerli değildir. |
| ExifVersion | `36864` | Desteklenen EXIF standardının sürümü. |
| ComponentsConfiguration | `37121` | Sıkıştırılmış verilere özel bilgiler. Her bileşenin kanalları 1. bileşenden 4. bileşene doğru sıralanmıştır. |
| FlashpixVersion | `40960` | Bir FPXR dosyası tarafından desteklenen Flashpix biçimi sürümü. FPXR işlevi Flashpix biçimi Ver. 1.0'da bu, "0100"ün 4 bayt ASCII. olarak kaydedilmesiyle ExifVersion'a benzer şekilde belirtilir. |
| ColorSpace | `40961` | Renk alanı bilgi etiketi (ColorSpace) her zaman renk alanı belirleyicisi olarak kaydedilir. Normalde sRGB (=1), PC monitör koşulları ve ortamına göre renk uzayını tanımlamak için kullanılır. sRGB dışında bir renk alanı kullanılıyorsa Kalibre Edilmemiş (=FFFF.H) ayarlanır. |
| PixelXDimension | `40962` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir dosya kaydedildiğinde, , dolgu verisi veya yeniden başlatma işaretçisi olsun ya da olmasın, anlamlı görüntünün geçerli genişliği bu etikete kaydedilecektir. |
| PixelYDimension | `40963` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir dosya kaydedildiğinde, , dolgu verisi veya yeniden başlatma işaretçisi olsun veya olmasın, anlamlı görüntünün geçerli yüksekliği bu etikete kaydedilmelidir. |
| SceneCaptureType | `41990` | Bu etiket, çekilen sahnenin türünü belirtir. Görüntünün çekildiği modu kaydetmek için de kullanılabilir. |
| Gamma | `42240` | gama katsayısının değerini gösterir. |
| CompressedBitsPerPixel | `37122` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir görüntü için kullanılan sıkıştırma modu, piksel başına birim bit cinsinden belirtilir. |
| RelatedSoundFile | `40964` | Bu etiket, görüntü verileriyle ilgili bir ses dosyasının adını kaydetmek için kullanılır. Burada kaydedilen tek ilişkisel bilgi, Exif ses dosyası adı ve uzantısı 'dir (8 karakter + '.' + 3 karakterden oluşan bir ASCII dizisi). |
| DateTimeOriginal | `36867` | Orijinal görüntü verilerinin oluşturulduğu tarih ve saat. Bir DSC için resmin çekildiği tarih ve saat kaydedilir. Biçim "YYYY:AA:GG SS:DD:SS" şeklindedir, saat 24 saat biçiminde gösterilir ve tarih ve saat bir boş karakterle ayrılır. |
| DateTimeDigitized | `36868` | Görüntünün dijital veri olarak depolandığı tarih ve saat. Örneğin, DSC tarafından bir görüntü yakalanmışsa ve aynı zamanda dosya kaydedilmişse, DateTimeOriginal ve DateTimeDigitized aynı içeriğe sahip olacaktır. Biçim "YYYY:AA:GG SS:DD:SS" şeklindedir, saat 24 saat biçiminde gösterilir ve tarih ve saat bir boş karakterle ayrılır. |
| OffsetTime | `36880` | DateTime etiketinin saatinin UTC'den (gün ışığından yararlanma saati dahil Evrensel Saat Koordineli saat farkı) farkını kaydetmek için kullanılan bir etiket. Ofseti kaydederken format "±SS:DD" şeklindedir. "±" kısmı "+" veya "-" olarak kaydedilecektir. |
| OffsetTimeOriginal | `36881` | DateTimeOriginal etiketinin saatinin UTC'den (yaz saati uygulaması da dahil olmak üzere Koordineli Evrensel Saat'ten saat farkı) farkını kaydetmek için kullanılan bir etiket. Farkı kaydederken format "±SS:DD" şeklindedir. "±" kısmı "+" veya "-" olarak kaydedilecektir. |
| OffsetTimeDigitized | `36882` | DateTimeDigitized etiketinin saatinin UTC'den (gün ışığından yararlanma saati dahil Universal Time Coordinated'den saat farkı) farkını kaydetmek için kullanılan bir etiket. Ofseti kaydederken format "±SS:DD" şeklindedir. "±" kısmı "+" veya "-" olarak kaydedilecektir. |
| SubsecTime | `37520` | DateTime etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| ExposureTime | `33434` | Saniye (sn) cinsinden verilen maruz kalma süresi. |
| FNumber | `33437` | F numarası. |
| ExposureProgram | `34850` | Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan programın sınıfı. |
| SpectralSensitivity | `34852` | Kullanılan kameranın her bir kanalının spektral hassasiyetini gösterir. Etiket değeri, ASTM Teknik komitesi tarafından geliştirilen standartla uyumlu bir ASCII dizisidir. |
| PhotographicSensitivity | `34855` | Bu etiket, fotoğraf çekildiğinde kameranın veya giriş cihazının hassasiyetini gösterir. |
| Oecf | `34856` | ISO 14524'te belirtilen Opto-Elektrik Dönüştürme İşlevini (OECF) belirtir. OECF, kamera optik girişi ile görüntü değerleri arasındaki ilişkidir. |
| SensitivityType | `34864` | SensitivityType etiketi, ISO12232 parametrelerinden hangisinin PhotographicSensitivity etiketi olduğunu gösterir. İsteğe bağlı bir etiket olmasına rağmen, bir PhotographicSensitivity etiketi kaydedildiğinde kaydedilmelidir. |
| StandardOutputSensitivity | `34865` | Bu etiket, ISO 12232'de tanımlanan bir kameranın veya giriş cihazının standart çıkış hassasiyet değerini gösterir. Bu etiketi kaydederken, PhotographicSensitivity ve SensitivityType etiketleri de kaydedilecektir. |
| RecommendedExposureIndex | `34866` | Bu etiket, bir kameranın veya ISO 12232'de tanımlanan giriş cihazının önerilen poz indeks değerini gösterir. Bu etiketi kaydederken, PhotographicSensitivity ve SensitivityType etiketleri de kaydedilmelidir. |
| IsoSpeed | `34867` | Bu etiket, ISO 12232'de tanımlanan bir kameranın veya giriş cihazının ISO hız değerini gösterir. Bu etiketi kaydederken, PhotographicSensitivity ve SensitivityType etiketleri de kaydedilmelidir. |
| ISOSpeedLatitudeYyy | `34868` | Bu etiket, bir kameranın veya ISO 12232. 'de tanımlanan giriş cihazının ISO hız enlem yyy değerini gösterir. |
| ISOSpeedLatitudeZzz | `34869` | Bu etiket, bir kameranın veya ISO 12232. 'de tanımlanan giriş cihazının ISO hız enlemi zzz değerini gösterir. |
| ShutterSpeedValue | `37377` | Deklanşör hızı. Birim, APEX (Katkılı Fotoğraf Pozlama Sistemi) ayarıdır. |
| ApertureValue | `37378` | Mercek açıklığı. Birim APEX değeridir. |
| BrightnessValue | `37379` | Parlaklık değeri. Birim APEX değeridir. |
| ExposureBiasValue | `37380` | Maruz kalma yanlılığı. Birim APEX değeridir. |
| MaxApertureValue | `37381` | Merceğin en küçük F sayısı. Birim APEX değeridir. |
| SubjectDistance | `37382` | Özneye metre olarak verilen mesafe. |
| MeteringMode | `37383` | Ölçüm modu. |
| LightSource | `37384` | Bir çeşit ışık kaynağı. |
| Flash | `37385` | Bu etiket, resim çekildiğinde flaşın durumunu gösterir. Bit 0 flaş patlama durumunu, bit 1 ve 2 flaş dönüş durumunu, bit 3 ve 4 flaş modunu, bit 5 flaş işlevinin mevcut olup olmadığını ve bit 6 "kırmızı göz" modunu belirtir. |
| SubjectArea | `37396` | Bu etiket, genel sahnede ana konunun konumunu ve alanını belirtir. |
| FocalLength | `37386` | Merceğin mm cinsinden gerçek odak uzaklığı. 35 mm film kamerasının odak uzaklığına dönüştürme yapılmaz. |
| FlashEnergy | `41483` | Işın Mum Gücü Saniyesi (BCPS) cinsinden ölçüldüğü şekliyle görüntünün çekildiği andaki flaş enerjisini gösterir. |
| SpatialFrequencyResponse | `41484` | Bu etiket, ISO 12233. 'de belirtildiği gibi görüntü genişliği, görüntü yüksekliği ve köşegen yönü yönünde kamera veya giriş cihazı uzamsal frekans tablosunu ve SFR değerlerini kaydeder. |
| FocalPlaneXResolution | `41486` | Kamera odak düzlemindeki Odak Düzlemi Çözünürlük Birimi başına görüntü genişliği (X) yönündeki piksel sayısını belirtir. |
| FocalPlaneYResolution | `41487` | Kamera odak düzlemindeki Odak Düzlemi Çözünürlük Birimi başına görüntü yüksekliği (Y) yönündeki piksel sayısını belirtir. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution ve FocalPlaneYResolution ölçüm birimini belirtir. Bu değer, ResolutionUnit. ile aynıdır. |
| SubjectLocation | `41492` | Sahnedeki ana öznenin konumunu belirtir. Bu etiketin değeri, Rotasyon etiketine göre döndürme işleminden önce sol kenara göre ana konunun merkezindeki pikseli temsil eder. İlk değer X sütun numarasını, ikincisi ise Y satır numarasını gösterir. |
| ExposureIndex | `41493` | Görüntünün çekildiği sırada kamerada veya giriş cihazında seçilen poz indeksini gösterir. |
| SensingMethod | `41495` | Kamera veya giriş aygıtı üzerindeki görüntü sensörü tipini belirtir. |
| FileSource | `41728` | Görüntü kaynağını gösterir. Görüntüyü bir DSC kaydettiyse, bu etiket değeri her zaman 3. olarak ayarlanmalıdır. |
| SceneType | `41729` | Sahne tipini belirtir. Görüntüyü bir DSC kaydettiyse, bu etiket değeri her zaman 1'e ayarlanarak görüntünün doğrudan fotoğraflandığını gösterir. |
| CustomRendered | `41985` | Bu etiket, görüntü verileri üzerinde, çıktıya yönelik işleme gibi özel işlemlerin kullanıldığını gösterir. |
| ExposureMode | `41986` | Bu etiket, resim çekildiğinde ayarlanan pozlama modunu gösterir. Otomatik basamaklama modunda kamera, farklı pozlama ayarlarında aynı sahnenin bir dizi karesini çeker. |
| WhiteBalance | `41987` | Bu etiket, resim çekildiğinde ayarlanan beyaz dengesi modunu gösterir. |
| DigitalZoomRatio | `41988` | Bu etiket, resim çekildiğinde dijital yakınlaştırma oranını gösterir. Kaydedilen değerin payı 0 ise bu, dijital yakınlaştırmanın kullanılmadığını gösterir. |
| FocalLengthIn35mmFilm | `41989` | Bu etiket, 35 mm'lik bir film kamerası varsayıldığında mm cinsinden eşdeğer odak uzaklığını gösterir. 0 değeri, odak uzunluğunun bilinmediği anlamına gelir. Bu etiketin FocalLength etiketinden farklı olduğunu unutmayın. |
| GainControl | `41991` | Bu etiket, genel görüntü kazanç ayarının derecesini gösterir. |
| Contrast | `41992` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan kontrast işleme yönünü gösterir. |
| Saturation | `41993` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan doygunluk işleme yönünü gösterir. |
| Sharpness | `41994` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan keskinlik işleme yönünü gösterir. |
| DeviceSettingDescription | `41995` | Bu etiket, belirli bir kamera modelinin fotoğraf çekme koşulları hakkında bilgi verir. |
| SubjectDistanceRange | `41996` | Bu etiket, özneye olan mesafeyi gösterir. |
| CompositeImage | `42080` | Bu etiket, kaydedilen görüntünün bir bileşik görüntü* olup olmadığını gösterir. |
| SourceImageNumberOfCompositeImage | `42081` | Bu etiket, bileşik bir Görüntü için çekilen kaynak görüntülerin (geçici olarak kaydedilmiş görüntüler) sayısını gösterir. |
| SourceExposureTimesOfCompositeImage | `42082` | Bileşik bir görüntü için, bu etiket, yakalanan kaynak görüntülerin (geçici olarak kaydedilmiş görüntüler) ilgili pozlama süreleri gibi, , söz konusu bileşik görüntünün oluşturulması için pozlamaların pozlama süresi ile ilgili parametreleri kaydeder. |
| Temperature | `37888` | Çekim sırasındaki ortam durumu olarak sıcaklık, örneğin fotoğrafçının kamerayı tuttuğu oda sıcaklığı. Birimi °C'dir. |
| Humidity | `37889` | Çekimdeki ortam durumu olarak nem, örneğin fotoğrafçının kamerayı tuttuğu odadaki nem. Birim %'dir. |
| Pressure | `37890` | Çekimdeki ortam durumu olarak basınç, örneğin fotoğrafçının kamerayı tuttuğu oda atmosferi veya deniz altındaki su basıncı. Birim hPa. |
| WaterDepth | `37891` | Çekimdeki ortam durumu olarak su derinliği, örneğin su altı fotoğrafçılığında kameranın su derinliği. Birim m. |
| Acceleration | `37892` | Çekimdeki ortam durumu olarak hızlanma (yönden bağımsız bir skaler), örneğin, fotoğrafçının çekimde bindiği aracın sürüş ivmesi. Birim mGal'dir (10-5 m/s2). |
| CameraElevationAngle | `37893` | Yükseklik/alçalma. çekimdeki ortam durumu olarak kameranın yönlendirme açısı (görüntüleme optik ekseni). Birim derecedir(°). |
| ImageUniqueID | `42016` | Bu etiket, her görüntüye benzersiz bir şekilde atanan bir tanımlayıcıyı gösterir. |
| LensSpecification | `42034` | Bu etiket, fotoğrafçılıkta kullanılan lensin özellik bilgileri olan minimum odak uzaklığı, maksimum odak uzaklığı, minimum odak uzaklığında minimum F sayısını, maksimum odak uzunluğunda ve minimum F sayısını not eder. |
| LensMake | `42035` | Bu etiket, lens üreticisini bir ASCII dizisi olarak kaydeder. |
| LensModel | `42036` | Bu etiket, merceğin model adını ve model numarasını bir ASCII dizisi olarak kaydeder. |
| LensSerialNumber | `42037` | Bu etiket, fotoğrafçılıkta ASCII dizisi olarak kullanılan değiştirilebilir lensin seri numarasını kaydeder. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
