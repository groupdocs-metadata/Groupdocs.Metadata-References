---
title: VCardSecurityRecordset
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents a set of Security vCard records. These properties are concerned with the security of communication pathways or access to the vCard.
type: docs
weight: 940
url: /net/groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/
---
## VCardSecurityRecordset class

Represents a set of Security vCard records. These properties are concerned with the security of communication pathways or access to the vCard.

```csharp
public class VCardSecurityRecordset : VCardRecordset
```

## Properties

| Name | Description |
| --- | --- |
| [AccessClassification](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/accessclassification) { get; } | Gets the sensitivity of the information in the vCard. |
| [BinaryPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/binarypublickeys) { get; } | Gets the public keys or authentication certificates associated with the object. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [PublicKeyBinaryRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeybinaryrecords) { get; } | Gets the public keys or authentication certificates associated with the object. |
| [PublicKeyRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyrecords) { get; } | Gets the public keys or authentication certificates associated with the object. |
| [PublicKeyUriRecords](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/publickeyurirecords) { get; } | Gets the public keys or authentication certificates associated with the object. |
| [UriPublicKeys](../../groupdocs.metadata.formats.businesscard/vcardsecurityrecordset/uripublickeys) { get; } | Gets the public keys or authentication certificates associated with the object. |

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

* [Working with vCard metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### See Also

* class [VCardRecordset](../vcardrecordset)
* namespace [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
