---
title: DigitalSignature class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.signing/digitalsignature/
is_root: false
weight: 10
---

## DigitalSignature class

Represents a digital signature used to sign a document.



**Inheritance:** [`DigitalSignature`](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The DigitalSignature type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/count) | Gets the number of metadata properties. |
| [comments](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/comments) | Gets the signing purpose comment. |
| [is_valid](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/is_valid) | Gets a value indicating whether the signature is valid. |
| [sign_time](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/sign_time) | Gets the time the document was signed. |
| [certificate_subject](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/certificate_subject) | Gets the subject distinguished name from a certificate. |
| [certificate_raw_data](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/certificate_raw_data) | Gets the certificate raw data. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.standards.signing`](..)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DigitalSignature`](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
