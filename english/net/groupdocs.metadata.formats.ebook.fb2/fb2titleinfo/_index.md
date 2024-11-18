---
title: Fb2TitleInfo
second_title: GroupDocs.Metadata for .NET API Reference
description: Description of information about the work including translation but excluding publication.
type: docs
weight: 1520
url: /net/groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/
---
## Fb2TitleInfo class

Description of information about the work (including translation, but excluding publication).

```csharp
public class Fb2TitleInfo : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Authors](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/authors) { get; } | Information about the author of the book |
| [BookTitle](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/booktitle) { get; } | The title of the book. It can either match the book title (book-name) or differ (for example, when there are several works under one cover). |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Coverpage](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/coverpage) { get; } | Contains a link to a graphic image of the book cover. |
| [Date](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/date) { get; } | Date |
| [Genres](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/genres) { get; } | Describes the genre of the book. It is used to place the book in the library rubricator, for this reason the list of possible genres is strictly defined. It is allowed to specify several genres. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/keywords) { get; } | List of keywords for the book. Intended for use by search engines. |
| [Lang](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/lang) { get; } | Language of the book (work) |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Sequence](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/sequence) { get; } | The series of publications that the book belongs to and the number in the series. |
| [SrcLang](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/srclang) { get; } | Original language (for translations). |
| [Translators](../../groupdocs.metadata.formats.ebook.fb2/fb2titleinfo/translators) { get; } | Information about the author of the book |

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
