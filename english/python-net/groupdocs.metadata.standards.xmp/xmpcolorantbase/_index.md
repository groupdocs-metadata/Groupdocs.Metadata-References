---
title: XmpColorantBase class
second_title: GroupDocs.Metadata for Python via .NET API References
description: "Represents a structure containing the characteristics of a colorant (swatch) used in a document."
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase/
is_root: false
weight: 80
---


## XmpColorantBase class

Represents a structure containing the characteristics of a colorant (swatch) used in a document.

The XmpColorantBase type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase/get_xmp_representation/) | Converts the XMP value to the XML representation. |
| [add_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties/) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [add_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains/) | Returns True if the package contains a metadata property with the specified name; otherwise, False. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [contains_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/contains_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties/) | Finds metadata properties that satisfy the specified predicate, searching recursively through all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [find_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/find_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_enumerator](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_enumerator/) | Returns an enumerator that iterates through the collection. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_file](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_file/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [get_namespace_uri](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/get_namespace_uri/) | Retrieves the namespace URI associated with the specified prefix. (inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/)) |
| [get_namespace_uri_file](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/get_namespace_uri_file/) |  (inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/)) |
| [get_namespace_uri_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/get_namespace_uri_string/) |  (inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/)) |
| [get_string](/metadata/python-net/groupdocs.metadata.common/metadatapackage/get_string/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties/) | Removes metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [remove_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/remove_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [sanitize](/metadata/python-net/groupdocs.metadata.common/metadatapackage/sanitize/) | Removes writable metadata properties from the package, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties/) | Sets known metadata properties satisfying the specified predicate. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [set_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/set_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [to_string](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/to_string/) | Returns a str that represents this instance. (inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/)) |
| [update_properties](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties/) | Updates known metadata properties that satisfy the specified predicate, recursively affecting all nested packages. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [update_properties_func](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties_func/) |  (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### Properties
| Property | Description |
| :- | :- |
| [color_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase/color_type/) | The type of color. |
| [mode](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase/mode/) | The colour mode, indicating the colour space in which the colour is defined (one of: CMYK, RGB, LAB). |
| [swatch_name](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcolorantbase/swatch_name/) | The name of the swatch. |
| [count](/metadata/python-net/groupdocs.metadata.common/metadatapackage/count/) | The number of metadata properties. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [keys](/metadata/python-net/groupdocs.metadata.common/metadatapackage/keys/) | The collection of metadata property names. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [know_property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/know_property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [metadata_type](/metadata/python-net/groupdocs.metadata.common/metadatapackage/metadata_type/) | The metadata type of the package. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |
| [namespace_uris](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/namespace_uris/) | The namespace URIs used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/) instance. (inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/)) |
| [prefixes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/prefixes/) | The namespace prefixes used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/) instance. (inherited from [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype/)) |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.common/metadatapackage/property_descriptors/) | The collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. (inherited from [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/)) |

### See Also
* module [`groupdocs.metadata.standards.xmp`](/metadata/python-net/groupdocs.metadata.standards.xmp/)
