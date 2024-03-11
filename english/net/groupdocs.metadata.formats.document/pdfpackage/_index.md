---
title: PdfPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents native metadata in a PDF document.
type: docs
weight: 1170
url: /net/groupdocs.metadata.formats.document/pdfpackage/
---
## PdfPackage class

Represents native metadata in a PDF document.

```csharp
public class PdfPackage : DocumentPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/pdfpackage/author) { get; set; } | Gets or sets the document author. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreatedDate](../../groupdocs.metadata.formats.document/pdfpackage/createddate) { get; set; } | Gets or sets the date of document creation. |
| [Creator](../../groupdocs.metadata.formats.document/pdfpackage/creator) { get; set; } | Gets the creator of the document. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.document/pdfpackage/keywords) { get; set; } | Gets or sets the keywords. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ModifiedDate](../../groupdocs.metadata.formats.document/pdfpackage/modifieddate) { get; set; } | Gets or sets the date of the last modification. |
| [Producer](../../groupdocs.metadata.formats.document/pdfpackage/producer) { get; set; } | Gets the document producer. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Subject](../../groupdocs.metadata.formats.document/pdfpackage/subject) { get; set; } | Gets or sets the subject of the document. |
| [Title](../../groupdocs.metadata.formats.document/pdfpackage/title) { get; set; } | Gets or sets the title of the document. |
| [TrappedFlag](../../groupdocs.metadata.formats.document/pdfpackage/trappedflag) { get; set; } | Gets or sets the trapped flag. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Removes all writable metadata properties from the package. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Removes all built-in metadata properties. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Removes all custom metadata properties. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Removes a writable metadata property by the specified name. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.document/pdfpackage/set)(string, string) | Adds or replaces the metadata property with the specified name. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in PDF documents](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Examples

This code snippet demonstrates how to update built-in metadata properties in a PDF document.

```csharp
using (Metadata metadata = new Metadata(Constants.InputPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedDate = DateTime.Now;
    root.DocumentProperties.Title = "test title";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputPdf);
}
```

### See Also

* class [DocumentPackage](../documentpackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
