---
title: WordProcessingPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a native metadata package in a word processing document.
type: docs
weight: 292
url: /nodejs-java/com.groupdocs.metadata.core/wordprocessingpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DocumentPackage](../../com.groupdocs.metadata.core/documentpackage)
```
public class WordProcessingPackage extends DocumentPackage
```

Represents a native metadata package in a word processing document.

**Learn more**

 *  [Working with metadata in WordProcessing documents][]

This code sample shows how to update built-in metadata properties in a WordProcessing document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputDoc)) {
>      WordProcessingRootPackage root = metadata.getRootPackageGeneric();
>      root.getDocumentProperties().setAuthor("test author");
>      root.getDocumentProperties().setCreatedTime(new Date());
>      root.getDocumentProperties().setCompany("GroupDocs");
>      root.getDocumentProperties().setCategory("test category");
>      root.getDocumentProperties().setKeywords("metadata, built-in, update");
>      // ...
>      metadata.save(Constants.OutputDoc);
>  }
>  
> ```
> ```


[Working with metadata in WordProcessing documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Word+Processing+documents
## Methods

| Method | Description |
| --- | --- |
| [getAuthor()](#getAuthor--) | Gets the document's author. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the document's author. |
| [getBytesInDocument()](#getBytesInDocument--) | Gets an estimate of the number of bytes in the document. |
| [getCategory()](#getCategory--) | Gets the category. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sets the category. |
| [getComments()](#getComments--) | Gets the comments. |
| [setComments(String value)](#setComments-java.lang.String-) | Sets the comments. |
| [getCompany()](#getCompany--) | Gets the company. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Sets the company. |
| [getContentStatus()](#getContentStatus--) | Gets the content status. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Sets the content status. |
| [getContentType()](#getContentType--) | Gets the content type of the document. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Sets the content type of the document. |
| [getCreatedTime()](#getCreatedTime--) | Gets the document created date. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Sets the document created date. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gets the hyperlink base. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Sets the hyperlink base. |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getSubject()](#getSubject--) | Gets the subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject. |
| [getTemplate()](#getTemplate--) | Gets the template. |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | Sets the template. |
| [getLastPrintedDate()](#getLastPrintedDate--) | Gets the last printed date. |
| [setLastPrintedDate(Date value)](#setLastPrintedDate-java.util.Date-) | Sets the last printed date. |
| [getLastSavedBy()](#getLastSavedBy--) | Gets the name of the last author. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Sets the name of the last author. |
| [getLastSavedTime()](#getLastSavedTime--) | Gets the time of the last save. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Sets the time of the last save. |
| [getManager()](#getManager--) | Gets the manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets the manager. |
| [getNameOfApplication()](#getNameOfApplication--) | Gets the name of the application. |
| [getRevisionNumber()](#getRevisionNumber--) | Gets the revision number. |
| [setRevisionNumber(Integer value)](#setRevisionNumber-java.lang.Integer-) | Sets the revision number. |
| [getVersion()](#getVersion--) | Gets the version number of the application that created the document. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Gets the total editing time in minutes. |
| [setTotalEditingTime(Integer value)](#setTotalEditingTime-java.lang.Integer-) | Sets the total editing time in minutes. |
| [getTitle()](#getTitle--) | Gets the title of the document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the document. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Gets a value indicating whether the hyperlinks in the document are up-to-date. |
| [setLinksUpToDate(Boolean value)](#setLinksUpToDate-java.lang.Boolean-) | Sets a value indicating whether the hyperlinks in the document are up-to-date. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Gets the titles of document parts. |
| [getWords()](#getWords--) | Gets an estimate of the number of words in the document. |
| [set(String propertyName, String value)](#set-java.lang.String-java.lang.String-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, boolean value)](#set-java.lang.String-boolean-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, Date value)](#set-java.lang.String-java.util.Date-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, int value)](#set-java.lang.String-int-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, double value)](#set-java.lang.String-double-) | Adds or replaces the metadata property with the specified name. |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the document's author.

**Returns:**
java.lang.String - The author.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sets the document's author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The author. |

### getBytesInDocument() {#getBytesInDocument--}
```
public final Integer getBytesInDocument()
```


Gets an estimate of the number of bytes in the document.

**Returns:**
java.lang.Integer - An estimate of the number of bytes in the document.
### getCategory() {#getCategory--}
```
public final String getCategory()
```


Gets the category.

**Returns:**
java.lang.String - The category.
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Sets the category.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The category. |

### getComments() {#getComments--}
```
public final String getComments()
```


Gets the comments.

**Returns:**
java.lang.String - The comments.
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Sets the comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The comments. |

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Gets the company.

**Returns:**
java.lang.String - The company.
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Sets the company.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The company. |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Gets the content status.

**Returns:**
java.lang.String - The content status.
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Sets the content status.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The content status. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Gets the content type of the document.

**Returns:**
java.lang.String - The type of the content.
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Sets the content type of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The type of the content. |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Gets the document created date.

**Returns:**
java.util.Date - The created time.
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Sets the document created date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The created time. |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Gets the hyperlink base.

**Returns:**
java.lang.String - The hyperlink base.
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Sets the hyperlink base.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The hyperlink base. |

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

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject.

**Returns:**
java.lang.String - The subject.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject. |

### getTemplate() {#getTemplate--}
```
public final String getTemplate()
```


Gets the template.

**Returns:**
java.lang.String - The template.
### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public final void setTemplate(String value)
```


Sets the template.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The template. |

### getLastPrintedDate() {#getLastPrintedDate--}
```
public final Date getLastPrintedDate()
```


Gets the last printed date.

**Returns:**
java.util.Date - The last printed date.
### setLastPrintedDate(Date value) {#setLastPrintedDate-java.util.Date-}
```
public final void setLastPrintedDate(Date value)
```


Sets the last printed date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The last printed date. |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Gets the name of the last author.

**Returns:**
java.lang.String - The name of the last author.
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Sets the name of the last author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the last author. |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Gets the time of the last save.

**Returns:**
java.util.Date - The time of the last save.
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Sets the time of the last save.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The time of the last save. |

### getManager() {#getManager--}
```
public final String getManager()
```


Gets the manager.

**Returns:**
java.lang.String - The manager.
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Sets the manager.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The manager. |

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```


Gets the name of the application.

**Returns:**
java.lang.String - The name of the application.
### getRevisionNumber() {#getRevisionNumber--}
```
public final Integer getRevisionNumber()
```


Gets the revision number.

**Returns:**
java.lang.Integer - The revision number.
### setRevisionNumber(Integer value) {#setRevisionNumber-java.lang.Integer-}
```
public final void setRevisionNumber(Integer value)
```


Sets the revision number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The revision number. |

### getVersion() {#getVersion--}
```
public final Integer getVersion()
```


Gets the version number of the application that created the document.

**Returns:**
java.lang.Integer - The version number of the application that created the document.

--------------------

When a document was created by Microsoft Word, then high 16 bit represent the major version and low 16 bit represent the build number.
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final Integer getTotalEditingTime()
```


Gets the total editing time in minutes.

**Returns:**
java.lang.Integer - The total editing time in minutes.
### setTotalEditingTime(Integer value) {#setTotalEditingTime-java.lang.Integer-}
```
public final void setTotalEditingTime(Integer value)
```


Sets the total editing time in minutes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The total editing time in minutes. |

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

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final Boolean getLinksUpToDate()
```


Gets a value indicating whether the hyperlinks in the document are up-to-date.

**Returns:**
java.lang.Boolean - A value indicating whether the hyperlinks in the document are up-to-date.
### setLinksUpToDate(Boolean value) {#setLinksUpToDate-java.lang.Boolean-}
```
public final void setLinksUpToDate(Boolean value)
```


Sets a value indicating whether the hyperlinks in the document are up-to-date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Boolean | A value indicating whether the hyperlinks in the document are up-to-date. |

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```


Gets the titles of document parts. Read-only.

**Returns:**
java.lang.String[] - The titles of document parts.
### getWords() {#getWords--}
```
public final Integer getWords()
```


Gets an estimate of the number of words in the document.

**Returns:**
java.lang.Integer - The number of words in the document.
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

### set(String propertyName, boolean value) {#set-java.lang.String-boolean-}
```
public final void set(String propertyName, boolean value)
```


Adds or replaces the metadata property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| value | boolean | The property value. |

### set(String propertyName, Date value) {#set-java.lang.String-java.util.Date-}
```
public final void set(String propertyName, Date value)
```


Adds or replaces the metadata property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| value | java.util.Date | The property value. |

### set(String propertyName, int value) {#set-java.lang.String-int-}
```
public final void set(String propertyName, int value)
```


Adds or replaces the metadata property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| value | int | The property value. |

### set(String propertyName, double value) {#set-java.lang.String-double-}
```
public final void set(String propertyName, double value)
```


Adds or replaces the metadata property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The property name. |
| value | double | The property value. |

