---
title: ExifGpsPackage
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Bir EXIF meta veri paketindeki GPS meta verilerini temsil eder.
type: docs
weight: 2770
url: /tr/net/groupdocs.metadata.standards.exif/exifgpspackage/
---
## ExifGpsPackage class

Bir EXIF meta veri paketindeki GPS meta verilerini temsil eder.

```csharp
public sealed class ExifGpsPackage : ExifDictionaryBasePackage
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ExifGpsPackage](exifgpspackage)() | Yeni bir örneğini başlatır.[`ExifGpsPackage`](../exifgpspackage) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Altitude](../../groupdocs.metadata.standards.exif/exifgpspackage/altitude) { get; set; } | İçindeki referansa göre yüksekliği alır veya ayarlar.[`AltitudeRef`](./altituderef) . Referans birimi metredir. |
| [AltitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/altituderef) { get; set; } | Referans yükseklik olarak kullanılan yüksekliği alır veya ayarlar. Referans deniz seviyesi ve rakım deniz seviyesinden yüksek ise 0 verilir. Eğer rakım deniz seviyesinin altında ise 1 değeri verilir ve rakım mutlak değer olarak gösterilir.[`Altitude`](./altitude) etiket. |
| [AreaInformation](../../groupdocs.metadata.standards.exif/exifgpspackage/areainformation) { get; set; } | GPS alanının adını kaydeden karakter dizisini alır veya ayarlar. İlk bayt, kullanılan karakter kodunu gösterir ve bunu GPS alanının adı izler. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Meta veri özelliklerinin sayısını alır. |
| [DataDegreeOfPrecision](../../groupdocs.metadata.standards.exif/exifgpspackage/datadegreeofprecision) { get; set; } | GPS DOP'u (veri kesinlik derecesi) alır veya ayarlar. İki boyutlu ölçüm sırasında bir HDOP değeri ve üç boyutlu ölçüm sırasında PDOP yazılır. |
| [DateStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/datestamp) { get; set; } | UTC'ye (Koordineli Evrensel Zaman) göre karakter dizisi kayıt tarih ve saat bilgilerini alır veya ayarlar. Biçim YYYY:AA:GG. şeklindedir. |
| [DestBearing](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearing) { get; set; } | Hedef noktaya GPS yönünü alır veya ayarlar. Değer aralığı 0,00 ile 359,99 arasındadır. |
| [DestBearingRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destbearingref) { get; set; } | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. 'T' gerçek yönü ve 'M' manyetik yönü belirtir. |
| [DestDistance](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistance) { get; set; } | Hedef noktaya GPS mesafesini alır veya ayarlar. |
| [DestDistanceRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destdistanceref) { get; set; } | Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. 'K', 'M' ve 'N' kilometre, mil ve deniz milini temsil eder. |
| [DestLatitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatitude) { get; set; } | Hedef noktanın GPS enlemini alır veya ayarlar. |
| [DestLatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlatituderef) { get; set; } | Hedef noktanın enleminin kuzey mi yoksa güney enlemi mi olduğunu gösteren GPS değerini alır veya ayarlar. ASCII değeri 'N' kuzey enlemini ve 'S' güney enlemini gösterir. |
| [DestLongitude](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongitude) { get; set; } | Hedef noktanın GPS boylamını alır veya ayarlar. |
| [DestLongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/destlongituderef) { get; set; } | Hedef noktanın doğu boylamının mı yoksa batı boylamının mı olduğunu gösteren GPS değerini alır veya ayarlar. ASCII 'E' doğu boylamını ve 'W' batı boylamını gösterir. |
| [Differential](../../groupdocs.metadata.standards.exif/exifgpspackage/differential) { get; set; } | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değeri alır veya ayarlar. |
| [GpsTrack](../../groupdocs.metadata.standards.exif/exifgpspackage/gpstrack) { get; set; } | GPS alıcı hareketinin yönünü alır veya ayarlar. |
| [ImgDirection](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirection) { get; set; } | Yakalandığında görüntünün GPS yönünü alır veya ayarlar. Değer aralığı 0,00 ile 359,99 arasındadır. |
| [ImgDirectionRef](../../groupdocs.metadata.standards.exif/exifgpspackage/imgdirectionref) { get; set; } | Yakalandığında görüntünün yönünü vermek için GPS referansını alır veya ayarlar. 'T' gerçek yönü ve 'M' manyetik yönü belirtir. |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | Belirtilen kimliğe sahip TIFF etiketini alır. (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Meta veri özellik adlarının bir koleksiyonunu alır. |
| [Latitude](../../groupdocs.metadata.standards.exif/exifgpspackage/latitude) { get; set; } | GPS enlemini alır veya ayarlar. |
| [LatitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/latituderef) { get; set; } | Enlemin kuzey mi güney mi olduğunu gösteren bir GPS değeri alır veya ayarlar. |
| [Longitude](../../groupdocs.metadata.standards.exif/exifgpspackage/longitude) { get; set; } | GPS boylamını alır veya ayarlar. |
| [LongitudeRef](../../groupdocs.metadata.standards.exif/exifgpspackage/longituderef) { get; set; } | Boylamın doğu mu yoksa batı boylamı mı olduğunu gösteren bir GPS değeri alır veya ayarlar. |
| [MapDatum](../../groupdocs.metadata.standards.exif/exifgpspackage/mapdatum) { get; set; } | GPS alıcısı tarafından kullanılan jeodezik araştırma verilerini alır veya ayarlar. |
| [MeasureMode](../../groupdocs.metadata.standards.exif/exifgpspackage/measuremode) { get; set; } | GPS ölçüm modunu alır veya ayarlar. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Meta veri türünü alır. |
| [ProcessingMethod](../../groupdocs.metadata.standards.exif/exifgpspackage/processingmethod) { get; set; } | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizesi alır veya ayarlar. İlk bayt, kullanılan karakter kodunu gösterir ve bunu yöntemin adı izler. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | GroupDocs.Metadata arama motoru aracılığıyla erişilebilen özellikler hakkında bilgi içeren bir tanımlayıcı koleksiyonu alır. |
| [Satellites](../../groupdocs.metadata.standards.exif/exifgpspackage/satellites) { get; set; } | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. Bu etiket, uydu sayısını, kimlik numarasını, yükseklik açısını, azimutu, SNR'yi ve ASCII notasyonundaki diğer bilgileri tanımlamak için kullanılabilir. Biçim not belirtilmedi. GPS alıcısı ölçüm yapamıyorsa, etiketin değeri NULL. olarak ayarlanmalıdır. |
| [Speed](../../groupdocs.metadata.standards.exif/exifgpspackage/speed) { get; set; } | GPS alıcı hareketinin hızını alır veya ayarlar. |
| [SpeedRef](../../groupdocs.metadata.standards.exif/exifgpspackage/speedref) { get; set; } | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. 'K' 'M' ve 'N', kilometre/saat, mil/saat ve deniz milini temsil eder. |
| [Status](../../groupdocs.metadata.standards.exif/exifgpspackage/status) { get; set; } | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| [TimeStamp](../../groupdocs.metadata.standards.exif/exifgpspackage/timestamp) { get; set; } | Saati UTC (Eşgüdümlü Evrensel Saat) olarak alır veya ayarlar. TimeStamp, saat, dakika ve saniyeyi veren üç RATIONAL değeri olarak ifade edilir. |
| [TrackRef](../../groupdocs.metadata.standards.exif/exifgpspackage/trackref) { get; set; } | GPS alıcı hareketinin yönünü vermek için referansı alır veya ayarlar. 'T' gerçek yönü ve 'M' manyetik yönü belirtir. |
| [VersionID](../../groupdocs.metadata.standards.exif/exifgpspackage/versionid) { get; set; } | GPS IFD sürümünü alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ekler. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | Pakette saklanan tüm TIFF etiketlerini kaldırır. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Paketin belirtilen ada sahip bir meta veri özelliği içerip içermediğini belirler. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini bulur. Arama özyinelemeli olduğu için iç içe geçmiş tüm paketleri de etkiler. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Koleksiyon boyunca yinelenen bir numaralandırıcı döndürür. |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | Belirtilen kimliğe sahip özelliği kaldırır. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Belirtilen yüklemi karşılayan meta veri özelliklerini kaldırır. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Paketten yazılabilir meta veri özelliklerini kaldırır. İşlem özyinelemeli olduğundan iç içe geçmiş tüm paketleri de etkiler. |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | Belirtilen etiketi ekler veya değiştirir. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini ayarlar. İşlem özyinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. Bu yöntem,[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) ve[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) Mevcut bir özellik yüklemi karşılıyorsa, değeri güncellenir. Yüklemi karşılayan pakette eksik bilinen bir özellik varsa, pakete eklenir. |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | Paketten bir liste oluşturur. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Belirtilen yüklemi karşılayan bilinen meta veri özelliklerini günceller. İşlem yinelemeli olduğundan tüm iç içe geçmiş paketleri de etkiler. |

### Notlar

**Daha fazla bilgi edin**

* [EXIF meta verileriyle çalışma](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### Ayrıca bakınız

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* ad alanı [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
