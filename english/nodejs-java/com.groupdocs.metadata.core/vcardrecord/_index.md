---
title: VCardRecord
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents abstract vCard record metadata class.
type: docs
weight: 278
url: /nodejs-java/com.groupdocs.metadata.core/vcardrecord/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.VCardBasePackage](../../com.groupdocs.metadata.core/vcardbasepackage)
```
public abstract class VCardRecord extends VCardBasePackage
```

Represents abstract vCard record metadata class.

**Learn more**

 *  [Working with vCard metadata][]


[Working with vCard metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+vCard+metadata
## Methods

| Method | Description |
| --- | --- |
| [getGroup()](#getGroup--) | Gets the grouping value. |
| [getValueParameters()](#getValueParameters--) | Gets the value parameters. |
| [getPrefParameter()](#getPrefParameter--) | Gets the preferred parameter. |
| [getAltIdParameter()](#getAltIdParameter--) | Gets the alternative representations parameter value. |
| [getTypeParameters()](#getTypeParameters--) | Gets the type parameter values. |
| [getEncodingParameter()](#getEncodingParameter--) | Gets the encoding parameter value. |
| [getLanguageParameter()](#getLanguageParameter--) | Gets the language parameter value. |
| [getAnonymParameters()](#getAnonymParameters--) | Gets the anonymous parameters. |
| [getContentType()](#getContentType--) | Gets the content type of record. |
| [getTypeName()](#getTypeName--) | Gets the type of the record. |
### getGroup() {#getGroup--}
```
public final String getGroup()
```


Gets the grouping value.

**Returns:**
java.lang.String - The grouping value.
### getValueParameters() {#getValueParameters--}
```
public final String[] getValueParameters()
```


Gets the value parameters.

**Returns:**
java.lang.String[] - The value parameters.

--------------------

Used to identify the value type (data type) and format of the value.
### getPrefParameter() {#getPrefParameter--}
```
public final Integer getPrefParameter()
```


Gets the preferred parameter.

**Returns:**
java.lang.Integer - The preferred parameter.

--------------------

Used to indicate that the corresponding instance of a property is preferred by the vCard author.
### getAltIdParameter() {#getAltIdParameter--}
```
public final String getAltIdParameter()
```


Gets the alternative representations parameter value.

**Returns:**
java.lang.String - The alternative representations parameter value.

--------------------

Used to "tag" property instances as being alternative representations of the same logical property.
### getTypeParameters() {#getTypeParameters--}
```
public final String[] getTypeParameters()
```


Gets the type parameter values.

**Returns:**
java.lang.String[] - The type parameter values.

--------------------

The type parameter has multiple, different uses. In general, it is a way of specifying class characteristics of the associated property.
### getEncodingParameter() {#getEncodingParameter--}
```
public final String getEncodingParameter()
```


Gets the encoding parameter value.

**Returns:**
java.lang.String - The encoding parameter value.
### getLanguageParameter() {#getLanguageParameter--}
```
public final String getLanguageParameter()
```


Gets the language parameter value.

**Returns:**
java.lang.String - The language parameter value.
### getAnonymParameters() {#getAnonymParameters--}
```
public final String[] getAnonymParameters()
```


Gets the anonymous parameters.

**Returns:**
java.lang.String[] - The anonymous parameters.
### getContentType() {#getContentType--}
```
public abstract VCardContentType getContentType()
```


Gets the content type of record.

**Returns:**
[VCardContentType](../../com.groupdocs.metadata.core/vcardcontenttype) - The content type of record.
### getTypeName() {#getTypeName--}
```
public final String getTypeName()
```


Gets the type of the record.

**Returns:**
java.lang.String - The type of the record.
