---
title: ImageResourcePackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: फटशप इमेज रसर्स मेटडेट पैकेज प्रप्त करत है इमेज रसर्स ब्लक फटशप नेटव फइल फर्मेट क मूल बल्डंग यूनट हैं
type: docs
weight: 20
url: /hi/net/groupdocs.metadata.formats.image/psdrootpackage/imageresourcepackage/
---
## PsdRootPackage.ImageResourcePackage property

फोटोशॉप इमेज रिसोर्स मेटाडेटा पैकेज प्राप्त करता है। इमेज रिसोर्स ब्लॉक फोटोशॉप नेटिव फाइल फॉर्मेट की मूल बिल्डिंग यूनिट हैं।

```csharp
public ImageResourcePackage ImageResourcePackage { get; }
```

### संपत्ति मूल्य

छवि संसाधन मेटाडेटा पैकेज.

### टिप्पणियों

**और अधिक जानें**

* [PSD छवियों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PSD+images)

### उदाहरण

नीचे दिया गया कोड नमूना दिखाता है कि कैसे एक PSD छवि से छवि संसाधन ब्लॉक (फ़ोटोशॉप फ़ाइल प्रारूप के बिल्डिंग ब्लॉक) को निकाला जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.PsdWithIrb))
{
    var root = metadata.GetRootPackage<PsdRootPackage>();

    if (root.ImageResourcePackage != null)
    {
        foreach (var block in root.ImageResourcePackage.ToList())
        {
            Console.WriteLine(block.Signature);
            Console.WriteLine(block.ID);
            Console.WriteLine(block.Name);
            Console.WriteLine(block.Data);
        }
    }
}
```

### यह सभी देखें

* class [ImageResourcePackage](../../imageresourcepackage)
* class [PsdRootPackage](../../psdrootpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Image](../../psdrootpackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
