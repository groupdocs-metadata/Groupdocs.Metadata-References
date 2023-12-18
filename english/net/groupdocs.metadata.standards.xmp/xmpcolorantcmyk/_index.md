---
title: XmpColorantCmyk
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents the CMYK Colorant.
type: docs
weight: 4300
url: /net/groupdocs.metadata.standards.xmp/xmpcolorantcmyk/
---
## XmpColorantCmyk class

Represents the CMYK Colorant.

```csharp
public sealed class XmpColorantCmyk : XmpColorantBase
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpColorantCmyk](xmpcolorantcmyk#constructor)() | Initializes a new instance of the [`XmpColorantCmyk`](../xmpcolorantcmyk) class. |
| [XmpColorantCmyk](xmpcolorantcmyk#constructor_1)(double, double, double, double) | Initializes a new instance of the [`XmpColorantCmyk`](../xmpcolorantcmyk) class. |

## Properties

| Name | Description |
| --- | --- |
| [Black](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/black) { get; set; } | Gets or sets the black component. |
| [ColorType](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/colortype) { get; set; } | Gets or sets the type of color. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Cyan](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/cyan) { get; set; } | Gets or sets the cyan component. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [Magenta](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/magenta) { get; set; } | Gets or sets the magenta component. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [Mode](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/mode) { get; } | Gets the colour space in which the colour is defined. One of: CMYK, RGB, LAB. |
| [NamespaceUris](../../groupdocs.metadata.standards.xmp/xmpcomplextype/namespaceuris) { get; } | Gets the namespace URIs that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [Prefixes](../../groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes) { get; } | Gets the namespace prefixes that are used in the [`XmpComplexType`](../xmpcomplextype) instance. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [SwatchName](../../groupdocs.metadata.standards.xmp/xmpcolorantbase/swatchname) { get; set; } | Gets or sets the name of the swatch. |
| [Yellow](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/yellow) { get; set; } | Gets or sets the yellow component. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [GetNamespaceUri](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getnamespaceuri)(string) | Gets the namespace URI associated with the specified prefix. |
| override [GetXmpRepresentation](../../groupdocs.metadata.standards.xmp/xmpcomplextype/getxmprepresentation)() | Returns string contained value in XMP format. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| override [ToString](../../groupdocs.metadata.standards.xmp/xmpcomplextype/tostring)() | Returns a String that represents this instance. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

## Fields

| Name | Description |
| --- | --- |
| const [ColorValueMax](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/colorvaluemax) | Color max value in CMYK colorant. |
| const [ColorValueMin](../../groupdocs.metadata.standards.xmp/xmpcolorantcmyk/colorvaluemin) | Color min value in CMYK colorant. |

### See Also

* class [XmpColorantBase](../xmpcolorantbase)
* namespace [GroupDocs.Metadata.Standards.Xmp](../../groupdocs.metadata.standards.xmp)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
