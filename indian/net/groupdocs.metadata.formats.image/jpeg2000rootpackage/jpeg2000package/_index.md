---
title: Jpeg2000Package
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: JPEG2000 देश मेटडेट पैकेज प्रप्त करत है
type: docs
weight: 20
url: /hi/net/groupdocs.metadata.formats.image/jpeg2000rootpackage/jpeg2000package/
---
## Jpeg2000RootPackage.Jpeg2000Package property

JPEG2000 देशी मेटाडेटा पैकेज प्राप्त करता है।

```csharp
public Jpeg2000Package Jpeg2000Package { get; }
```

### संपत्ति मूल्य

JPEG2000 नेटिव मेटाडेटा पैकेज.

### टिप्पणियों

**और अधिक जानें**

* [JPEG2000 छवियों में मेटाडेटा के साथ कार्य करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+JPEG2000+images)

### उदाहरण

यह कोड स्निपेट प्रदर्शित करता है कि JPEG2000 छवि टिप्पणियों को कैसे पढ़ा जाए.

```csharp
using (Metadata metadata = new Metadata(Constants.InputJpeg2000))
{
    var root = metadata.GetRootPackage<Jpeg2000RootPackage>();

    if (root.Jpeg2000Package.Comments != null)
    {
        foreach (var comment in root.Jpeg2000Package.Comments)
        {
            Console.WriteLine(comment);
        }
    }
}
```

### यह सभी देखें

* class [Jpeg2000Package](../../jpeg2000package)
* class [Jpeg2000RootPackage](../../jpeg2000rootpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Image](../../jpeg2000rootpackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->