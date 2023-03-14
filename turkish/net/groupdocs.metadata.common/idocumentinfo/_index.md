---
title: IDocumentInfo
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Yüklenen bir belge hakkında genel bilgiler sağlar.
type: docs
weight: 90
url: /tr/net/groupdocs.metadata.common/idocumentinfo/
---
## IDocumentInfo interface

Yüklenen bir belge hakkında genel bilgiler sağlar.

```csharp
public interface IDocumentInfo
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FileType](../../groupdocs.metadata.common/idocumentinfo/filetype) { get; } | Yüklenen belgenin dosya türünü alır. |
| [IsEncrypted](../../groupdocs.metadata.common/idocumentinfo/isencrypted) { get; } | Belgenin şifrelenip şifrelenmediğini ve açmak için parola gerektirip gerektirmediğini gösteren bir değer alır. |
| [PageCount](../../groupdocs.metadata.common/idocumentinfo/pagecount) { get; } | Yüklenen belgedeki sayfa sayısını (slaytlar, çalışma sayfaları vb.) alır. |
| [Pages](../../groupdocs.metadata.common/idocumentinfo/pages) { get; } | Belge sayfaları (slaytlar, çalışma sayfaları vb.) hakkında ortak bilgileri temsil eden nesnelerin bir koleksiyonunu alır. |
| [Size](../../groupdocs.metadata.common/idocumentinfo/size) { get; } | Yüklenen belgenin boyutunu bayt cinsinden alır. |

### Notlar

**Daha fazla bilgi edin**

* [Belge bilgilerini al](https://docs.groupdocs.com/display/metadatanet/Get+document+info)

### Örnekler

Bu örnek, temel biçim bilgilerinin bir dosyadan nasıl çıkarılacağını gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    if (metadata.FileFormat != FileFormat.Unknown)
    {
        IDocumentInfo info = metadata.GetDocumentInfo();

        Console.WriteLine("File format: {0}", info.FileType.FileFormat);
        Console.WriteLine("File extension: {0}", info.FileType.Extension);
        Console.WriteLine("MIME Type: {0}", info.FileType.MimeType);
        Console.WriteLine("Number of pages: {0}", info.PageCount);
        Console.WriteLine("Document size: {0} bytes", info.Size);
        Console.WriteLine("Is document encrypted: {0}", info.IsEncrypted);
    }
}
```

### Ayrıca bakınız

* ad alanı [GroupDocs.Metadata.Common](../../groupdocs.metadata.common)
* toplantı [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->