---
title: SpreadsheetPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a native metadata package in a spreadsheet.
type: docs
weight: 235
url: /nodejs-java/com.groupdocs.metadata.core/spreadsheetpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DocumentPackage](../../com.groupdocs.metadata.core/documentpackage)
```
public class SpreadsheetPackage extends DocumentPackage
```

Represents a native metadata package in a spreadsheet.

**Learn more**

 *  [Working with metadata in Spreadsheets][]

This example shows how to update built-in metadata properties in a spreadsheet.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputXlsx)) {
>      SpreadsheetRootPackage root = metadata.getRootPackageGeneric();
>      root.getDocumentProperties().setAuthor("test author");
>      root.getDocumentProperties().setCreatedTime(new Date());
>      root.getDocumentProperties().setCompany("GroupDocs");
>      root.getDocumentProperties().setCategory("test category");
>      root.getDocumentProperties().setKeywords("metadata, built-in, update");
>      // ...
>      metadata.save(Constants.OutputXlsx);
>  }
>  
> ```
> ```


[Working with metadata in Spreadsheets]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Spreadsheets
## Methods

| Method | Description |
| --- | --- |
| [getLanguage()](#getLanguage--) | Gets the document language. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Sets the document language. |
| [getAuthor()](#getAuthor--) | Gets the document author. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the document author. |
| [getCategory()](#getCategory--) | Gets the category. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sets the category. |
| [getComments()](#getComments--) | Gets the comments. |
| [setComments(String value)](#setComments-java.lang.String-) | Sets the comments. |
| [getCompany()](#getCompany--) | Gets the company. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Sets the company. |
| [getContentStatus()](#getContentStatus--) | Gets the content status. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Sets the content status. |
| [getContentType()](#getContentType--) | Gets the content type. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Sets the content type. |
| [getCreatedTime()](#getCreatedTime--) | Gets the document created date. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Sets the document created date. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Gets the total editing time in minutes. |
| [setTotalEditingTime(Double value)](#setTotalEditingTime-java.lang.Double-) | Sets the total editing time in minutes. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gets the hyperlink base. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Sets the hyperlink base. |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getLastSavedTime()](#getLastSavedTime--) | Gets the time of the last saving in UTC. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Sets the time of the last saving in UTC. |
| [getLastPrintedDate()](#getLastPrintedDate--) | Gets the last printed date in UTC. |
| [setLastPrintedDate(Date value)](#setLastPrintedDate-java.util.Date-) | Sets the last printed date in UTC. |
| [getLastSavedBy()](#getLastSavedBy--) | Gets the name of the last author. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Sets the name of the last author. |
| [getManager()](#getManager--) | Gets the manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets the manager. |
| [getNameOfApplication()](#getNameOfApplication--) | Gets the name of application. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Sets the name of application. |
| [getRevision()](#getRevision--) | Gets the document revision number. |
| [setRevision(String value)](#setRevision-java.lang.String-) | Sets the document revision number. |
| [getSubject()](#getSubject--) | Gets the subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject. |
| [getTemplate()](#getTemplate--) | Gets the document template name. |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | Sets the document template name. |
| [getTitle()](#getTitle--) | Gets the title of the document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the document. |
| [getVersion()](#getVersion--) | Gets the version number of the application that created the document. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Sets the version number of the application that created the document. |
| [getContentTypeProperties()](#getContentTypeProperties--) | Gets the metadata package containing the content type properties. |
| [set(String propertyName, String value)](#set-java.lang.String-java.lang.String-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, boolean value)](#set-java.lang.String-boolean-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, Date value)](#set-java.lang.String-java.util.Date-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, int value)](#set-java.lang.String-int-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, double value)](#set-java.lang.String-double-) | Adds or replaces the metadata property with the specified name. |
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the document language.

**Returns:**
java.lang.String - The document language.
### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Sets the document language.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The document language. |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the document author.

**Returns:**
java.lang.String - The author.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sets the document author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The author. |

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
java.lang.String - Comments value.
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Sets the comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Comments value. |

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


Gets the content type.

**Returns:**
java.lang.String - The type of the content.
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Sets the content type.

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

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final Double getTotalEditingTime()
```


Gets the total editing time in minutes.

**Returns:**
java.lang.Double - The total editing time.
### setTotalEditingTime(Double value) {#setTotalEditingTime-java.lang.Double-}
```
public final void setTotalEditingTime(Double value)
```


Sets the total editing time in minutes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Double | The total editing time. |

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
java.lang.String - Keywords.
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Sets the keywords.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Keywords. |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Gets the time of the last saving in UTC.

**Returns:**
java.util.Date - The time of the last saving.
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Sets the time of the last saving in UTC.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The time of the last saving. |

### getLastPrintedDate() {#getLastPrintedDate--}
```
public final Date getLastPrintedDate()
```


Gets the last printed date in UTC.

**Returns:**
java.util.Date - The last printed date.
### setLastPrintedDate(Date value) {#setLastPrintedDate-java.util.Date-}
```
public final void setLastPrintedDate(Date value)
```


Sets the last printed date in UTC.

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


Gets the name of application.

**Returns:**
java.lang.String - The name of application.
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```


Sets the name of application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of application. |

### getRevision() {#getRevision--}
```
public final String getRevision()
```


Gets the document revision number.

**Returns:**
java.lang.String - The revision number.
### setRevision(String value) {#setRevision-java.lang.String-}
```
public final void setRevision(String value)
```


Sets the document revision number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The revision number. |

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


Gets the document template name.

**Returns:**
java.lang.String - The template.
### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public final void setTemplate(String value)
```


Sets the document template name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The template. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the title of the document.

**Returns:**
java.lang.String - The title.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets the title of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The title. |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


Gets the version number of the application that created the document.

**Returns:**
java.lang.String - The version.

--------------------

Its format is "00.0000",for example 12.0000
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


Sets the version number of the application that created the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The version.

--------------------

Its format is "00.0000",for example 12.0000 |

### getContentTypeProperties() {#getContentTypeProperties--}
```
public final SpreadsheetContentTypePackage getContentTypeProperties()
```


Gets the metadata package containing the content type properties.

**Returns:**
[SpreadsheetContentTypePackage](../../com.groupdocs.metadata.core/spreadsheetcontenttypepackage) - The metadata package containing the content type properties.
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

