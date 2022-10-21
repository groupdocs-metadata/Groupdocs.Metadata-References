---
title: XmpRightsManagementPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents XMP Rights Management namespace.
type: docs
weight: 291
url: /java/com.groupdocs.metadata.core/xmprightsmanagementpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpRightsManagementPackage extends XmpPackage
```

Represents XMP Rights Management namespace.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage--) | Initializes a new instance of the  XmpRightsManagementPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Gets the Web URL for a rights management certificate. |
| [setCertificate(String value)](#setCertificate-java.lang.String-) | Sets the Web URL for a rights management certificate. |
| [getMarked()](#getMarked--) | Gets a value indicating whether this is a rights-managed resource. |
| [setMarked(Boolean value)](#setMarked-java.lang.Boolean-) | Sets a value indicating whether this is a rights-managed resource. |
| [getOwners()](#getOwners--) | Gets the legal owners. |
| [setOwners(String[] value)](#setOwners-java.lang.String---) | Sets the legal owners. |
| [getUsageTerms()](#getUsageTerms--) | Gets the instructions on how the resource can be legally used, given in a variety of languages. |
| [setUsageTerms(XmpLangAlt value)](#setUsageTerms-com.groupdocs.metadata.core.XmpLangAlt-) | Sets the instructions on how the resource can be legally used, given in a variety of languages. |
| [getWebStatement()](#getWebStatement--) | Gets the Web URL for a statement of the ownership and usage rights for this resource. |
| [setWebStatement(String value)](#setWebStatement-java.lang.String-) | Sets the Web URL for a statement of the ownership and usage rights for this resource. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
### XmpRightsManagementPackage() {#XmpRightsManagementPackage--}
```
public XmpRightsManagementPackage()
```


Initializes a new instance of the  XmpRightsManagementPackage  class.

### getCertificate() {#getCertificate--}
```
public final String getCertificate()
```


Gets the Web URL for a rights management certificate.

**Returns:**
java.lang.String - The Web URL for a rights management certificate.
### setCertificate(String value) {#setCertificate-java.lang.String-}
```
public final void setCertificate(String value)
```


Sets the Web URL for a rights management certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Web URL for a rights management certificate. |

### getMarked() {#getMarked--}
```
public final Boolean getMarked()
```


Gets a value indicating whether this is a rights-managed resource.

**Returns:**
java.lang.Boolean -  true  if the resource is rights-managed; otherwise  false . When false, indicates that this is a public-domain resource. Omit if the state is unknown.
### setMarked(Boolean value) {#setMarked-java.lang.Boolean-}
```
public final void setMarked(Boolean value)
```


Sets a value indicating whether this is a rights-managed resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean |  true  if the resource is rights-managed; otherwise  false . When false, indicates that this is a public-domain resource. Omit if the state is unknown. |

### getOwners() {#getOwners--}
```
public final String[] getOwners()
```


Gets the legal owners.

**Returns:**
java.lang.String[] - The legal owners.
### setOwners(String[] value) {#setOwners-java.lang.String---}
```
public final void setOwners(String[] value)
```


Sets the legal owners.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | The legal owners. |

### getUsageTerms() {#getUsageTerms--}
```
public final XmpLangAlt getUsageTerms()
```


Gets the instructions on how the resource can be legally used, given in a variety of languages.

**Returns:**
[XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) - The instructions on how the resource can be legally used, given in a variety of languages.
### setUsageTerms(XmpLangAlt value) {#setUsageTerms-com.groupdocs.metadata.core.XmpLangAlt-}
```
public final void setUsageTerms(XmpLangAlt value)
```


Sets the instructions on how the resource can be legally used, given in a variety of languages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpLangAlt](../../com.groupdocs.metadata.core/xmplangalt) | The instructions on how the resource can be legally used, given in a variety of languages. |

### getWebStatement() {#getWebStatement--}
```
public final String getWebStatement()
```


Gets the Web URL for a statement of the ownership and usage rights for this resource.

**Returns:**
java.lang.String - The Web URL for a statement of the ownership and usage rights for this resource.
### setWebStatement(String value) {#setWebStatement-java.lang.String-}
```
public final void setWebStatement(String value)
```


Sets the Web URL for a statement of the ownership and usage rights for this resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The Web URL for a statement of the ownership and usage rights for this resource. |

### set(String name, String value) {#set-java.lang.String-java.lang.String-}
```
public void set(String name, String value)
```


Sets string property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | XMP metadata property name. |
| value | java.lang.String | XMP metadata property value. |

