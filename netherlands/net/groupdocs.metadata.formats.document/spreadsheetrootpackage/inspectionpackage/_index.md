---
title: InspectionPackage
second_title: GroupDocs.Metadata voor .NET API-referentie
description: Haalt een metadatapakket op met inspectieresultaten voor het document. Het pakket bevat informatie over documentonderdelen die in sommige gevallen als metadata kunnen worden beschouwd.
type: docs
weight: 30
url: /nl/net/groupdocs.metadata.formats.document/spreadsheetrootpackage/inspectionpackage/
---
## SpreadsheetRootPackage.InspectionPackage property

Haalt een metadatapakket op met inspectieresultaten voor het document. Het pakket bevat informatie over documentonderdelen die in sommige gevallen als metadata kunnen worden beschouwd.

```csharp
public SpreadsheetInspectionPackage InspectionPackage { get; }
```

### Eigendoms-waarde

Een metadatapakket met inspectieresultaten voor het document.

### Opmerkingen

**Kom meer te weten**

* [Werken met metadata in Spreadsheets](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Voorbeelden

Dit codefragment laat zien hoe u een spreadsheetdocument inspecteert.

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

### Zie ook

* class [SpreadsheetInspectionPackage](../../spreadsheetinspectionpackage)
* class [SpreadsheetRootPackage](../../spreadsheetrootpackage)
* naamruimte [GroupDocs.Metadata.Formats.Document](../../spreadsheetrootpackage)
* montage [GroupDocs.Metadata](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Metadata.dll -->