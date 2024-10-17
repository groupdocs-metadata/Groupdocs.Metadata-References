---
title: Fb2PublishInfo
second_title: GroupDocs.Metadata for .NET API Reference
description: Information about the paper or other publication on the basis of which the FB2.x document was created. It is not recommended to fill in data from an arbitrary publication if the source is unknown except for the case when verification was carried out on it and the document was brought to the form of this publication. If the source is unknown it is better to omit this element altogether.
type: docs
weight: 1520
url: /net/groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/
---
## Fb2PublishInfo class

Information about the paper (or other) publication on the basis of which the FB2.x document was created. It is not recommended to fill in data from an arbitrary publication if the source is unknown, except for the case when verification was carried out on it and the document was brought to the form of this publication. If the source is unknown, it is better to omit this element altogether.

```csharp
public class Fb2PublishInfo : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [BookName](../../groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/bookname) { get; } | The title of the original (paper) book. |
| [City](../../groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/city) { get; } | City, place of publication of the original (paper) book. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Isbn](../../groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/isbn) { get; } | ISBN of the original (paper) book. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Publisher](../../groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/publisher) { get; } | The title of the original (paper) book. |
| [Sequence](../../groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/sequence) { get; } | The series of publications that the book belongs to and the number in the series. |
| [Year](../../groupdocs.metadata.formats.ebook.fb2/fb2publishinfo/year) { get; } | Year of publication of the original (paper) book. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Ebook.Fb2](../../groupdocs.metadata.formats.ebook.fb2)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
