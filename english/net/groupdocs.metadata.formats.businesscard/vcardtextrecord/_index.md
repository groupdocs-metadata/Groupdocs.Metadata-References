---
title: VCardTextRecord
second_title: GroupDocs.Metadata for .NET API Reference
description: Represents vCard text record metadata class.
type: docs
weight: 930
url: /net/groupdocs.metadata.formats.businesscard/vcardtextrecord/
---
## VCardTextRecord class

Represents vCard text record metadata class.

```csharp
public class VCardTextRecord : VCardRecord
```

## Properties

| Name | Description |
| --- | --- |
| [AltIdParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/altidparameter) { get; } | Gets the alternative representations parameter value. |
| [AnonymParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/anonymparameters) { get; } | Gets the anonymous parameters. |
| [CharsetParameter](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/charsetparameter) { get; } | Gets the charset parameter. |
| override [ContentType](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/contenttype) { get; } | Gets the content type of record. |
| [Count](../../groupdocs.metadata.common/metadatapackage/count) { get; } | Gets the number of metadata properties. |
| [EncodingParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/encodingparameter) { get; } | Gets the encoding parameter value. |
| [Group](../../groupdocs.metadata.formats.businesscard/vcardrecord/group) { get; } | Gets the grouping value. |
| [IsQuotedPrintable](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/isquotedprintable) { get; } | Gets a value indicating whether this instance is quoted printable string. |
| [Item](../../groupdocs.metadata.common/metadatapackage/item) { get; } | Gets the [`MetadataProperty`](../../groupdocs.metadata.common/metadataproperty) with the specified name. |
| [Keys](../../groupdocs.metadata.common/metadatapackage/keys) { get; } | Gets a collection of the metadata property names. |
| [LanguageParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/languageparameter) { get; } | Gets the language parameter value. |
| [MediaTypeParameter](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/mediatypeparameter) { get; } | Gets the media type parameter value. |
| [MetadataType](../../groupdocs.metadata.common/metadatapackage/metadatatype) { get; } | Gets the metadata type. |
| [PrefParameter](../../groupdocs.metadata.formats.businesscard/vcardrecord/prefparameter) { get; } | Gets the preferred parameter. |
| [PropertyDescriptors](../../groupdocs.metadata.common/metadatapackage/propertydescriptors) { get; } | Gets a collection of descriptors that contain information about properties accessible through the GroupDocs.Metadata search engine. |
| [TypeName](../../groupdocs.metadata.formats.businesscard/vcardrecord/typename) { get; } | Gets the type of the record. |
| [TypeParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/typeparameters) { get; } | Gets the type parameter values. |
| [Value](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/value) { get; } | Gets the record value. |
| [ValueParameters](../../groupdocs.metadata.formats.businesscard/vcardrecord/valueparameters) { get; } | Gets the value parameters. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddProperties](../../groupdocs.metadata.common/metadatapackage/addproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Adds known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |
| [Contains](../../groupdocs.metadata.common/metadatapackage/contains)(string) | Determines whether the package contains a metadata property with the specified name. |
| virtual [FindProperties](../../groupdocs.metadata.common/metadatapackage/findproperties)(Func&lt;MetadataProperty, bool&gt;) | Finds the metadata properties satisfying the specified predicate. The search is recursive so it affects all nested packages as well. |
| [GetEnumerator](../../groupdocs.metadata.common/metadatapackage/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [GetReadabilityValue](../../groupdocs.metadata.formats.businesscard/vcardtextrecord/getreadabilityvalue)(string) | Gets the readability value. |
| virtual [RemoveProperties](../../groupdocs.metadata.common/metadatapackage/removeproperties)(Func&lt;MetadataProperty, bool&gt;) | Removes metadata properties satisfying the specified predicate. |
| virtual [Sanitize](../../groupdocs.metadata.common/metadatapackage/sanitize)() | Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well. |
| virtual [SetProperties](../../groupdocs.metadata.common/metadatapackage/setproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Sets known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. This method is a combination of [`AddProperties`](../../groupdocs.metadata.common/metadatapackage/addproperties) and [`UpdateProperties`](../../groupdocs.metadata.common/metadatapackage/updateproperties). If an existing property satisfies the predicate its value is updated. If there is a known property missing in the package that satisfies the predicate it is added to the package. |
| virtual [UpdateProperties](../../groupdocs.metadata.common/metadatapackage/updateproperties)(Func&lt;MetadataProperty, bool&gt;, PropertyValue) | Updates known metadata properties satisfying the specified predicate. The operation is recursive so it affects all nested packages as well. |

### Remarks

**Learn more**

* [Working with vCard metadata](https://docs.groupdocs.com/display/metadatanet/Working+with+vCard+metadata)

### See Also

* class [VCardRecord](../vcardrecord)
* namespace [GroupDocs.Metadata.Formats.BusinessCard](../../groupdocs.metadata.formats.businesscard)
* assembly [GroupDocs.Metadata](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.metadata.dll -->
