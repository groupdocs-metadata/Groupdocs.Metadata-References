---
title: XmpDublinCorePackage
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the Dublin Core scheme.
type: docs
weight: 4590
url: /net/groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/
---
## XmpDublinCorePackage class

Represents the Dublin Core scheme.

```csharp
public sealed class XmpDublinCorePackage : XmpPackage
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpDublinCorePackage](xmpdublincorepackage)() | Initializes a new instance of the [`XmpDublinCorePackage`](../xmpdublincorepackage) class. |

## Properties

| Name | Description |
| --- | --- |
| [Contributors](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/contributors) { get; set; } | Gets or sets an array of the contributors. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Coverage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/coverage) { get; set; } | Gets or sets the extent or scope of the resource. |
| [Creators](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/creators) { get; set; } | Gets or sets an array of the creators. |
| [Dates](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/dates) { get; set; } | Gets or sets an array of dates associated with an event in the life cycle of the resource. |
| [Descriptions](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/descriptions) { get; set; } | Gets or sets an array of textual descriptions of the content of the resource, given in various languages. |
| [Format](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/format) { get; set; } | Gets or sets the MIME type of the resource. |
| [Identifier](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/identifier) { get; set; } | Gets or sets a string value representing an unambiguous reference to the resource within a given context. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Languages](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/languages) { get; set; } | Gets or sets an array of languages used in the content of the resource. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [NamespaceUri](../../groupdocs.metadata.standards.xmp/xmppackage/namespaceuri) { get; } | Gets the namespace URI. |
| [Prefix](../../groupdocs.metadata.standards.xmp/xmppackage/prefix) { get; } | Gets the xmlns prefix. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Publishers](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/publishers) { get; set; } | Gets or sets an array of publishers made the resource available. |
| [Relations](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/relations) { get; set; } | Gets or sets an array of the related resources. |
| [Rights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/rights) { get; set; } | Gets or sets an array of the informal rights statements, given in various languages. |
| [Source](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/source) { get; set; } | Gets or sets the related resource from which the described resource is derived. |
| [Subjects](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/subjects) { get; set; } | Gets or sets an array of descriptive phrases or keywords that specify the content of the resource. |
| [Titles](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/titles) { get; set; } | Gets or sets the title or name of the resource, given in various languages. |
| [Types](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/types) { get; set; } | Gets or sets an array of string values representing the nature or genre of the resource. |
| [XmlNamespace](../../groupdocs.metadata.standards.xmp/xmppackage/xmlnamespace) { get; } | Gets the XML namespace. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Clear](../../groupdocs.metadata.standards.xmp/xmppackage/clear)() | Removes all XMP properties. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmppackage/getxmprepresentation)() | Converts the XMP value to the XML representation. |
| [Remove](../../groupdocs.metadata.standards.xmp/xmppackage/remove)(string) | Removes the property with the specified name. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, bool) | Sets boolean property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, DateTime) | Sets DateTime property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, double) | Sets double property. |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, int) | Sets integer property. |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, string) | Sets string property. |
| override [Set](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/set#set_2)(string, XmpArray) | Sets the value inherited from [`XmpArray`](../../groupdocs.metadata.standards.xmp/xmparray) . |
| virtual [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpComplexType) | Sets the value inherited from [`XmpComplexType`](../../groupdocs.metadata.standards.xmp/xmpcomplextype) . |
| [Set](../../groupdocs.metadata.standards.xmp/xmppackage/set)(string, XmpValueBase) | Sets the value inherited from [`XmpValueBase`](../../groupdocs.metadata.standards.xmp/xmpvaluebase) . |
| [SetContributor](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcontributor)(string) | Sets a single contributor of the resource. |
| [SetCreator](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setcreator)(string) | Sets a single creator of the resource. |
| [SetDate](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdate)(DateTime) | Sets a single date associated with the resource. |
| [SetDescription](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setdescription)(string) | Sets the resource description, given in a single laguage. |
| [SetLanguage](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setlanguage)(string) | Sets a single language associated with the resource. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| [SetPublisher](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setpublisher)(string) | Sets a single publisher of the resource. |
| [SetRelation](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrelation)(string) | Sets a single related resource. |
| [SetRights](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setrights)(string) | Sets the resource rights, given in a single laguage. |
| [SetSubject](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/setsubject)(string) | Sets a single subject of the resource. |
| [SetTitle](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settitle)(string) | Sets the resource title, given in a single laguage. |
| [SetType](../../groupdocs.metadata.standards.xmp.schemes/xmpdublincorepackage/settype)(string) | Sets a single type of the resource. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

For more information see: http://dublincore.org/documents/usageguide/elements.shtml.

### See Also

* class [XmpPackage](../../groupdocs.metadata.standards.xmp/xmppackage)
* namespace [GroupDocs.Metadata.Standards.Xmp.Schemes](../../groupdocs.metadata.standards.xmp.schemes)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
