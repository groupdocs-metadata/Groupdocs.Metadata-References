---
title: Set
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: नर्दष्ट टैग जड़त य प्रतस्थपत करत है
type: docs
weight: 40
url: /hi/net/groupdocs.metadata.standards.exif/exifdictionarybasepackage/set/
---
## ExifDictionaryBasePackage.Set method

निर्दिष्ट टैग जोड़ता या प्रतिस्थापित करता है।

```csharp
public void Set(TiffTag tag)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tag | TiffTag | सेट करने के लिए टैग। |

### उदाहरण

यह कोड नमूना प्रदर्शित करता है कि एक EXIF पैकेज में एक कस्टम टैग कैसे जोड़ा जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.TiffWithExif))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // EXIF पैकेज सेट करें यदि यह गायब है
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        // एक ज्ञात संपत्ति जोड़ें
        root.ExifPackage.Set(new TiffAsciiTag(TiffTagID.Artist, "test artist"));

        // पूरी तरह से कस्टम संपत्ति जोड़ें (जो EXIF विनिर्देश में वर्णित नहीं है)।
        // कृपया ध्यान दें कि चुनी गई आईडी कुछ तृतीय पक्ष टूल द्वारा उपयोग की जाने वाली आईडी के साथ मिल सकती है।
        root.ExifPackage.Set(new TiffAsciiTag((TiffTagID)65523, "custom"));

        metadata.Save(Constants.OutputTiff);
    }
}
```

### यह सभी देखें

* class [TiffTag](../../../groupdocs.metadata.formats.image/tifftag)
* class [ExifDictionaryBasePackage](../../exifdictionarybasepackage)
* नाम स्थान [GroupDocs.Metadata.Standards.Exif](../../exifdictionarybasepackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->