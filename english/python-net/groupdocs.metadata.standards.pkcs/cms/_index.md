---
title: Cms class
second_title: GroupDocs.Metadata for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.metadata.standards.pkcs/cms/
is_root: false
weight: 10
---

## Cms class

Represents a digital sign created with Cryptographic Message Syntax (CMS) - IETF's standard for cryptographically protected messages. 
CMS is based on the syntax of PKCS #7, specified in RFC 5652.
Please see [https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) for more information.



**Inheritance:** [`Cms`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms) → 
[`DigitalSignature`](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature) → 
[`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage) → 
[`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)



The Cms type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [metadata_type](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/metadata_type) | Gets the metadata type. |
| [keys](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/keys) | Gets a collection of the metadata property names. |
| [property_descriptors](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/property_descriptors) | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [count](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/count) | Gets the number of metadata properties. |
| [comments](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/comments) | Gets the signing purpose comment. |
| [is_valid](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/is_valid) | Gets a value indicating whether the signature is valid. |
| [sign_time](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/sign_time) | Gets the time at which the signer (purportedly) performed the signing process. |
| [certificate_subject](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/certificate_subject) | Gets the subject distinguished name from a certificate. |
| [certificate_raw_data](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/certificate_raw_data) | Gets the certificate raw data. |
| [digest_algorithms](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/digest_algorithms) | Gets the array of message-digest algorithm identifiers. There may be any number of elements in the collection, including zero. |
| [encapsulated_content](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/encapsulated_content) | Gets the signed content, consisting of a content type identifier and the content itself. |
| [certificates](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/certificates) | Gets the collection of certificates. |
| [signers](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/signers) | Gets the collection of per-signer information packages. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/contains/#System.String) | Determines whether the package contains a metadata property with the specified name. |
| [find_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/find_properties/#groupdocs.metadata.search.Specification) | Finds the metadata properties satisfying a specification. <br/>The search is recursive so it affects all nested packages as well. |
| [update_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/update_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Updates known metadata properties satisfying a specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [remove_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/remove_properties/#groupdocs.metadata.search.Specification) | Removes metadata properties satisfying a specification. |
| [add_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/add_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Adds known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well. |
| [set_properties](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/set_properties/#groupdocs.metadata.search.Specification-groupdocs.metadata.common.PropertyValue) | Sets known metadata properties satisfying the specification.<br/>The operation is recursive so it affects all nested packages as well.<br/>This method is a combination of [`MetadataPackage.add_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/add_properties) and [`MetadataPackage.update_properties`](/metadata/python-net/groupdocs.metadata.common/metadatapackage/update_properties). <br/>If an existing property satisfies the specification its value is updated. <br/>If there is a known property missing in the package that satisfies the specification it is added to the package. |
| [sanitize](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms/sanitize/#) | Removes writable metadata properties from the package.<br/>The operation is recursive so it affects all nested packages as well. |



### See Also
* module [`groupdocs.metadata.standards.pkcs`](..)
* class [`Cms`](/metadata/python-net/groupdocs.metadata.standards.pkcs/cms)
* class [`CustomPackage`](/metadata/python-net/groupdocs.metadata.common/custompackage)
* class [`DigitalSignature`](/metadata/python-net/groupdocs.metadata.standards.signing/digitalsignature)
* class [`MetadataPackage`](/metadata/python-net/groupdocs.metadata.common/metadatapackage)
