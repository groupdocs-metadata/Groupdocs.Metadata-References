---
title: Metadata
second_title: .NET API Başvurusu için GroupDocs.Metadata
description: Yeni bir örneğini başlatır.Metadatagroupdocs.metadata/metadata sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

Yeni bir örneğini başlatır.[`Metadata`](../../metadata) sınıf.

```csharp
public Metadata(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosyanın tam adını içeren bir dize[`Metadata`](../../metadata) misal. |

### Notlar

**Daha fazla bilgi edin**

* [Yerel bir diskten yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Akıştan yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Belirli bir biçimde bir dosya yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Parola korumalı bir belge yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Örnekler

Bu örnek, bir dosyanın yerel diskten nasıl yükleneceğini gösterir.

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // Meta verileri buradan ayıklayın, düzenleyin veya kaldırın
}
```

### Ayrıca bakınız

* class [Metadata](../../metadata)
* ad alanı [GroupDocs.Metadata](../../metadata)
* toplantı [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

Yeni bir örneğini başlatır.[`Metadata`](../../metadata) sınıf.

```csharp
public Metadata(Stream document)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Yüklenecek belgeyi içeren bir akış. |

### Notlar

**Daha fazla bilgi edin**

* [Yerel bir diskten yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Akıştan yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Belirli bir biçimde bir dosya yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Parola korumalı bir belge yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Örnekler

Bu örnek, bir dosyanın bir akıştan nasıl yükleneceğini gösterir.

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // Meta verileri buradan ayıklayın, düzenleyin veya kaldırın
}
```

### Ayrıca bakınız

* class [Metadata](../../metadata)
* ad alanı [GroupDocs.Metadata](../../metadata)
* toplantı [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

Yeni bir örneğini başlatır.[`Metadata`](../../metadata) sınıf.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Oluşturulacak dosyanın tam adını içeren bir dize[`Metadata`](../../metadata) misal. |
| loadOptions | LoadOptions | Belge yüklerken kullanılacak ek seçenekler. |

### Notlar

**Daha fazla bilgi edin**

* [Yerel bir diskten yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Akıştan yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Belirli bir biçimde bir dosya yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Parola korumalı bir belge yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Örnekler

Bu örnek, parola korumalı bir belgenin nasıl yükleneceğini gösterir.

```csharp
// Parolayı belirtin
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // Meta verileri buradan ayıklayın, düzenleyin veya kaldırın
}
```

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* ad alanı [GroupDocs.Metadata](../../metadata)
* toplantı [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

Yeni bir örneğini başlatır.[`Metadata`](../../metadata) sınıf.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Yüklenecek belgeyi içeren bir akış. |
| loadOptions | LoadOptions | Belge yüklerken kullanılacak ek seçenekler. |

### Notlar

**Daha fazla bilgi edin**

* [Yerel bir diskten yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [Akıştan yükle](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [Belirli bir biçimde bir dosya yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [Parola korumalı bir belge yükleyin](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* ad alanı [GroupDocs.Metadata](../../metadata)
* toplantı [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
