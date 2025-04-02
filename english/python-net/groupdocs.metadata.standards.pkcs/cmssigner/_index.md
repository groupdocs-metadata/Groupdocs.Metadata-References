---
title: CmsSigner class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.pkcs/cmssigner/
is_root: false
weight: 60
---

## CmsSigner class

Represents CMS per-signer information.



**Inheritance:** [`CmsSigner`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The CmsSigner type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/count) | Gets the number of metadata properties. |
| [signer_identifier](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/signer_identifier) | Gets the signer's certificate (and thereby the signer's public key) raw data. |
| [digest_algorithm](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/digest_algorithm) | Gets the message digest algorithm, and any associated parameters, used by the signer. |
| [signed_attributes](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/signed_attributes) | Gets the collection of attributes that are signed. |
| [signature_algorithm](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/signature_algorithm) | Gets the signature algorithm, and any associated parameters, used by the signer to generate the digital signature. |
| [signature_value](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/signature_value) | Gets the result of digital signature generation, using the message digest and the signer's private key. |
| [unsigned_attributes](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/unsigned_attributes) | Gets the collection of attributes that are not signed. |
| [signing_time](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/signing_time) | Gets the time at which the signer (purportedly) performed the signing process. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/contains/#str) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.standards.pkcs`](..)
* class [`CmsSigner`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cmssigner)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
