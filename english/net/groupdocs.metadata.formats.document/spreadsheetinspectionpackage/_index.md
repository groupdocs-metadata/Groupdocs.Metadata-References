---
title: SpreadsheetInspectionPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Contains information about spreadsheet parts that can be considered as metadata in some cases.
type: docs
weight: 1230
url: /net/groupdocs.metadata.formats.document/spreadsheetinspectionpackage/
---
## SpreadsheetInspectionPackage class

Contains information about spreadsheet parts that can be considered as metadata in some cases.

```csharp
public sealed class SpreadsheetInspectionPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/comments) { get; } | Gets an array of the user comments. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/digitalsignatures) { get; } | Gets an array of digital signatures presented in the document. |
| [HiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/hiddensheets) { get; } | Gets an array of the hidden sheets. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [ClearComments](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearcomments)() | Removes all detected user comments from the spreadsheet. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/cleardigitalsignatures)() | Removes all detected digital signatures from the spreadsheet. |
| [ClearHiddenSheets](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/clearhiddensheets)() | Removes all detected hidden sheets from the spreadsheet. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| override [Sanitize](../../groupdocs.metadata.formats.document/spreadsheetinspectionpackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in Spreadsheets](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Spreadsheets)

### Examples

This code sample shows hot to remove inspection properties from a spreadsheet.

```csharp
using (Metadata metadata = new Metadata(Constants.InputXlsx))
{
    var root = metadata.GetRootPackage<SpreadsheetRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.ClearDigitalSignatures();
    root.InspectionPackage.ClearHiddenSheets();

    metadata.Save(Constants.OutputXlsx);
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
