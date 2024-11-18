---
title: PDBHeader
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents metadata in a Mobi ebook.
type: docs
weight: 1570
url: /net/groupdocs.metadata.formats.ebook.mobi/pdbheader/
---
## PDBHeader class

Represents metadata in a Mobi e-book.

```csharp
public sealed class PDBHeader : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [AppInfoID](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/appinfoid) { get; set; } | Gets the app info ID. |
| [Attributes](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/attributes) { get; set; } | Gets the mobi attributes. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreationDate](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/creationdate) { get; set; } | Gets the creation date. |
| [Creator](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/creator) { get; set; } | Gets the creator. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [LastBackupDate](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/lastbackupdate) { get; set; } | Gets the last backup date. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ModificationDate](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/modificationdate) { get; set; } | Gets the modification date. |
| [ModificationNumber](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/modificationnumber) { get; set; } | Gets the modification number. |
| [Name](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/name) { get; set; } | Gets the Mobi e-book name. |
| [NextRecordList](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/nextrecordlist) { get; } |  |
| [NumRecords](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/numrecords) { get; } | Gets the num records. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [SortInfoID](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/sortinfoid) { get; set; } | Gets the sort info ID. |
| [Type](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/type) { get; set; } | Gets the type. |
| [UniqueIDSeed](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/uniqueidseed) { get; set; } | Gets the unique ID seed. |
| [Version](../../groupdocs.metadata.formats.ebook.mobi/pdbheader/version) { get; set; } | Gets the Mobi version. |

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

* [Working with metadata in Mobi E-Books](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Mobi+E-Books)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Ebook.Mobi](../../groupdocs.metadata.formats.ebook.mobi)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
