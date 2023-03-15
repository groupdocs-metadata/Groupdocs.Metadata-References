---
title: Metadata
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: क एक नय उदहरण प्ररंभ करत हैMetadatagroupdocs.metadata/metadata वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.metadata/metadata/metadata/
---
## Metadata(string) {#constructor_2}

का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../../metadata) वर्ग.

```csharp
public Metadata(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | एक स्ट्रिंग जिसमें फ़ाइल का पूरा नाम होता है जिससे a बनाना है[`Metadata`](../../metadata) उदाहरण। |

### टिप्पणियों

**और अधिक जानें**

* [स्थानीय डिस्क से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [एक धारा से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [एक विशिष्ट प्रारूप की फ़ाइल लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [पासवर्ड से सुरक्षित दस्तावेज़ लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### उदाहरण

यह उदाहरण दर्शाता है कि स्थानीय डिस्क से फ़ाइल को कैसे लोड किया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.InputOne))
{
    // यहां मेटाडेटा निकालें, संपादित करें या हटाएं
}
```

### यह सभी देखें

* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

---

## Metadata(Stream) {#constructor}

का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../../metadata) वर्ग.

```csharp
public Metadata(Stream document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | एक स्ट्रीम जिसमें लोड करने के लिए दस्तावेज़ होता है। |

### टिप्पणियों

**और अधिक जानें**

* [स्थानीय डिस्क से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [एक धारा से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [एक विशिष्ट प्रारूप की फ़ाइल लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [पासवर्ड से सुरक्षित दस्तावेज़ लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### उदाहरण

यह उदाहरण दर्शाता है कि स्ट्रीम से फ़ाइल कैसे लोड करें।

```csharp
using (Stream stream = File.Open(Constants.InputDoc, FileMode.Open, FileAccess.ReadWrite))
using (Metadata metadata = new Metadata(stream))
{
   // यहां मेटाडेटा निकालें, संपादित करें या हटाएं
}
```

### यह सभी देखें

* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

---

## Metadata(string, LoadOptions) {#constructor_3}

का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../../metadata) वर्ग.

```csharp
public Metadata(string filePath, LoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | एक स्ट्रिंग जिसमें फ़ाइल का पूरा नाम होता है जिससे a बनाना है[`Metadata`](../../metadata) उदाहरण। |
| loadOptions | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* [स्थानीय डिस्क से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [एक धारा से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [एक विशिष्ट प्रारूप की फ़ाइल लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [पासवर्ड से सुरक्षित दस्तावेज़ लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### उदाहरण

यह उदाहरण दर्शाता है कि पासवर्ड से सुरक्षित दस्तावेज़ को कैसे लोड किया जाए।

```csharp
// पासवर्ड निर्दिष्ट करें
var loadOptions = new LoadOptions
{
    Password = "123"
};

using (var metadata = new Metadata(Constants.ProtectedDocx, loadOptions))
{
    // यहां मेटाडेटा निकालें, संपादित करें या हटाएं
}
```

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

---

## Metadata(Stream, LoadOptions) {#constructor_1}

का एक नया उदाहरण प्रारंभ करता है[`Metadata`](../../metadata) वर्ग.

```csharp
public Metadata(Stream document, LoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Stream | एक स्ट्रीम जिसमें लोड करने के लिए दस्तावेज़ होता है। |
| loadOptions | LoadOptions | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### टिप्पणियों

**और अधिक जानें**

* [स्थानीय डिस्क से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+local+disk)
* [एक धारा से लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+from+a+stream)
* [एक विशिष्ट प्रारूप की फ़ाइल लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+file+of+a+specific+format)
* [पासवर्ड से सुरक्षित दस्तावेज़ लोड करें](https://docs.groupdocs.com/display/metadatanet/Load+a+password-protected+document)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.metadata.options/loadoptions)
* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
