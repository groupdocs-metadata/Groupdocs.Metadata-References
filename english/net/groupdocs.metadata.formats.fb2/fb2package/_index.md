---
title: Fb2Package
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents metadata in a Fb2 ebook.
type: docs
weight: 1720
url: /net/groupdocs.metadata.formats.fb2/fb2package/
---
## Fb2Package class

Represents metadata in a Fb2 e-book.

```csharp
public sealed class Fb2Package : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CustomInfo](../../groupdocs.metadata.formats.fb2/fb2package/custominfo) { get; } | Some information about the document that is not provided in the rest of the description. This may be either just some information from the author or some information that may be useful to some FB2 software. |
| [DocumentInfo](../../groupdocs.metadata.formats.fb2/fb2package/documentinfo) { get; } | Description of information about a specific FB2.x document (creator(s), history, etc.). |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [PublishInfo](../../groupdocs.metadata.formats.fb2/fb2package/publishinfo) { get; } | Information about the paper (or other) publication on the basis of which the FB2.x document was created. It is not recommended to fill in data from an arbitrary publication if the source is unknown, except for the case when verification was carried out on it and the document was brought to the form of this publication. If the source is unknown, it is better to omit this element altogether. |
| [SrcTitleInfo](../../groupdocs.metadata.formats.fb2/fb2package/srctitleinfo) { get; } | Description of information about the work in the original language (not available for the original book). |
| [TitleInfo](../../groupdocs.metadata.formats.fb2/fb2package/titleinfo) { get; } | Description of information about the work (including translation, but excluding publication). |

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

### Remarks

**Learn more**

* [Working with metadata in Fb2 E-Books](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Fb2+E-Books)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Fb2](../../groupdocs.metadata.formats.fb2)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
