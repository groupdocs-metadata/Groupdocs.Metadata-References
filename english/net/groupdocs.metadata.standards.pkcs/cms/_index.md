---
title: Cms
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a digital sign created with Cryptographic Message Syntax CMS  IETFs standard for cryptographically protected messages. CMS is based on the syntax of PKCS 7 specified in RFC 5652. Please see https//tools.ietf.org/html/rfc5652https//tools.ietf.org/html/rfc5652 for more information.
type: docs
weight: 4040
url: /net/groupdocs.metadata.standards.pkcs/cms/
---
## Cms class

Represents a digital sign created with Cryptographic Message Syntax (CMS) - IETF's standard for cryptographically protected messages. CMS is based on the syntax of PKCS #7, specified in RFC 5652. Please see [https://tools.ietf.org/html/rfc5652](https://tools.ietf.org/html/rfc5652) for more information.

```csharp
public class Cms : DigitalSignature
```

## Properties

| Name | Description |
| --- | --- |
| [CertificateRawData](../../groupdocs.metadata.standards.signing/digitalsignature/certificaterawdata) { get; } | Gets the certificate raw data. |
| [Certificates](../../groupdocs.metadata.standards.pkcs/cms/certificates) { get; } | Gets the collection of certificates. |
| [CertificateSubject](../../groupdocs.metadata.standards.signing/digitalsignature/certificatesubject) { get; } | Gets the subject distinguished name from a certificate. |
| [Comments](../../groupdocs.metadata.standards.signing/digitalsignature/comments) { get; } | Gets the signing purpose comment. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [DigestAlgorithms](../../groupdocs.metadata.standards.pkcs/cms/digestalgorithms) { get; } | Gets the array of message-digest algorithm identifiers. There may be any number of elements in the collection, including zero. |
| [EncapsulatedContent](../../groupdocs.metadata.standards.pkcs/cms/encapsulatedcontent) { get; } | Gets the signed content, consisting of a content type identifier and the content itself. |
| virtual [IsValid](../../groupdocs.metadata.standards.signing/digitalsignature/isvalid) { get; } | Gets a value indicating whether the signature is valid. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [Signers](../../groupdocs.metadata.standards.pkcs/cms/signers) { get; } | Gets the collection of per-signer information packages. |
| override [SignTime](../../groupdocs.metadata.standards.pkcs/cms/signtime) { get; } | Gets the time at which the signer (purportedly) performed the signing process. |

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

### See Also

* class [DigitalSignature](../../groupdocs.metadata.standards.signing/digitalsignature)
* namespace [GroupDocs.Metadata.Standards.Pkcs](../../groupdocs.metadata.standards.pkcs)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
