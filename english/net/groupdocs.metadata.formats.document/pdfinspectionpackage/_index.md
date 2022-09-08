---
title: PdfInspectionPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Contains information about PDF document parts that can be considered as metadata in some cases.
type: docs
weight: 1010
url: /net/groupdocs.metadata.formats.document/pdfinspectionpackage/
---
## PdfInspectionPackage class

Contains information about PDF document parts that can be considered as metadata in some cases.

```csharp
public sealed class PdfInspectionPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Annotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/annotations) { get; } | Gets an array of the annotations. |
| [Attachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/attachments) { get; } | Gets an array of the attachments. |
| [Bookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/bookmarks) { get; } | Gets an array of the bookmarks. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/digitalsignatures) { get; } | Gets an array of the digital signatures. |
| [Fields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/fields) { get; } | Gets an array of the form fields. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [ClearAnnotations](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearannotations)() | Removes all detected annotations from the document. |
| [ClearAttachments](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearattachments)() | Removes all detected attachments from the document. |
| [ClearBookmarks](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearbookmarks)() | Removes all detected bookmarks from the document. |
| [ClearDigitalSignatures](../../groupdocs.metadata.formats.document/pdfinspectionpackage/cleardigitalsignatures)() | Removes all detected digital signatures from the document. |
| [ClearFields](../../groupdocs.metadata.formats.document/pdfinspectionpackage/clearfields)() | Removes all detected form fields from the document. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/pdfinspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| override [Sanitize](../../groupdocs.metadata.formats.document/pdfinspectionpackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in PDF documents](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+PDF+documents)

### Examples

This code sample demonstrates how to remove the inspection properties in a PDF document.

```csharp
using (Metadata metadata = new Metadata(Constants.SignedPdf))
{
    var root = metadata.GetRootPackage<PdfRootPackage>();

    root.InspectionPackage.ClearAnnotations();
    root.InspectionPackage.ClearAttachments();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearBookmarks();
    root.InspectionPackage.ClearDigitalSignatures();

    metadata.Save(Constants.OutputPdf);
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
