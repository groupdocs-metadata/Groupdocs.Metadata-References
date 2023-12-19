---
title: ProjectManagementPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a native metadata package in a project management file.
type: docs
weight: 1180
url: /net/groupdocs.metadata.formats.document/projectmanagementpackage/
---
## ProjectManagementPackage class

Represents a native metadata package in a project management file.

```csharp
public sealed class ProjectManagementPackage : DocumentPackage
```

## Properties

| Name | Description |
| --- | --- |
| [Author](../../groupdocs.metadata.formats.document/projectmanagementpackage/author) { get; set; } | Gets or sets the author of the project. |
| [Category](../../groupdocs.metadata.formats.document/projectmanagementpackage/category) { get; set; } | Gets or sets the category. |
| [Comments](../../groupdocs.metadata.formats.document/projectmanagementpackage/comments) { get; set; } | Gets or sets the user comments. |
| [Company](../../groupdocs.metadata.formats.document/projectmanagementpackage/company) { get; set; } | Gets or sets the company. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreationDate](../../groupdocs.metadata.formats.document/projectmanagementpackage/creationdate) { get; set; } | Gets or sets the creation date. |
| [Guid](../../groupdocs.metadata.formats.document/projectmanagementpackage/guid) { get; set; } | Gets or sets the id of the project. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/projectmanagementpackage/hyperlinkbase) { get; set; } | Gets or sets the hyperlink base. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.document/projectmanagementpackage/keywords) { get; set; } | Gets or sets the keywords. |
| [LastAuthor](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastauthor) { get; set; } | Gets or sets the last author. |
| [LastPrinted](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastprinted) { get; set; } | Gets or sets the project's last print time. |
| [LastSaved](../../groupdocs.metadata.formats.document/projectmanagementpackage/lastsaved) { get; set; } | Gets or sets the date when the project was saved last time. |
| [Manager](../../groupdocs.metadata.formats.document/projectmanagementpackage/manager) { get; set; } | Gets or sets the project manager. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Revision](../../groupdocs.metadata.formats.document/projectmanagementpackage/revision) { get; set; } | Gets or sets the revision number. |
| [SaveVersion](../../groupdocs.metadata.formats.document/projectmanagementpackage/saveversion) { get; } | Gets the version of Microsoft Office Project from which a project file was saved. |
| [Subject](../../groupdocs.metadata.formats.document/projectmanagementpackage/subject) { get; set; } | Gets or sets the subject. |
| [Template](../../groupdocs.metadata.formats.document/projectmanagementpackage/template) { get; set; } | Gets or sets the template. |
| [Title](../../groupdocs.metadata.formats.document/projectmanagementpackage/title) { get; set; } | Gets or sets the title. |

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
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set)(string, bool) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_3)(string, DateTime) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_1)(string, double) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_2)(string, int) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/projectmanagementpackage/set#set_4)(string, string) | Adds or replaces the metadata property with the specified name. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in ProjectManagement formats](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+ProjectManagement+formats)

### Examples

This code sample demonstrates how to update built-in properties in a ProjectManagement document.

```csharp
using (Metadata metadata = new Metadata(Constants.InputMpp))
{
    var root = metadata.GetRootPackage<ProjectManagementRootPackage>();

    root.DocumentProperties.Author = "test author";
    root.DocumentProperties.CreationDate = DateTime.Now;
    root.DocumentProperties.Company = "GroupDocs";
    root.DocumentProperties.Comments = "test comment";
    root.DocumentProperties.Keywords = "metadata, built-in, update";

    // ... 

    metadata.Save(Constants.OutputMpp);
}
```

### See Also

* class [DocumentPackage](../documentpackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
