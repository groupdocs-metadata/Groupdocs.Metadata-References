---
title: DiagramPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a native metadata package in a diagram format.
type: docs
weight: 890
url: /net/groupdocs.metadata.formats.document/diagrampackage/
---
## DiagramPackage class

Represents a native metadata package in a diagram format.

```csharp
public class DiagramPackage : DocumentPackage
```

## Properties

| Name | Description |
| --- | --- |
| [AlternateNames](../../groupdocs.metadata.formats.document/diagrampackage/alternatenames) { get; set; } | Gets or sets the alternate names for the document. Can be updated in VDX and VSX formats only. |
| [BuildNumberCreated](../../groupdocs.metadata.formats.document/diagrampackage/buildnumbercreated) { get; } | Gets the full build number of the instance used to create the document. |
| [BuildNumberEdited](../../groupdocs.metadata.formats.document/diagrampackage/buildnumberedited) { get; } | Gets the build number of the instance last used to edit the document. |
| [Category](../../groupdocs.metadata.formats.document/diagrampackage/category) { get; set; } | Gets or sets the descriptive text for the type of drawing, such as flowchart or office layout. This text can also be entered in the Microsoft Visio user interface in the Category box in the Properties dialog box. |
| [Company](../../groupdocs.metadata.formats.document/diagrampackage/company) { get; set; } | Gets or sets the user-entered information identifying the company creating the drawing or the company the drawing is being created for. Maximum length is 63 characters. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Creator](../../groupdocs.metadata.formats.document/diagrampackage/creator) { get; set; } | Gets or sets the person who created or last updated the file. The maximum length is 63 characters.. |
| [Description](../../groupdocs.metadata.formats.document/diagrampackage/description) { get; set; } | Gets or sets a descriptive text string for the document. Use this element to store important information about the document, such as its purpose, recent changes, or pending changes. The maximum is 191 characters. |
| [HyperlinkBase](../../groupdocs.metadata.formats.document/diagrampackage/hyperlinkbase) { get; set; } | Gets or sets the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). By default, a hyperlink path is relative to the current document unless a different path is specified in this element. Maximum length is 256 characters. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.document/diagrampackage/keywords) { get; set; } | Gets or sets a text string that identifies topics or other important information about the file, such as project name, client name, or version number. The maximum string length is 63 characters. |
| [Language](../../groupdocs.metadata.formats.document/diagrampackage/language) { get; set; } | Gets or sets the language of the document. Can be updated in VSD and VSDX formats only. |
| [Manager](../../groupdocs.metadata.formats.document/diagrampackage/manager) { get; set; } | Gets or sets a user-entered text string identifying the person in charge of the project or department. The maximum length is 63 characters. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PreviewPicture](../../groupdocs.metadata.formats.document/diagrampackage/previewpicture) { get; set; } | Gets or sets the preview picture. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Subject](../../groupdocs.metadata.formats.document/diagrampackage/subject) { get; set; } | Gets or sets a user-defined text string that describes the contents of the document. Maximum length is 63 characters. |
| [Template](../../groupdocs.metadata.formats.document/diagrampackage/template) { get; set; } | Gets or sets a string value specifying the file name of the template from which the document was created. |
| [TimeCreated](../../groupdocs.metadata.formats.document/diagrampackage/timecreated) { get; set; } | Gets or sets a date and time value indicating when the document was created. |
| [TimeEdited](../../groupdocs.metadata.formats.document/diagrampackage/timeedited) { get; } | Gets a date and time value indicating when the document was last edited. |
| [TimePrinted](../../groupdocs.metadata.formats.document/diagrampackage/timeprinted) { get; } | Gets a date and time value indicating when the document was last printed. |
| [TimeSaved](../../groupdocs.metadata.formats.document/diagrampackage/timesaved) { get; } | Gets a date and time value indicating when the document was last saved. |
| [Title](../../groupdocs.metadata.formats.document/diagrampackage/title) { get; set; } | Gets or sets a user-defined text string that serves as a descriptive title for the document. Maximum length is 63 characters. |

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
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set)(string, bool) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_2)(string, DateTime) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_1)(string, double) | Adds or replaces the metadata property with the specified name. |
| [Set](../../groupdocs.metadata.formats.document/diagrampackage/set#set_3)(string, string) | Adds or replaces the metadata property with the specified name. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with metadata in Diagrams](https://docs.groupdocs.com/display/metadatanet/Working+with+metadata+in+Diagrams)

### Examples

This code sample demonstrates how to extract built-in metadata properties from a diagram.

```csharp
using (Metadata metadata = new Metadata(Constants.InputVsdx))
{
    var root = metadata.GetRootPackage<DiagramRootPackage>();

    Console.WriteLine(root.DocumentProperties.Creator);
    Console.WriteLine(root.DocumentProperties.Company);
    Console.WriteLine(root.DocumentProperties.Keywords);
    Console.WriteLine(root.DocumentProperties.Language);
    Console.WriteLine(root.DocumentProperties.TimeCreated);
    Console.WriteLine(root.DocumentProperties.Category);

    // ... 
}
```

### See Also

* class [DocumentPackage](../documentpackage)
* namespace [GroupDocs.Metadata.Formats.Document](../../groupdocs.metadata.formats.document)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
