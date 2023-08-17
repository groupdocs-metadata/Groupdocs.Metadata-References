---
title: CadPackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents CAD Computeraided design metadata.
type: docs
weight: 840
url: /net/groupdocs.metadata.formats.cad/cadpackage/
---
## CadPackage class

Represents CAD (Computer-aided design) metadata.

```csharp
public sealed class CadPackage : CustomPackage
```

## Properties

| Name | Description |
| --- | --- |
| [AcadVersion](../../groupdocs.metadata.formats.cad/cadpackage/acadversion) { get; } | Gets the AutoCAD drawing database version number. |
| [Author](../../groupdocs.metadata.formats.cad/cadpackage/author) { get; } | Gets the drawing author. |
| [Comments](../../groupdocs.metadata.formats.cad/cadpackage/comments) { get; } | Gets the user comments. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [CreatedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/createddatetime) { get; } | Gets the date and time when the drawing was created. |
| [CustomProperties](../../groupdocs.metadata.formats.cad/cadpackage/customproperties) { get; } | Gets the package containing custom metadata properties. |
| [Height](../../groupdocs.metadata.formats.cad/cadpackage/height) { get; } | Gets the drawing height. |
| [HyperlinkBase](../../groupdocs.metadata.formats.cad/cadpackage/hyperlinkbase) { get; } | Gets the hyperlink base. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Keywords](../../groupdocs.metadata.formats.cad/cadpackage/keywords) { get; } | Gets the keywords. |
| [LastSavedBy](../../groupdocs.metadata.formats.cad/cadpackage/lastsavedby) { get; } | Gets the name of the last editor. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [ModifiedDateTime](../../groupdocs.metadata.formats.cad/cadpackage/modifieddatetime) { get; } | Gets the date and time when the drawing was modified. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [RevisionNumber](../../groupdocs.metadata.formats.cad/cadpackage/revisionnumber) { get; } | Gets the revision number. |
| [Subject](../../groupdocs.metadata.formats.cad/cadpackage/subject) { get; } | Gets the subject. |
| [Title](../../groupdocs.metadata.formats.cad/cadpackage/title) { get; } | Gets the title. |
| [Width](../../groupdocs.metadata.formats.cad/cadpackage/width) { get; } | Gets the drawing width. |

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

* [Working with CAD metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+CAD+metadata)

### See Also

* class [CustomPackage](../../groupdocs.metadata.common/custompackage)
* namespace [GroupDocs.Metadata.Formats.Cad](../../groupdocs.metadata.formats.cad)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
