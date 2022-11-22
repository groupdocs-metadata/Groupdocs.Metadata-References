---
title: WordProcessingInspectionPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Contains information about document parts that can be considered as metadata in some cases.
type: docs
weight: 1270
url: /net/groupdocs.metadata.formats.document/wordprocessinginspectionpackage/
---
## WordProcessingInspectionPackage class

Contains information about document parts that can be considered as metadata in some cases.

```csharp
public sealed class WordProcessingInspectionPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/comments) { get; } | Gets an array of the user comments. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DigitalSignatures](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/digitalsignatures) { get; } | Gets an array of digital signatures presented in the document. |
| [Fields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/fields) { get; } | Gets an array of document fields. |
| [HiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/hiddentext) { get; } | Gets an array of hidden text fragments extracted from the document. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Revisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/revisions) { get; } | Gets an array of digital signatures presented in the document. |

## Methods

| Name | Description |
| --- | --- |
| [AcceptAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/acceptallrevisions)() | Accepts all detected revisions in the document. |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [ClearComments](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearcomments)() | Removes all detected user comments from the document. |
| [ClearFields](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearfields)() | Removes all detected fields from the document. |
| [ClearHiddenText](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/clearhiddentext)() | Removes all hidden text fragments from the document. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [RejectAllRevisions](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/rejectallrevisions)() | Rejects all detected revisions in the document. |
| override [RemoveProperties](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| override [Sanitize](../../groupdocs.metadata.formats.document/wordprocessinginspectionpackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in WordProcessing documents](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Examples

This code sample shows how to update inspection properties in a WordProcessing document.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.InspectionPackage.ClearComments();
    root.InspectionPackage.AcceptAllRevisions();
    root.InspectionPackage.ClearFields();
    root.InspectionPackage.ClearHiddenText();

    metadata.Save(Constants.OutputDoc);
}
```

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
