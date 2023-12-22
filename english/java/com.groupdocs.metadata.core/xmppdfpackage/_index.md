---
title: XmpPdfPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Specifies properties used with Adobe PDF documents.
type: docs
weight: 323
url: /java/com.groupdocs.metadata.core/xmppdfpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpPackage](../../com.groupdocs.metadata.core/xmppackage)
```
public final class XmpPdfPackage extends XmpPackage
```

Specifies properties used with Adobe PDF documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPdfPackage()](#XmpPdfPackage--) | Initializes a new instance of the  XmpPdfPackage  class. |
## Methods

| Method | Description |
| --- | --- |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getPdfVersion()](#getPdfVersion--) | Gets the PDF file version. |
| [setPdfVersion(String value)](#setPdfVersion-java.lang.String-) | Sets the PDF file version. |
| [getProducer()](#getProducer--) | Gets the name of the tool that created the PDF document. |
| [setProducer(String value)](#setProducer-java.lang.String-) | Sets the name of the tool that created the PDF document. |
| [isTrapped()](#isTrapped--) | Gets a value indicating whether the document has been trapped. |
| [setTrapped(Boolean value)](#setTrapped-java.lang.Boolean-) | Sets a value indicating whether the document has been trapped. |
| [set(String name, String value)](#set-java.lang.String-java.lang.String-) | Sets string property. |
### XmpPdfPackage() {#XmpPdfPackage--}
```
public XmpPdfPackage()
```


Initializes a new instance of the  XmpPdfPackage  class.

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Gets the keywords.

**Returns:**
java.lang.String - The keywords.
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Sets the keywords.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The keywords. |

### getPdfVersion() {#getPdfVersion--}
```
public final String getPdfVersion()
```


Gets the PDF file version. For example, 1.0, 1.3 and so on.

**Returns:**
java.lang.String - The PDF version.
### setPdfVersion(String value) {#setPdfVersion-java.lang.String-}
```
public final void setPdfVersion(String value)
```


Sets the PDF file version. For example, 1.0, 1.3 and so on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The PDF version. |

### getProducer() {#getProducer--}
```
public final String getProducer()
```


Gets the name of the tool that created the PDF document.

**Returns:**
java.lang.String - The producer.
### setProducer(String value) {#setProducer-java.lang.String-}
```
public final void setProducer(String value)
```


Sets the name of the tool that created the PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The producer. |

### isTrapped() {#isTrapped--}
```
public final Boolean isTrapped()
```


Gets a value indicating whether the document has been trapped.

**Returns:**
java.lang.Boolean -  true  if the document has been trapped; otherwise,  false .
### setTrapped(Boolean value) {#setTrapped-java.lang.Boolean-}
```
public final void setTrapped(Boolean value)
```


Sets a value indicating whether the document has been trapped.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean |  true  if the document has been trapped; otherwise,  false . |

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

