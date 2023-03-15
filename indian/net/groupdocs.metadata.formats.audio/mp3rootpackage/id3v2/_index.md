---
title: ID3V2
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: ID3v2 मेटडेट टैग प्रप्त य सेट करत है
type: docs
weight: 30
url: /hi/net/groupdocs.metadata.formats.audio/mp3rootpackage/id3v2/
---
## MP3RootPackage.ID3V2 property

ID3v2 मेटाडेटा टैग प्राप्त या सेट करता है।

```csharp
public ID3V2Tag ID3V2 { get; set; }
```

### संपत्ति मूल्य

ऑडियो फ़ाइल से अनुलग्न ID3v2 मेटाडेटा टैग.

### उदाहरण

कोड नमूना दिखाता है कि MP3 फ़ाइल में ID3v2 टैग को कैसे अपडेट किया जाए।

```csharp
using (Metadata metadata = new Metadata(Constants.MP3WithID3V2))
{
    var root = metadata.GetRootPackage<MP3RootPackage>();

    if (root.ID3V2 == null)
    {
        root.ID3V2 = new ID3V2Tag();
    }

    root.ID3V2.Album = "test album";
    root.ID3V2.Artist = "test artist";
    root.ID3V2.Band = "test band";
    root.ID3V2.TrackNumber = "1";
    root.ID3V2.MusicalKey = "C#";
    root.ID3V2.Title = "code sample";
    root.ID3V2.Date = "2019";

    // ...

    metadata.Save(Constants.OutputMp3);
}
```

### यह सभी देखें

* class [ID3V2Tag](../../id3v2tag)
* class [MP3RootPackage](../../mp3rootpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Audio](../../mp3rootpackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->