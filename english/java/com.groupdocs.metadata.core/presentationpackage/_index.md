---
title: PresentationPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a native metadata package in a presentation.
type: docs
weight: 201
url: /java/com.groupdocs.metadata.core/presentationpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DocumentPackage](../../com.groupdocs.metadata.core/documentpackage)
```
public class PresentationPackage extends DocumentPackage
```

Represents a native metadata package in a presentation.

**Learn more**

 *  [Working with metadata in Presentations][]

This example demonstrates how to update built-in metadata properties in a presentation.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputPptx)) {
>      PresentationRootPackage root = metadata.getRootPackageGeneric();
>      root.getDocumentProperties().setAuthor("test author");
>      root.getDocumentProperties().setCreatedTime(new Date());
>      root.getDocumentProperties().setCompany("GroupDocs");
>      root.getDocumentProperties().setCategory("test category");
>      root.getDocumentProperties().setKeywords("metadata, built-in, update");
>      // ...
>      metadata.save(Constants.OutputPptx);
>  }
>  
> ```
> ```


[Working with metadata in Presentations]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Presentations
## Methods

| Method | Description |
| --- | --- |
| [getApplicationTemplate()](#getApplicationTemplate--) | Gets the application template. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Sets the application template. |
| [getAuthor()](#getAuthor--) | Gets the document's author. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the document's author. |
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
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getLastPrintedDate()](#getLastPrintedDate--) | Gets the last printed date. |
| [setLastPrintedDate(Date value)](#setLastPrintedDate-java.util.Date-) | Sets the last printed date. |
| [getLastSavedTime()](#getLastSavedTime--) | Gets the date and time when the presentation was modified last time. |
| [getLastSavedBy()](#getLastSavedBy--) | Gets the name of the last author. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Sets the name of the last author. |
| [getManager()](#getManager--) | Gets the manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets the manager. |
| [getNameOfApplication()](#getNameOfApplication--) | Gets the name of the application created the document. |
| [getRevisionNumber()](#getRevisionNumber--) | Gets the revision number. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Sets the revision number. |
| [getSubject()](#getSubject--) | Gets the subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject. |
| [getTitle()](#getTitle--) | Gets the title of the document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the document. |
| [getVersion()](#getVersion--) | Gets the application version. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gets the hyperlink base. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Sets the hyperlink base. |
| [getPresentationFormat()](#getPresentationFormat--) | Gets the presentation format. |
| [getSharedDoc()](#getSharedDoc--) | Gets a value indicating whether the presentation is shared between multiple people. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Sets a value indicating whether the presentation is shared between multiple people. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Gets the total editing time of the document. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Sets the total editing time of the document. |
| [set(String propertyName, String value)](#set-java.lang.String-java.lang.String-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, boolean value)](#set-java.lang.String-boolean-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, Date value)](#set-java.lang.String-java.util.Date-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, int value)](#set-java.lang.String-int-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, double value)](#set-java.lang.String-double-) | Adds or replaces the metadata property with the specified name. |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```


Gets the application template.

**Returns:**
java.lang.String - The application template.
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```


Sets the application template.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The application template. |

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


Gets the content status. Can be updated in a PPTX document only.

**Returns:**
java.lang.String - The content status.

--------------------

Can be updated in a PPTX document only. Read-only for other supported formats.
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Sets the content status. Can be updated in a PPTX document only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The content status.

--------------------

Can be updated in a PPTX document only. Read-only for other supported formats. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Gets the content type. Can be updated in a PPTX document only.

**Returns:**
java.lang.String - The type of the content.

--------------------

Can be updated in a PPTX document only. Read-only for other supported formats.
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Sets the content type. Can be updated in a PPTX document only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The type of the content.

--------------------

Can be updated in a PPTX document only. Read-only for other supported formats. |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Gets the document created date.

**Returns:**
java.util.Date - The document created date.
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Sets the document created date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The document created date. |

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

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Gets the date and time when the presentation was modified last time.

**Returns:**
java.util.Date - The last saved time.
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Gets the name of the last author.

**Returns:**
java.lang.String - The last saved by.
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Sets the name of the last author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The last saved by. |

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


Gets the name of the application created the document.

**Returns:**
java.lang.String - The name of the application.
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Gets the revision number.

**Returns:**
int - The revision number.
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Sets the revision number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The revision number. |

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


Gets the application version.

**Returns:**
java.lang.String - The application version.
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Gets the hyperlink base.

**Returns:**
java.lang.String - The hyperlink base.

--------------------

Read-only in old PPT.
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Sets the hyperlink base.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The hyperlink base.

--------------------

Read-only in old PPT. |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```


Gets the presentation format.

**Returns:**
java.lang.String - The presentation format.
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Gets a value indicating whether the presentation is shared between multiple people. Can be updated in a PPTX document only.

**Returns:**
boolean -  true  if the presentation shared between multiple people; otherwise,  false .

--------------------

Can be updated in a PPTX document only. Read-only for other formats like PPT, POT etc.
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Sets a value indicating whether the presentation is shared between multiple people. Can be updated in a PPTX document only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if the presentation shared between multiple people; otherwise,  false .

--------------------

Can be updated in a PPTX document only. Read-only for other formats like PPT, POT etc. |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```


Gets the total editing time of the document.

**Returns:**
double - The total editing time of the document.
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```


Sets the total editing time of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The total editing time of the document. |

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

