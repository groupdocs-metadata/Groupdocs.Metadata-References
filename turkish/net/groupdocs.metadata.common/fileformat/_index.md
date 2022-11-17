---
title: FileFormat
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Yüklenen bir dosyanın tanınan biçimini temsil eder.
type: docs
weight: 40
url: /tr/net/groupdocs.metadata.common/fileformat/
---
## FileFormat enumeration

Yüklenen bir dosyanın tanınan biçimini temsil eder.

```csharp
public enum FileFormat
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Unknown | `0` | Dosya türü tanınmadı. |
| Presentation | `1` | Bir sunum dosyası. Microsoft PowerPoint ile çalışırken PPTX ve PPT uzantı dosyalarına aşina olmalısınız. Bunlar, slaytlar, şekiller, metin, animasyonlar, video, ses ve katıştırılmış nesneler. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/presentation/) . |
| Spreadsheet | `2` | Bir elektronik tablo dosyası. Bir elektronik tablo dosyası, satırlar ve sütunlar biçimindeki verileri içerir. Artık hem Windows hem de MacOS işletim sistemi için kullanılabilen Microsoft Excel gibi elektronik tablo yazılım uygulamalarını kullanarak bu tür dosyaları açabilir, görüntüleyebilir ve düzenleyebilirsiniz. Benzer şekilde, Google sayfaları herhangi bir web tarayıcısından çalışan ücretsiz bir çevrimiçi e-tablo oluşturma ve düzenleme aracıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/spreadsheet/) . |
| WordProcessing | `3` | Bir kelime işlem dosyası. Bir kelime işlemci dosyası, düz metin veya zengin metin biçiminde kullanıcı bilgilerini içerir. Düz metin dosyası format , biçimlendirilmemiş metin içerir ve hiçbir yazı tipi veya sayfa ayarı vb. uygulanamaz. sayfa kenar boşlukları, başlıklar, madde işaretleri ve sayılar ve diğer birçok biçimlendirme özelliği. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/word-processing/) . |
| Diagram | `4` | Bir diyagram dosyası. |
| Note | `5` | Bir elektronik not dosyası. Microsoft OneNote gibi not alma programları, notları saklamak için bölümler ve sayfalar içeren not dosyaları oluşturmanıza, açmanıza ve düzenlemenize olanak tanır. Bir not belgesi, bir metin belgesi kadar basit olabileceği gibi daha ayrıntılı da olabilir dijital görüntüler, ses/video klipler ve el çizimlerinden oluşur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/note-taking/) . |
| ProjectManagement | `6` | Bir proje yönetimi formatı. Hiç bir MPP dosyasının ne olduğunu veya nasıl açılacağını merak ettiniz mi? MPP ve diğer benzer dosyalar, Microsoft Project gibi Proje Yönetimi yazılımı tarafından oluşturulan Proje dosya biçimleridir. Bir proje dosya, formda veya bir üründe veya hizmette ölçülebilir bir çıktı elde etmek için görevler, kaynaklar ve bunların zamanlaması koleksiyonudur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/project-management/) . |
| Pdf | `7` | Bir PDF dosyası. Taşınabilir Belge Biçimi (PDF), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. this dosya formatının amacı, uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir format olan 'de belgelerin ve diğer referans materyallerinin temsili için bir standart getirmekti. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/view/pdf/) . |
| Tiff | `8` | A TIFF image. TIFF veya TIF, Etiketli Görüntü Dosyası Biçimi, bu dosya biçimi standardına uyan çeşitli aygıtlarda kullanım amaçlı raster görüntüleri temsil eder. Bu dosya hakkında daha fazla bilgi edinin format [burada](https://wiki.fileformat.com/image/tiff/) . |
| Jpeg | `9` | Bir JPEG görüntüsü. JPEG, kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir tür görüntü biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/jpeg/) . |
| Psd | `10` | Bir PSD görüntüsü. PSD, Photoshop Belgesi, Adobe Photoshop'un grafik tasarlama ve geliştirme için kullanılan yerel dosya biçimini temsil eder. PSD dosyaları görüntü katmanları, ayarlama katmanları, katman maskeleri, ek açıklamalar, dosya bilgileri, anahtar sözcükler ve diğer Photoshop'a özgü öğeleri içerebilir . Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/psd/) . |
| Jpeg2000 | `11` | A Jpeg2000 image. JPEG 2000 (JPX), bir görüntü kodlama sistemi ve en gelişmiş görüntü sıkıştırma standardıdır. Wavelet teknolojisi kullanılarak olarak tasarlanan JPEG 2000, herhangi bir kalitedeki kayıpsız içeriği aynı anda kodlayabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/jp2/) . |
| Gif | `12` | Bir GIF görüntüsü. Bir GIF veya Grafik Değişim Biçimi, yüksek oranda sıkıştırılmış bir görüntü türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/gif/) . |
| Png | `13` | Bir PNG görüntüsü. PNG, Taşınabilir Ağ Grafikleri, kayıpsız sıkıştırma kullanan bir tür raster görüntü dosyası biçimi anlamına gelir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/png/) . |
| Bmp | `14` | Bir BMP görüntüsü. .BMP uzantılı dosyalar, bit eşlem dijital görüntüleri depolamak için kullanılan Bit Eşlem Görüntü dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/bmp/) . |
| Dicom | `15` | Bir DICOM görüntüsü. DICOM, Tıpta Dijital Görüntüleme ve İletişim'in kısaltmasıdır ve Tıbbi Bilişim alanıyla ilgilidir. DICOM, dosya formatı tanımı ile bir ağ iletişim protokolünün birleşimidir. Bu dosya formatı hakkında daha fazla bilgi edinin[ burada](https://wiki.fileformat.com/image/dicom/) . |
| WebP | `16` | Bir WEBP görüntüsü. Google tarafından sunulan WebP, kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web görüntü dosyası biçimidir. Görüntü boyutunu önemli ölçüde azaltırken aynı görüntü kalitesini sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/webp/) . |
| Emf | `17` | Bir EMF görüntüsü. Gelişmiş meta dosyası formatı (EMF), grafik görüntüleri cihazdan bağımsız olarak depolar. EMF'nin meta dosyaları, herhangi bir çıktı cihazında ayrıştırıldıktan sonra saklanan görüntüyü işleyebilen, kronolojik sırayla değişken uzunluklu kayıtlardan oluşur. Bu konuda daha fazla bilgi edinin dosya formatı[burada](https://wiki.fileformat.com/image/emf/) . |
| Wmf | `18` | Bir WMF görüntüsü. WMF uzantılı dosyalar, vektörün yanı sıra bitmap biçimli görüntü verilerini depolamak için Microsoft Windows Meta Dosyasını (WMF) temsil eder. Daha doğru olmak gerekirse, WMF, aygıt olan Grafik dosya biçimlerinin vektör dosya biçimi kategorisine aittir. Independent. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/wmf/) . |
| DjVu | `19` | Bir DjVu dosyası. DjVu, özellikle metin, çizimler, resimler ve fotoğrafların birleşimini içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosyası biçimidir. AT&amp;T Labs tarafından geliştirilmiştir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/djvu/) . |
| Wav | `20` | Bir WAV ses dosyası. WAVE (Dalga Biçimi Ses Dosyası Biçimi) olarak bilinen WAV, Microsoft'un dijital ses dosyalarını depolamak için Kaynak Değişim Dosyası Biçimi (RIFF) özelliğinin bir alt kümesidir. Biçim, bit akışına herhangi bir sıkıştırma uygulamaz ve ses kayıtlarını farklı örnekleme hızları ve bit hızlarıyla depolar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/audio/wav/) . |
| Mp3 | `21` | Bir Mp3 ses dosyası. MP3 uzantılı dosyalar, resmi olarak MPEG-1 Ses Katmanı III veya MPEG-2 Ses Katmanı III'ü temel alan ses dosyaları için dijital olarak kodlanmış dosya biçimleridir. Hareketli Görüntü Uzmanları Grubu tarafından geliştirilmiştir ( Katman 3 ses sıkıştırmasını kullanan MPEG). Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/audio/mp3/) . |
| Avi | `22` | Bir AVI video. AVI dosya formatı, Microsoft tarafından tanıtılan bir Audio Video multimedya kapsayıcı dosya formatıdır. Xvid ve DivX gibi çeşitli codec'ler (Kodlayıcılar/Kod Çözücüler) kullanılarak oluşturulan ve sıkıştırılan ses ve video verilerini tutar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/video/avi/) . |
| Flv | `23` | Bir FLV videosu. |
| Asf | `24` | Bir ASF video. Advanced Systems Format (ASF), öncelikle medya akışlarını depolamak ve iletmek için tasarlanmış bir dijital multimedya kabıdır. Microsoft Windows Media Video (WMV), sıkıştırılmış video formatıdır ve Microsoft Windows Media Audio (WMA), sıkıştırılmış video formatıdır. Microsoft. tarafından geliştirilen ASF kapsayıcısındaki ek meta verilerle birlikte sıkıştırılmış ses formatı Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/video/wmv/) . |
| Mov | `25` | Bir QuickTime video. Mov veya QuickTime Dosya formatı, Apple tarafından geliştirilen bir multimedya kapsayıcıdır: bir veya daha fazla parça içerir, her iz, Video, Ses, metin vb. Windows ve Macintosh sistemleri. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/video/mov/) . |
| Matroska | `26` | Matroska multimedya kapsayıcısı ile kodlanmış bir video. |
| Zip | `27` | Bir ZIP arşivi. ZIP dosya uzantısı, bir veya daha fazla dosya veya dizini tutabilen arşivleri temsil eder. ZIP dosya boyutunu azaltmak için arşiv, dahil edilen dosyalara sıkıştırma uygulayabilir. ZIP dosya formatı, geri Şubat 1989, Phil Katz tarafından dosya ve klasörlerin arşivlenmesini başardığı için. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/compression/zip/) . |
| VCard | `28` | Bir VCard dosyası. VCF (Sanal Kart Formatı) veya vCard, iletişim bilgilerini depolamak için bir dijital dosya formatıdır. Format, popüler bilgi alışverişi uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/email/vcf/) . |
| Epub | `29` | Bir EPUB elektronik kitap. .EPUB uzantılı dosyalar, yayıncılar ve tüketiciler için standart bir dijital yayın biçimi sağlayan bir e-kitap dosya biçimidir. Biçim, şimdiye kadar o kadar yaygınlaştı ki, birçok e-okuyucu tarafından destekleniyor ve yazılım uygulamaları. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/ebook/epub/) . |
| OpenType | `30` | Bir OpenType yazı tipi. |
| Dxf | `31` | Bir DXF (Çizim Değişim Formatı) çizimi. DXF, Çizim Değişim Formatı veya Çizim Değişim Formatı, AutoCAD çizim dosyasının etiketli bir veri temsilidir. Dosyadaki her öğenin, grup kodu adı verilen bir önek tamsayı numarası vardır. Öğrenin bu dosya formatı hakkında daha fazla bilgi[burada](https://wiki.fileformat.com/cad/dxf/) . |
| Dwg | `32` | Bir DWG çizimi. DWG uzantılı dosyalar, 2B ve 3B tasarım verilerini içermek için kullanılan tescilli ikili dosyaları temsil eder. ASCII dosyaları olan DXF gibi, DWG de CAD (Bilgisayar Destekli Tasarım) çizimleri için ikili dosya formatını temsil eder. Daha fazlasını öğrenin bu dosya formatı hakkında[burada](https://wiki.fileformat.com/cad/dwg/) . |
| Eml | `33` | Bir EML e-posta mesajı. EML dosya biçimi, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Hemen hemen tüm e-posta istemcileri, RFC-822 İnternet İleti Biçimi Standardı ile uyumluluğu nedeniyle bu dosya biçimini destekler. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/email/eml/) . |
| Msg | `34` | Bir MSG e-posta mesajı. MSG, e-posta mesajlarını, kişiyi, randevuyu veya diğer görevleri depolamak için Microsoft Outlook ve Exchange tarafından kullanılan bir dosya biçimidir. Bu tür mesajlar, gönderen, alıcı, konu, tarih, ve ileti gövdesi veya iletişim bilgileri, randevu ayrıntıları ve bir veya daha fazla görev belirtimi. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/email/msg/) . |
| Torrent | `35` | Dağıtılacak dosya ve klasörler hakkında meta veriler içeren bir torrent dosyası. |
| Heif | `36` | Bir HEIF/HEIC görüntüsü. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
