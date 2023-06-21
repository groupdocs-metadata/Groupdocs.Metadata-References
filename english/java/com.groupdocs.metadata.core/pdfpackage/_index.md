---
title: PdfPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents native metadata in a PDF document.
type: docs
weight: 190
url: /java/com.groupdocs.metadata.core/pdfpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DocumentPackage](../../com.groupdocs.metadata.core/documentpackage)
```
public class PdfPackage extends DocumentPackage
```

Represents native metadata in a PDF document.

**Learn more**

 *  [Working with metadata in PDF documents][]

This code snippet demonstrates how to update built-in metadata properties in a PDF document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputPdf)) {
>      PdfRootPackage root = metadata.getRootPackageGeneric();
>      root.getDocumentProperties().setAuthor("test author");
>      root.getDocumentProperties().setCreatedDate(new Date());
>      root.getDocumentProperties().setTitle("test title");
>      root.getDocumentProperties().setKeywords("metadata, built-in, update");
>      // ...
>      metadata.save(Constants.OutputPdf);
>  }
>  
> ```
> ```


[Working with metadata in PDF documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+PDF+documents
## Methods

| Method | Description |
| --- | --- |
| [getAuthor()](#getAuthor--) | Gets the document author. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the document author. |
| [getCreatedDate()](#getCreatedDate--) | Gets the date of document creation. |
| [setCreatedDate(Date value)](#setCreatedDate-java.util.Date-) | Sets the date of document creation. |
| [getCreator()](#getCreator--) | Gets the creator of the document. |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getModifiedDate()](#getModifiedDate--) | Gets the date of the last modification. |
| [setModifiedDate(Date value)](#setModifiedDate-java.util.Date-) | Sets the date of the last modification. |
| [getProducer()](#getProducer--) | Gets the document producer. |
| [getSubject()](#getSubject--) | Gets the subject of the document. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the document. |
| [getTitle()](#getTitle--) | Gets the title of the document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the document. |
| [getTrappedFlag()](#getTrappedFlag--) | Gets the trapped flag. |
| [setTrappedFlag(Boolean value)](#setTrappedFlag-java.lang.Boolean-) | Sets the trapped flag. |
| [set(String propertyName, String value)](#set-java.lang.String-java.lang.String-) | Adds or replaces the metadata property with the specified name. |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the document author.

**Returns:**
java.lang.String - The document author.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sets the document author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The document author. |

### getCreatedDate() {#getCreatedDate--}
```
public final Date getCreatedDate()
```


Gets the date of document creation.

**Returns:**
java.util.Date - The date of document creation.
### setCreatedDate(Date value) {#setCreatedDate-java.util.Date-}
```
public final void setCreatedDate(Date value)
```


Sets the date of document creation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date of document creation. |

### getCreator() {#getCreator--}
```
public final String getCreator()
```


Gets the creator of the document.

**Returns:**
java.lang.String - The creator of the document.
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

### getModifiedDate() {#getModifiedDate--}
```
public final Date getModifiedDate()
```


Gets the date of the last modification.

**Returns:**
java.util.Date - The date of the last modification.
### setModifiedDate(Date value) {#setModifiedDate-java.util.Date-}
```
public final void setModifiedDate(Date value)
```


Sets the date of the last modification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date of the last modification. |

### getProducer() {#getProducer--}
```
public final String getProducer()
```


Gets the document producer.

**Returns:**
java.lang.String - The document producer.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the document.

**Returns:**
java.lang.String - The subject of the document.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject of the document. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the title of the document.

**Returns:**
java.lang.String - The title of the document.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets the title of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The title of the document. |

### getTrappedFlag() {#getTrappedFlag--}
```
public final Boolean getTrappedFlag()
```


Gets the trapped flag.

**Returns:**
java.lang.Boolean -  true  if the trapped flag is set; otherwise,  false .
### setTrappedFlag(Boolean value) {#setTrappedFlag-java.lang.Boolean-}
```
public final void setTrappedFlag(Boolean value)
```


Sets the trapped flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean |  true  if the trapped flag is set; otherwise,  false . |

### set(String propertyName, String value) {#set-java.lang.String-java.lang.String-}
```
public final void set(String propertyName, String value)
```


Adds or replaces the metadata property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| value | java.lang.String | The property value. |

