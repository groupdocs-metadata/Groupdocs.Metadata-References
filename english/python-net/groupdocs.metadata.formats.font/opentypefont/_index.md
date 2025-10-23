---
title: OpenTypeFont class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.formats.font/opentypefont/
is_root: false
weight: 20
---

## OpenTypeFont class

Represents a single font extracted from a file.



**Inheritance:** [`OpenTypeFont`](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The OpenTypeFont type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/count) | Gets the number of metadata properties. |
| [sfnt_version](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/sfnt_version) | Gets the header SFNT version. |
| [major_version](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/major_version) | Gets the header major version. |
| [minor_version](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/minor_version) | Gets the header minor version. |
| [font_revision](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/font_revision) | Gets the font revision. |
| [flags](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/flags) | Gets the header flags. |
| [created](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/created) | Gets the created date. |
| [modified](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/modified) | Gets the modified date. |
| [glyph_bounds](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/glyph_bounds) | Gets the glyph bounds. |
| [style](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/style) | Gets the font style. |
| [direction_hint](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/direction_hint) | Gets the direction hint. |
| [names](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/names) | Gets the name records. |
| [font_family_name](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/font_family_name) | Gets the name of the font family. |
| [font_subfamily_name](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/font_subfamily_name) | Gets the name of the font subfamily. |
| [full_font_name](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/full_font_name) | Gets the full name of the font. |
| [typographic_family](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/typographic_family) | Gets the typographic family. |
| [typographic_subfamily](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/typographic_subfamily) | Gets the typographic subfamily. |
| [weight](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/weight) | Gets the font weight. |
| [width](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/width) | Gets the font width. |
| [embedding_licensing_rights](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/embedding_licensing_rights) | Gets the embedding licensing rights type. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.metadata.formats.font`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`OpenTypeFont`](/metadata/python-net/groupdocs.metadata.formats.font/opentypefont)
