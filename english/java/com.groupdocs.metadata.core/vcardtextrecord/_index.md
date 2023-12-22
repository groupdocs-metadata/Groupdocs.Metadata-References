---
title: VCardTextRecord
second_title: GroupDocs.Metadata for Java API Reference
description: Represents vCard text record metadata class.
type: docs
weight: 273
url: /java/com.groupdocs.metadata.core/vcardtextrecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage), [com.groupdocs.metadata.core.VCardRecord](../../com.groupdocs.metadata.core/vcardrecord)

**All Implemented Interfaces:**
com.groupdocs.metadata.core.IVCardRecord
```
public class VCardTextRecord extends VCardRecord implements IVCardRecord<String>
```

Represents vCard text record metadata class.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Gets the content type of record. |
| [getMediaTypeParameter()](#getMediaTypeParameter--) | Gets the media type parameter value. |
| [getCharsetParameter()](#getCharsetParameter--) | Gets the charset parameter. |
| [getValue()](#getValue--) | Gets the record value. |
| [isQuotedPrintable()](#isQuotedPrintable--) | Gets a value indicating whether this instance is quoted printable string. |
| [getReadabilityValue(String codePageName)](#getReadabilityValue-java.lang.String-) | Gets the readability value. |
### getContentType() {#getContentType--}
```
public VCardContentType getContentType()
```


Gets the content type of record.

**Returns:**
[VCardContentType](../../com.groupdocs.metadata.core/vcardcontenttype) - The content type of record.
### getMediaTypeParameter() {#getMediaTypeParameter--}
```
public final String getMediaTypeParameter()
```


Gets the media type parameter value.

**Returns:**
java.lang.String - The media type parameter value.

--------------------

Used with properties whose value is a URI. It provides a hint to the vCard consumer application about the media type [RFC2046] of the resource identified by the URI.
### getCharsetParameter() {#getCharsetParameter--}
```
public final String getCharsetParameter()
```


Gets the charset parameter.

**Returns:**
java.lang.String - The charset parameter.
### getValue() {#getValue--}
```
public final String getValue()
```


Gets the record value.

**Returns:**
java.lang.String - The record value.
### isQuotedPrintable() {#isQuotedPrintable--}
```
public final boolean isQuotedPrintable()
```


Gets a value indicating whether this instance is quoted printable string.

**Returns:**
boolean -  true  if this instance is quoted printable; otherwise,  false .
### getReadabilityValue(String codePageName) {#getReadabilityValue-java.lang.String-}
```
public final String getReadabilityValue(String codePageName)
```


Gets the readability value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codePageName | java.lang.String | The using encoding code page name or null for ASCII encoding. |

**Returns:**
java.lang.String - The readability value.
