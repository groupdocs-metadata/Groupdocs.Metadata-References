---
title: GeneratePreview
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: नर्दष्ट पृष्ठं के लए पूर्ववलकन चत्र बनत है
type: docs
weight: 60
url: /hi/net/groupdocs.metadata/metadata/generatepreview/
---
## Metadata.GeneratePreview method

निर्दिष्ट पृष्ठों के लिए पूर्वावलोकन चित्र बनाता है।

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| previewOptions | PreviewOptions | पूर्वावलोकन पीढ़ी के लिए विकल्पों का एक सेट। |

### टिप्पणियों

**और अधिक जानें**

* [दस्तावेज़ पूर्वावलोकन उत्पन्न करें](https://docs.groupdocs.com/display/metadatanet/Generate+document+preview)

### उदाहरण

यह कोड स्निपेट प्रदर्शित करता है कि दस्तावेज़ पृष्ठों के लिए छवि पूर्वावलोकन कैसे बनाया जाता है.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDocx))
{
    PreviewOptions previewOptions = new PreviewOptions(pageNumber => File.Create($"{Constants.OutputPath}\\result_{pageNumber}.png"));
    previewOptions.PreviewFormat = PreviewOptions.PreviewFormats.PNG;
    previewOptions.PageNumbers = new int[] { 1 };

    metadata.GeneratePreview(previewOptions);
}
```

### यह सभी देखें

* class [PreviewOptions](../../../groupdocs.metadata.options/previewoptions)
* class [Metadata](../../metadata)
* नाम स्थान [GroupDocs.Metadata](../../metadata)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->
