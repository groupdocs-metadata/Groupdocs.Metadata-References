---
title: Comment
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक उपयगकर्त द्वर बनई गई ज़प संग्रह टप्पण क प्रप्त य सेट करत है
type: docs
weight: 10
url: /hi/net/groupdocs.metadata.formats.archive/zippackage/comment/
---
## ZipPackage.Comment property

एक उपयोगकर्ता द्वारा बनाई गई ज़िप संग्रह टिप्पणी को प्राप्त या सेट करता है।

```csharp
public string Comment { get; set; }
```

### संपत्ति मूल्य

यूजर का कमेंट।

### उदाहरण

निम्न कोड स्निपेट दिखाता है कि ज़िप संग्रह से उपयोगकर्ता टिप्पणी को कैसे हटाया जाए.

```csharp
using (Metadata metadata = new Metadata(Constants.InputZip))
{
    var root = metadata.GetRootPackage<ZipRootPackage>();

    root.ZipPackage.Comment = null;

    metadata.Save(Constants.OutputZip);
}
```

### यह सभी देखें

* class [ZipPackage](../../zippackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Archive](../../zippackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
