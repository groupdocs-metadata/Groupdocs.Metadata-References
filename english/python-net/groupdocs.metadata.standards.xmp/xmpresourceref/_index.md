---
title: XmpResourceRef class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.xmp/xmpresourceref/
is_root: false
weight: 290
---

## XmpResourceRef class

Represents a multiple part reference to a resource.  

Used to indicate prior versions, originals of renditions, originals for derived documents, and so on.



**Inheritance:** [`XmpResourceRef`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref) → 
[`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) → 
[`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The XmpResourceRef type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/__init__/#) | Initializes a new instance of the [`XmpResourceRef`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref) class. |


### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/count) | Gets the number of metadata properties. |
| [prefixes](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/prefixes) | Gets the namespace prefixes that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [namespace_uris](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/namespace_uris) | Gets the namespace URIs that are used in the [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype) instance. |
| [alternate_paths](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/alternate_paths) | Gets or sets the referenced resource’s fallback file paths or URLs. |
| [document_id](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/document_id) | Gets or sets the value of the xmpMM:DocumentID property from the referenced resource. |
| [file_path](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/file_path) | Gets or sets the referenced resource’s file path or URL. |
| [instance_id](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/instance_id) | Gets or sets the value of the xmpMM:InstanceID property from the referenced resource. |
| [last_modify_date](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/last_modify_date) | Gets or sets the value of stEvt:when for the last time the file was written. |
| [manager](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/manager) | Gets or sets the referenced resource’s xmpMM:Manager. |
| [manager_variant](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/manager_variant) | Gets or sets the referenced resource’s xmpMM:Manager. |
| [manage_to](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/manage_to) | Gets or sets the referenced resource’s xmpMM:ManageTo. |
| [manage_ui](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/manage_ui) | Gets or sets the referenced resource’s xmpMM:ManageUI. |
| [part_mapping](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/part_mapping) | Gets or sets the name or URI of a mapping function used to map the fromPart to the toPart. |
| [rendition_class](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/rendition_class) | Gets or sets the value of the xmpMM:RenditionClass property from the referenced resource. |
| [rendition_params](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/rendition_params) | Gets or sets the value of the xmpMM:RenditionParams property from the referenced resource. |
| [version_id](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/version_id) | Gets or sets the value of the xmpMM:RenditionParams property from the referenced resource. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |
| [get_xmp_representation](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/get_xmp_representation/#) | Returns string contained value in XMP format. |
| [get_namespace_uri](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref/get_namespace_uri/#System.String) | Gets the namespace URI associated with the specified prefix. |



### See Also
* module [`groupdocs.metadata.standards.xmp`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
* class [`XmpComplexType`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpcomplextype)
* class [`XmpMetadataContainer`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpmetadatacontainer)
* class [`XmpResourceRef`](/metadata/python-net/groupdocs.metadata.standards.xmp/xmpresourceref)
