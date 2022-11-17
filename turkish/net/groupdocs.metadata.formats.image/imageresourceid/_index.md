---
title: ImageResourceID
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Görüntü kaynakları standart kimlik numaraları. Tüm dosya biçimleri tüm kimlikleri kullanmaz. Bazı bilgiler dosyanın diğer bölümlerinde saklanabilir.
type: docs
weight: 1750
url: /tr/net/groupdocs.metadata.formats.image/imageresourceid/
---
## ImageResourceID enumeration

Görüntü kaynakları standart kimlik numaraları. Tüm dosya biçimleri tüm kimlikleri kullanmaz. Bazı bilgiler dosyanın diğer bölümlerinde saklanabilir.

```csharp
public enum ImageResourceID
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| ResolutionInfo | `1005` | Çözünürlük Bilgisi yapısı. Photoshop API Kılavuzu PDF belgesinde Ek A'ya bakın. |
| NamesOfAlphaChannels | `1006` | Bir dizi Pascal dizisi olarak alfa kanallarının adları. |
| Caption | `1008` | Pascal dizisi olarak resim yazısı. |
| BorderInformation | `1009` | Sınır bilgisi. Sınır genişliği için sabit bir sayı (2 bayt gerçek, 2 bayt kesir), sınır birimleri için ve 2 bayt içerir (1 = inç, 2 = cm, 3 = nokta, 4 = resim, 5 = sütun). |
| BackgroundColor | `1010` | Arka plan rengi. [Daha fazla gör.](http://www.adobe.com/devnet-apps/photoshop/fileformatashtml/#50577411_31265) |
| PrintFlags | `1011` | Bayrakları yazdırın. Bir baytlık boole değerleri dizisi (Sayfa Yapısı iletişim kutusuna bakın): etiketler, kırpma işaretleri, renk çubukları, kayıt işaretleri, negatif, çevirme, enterpolasyon, resim yazısı, yazdırma bayrakları. |
| Grayscale | `1012` | Gri tonlamalı ve çok kanallı yarı tonlama bilgisi. |
| ColorHalftoning | `1013` | Renkli yarı tonlama bilgisi. |
| DuotoneHalftoning | `1014` | Çift ton yarı tonlama bilgisi. |
| GrayscaleFunction | `1015` | Gri tonlamalı ve çok kanallı aktarım işlevi. |
| ColorTransferFunctions | `1016` | Renk aktarma işlevleri. |
| DuotoneTransferFunctions | `1017` | Çift ton aktarım işlevleri. |
| DuotoneImageInformation | `1018` | Çift tonlu resim bilgisi. |
| EPSOptions | `1021` | EPS seçenekleri. |
| QuickMaskInformation | `1022` | Hızlı Maske bilgisi. Quick Mask kanal kimliğini içeren 2 bayt; Maskenin başlangıçta boş olup olmadığını gösteren 1 bayt boolean. |
| LayerStateInformation | `1024` | Katman durumu bilgisi. Hedef katmanın dizinini içeren 2 bayt (0 = alt katman). |
| WorkingPath | `1025` | Çalışma yolu (kaydedilmemiş). Bkz. Yol kaynak formatı. |
| LayersGroupInformation | `1026` | Katmanlar grup bilgisi. Sürüklenen gruplar için bir grup kimliği içeren katman başına 2 bayt. Bir gruptaki katmanlar aynı grup kimliğine sahiptir. |
| Iptc | `1028` | IPTC-NAA kaydı. Dosya Bilgisi... bilgisini içerir. Documentation klasörünün IPTC klasöründeki belgelere bakın. |
| ImageModeForRawFormat | `1029` | Ham biçimli dosyalar için görüntü modu. |
| JpegQuality | `1030` | JPEG kalitesi. Özel. |
| GridAndGuidesInfoPhotoshop4 | `1032` | Izgara ve kılavuz bilgileri. |
| ThumbnailResourcePhotoshop4 | `1033` | Yalnızca Photoshop 4.0 için küçük resim kaynağı. |
| CopyrightFlagPhotoshop4 | `1034` | Telif hakkı bayrağı. Görüntünün telif hakkına sahip olup olmadığını gösteren Boolean. Özellik paketi aracılığıyla veya kullanıcı tarafından Dosya Bilgileri... içinde ayarlanabilir |
| UrlPhotoshop4 | `1035` | URL'si. Tek tip kaynak bulucuya sahip bir metin dizesinin tanıtıcısı. Özellik paketi aracılığıyla veya kullanıcı tarafından Dosya Bilgileri... içinde ayarlanabilir |
| ThumbnailResourcePhotoshop5 | `1036` | Küçük resim kaynağı (1033 kaynağının yerine geçer). Bkz. Küçük resim kaynak formatına bakın. |
| GlobalAnglePhotoshop5 | `1037` | Küresel Açı. Efekt katmanı için genel aydınlatma açısı olan 0 ile 359 arasında bir tamsayı içeren 4 bayt. Mevcut değilse, 30. olduğu varsayılır |
| IccProfilePhotoshop5 | `1039` | (Photoshop 5.0) ICC Profili. Bir ICC (Uluslararası Renk Konsorsiyumu) biçim profilinin ham baytları. Documentation klasöründeki ICC1v42_2006-05.pdf'ye ve Sample Code\Common\Includes. içindeki icProfileHeader.h'ye bakın. |
| WatermarkPhotoshop5 | `1040` | Filigran. Bir bayt. |
| IccUntaggedProfilePhotoshop5 | `1041` | ICC Etiketlenmemiş Profil. Dosyayı açarken varsayılan profil işlemeyi devre dışı bırakan 1 bayt. 1 = kasıtlı olarak etiketlenmemiş. |
| TransparencyIndexPhotoshop6 | `1047` | Şeffaflık Dizini. Varsa şeffaf rengin dizini için 2 bayt. |
| GlobalAltitudePhotoshop6 | `1049` | Küresel Yükseklik. Rakım için 4 baytlık giriş. |
| SlicesPhotoshop6 | `1050` | Dilimler (Photoshop 6). |
| WorkflowUrlPhotoshop6 | `1051` | İş Akışı URL'si. Unicode dizesi. Photoshop 6. |
| AlphaIdentifiersPhotoshop6 | `1053` | Alfa Tanımlayıcıları. 4 bayt uzunluk, ardından her alfa tanımlayıcı için 4 bayt. |
| UrlListPhotoshop6 | `1054` | URL Dahili Listesi. 4 bayt URL sayısı, ardından 4 bayt uzunluğunda, 4 bayt kimlik ve her sayı için Unicode dizesi. |
| VersionInfoPhotoshop6 | `1057` | Sürüm Bilgisi. 4 bayt sürüm, 1 bayt hasRealMergedData , Unicode dize: yazar adı, Unicode dize: okuyucu adı, 4 bayt dosya sürümü. |
| ExifData1Photoshop7 | `1058` | EXIF verileri 1,[daha fazla gör](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) . |
| ExifData3Photoshop7 | `1059` | [ EXIF verileri 3.](http://www.kodak.com/global/plugins/acrobat/en/service/digCam/exifStandard2.pdf) |
| XmpPhotoshop7 | `1060` | XMP meta verileri. XML açıklaması olarak dosya bilgisi,[daha fazla gör](http://www.adobe.com/devnet/xmp) . |
| CaptionDigestPhotoshop7 | `1061` | Altyazı özeti. 16 bayt: RSA Veri Güvenliği, MD5 mesaj özet algoritması. |
| PrintScalePhotoshop7 | `1062` | Yazdırma ölçeği. 2 bayt stili (0 = ortalanmış, 1 = sığacak boyut, 2 = kullanıcı tanımlı). 4 bayt x konum (kayan nokta). 4 bayt y konum (kayan nokta). 4 bayt ölçek (kayan nokta). |
| PixelAspectRatio | `1064` | Piksel En Boy Oranı. 4 bayt (sürüm = 1 veya 2), 8 bayt çift, bir pikselin x / y'si. Versiyon 2, NTSC ve PAL için değerleri düzeltmeye çalışıyor, daha önce yakl. %5. |
| LayerComps | `1065` | Katman Kompozisyonları. 4 bayt (tanımlayıcı sürümü = 16), Descriptor. |
| LayerSelectionIds | `1069` | Katman Seçim Kimlikleri. 2 bayt sayısı, her sayım için aşağıdakiler tekrarlanır: 4 bayt katman kimliği. |
| PrintInfoCS2 | `1071` | Yazdırma bilgisi (Photoshop CS2). |
| LayerGroupEnabledIdCS2 | `1072` | Katman Grup(lar)ı Etkin Kimlik. Belgedeki her katman için kaynağın uzunluğuna göre tekrarlanan 1 bayt. NOT: Katman gruplarının başlangıç ve bitiş işaretleri vardır (Photoshop CS2). |
| ColorSamplersResourceCS3 | `1073` | Renk örnekleyicileri kaynağı. Ayrıca eski format için ID 1038'e bakın. |
| MeasurementScaleCS3 | `1074` | Ölçüm Ölçeği. 4 bayt (tanımlayıcı sürümü = 16), Descriptor. |
| TimelineInformationCS3 | `1075` | Zaman Çizelgesi Bilgileri. 4 bayt (tanımlayıcı sürümü = 16), Descriptor. |
| SheetDisclosureCS3 | `1076` | Sayfa Açıklaması. 4 bayt (tanımlayıcı sürümü = 16), Descriptor. |
| PrintInformationCS5 | `1082` | Yazdırma Bilgileri (Photoshop CS5). |
| PrintStyleCS5 | `1083` | Yazdırma Stili (Photoshop CS5). |
| MacintoshNSPrintInfoCS5 | `1084` | Macintosh NSPrintInfo. Macintosh için değişken işletim sistemine özgü bilgi. NSPrintInfo. Bu verileri yorumlamamanız veya kullanmamanız önerilir. (Photoshop CS5). |
| WindowsDevmodeCS5 | `1085` | Windows DEVMODE. Windows için değişken işletim sistemine özgü bilgi. DEVMOD. Bu verileri yorumlamamanız veya kullanmamanız önerilir. (Photoshop CS5). |
| AutoSaveFilePathCS6 | `1086` | Dosya Yolunu Otomatik Kaydet. Unicode dizesi. (Photoshop CS6). |
| AutoSaveFormatCS6 | `1087` | Otomatik Kaydetme Biçimi. Unicode dizesi. (Photoshop CS6). |
| PathSelectionStateCC | `1088` | Yol Seçim Durumu. (Photoshop CC). |
| ImageReadyVariables | `7000` | Görüntü Hazır değişkenleri. Değişken tanımının XML gösterimi. |
| ImageReadyDatasets | `7001` | Görüntü Hazır veri setleri. |
| PrintFlagsInformation | `10000` | Bayrak bilgilerini yazdırın. 2 bayt sürüm ( = 1), 1 bayt merkez kırpma işaretleri, 1 bayt ( = 0), 4 bayt taşma genişliği değeri, 2 bayt taşma genişliği ölçeği. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Formats.Image](../../groupdocs.metadata.formats.image)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
