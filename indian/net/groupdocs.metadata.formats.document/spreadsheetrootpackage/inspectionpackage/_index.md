---
title: InspectionPackage
second_title: .NET API संदर्भ के लिए GroupDocs.Metadata
description: एक मेटडेट पैकेज प्रप्त करत है जसमें दस्तवेज़ के लए नरक्षण परणम हते हैं पैकेज में दस्तवेज़ के हस्सं के बरे में जनकर हत है जसे कुछ ममलं में मेटडेट मन ज सकत है
type: docs
weight: 30
url: /hi/net/groupdocs.metadata.formats.document/spreadsheetrootpackage/inspectionpackage/
---
## SpreadsheetRootPackage.InspectionPackage property

एक मेटाडेटा पैकेज प्राप्त करता है जिसमें दस्तावेज़ के लिए निरीक्षण परिणाम होते हैं। पैकेज में दस्तावेज़ के हिस्सों के बारे में जानकारी होती है जिसे कुछ मामलों में मेटाडेटा माना जा सकता है।

```csharp
public SpreadsheetInspectionPackage InspectionPackage { get; }
```

### संपत्ति मूल्य

एक मेटाडेटा पैकेज जिसमें दस्तावेज़ के निरीक्षण के परिणाम हैं।

### टिप्पणियों

**और अधिक जानें**

* [स्प्रेडशीट में मेटाडेटा के साथ काम करना](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### उदाहरण

यह कोड स्निपेट दिखाता है कि किसी स्प्रेडशीट दस्तावेज़ का निरीक्षण कैसे किया जाता है.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXls))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    if (root.InspectionPackage.Comments != null)
    {
        foreach (var comment in root.InspectionPackage.Comments)
        {
            Console.WriteLine(comment.Author);
            Console.WriteLine(comment.Text);
            Console.WriteLine(comment.SheetNumber);
            Console.WriteLine(comment.Row);
            Console.WriteLine(comment.Column);
        }
    }

    if (root.InspectionPackage.DigitalSignatures != null)
    {
        foreach (var signature in root.InspectionPackage.DigitalSignatures)
        {
            Console.WriteLine(signature.CertificateSubject);
            Console.WriteLine(signature.Comments);
            Console.WriteLine(signature.SignTime);

            // ...
        }
    }

    if (root.InspectionPackage.HiddenSheets != null)
    {
        foreach (var sheet in root.InspectionPackage.HiddenSheets)
        {
            Console.WriteLine(sheet.Name);
            Console.WriteLine(sheet.Number);
        }
    }
}
```

### यह सभी देखें

* class [SpreadsheetInspectionPackage](../../spreadsheetinspectionpackage)
* class [SpreadsheetRootPackage](../../spreadsheetrootpackage)
* नाम स्थान [GroupDocs.Metadata.Formats.Document](../../spreadsheetrootpackage)
* सभा [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->