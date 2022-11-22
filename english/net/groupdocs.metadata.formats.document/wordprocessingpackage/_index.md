---
title: WordProcessingPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a native metadata package in a word processing document.
type: docs
weight: 1280
url: /net/groupdocs.metadata.formats.document/wordprocessingpackage/
---
## WordProcessingPackage class

Represents a native metadata package in a word processing document.

```csharp
public class WordProcessingPackage : DocumentPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/wordprocessingpackage/author) { get; set; } | Gets or sets the document's author. |
| [BytesInDocument](../../groupdocs.metadata.formats.document/wordprocessingpackage/bytesindocument) { get; } | Gets an estimate of the number of bytes in the document. |
| [Category](../../groupdocs.metadata.formats.document/wordprocessingpackage/category) { get; set; } | Gets or sets the category. |
| [Comments](../../groupdocs.metadata.formats.document/wordprocessingpackage/comments) { get; set; } | Gets or sets the comments. |
| [Company](../../groupdocs.metadata.formats.document/wordprocessingpackage/company) { get; set; } | Gets or sets the company. |
| [ContentStatus](../../groupdocs.metadata.formats.document/wordprocessingpackage/contentstatus) { get; set; } | Gets or sets the content status. |
| [ContentType](../../groupdocs.metadata.formats.document/wordprocessingpackage/contenttype) { get; set; } | Gets or sets the content type of the document. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreatedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/createdtime) { get; set; } | Gets or sets the document created date. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/wordprocessingpackage/hyperlinkbase) { get; set; } | Gets or sets the hyperlink base. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.document/wordprocessingpackage/keywords) { get; set; } | Gets or sets the keywords. |
| [LastPrintedDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastprinteddate) { get; set; } | Gets or sets the last printed date. |
| [LastSavedBy](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedby) { get; set; } | Gets or sets the name of the last author. |
| [LastSavedTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/lastsavedtime) { get; set; } | Gets or sets the time of the last save. |
| [LinksUpToDate](../../groupdocs.metadata.formats.document/wordprocessingpackage/linksuptodate) { get; set; } | Gets or sets a value indicating whether the hyperlinks in the document are up-to-date. |
| [Manager](../../groupdocs.metadata.formats.document/wordprocessingpackage/manager) { get; set; } | Gets or sets the manager. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NameOfApplication](../../groupdocs.metadata.formats.document/wordprocessingpackage/nameofapplication) { get; } | Gets the name of the application. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RevisionNumber](../../groupdocs.metadata.formats.document/wordprocessingpackage/revisionnumber) { get; set; } | Gets or sets the revision number. |
| [Subject](../../groupdocs.metadata.formats.document/wordprocessingpackage/subject) { get; set; } | Gets or sets the subject. |
| [Template](../../groupdocs.metadata.formats.document/wordprocessingpackage/template) { get; set; } | Gets or sets the template. |
| [Title](../../groupdocs.metadata.formats.document/wordprocessingpackage/title) { get; set; } | Gets or sets the title of the document. |
| [TitlesOfParts](../../groupdocs.metadata.formats.document/wordprocessingpackage/titlesofparts) { get; } | Gets the titles of document parts. Read-only. |
| [TotalEditingTime](../../groupdocs.metadata.formats.document/wordprocessingpackage/totaleditingtime) { get; set; } | Gets or sets the total editing time in minutes. |
| [Version](../../groupdocs.metadata.formats.document/wordprocessingpackage/version) { get; } | Gets the version number of the application that created the document. |

## Methods

| Name | Description |
| --- | --- |
| [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.formats.document/documentpackage/clear)() | Removes all writable metadata properties from the package. |
| [ClearBuiltInProperties](../../groupdocs.metadata.formats.document/documentpackage/clearbuiltinproperties)() | Removes all built-in metadata properties. |
| [ClearCustomProperties](../../groupdocs.metadata.formats.document/documentpackage/clearcustomproperties)() | Removes all custom metadata properties. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [Remove](../../groupdocs.metadata.formats.document/documentpackage/remove)(string) | Removes a writable metadata property by the specified name. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set)(string, bool) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_3)(string, DateTime) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_1)(string, double) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_2)(string, int) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/wordprocessingpackage/set#set_4)(string, string) | Adds or replaces the metadata property with the specified name. |
| [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in WordProcessing documents](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+WordProcessing+documents)

### Examples

This code sample shows how to update built-in metadata properties in a WordProcessing document.

```csharp
using (Metadata metadata = new Metadata(Constants.InputDoc))
{
    var root = metadata.GetRootPackage<WordProcessingRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreatedTime = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Category = "test category";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputDoc);
}
```

### See Also

* class [DocumentPackage](../documentpackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
