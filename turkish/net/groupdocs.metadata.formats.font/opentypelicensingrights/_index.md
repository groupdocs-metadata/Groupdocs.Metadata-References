---
title: OpenTypeLicensingRights
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Yazı tipi için yazı tipi gömme lisans haklarını belirtir.
type: docs
weight: 1480
url: /tr/net/groupdocs.metadata.formats.font/opentypelicensingrights/
---
## OpenTypeLicensingRights enumeration

Yazı tipi için yazı tipi gömme lisans haklarını belirtir.

```csharp
[Flags]
public enum OpenTypeLicensingRights : ushort
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| None | `0` | Tanımlanmamış lisans hakları. |
| UsagePermissionsMask | `F` | Kullanım izinleri maskesi. |
| InstallableEmbedding | `1` | Kurulabilir gömme. Yazı tipi gömülü olabilir ve uzak sistemlerde veya diğer kullanıcılar tarafından kullanılmak üzere kalıcı olarak kurulabilir. |
| RestrictedLicenseEmbedding | `2` | Sınırlı Lisans gömme. Yazı tipi, önce yasal sahibin açık izni alınmadan değiştirilmemeli, gömülmemeli veya değiştirilmemelidir. |
| PreviewAndPrintEmbedding | `4` | Önizleme ve Yazdırma gömme. Yazı tipi gömülü olabilir ve belgeyi görüntülemek veya yazdırmak amacıyla geçici olarak diğer sistemlere yüklenebilir. Önizleme ve Yazdır yazı tiplerini içeren belgeler “salt okunur” olarak açılmalıdır; belgeye hiçbir düzenleme uygulanamaz. |
| EditableEmbedding | `8` | Düzenlenebilir gömme. Yazı tipi katıştırılabilir ve diğer sistemlere geçici olarak yüklenebilir. Önizleme ve Yazdırma gömmede olduğu gibi, Düzenlenebilir yazı tiplerini içeren belgeler okumak için açılabilir. Ek olarak, gömülü yazı tipini kullanarak yeni metni biçimlendirme yeteneği de dahil olmak üzere düzenlemeye izin verilir ve değişiklikler kaydedilebilir. |
| NoSubsetting | `100` | Alt ayar yok. Bu bit ayarlandığında, gömme işleminden önce yazı tipinin alt kümesi oluşturulamayabilir. 0 ila 3 bitleri ve 9 bitlerinde belirtilen diğer gömme kısıtlamaları da geçerlidir. |
| BitmapEmbeddingOnly | `200` | Yalnızca bitmap gömme. Bu bit ayarlandığında, yalnızca yazı tipinde bulunan bitmapler gömülebilir. Hiçbir anahat verisi gömülemez. Yazı tipinde kullanılabilir bit eşlem yoksa, yazı tipi gömülemez olarak kabul edilir ve katıştırma hizmetleri başarısız olur. 0-3 ve 8 bitlerinde belirtilen diğer yerleştirme kısıtlamaları da geçerlidir. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Formats.Font](../../groupdocs.metadata.formats.font)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->