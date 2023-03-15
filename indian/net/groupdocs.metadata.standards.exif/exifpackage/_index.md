---
title: ExifPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक EXIF मेटडेट पैकेज एक्सचेंजेबल इमेज फइल फर्मेट क प्रतनधत्व करत है
type: docs
weight: 2790
url: /hi/net/groupdocs.metadata.standards.exif/exifpackage/
---
## ExifPackage class

एक EXIF मेटाडेटा पैकेज (एक्सचेंजेबल इमेज फाइल फॉर्मेट) का प्रतिनिधित्व करता है।

```csharp
public class ExifPackage : ExifDictionaryBasePackage
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ExifPackage](exifpackage)() | का एक नया उदाहरण प्रारंभ करता है[`ExifPackage`](../exifpackage) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Artist](../../groupdocs.metadata.standards.exif/exifpackage/artist) { get; set; } | कैमरा मालिक, फोटोग्राफर या छवि निर्माता का नाम प्राप्त या सेट करता है। |
| [Copyright](../../groupdocs.metadata.standards.exif/exifpackage/copyright) { get; set; } | कॉपीराइट नोटिस प्राप्त या सेट करता है। |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | मेटाडेटा गुणों की संख्या प्राप्त करता है। |
| [DateTime](../../groupdocs.metadata.standards.exif/exifpackage/datetime) { get; set; } | छवि निर्माण की तिथि और समय प्राप्त या सेट करता है। EXIF मानक में, यह वह तिथि और समय है जब फ़ाइल बदली गई थी। |
| [ExifIfdPackage](../../groupdocs.metadata.standards.exif/exifpackage/exififdpackage) { get; } | EXIF IFD डेटा प्राप्त करता है। |
| [GpsPackage](../../groupdocs.metadata.standards.exif/exifpackage/gpspackage) { get; } | जीपीएस डेटा प्राप्त करता है। |
| [ImageDescription](../../groupdocs.metadata.standards.exif/exifpackage/imagedescription) { get; set; } | छवि का शीर्षक देते हुए एक वर्ण स्ट्रिंग प्राप्त या सेट करता है। यह "1988 कंपनी पिकनिक" या इसी तरह की टिप्पणी हो सकती है। |
| [ImageLength](../../groupdocs.metadata.standards.exif/exifpackage/imagelength) { get; set; } | छवि डेटा की पंक्तियों की संख्या प्राप्त या सेट करता है। |
| [ImageWidth](../../groupdocs.metadata.standards.exif/exifpackage/imagewidth) { get; set; } | प्रति पंक्ति पिक्सेल की संख्या के बराबर छवि डेटा के स्तंभों की संख्या प्राप्त या सेट करता है। |
| [Item](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/item) { get; } | निर्दिष्ट आईडी के साथ TIFF टैग प्राप्त करता है। (2 indexers) |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | मेटाडेटा गुण नामों का संग्रह प्राप्त करता है. |
| [Make](../../groupdocs.metadata.standards.exif/exifpackage/make) { get; set; } | रिकॉर्डिंग उपकरण के निर्माता को प्राप्त या सेट करता है। यह डीएससी, स्कैनर, वीडियो डिजिटाइज़र या छवि उत्पन्न करने वाले अन्य उपकरण का निर्माता है। |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | मेटाडेटा प्रकार प्राप्त करता है। |
| [Model](../../groupdocs.metadata.standards.exif/exifpackage/model) { get; set; } | उपकरण का मॉडल नाम या मॉडल संख्या प्राप्त या सेट करता है। यह छवि उत्पन्न करने वाले DSC, स्कैनर, वीडियो डिजिटाइज़र या अन्य उपकरण का मॉडल नाम या संख्या है। |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | वर्णनकर्ताओं का एक संग्रह प्राप्त करता है जिसमें GroupDocs.Metadata खोज इंजन के माध्यम से पहुंच योग्य गुणों के बारे में जानकारी होती है। |
| [Software](../../groupdocs.metadata.standards.exif/exifpackage/software) { get; set; } | छवि उत्पन्न करने के लिए उपयोग किए जाने वाले कैमरे या छवि इनपुट डिवाइस के सॉफ़्टवेयर या फ़र्मवेयर का नाम और संस्करण प्राप्त या सेट करता है। |
| [Thumbnail](../../groupdocs.metadata.standards.exif/exifpackage/thumbnail) { get; } | बाइट्स की एक सरणी के रूप में प्रस्तुत छवि थंबनेल प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को जोड़ता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Clear](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/clear)() | पैकेज में संग्रहीत सभी टीआईएफएफ टैग हटा देता है। |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | निर्धारित करता है कि पैकेज में निर्दिष्ट नाम के साथ मेटाडेटा गुण है या नहीं। |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को संतुष्ट करने वाले मेटाडेटा गुणों को ढूँढता है। खोज पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करती है। |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से पुनरावृति करता है। |
| [Remove](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/remove)(TiffTagID) | निर्दिष्ट आईडी के साथ संपत्ति को हटाता है। |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | निर्दिष्ट विधेय को पूरा करने वाले मेटाडेटा गुणों को हटाता है। |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | पैकेज से लिखने योग्य मेटाडेटा गुणों को हटाता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |
| [Set](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/set)(TiffTag) | निर्दिष्ट टैग जोड़ता या प्रतिस्थापित करता है। |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | निर्दिष्ट विधेय को संतुष्ट करने वाले ज्ञात मेटाडेटा गुणों को सेट करता है। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। यह विधि एक संयोजन है[`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) और[`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties) यदि कोई मौजूदा संपत्ति विधेय को संतुष्ट करती है तो उसका मान अपडेट किया जाता है। यदि पैकेज में कोई ज्ञात संपत्ति गायब है जो विधेय को संतुष्ट करती है तो इसे पैकेज में जोड़ा जाता है। |
| [ToList](../../groupdocs.metadata.standards.exif/exifdictionarybasepackage/tolist)() | पैकेज से एक सूची बनाता है। |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | अद्यतन ज्ञात मेटाडेटा गुण निर्दिष्ट विधेय को संतुष्ट करते हैं। ऑपरेशन पुनरावर्ती है इसलिए यह सभी नेस्टेड पैकेजों को भी प्रभावित करता है। |

### टिप्पणियों

**और अधिक जानें**

* [EXIF मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+EXIF+metadata)

### उदाहरण

यह कोड नमूना प्रदर्शित करता है कि सामान्य EXIF गुणों को कैसे अपडेट किया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg))
{
    IExif root = metadata.GetRootPackage() as IExif;
    if (root != null)
    {
        // EXIF पैकेज सेट करें यदि यह गायब है
        if (root.ExifPackage == null)
        {
            root.ExifPackage = new ExifPackage();
        }

        root.ExifPackage.Copyright = "Copyright (C) 2011-2022 GroupDocs. All Rights Reserved.";
        root.ExifPackage.ImageDescription = "test image";
        root.ExifPackage.Software = "GroupDocs.Metadata";

        // ...

        root.ExifPackage.ExifIfdPackage.BodySerialNumber = "test";
        root.ExifPackage.ExifIfdPackage.CameraOwnerName = "GroupDocs";
        root.ExifPackage.ExifIfdPackage.UserComment = "test comment";

        // ...

        metadata.Save(Constants.OutputJpeg);
    }
}
```

### यह सभी देखें

* class [ExifDictionaryBasePackage](../exifdictionarybasepackage)
* नाम स्थान [GroupDocs.Metadata.Standards.Exif](../../groupdocs.metadata.standards.exif)
* सभा [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
