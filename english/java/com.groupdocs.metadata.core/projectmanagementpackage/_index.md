---
title: ProjectManagementPackage
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a native metadata package in a project management file.
type: docs
weight: 205
url: /java/com.groupdocs.metadata.core/projectmanagementpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DocumentPackage](../../com.groupdocs.metadata.core/documentpackage)
```
public final class ProjectManagementPackage extends DocumentPackage
```

Represents a native metadata package in a project management file.

**Learn more**

 *  [Working with metadata in ProjectManagement formats][]

This code sample demonstrates how to update built-in properties in a ProjectManagement document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputMpp)) {
>      ProjectManagementRootPackage root = metadata.getRootPackageGeneric();
>      root.getDocumentProperties().setAuthor("test author");
>      root.getDocumentProperties().setCreationDate(new Date());
>      root.getDocumentProperties().setCompany("GroupDocs");
>      root.getDocumentProperties().setComments("test comment");
>      root.getDocumentProperties().setKeywords("metadata, built-in, update");
>      // ...
>      metadata.save(Constants.OutputMpp);
>  }
>  
> ```
> ```


[Working with metadata in ProjectManagement formats]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+ProjectManagement+formats
## Methods

| Method | Description |
| --- | --- |
| [getAuthor()](#getAuthor--) | Gets the author of the project. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sets the author of the project. |
| [getCategory()](#getCategory--) | Gets the category. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sets the category. |
| [getComments()](#getComments--) | Gets the user comments. |
| [setComments(String value)](#setComments-java.lang.String-) | Sets the user comments. |
| [getCompany()](#getCompany--) | Gets the company. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Sets the company. |
| [getCreationDate()](#getCreationDate--) | Gets the creation date. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Sets the creation date. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gets the hyperlink base. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Sets the hyperlink base. |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets the keywords. |
| [getLastAuthor()](#getLastAuthor--) | Gets the last author. |
| [setLastAuthor(String value)](#setLastAuthor-java.lang.String-) | Sets the last author. |
| [getRevision()](#getRevision--) | Gets the revision number. |
| [setRevision(int value)](#setRevision-int-) | Sets the revision number. |
| [getSubject()](#getSubject--) | Gets the subject. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject. |
| [getTitle()](#getTitle--) | Gets the title. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title. |
| [getTemplate()](#getTemplate--) | Gets the template. |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | Sets the template. |
| [getManager()](#getManager--) | Gets the project manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets the project manager. |
| [getLastSaved()](#getLastSaved--) | Gets the date when the project was saved last time. |
| [setLastSaved(Date value)](#setLastSaved-java.util.Date-) | Sets the date when the project was saved last time. |
| [getSaveVersion()](#getSaveVersion--) | Gets the version of Microsoft Office Project from which a project file was saved. |
| [getLastPrinted()](#getLastPrinted--) | Gets the project's last print time. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Sets the project's last print time. |
| [set(String propertyName, String value)](#set-java.lang.String-java.lang.String-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, double value)](#set-java.lang.String-double-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, boolean value)](#set-java.lang.String-boolean-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, Date value)](#set-java.lang.String-java.util.Date-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, int value)](#set-java.lang.String-int-) | Adds or replaces the metadata property with the specified name. |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the author of the project.

**Returns:**
java.lang.String - The author of the project.
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sets the author of the project.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The author of the project. |

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


Gets the user comments.

**Returns:**
java.lang.String - The user comments.
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Sets the user comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The user comments. |

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

### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Gets the creation date.

**Returns:**
java.util.Date - The creation date.
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


Sets the creation date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The creation date. |

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

### getLastAuthor() {#getLastAuthor--}
```
public final String getLastAuthor()
```


Gets the last author.

**Returns:**
java.lang.String - The last author.
### setLastAuthor(String value) {#setLastAuthor-java.lang.String-}
```
public final void setLastAuthor(String value)
```


Sets the last author.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The last author. |

### getRevision() {#getRevision--}
```
public final int getRevision()
```


Gets the revision number.

**Returns:**
int - The revision number.
### setRevision(int value) {#setRevision-int-}
```
public final void setRevision(int value)
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


Gets the title.

**Returns:**
java.lang.String - The title.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets the title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The title. |

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

### getManager() {#getManager--}
```
public final String getManager()
```


Gets the project manager.

**Returns:**
java.lang.String - The project manager.
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Sets the project manager.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The project manager. |

### getLastSaved() {#getLastSaved--}
```
public final Date getLastSaved()
```


Gets the date when the project was saved last time.

**Returns:**
java.util.Date - The date when the project was saved last time.
### setLastSaved(Date value) {#setLastSaved-java.util.Date-}
```
public final void setLastSaved(Date value)
```


Sets the date when the project was saved last time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The date when the project was saved last time. |

### getSaveVersion() {#getSaveVersion--}
```
public final int getSaveVersion()
```


Gets the version of Microsoft Office Project from which a project file was saved.

**Returns:**
int - The version of Microsoft Office Project from which a project file was saved.
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Gets the project's last print time.

**Returns:**
java.util.Date - The project's last print time.
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Sets the project's last print time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | The project's last print time. |

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

