---
title: IptcApplicationRecordDataSet
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: IPTC Uygulama Kaydı veri Kümesi numaralarını tanımlar.
type: docs
weight: 2890
url: /tr/net/groupdocs.metadata.standards.iptc/iptcapplicationrecorddataset/
---
## IptcApplicationRecordDataSet enumeration

IPTC Uygulama Kaydı veri Kümesi numaralarını tanımlar.

```csharp
public enum IptcApplicationRecordDataSet
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| RecordVersion | `0` | Kayıt sürümünü temsil eder. İkili. JPEG'lerde her zaman 2. |
| ObjectTypeReference | `3` | Nesne tipi referansı. Kullanılan kalıp: "/\d{2}:[\w\s]{0,64}?/". |
| ObjectAttributeReference | `4` | Nesne özniteliği başvurusu. |
| ObjectName | `5` | Nesne için kısa yol referansı olarak kullanılır. |
| EditStatus | `7` | Sağlayıcının uygulamasına göre nesne verilerinin durumu. |
| EditorialUpdate | `8` | Bu nesnenin önceki bir nesneye sağladığı güncelleme türünü belirtir. |
| Urgency | `10` | İçeriğin editoryal aciliyetini belirtir ve zarf işleme önceliği zorunlu değildir (bkz. 1:60, Zarf Önceliği). |
| SubjectReference | `12` | Konu referansı. |
| Category | `15` | Sağlayıcının görüşüne göre nesne verilerinin konusunu tanımlar. |
| SupplementalCategory | `20` | Tamamlayıcı kategoriler, bir nesne verisinin konusunu daha da hassaslaştırır. Her Veri Kümesinde yalnızca tek bir ek kategori bulunabilir. Ek bir kategori, 2:15'te kullanıldığı şekliyle tanınan kategorilerden herhangi birini içerebilir. |
| FixtureIdentifier | `22` | Fikstür tanımlayıcısı. |
| Keywords | `25` | Belirli bilgi alma sözcüklerini belirtmek için kullanılır. Her anahtar sözcük, tek bir Anahtar Sözcük Veri Kümesi kullanır. Birden çok anahtar sözcük, birden çok Anahtar Sözcük DataSets. kullanır |
| ContentLocationCode | `26` | Nesnenin içeriği tarafından başvurulan bir ülkenin/coğrafi konumun kodunu belirtir. |
| ContentLocationName | `27` | Nesnenin içeriği tarafından başvurulan bir ülke/coğrafi konumun tam, yayınlanabilir adını sağlar, sağlayıcının yönergelerine göre. |
| ReleaseDate | `30` | Sağlayıcının nesnenin kullanılmasını amaçladığı en erken tarihi CCYYAAGG biçiminde belirtir. ISO 8601 standardına uygundur. |
| ReleaseTime | `35` | HHMMSS±HHMM biçiminde, sağlayıcının nesnenin kullanılmasını amaçladığı en erken zamanı belirtir. ISO 8601 standardına uygundur. |
| ExpirationDate | `37` | Sağlayıcının veya sahibin nesne verilerinin kullanılmasını amaçladığı en son tarihi CCYYAAGG biçiminde belirtir. ISO 8601 standardına uygundur. |
| SpecialInstructions | `40` | Ambargolar ve uyarılar gibi, nesne verilerinin kullanımına ilişkin diğer düzenleme talimatları. |
| ActionAdvised | `42` | Bu nesnenin önceki bir nesneye sağladığı eylem türünü belirtir. |
| ReferenceService | `45` | Geçerli nesnenin başvurduğu önceki bir zarfın Hizmet Tanımlayıcısını tanımlar. |
| ReferenceDate | `47` | Geçerli nesnenin başvurduğu önceki bir zarfın tarihini tanımlar. |
| ReferenceNumber | `50` | Geçerli nesnenin başvurduğu önceki bir zarfın Zarf Numarasını tanımlar. |
| DateCreated | `55` | Fiziksel temsilin oluşturulma tarihi yerine nesne verilerinin entelektüel içeriğinin oluşturulduğu tarihi belirtmek için CCYYMMDD biçiminde temsil edilir. |
| TimeCreated | `60` | HHMMSS±HHMM biçiminde, fiziksel temsilin yaratılmasından ziyade, objectdata mevcut kaynak materyalin fikri içeriğinin yaratıldığı zamanı belirtmek için temsil edilir. |
| DigitalCreationDate | `62` | Nesne verilerinin dijital temsilinin oluşturulduğu tarihi belirtmek için CCYYMMDD biçiminde temsil edilir. |
| DigitalCreationTime | `63` | Nesne verilerinin dijital temsilinin oluşturulduğu zamanı belirtmek için HHMMSS±HHMM biçiminde temsil edilir. |
| OriginatingProgram | `65` | objectdata. 'yi oluşturmak için kullanılan programın türünü tanımlar. |
| ProgramVersion | `70` | 2:65'te belirtilen programın sürümünü belirtmek için kullanılır. 2:65 yoksa DataSet 2:70 geçersizdir. |
| ObjectCycle | `75` | Bir alfabetik karakterden oluşur. Burada: 'a' = sabah, 'p' = akşam, 'b' = her ikisi de. |
| Byline | `80` | Nesne verilerinin yaratıcısının adını içerir, örneğin yazar, fotoğrafçı veya grafik sanatçısı. |
| BylineTitle | `85` | Alt satır başlığı, bir nesneyi oluşturanın veya oluşturanların başlığıdır data. |
| City | `90` | Sağlayıcı tarafından belirlenen yönergelere göre nesne verilerinin kaynak şehrini tanımlar. |
| SubLocation | `92` | Sağlayıcı tarafından belirlenen yönergelere göre, nesne verilerinin kaynaklandığı bir şehir içindeki konumu tanımlar. |
| ProvinceState | `95` | Sağlayıcı tarafından belirlenen yönergelere göre İl/Menşe Eyaleti tanımlar. |
| PrimaryLocationCode | `100` | Nesne verilerinin fikri mülkiyetinin oluşturulduğu ülkenin/birincil konumun kodunu belirtir, örneğin bir fotoğrafın çekildiği, bir olayın meydana geldiği. |
| PrimaryLocationName | `101` | Nesne verilerinin fikri mülkiyetinin oluşturulduğu ülkenin/birincil konumun tam, yayınlanabilir adını sağlar, sağlayıcının yönergelerine göre. |
| OriginalTransmissionReference | `103` | Sağlayıcının uygulamalarına göre orijinal iletimin konumunu temsil eden bir kod. |
| Headline | `105` | objectdata. içeriğinin özetini sağlayan yayınlanabilir bir giriş |
| Credit | `110` | Nesne verilerinin sağlayıcısını tanımlar, mutlaka sahibini/yaratıcısını değil. |
| Source | `115` | İçerik tedarik zincirinde rolü olan bir kişinin veya tarafın adı. Bu bir ajans, bir ajansın üyesi, bir birey veya bunların birleşimi olabilir. |
| CopyrightNotice | `116` | Gerekli telif hakkı bildirimini içerir. |
| Contact | `118` | Nesne verileri hakkında daha fazla arka plan bilgisi sağlayabilecek kişi veya kuruluşu tanımlar. |
| CaptionAbstract | `120` | Nesne verilerinin metinsel açıklaması, özellikle nesnenin metin olmadığı durumlarda kullanılır. |
| WriterEditor | `122` | Nesne verilerinin veya başlık/özet. 'nin yazılması, düzenlenmesi veya düzeltilmesinde yer alan kişinin adının tanımlanması |
| RasterizedCaption | `125` | Görüntü genişliği 460 piksel ve görüntü yüksekliği 128 piksel. Tarama yönü aşağıdan yukarıya, soldan sağa. |
| ImageType | `130` | 1'den 4'e kadar olan sayısal karakterler, tekli veya çoklu zarflardaki bir görüntüdeki bileşenlerin sayısını belirtir. |
| ImageOrientation | `131` | Görüntü alanının düzenini gösterir. |
| LanguageIdentifier | `135` | ISO 639:1988. 'nin 2 harfli kodlarına göre nesnenin başlıca ulusal dilini tanımlar. |
| AudioType | `150` | Ses türü. |
| AudioSamplingRate | `151` | Hertz (Hz) cinsinden örnekleme hızını temsil eden örnekleme hızı sayısal karakterleri. |
| AudioSamplingResolution | `152` | Her ses örneğindeki bit sayısı. |
| AudioDuration | `153` | Süre HHMMSS biçiminde, kaydedildiği hızda oynatıldığında ses nesnesi verilerinin çalışma süresini belirtir. |
| AudioOutcue | `154` | Sağlayıcı tarafından belirlenen yönergelere göre bir ses nesne verilerinin sonunun içeriğini tanımlar. |
| ObjDataPreviewFileFormat | `200` | ObjectData Preview. dosya biçimini temsil eden bir ikili sayı |
| ObjDataPreviewFileFormatVer | `201` | 2:200. 'de belirtilen ObjectData Önizleme Dosya Biçiminin belirli sürümünü temsil eden bir ikili sayı |
| ObjDataPreviewData | `202` | Nesne verileri önizlemesi. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Standards.Iptc](../../groupdocs.metadata.standards.iptc)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
