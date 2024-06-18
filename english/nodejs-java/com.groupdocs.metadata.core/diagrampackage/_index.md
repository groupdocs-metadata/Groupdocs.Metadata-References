---
title: DiagramPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a native metadata package in a diagram format.
type: docs
weight: 70
url: /nodejs-java/com.groupdocs.metadata.core/diagrampackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.DocumentPackage](../../com.groupdocs.metadata.core/documentpackage)
```
public class DiagramPackage extends DocumentPackage
```

Represents a native metadata package in a diagram format.

**Learn more**

 *  [Working with metadata in Diagrams][]

The following code sample demonstrates how to update built-in metadata properties in a diagram document.

> ```
> ```
> 
>  try (Metadata metadata = new Metadata(Constants.InputVdx)) {
>      DiagramRootPackage root = metadata.getRootPackageGeneric();
>      root.getDocumentProperties().setCreator("test author");
>      root.getDocumentProperties().setTimeCreated(new Date());
>      root.getDocumentProperties().setCompany("GroupDocs");
>      root.getDocumentProperties().setCategory("test category");
>      root.getDocumentProperties().setKeywords("metadata, built-in, update");
>      // ...
>      metadata.save(Constants.OutputVdx);
>  }
>  
> ```
> ```


[Working with metadata in Diagrams]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Diagrams
## Methods

| Method | Description |
| --- | --- |
| [getAlternateNames()](#getAlternateNames--) | Gets the alternate names for the document. |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | Sets the alternate names for the document. |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | Gets the full build number of the instance used to create the document. |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | Gets the build number of the instance last used to edit the document. |
| [getCategory()](#getCategory--) | Gets the descriptive text for the type of drawing, such as flowchart or office layout. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sets the descriptive text for the type of drawing, such as flowchart or office layout. |
| [getCompany()](#getCompany--) | Gets the user-entered information identifying the company creating the drawing or the company the drawing is being created for. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Sets the user-entered information identifying the company creating the drawing or the company the drawing is being created for. |
| [getCreator()](#getCreator--) | Gets the person who created or last updated the file. |
| [setCreator(String value)](#setCreator-java.lang.String-) | Sets the person who created or last updated the file. |
| [getDescription()](#getDescription--) | Gets a descriptive text string for the document. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Sets a descriptive text string for the document. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gets the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Sets the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). |
| [getKeywords()](#getKeywords--) | Gets a text string that identifies topics or other important information about the file, such as project name, client name, or version number. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sets a text string that identifies topics or other important information about the file, such as project name, client name, or version number. |
| [getLanguage()](#getLanguage--) | Gets the language of the document. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Sets the language of the document. |
| [getManager()](#getManager--) | Gets a user-entered text string identifying the person in charge of the project or department. |
| [setManager(String value)](#setManager-java.lang.String-) | Sets a user-entered text string identifying the person in charge of the project or department. |
| [getPreviewPicture()](#getPreviewPicture--) | Gets the preview picture. |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | Sets the preview picture. |
| [getSubject()](#getSubject--) | Gets a user-defined text string that describes the contents of the document. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets a user-defined text string that describes the contents of the document. |
| [getTemplate()](#getTemplate--) | Gets a string value specifying the file name of the template from which the document was created. |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | Sets a string value specifying the file name of the template from which the document was created. |
| [getTimeCreated()](#getTimeCreated--) | Gets a date and time value indicating when the document was created. |
| [setTimeCreated(Date value)](#setTimeCreated-java.util.Date-) | Sets a date and time value indicating when the document was created. |
| [getTimeEdited()](#getTimeEdited--) | Gets a date and time value indicating when the document was last edited. |
| [getTimePrinted()](#getTimePrinted--) | Gets a date and time value indicating when the document was last printed. |
| [getTimeSaved()](#getTimeSaved--) | Gets a date and time value indicating when the document was last saved. |
| [getTitle()](#getTitle--) | Gets a user-defined text string that serves as a descriptive title for the document. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets a user-defined text string that serves as a descriptive title for the document. |
| [set(String propertyName, String value)](#set-java.lang.String-java.lang.String-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, boolean value)](#set-java.lang.String-boolean-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, double value)](#set-java.lang.String-double-) | Adds or replaces the metadata property with the specified name. |
| [set(String propertyName, Date value)](#set-java.lang.String-java.util.Date-) | Adds or replaces the metadata property with the specified name. |
### getAlternateNames() {#getAlternateNames--}
```
public final String getAlternateNames()
```


Gets the alternate names for the document. Can be updated in VDX and VSX formats only.

**Returns:**
java.lang.String - The alternate names for the document.
### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public final void setAlternateNames(String value)
```


Sets the alternate names for the document. Can be updated in VDX and VSX formats only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The alternate names for the document. |

### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public final String getBuildNumberCreated()
```


Gets the full build number of the instance used to create the document.

**Returns:**
java.lang.String - The full build number of the instance used to create the document.
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public final String getBuildNumberEdited()
```


Gets the build number of the instance last used to edit the document.

**Returns:**
java.lang.String - The build number of the instance last used to edit the document.
### getCategory() {#getCategory--}
```
public final String getCategory()
```


Gets the descriptive text for the type of drawing, such as flowchart or office layout. This text can also be entered in the Microsoft Visio user interface in the Category box in the Properties dialog box.

**Returns:**
java.lang.String - The descriptive text for the type of drawing, such as flowchart or office layout.
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Sets the descriptive text for the type of drawing, such as flowchart or office layout. This text can also be entered in the Microsoft Visio user interface in the Category box in the Properties dialog box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive text for the type of drawing, such as flowchart or office layout. |

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Gets the user-entered information identifying the company creating the drawing or the company the drawing is being created for. Maximum length is 63 characters.

**Returns:**
java.lang.String - The user-entered information identifying the company creating the drawing or the company the drawing is being created for.
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Sets the user-entered information identifying the company creating the drawing or the company the drawing is being created for. Maximum length is 63 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The user-entered information identifying the company creating the drawing or the company the drawing is being created for. |

### getCreator() {#getCreator--}
```
public final String getCreator()
```


Gets the person who created or last updated the file. The maximum length is 63 characters..

**Returns:**
java.lang.String - The person who created or last updated the file.
### setCreator(String value) {#setCreator-java.lang.String-}
```
public final void setCreator(String value)
```


Sets the person who created or last updated the file. The maximum length is 63 characters..

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The person who created or last updated the file. |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets a descriptive text string for the document. Use this element to store important information about the document, such as its purpose, recent changes, or pending changes. The maximum is 191 characters.

**Returns:**
java.lang.String - A descriptive text string for the document.
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Sets a descriptive text string for the document. Use this element to store important information about the document, such as its purpose, recent changes, or pending changes. The maximum is 191 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A descriptive text string for the document. |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Gets the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). By default, a hyperlink path is relative to the current document unless a different path is specified in this element. Maximum length is 256 characters.

**Returns:**
java.lang.String - The path to be used for relative hyperlinks.
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Sets the path to be used for relative hyperlinks (hyperlinks for which the linked file location is described in relation to the Microsoft Visio diagram). By default, a hyperlink path is relative to the current document unless a different path is specified in this element. Maximum length is 256 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The path to be used for relative hyperlinks. |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Gets a text string that identifies topics or other important information about the file, such as project name, client name, or version number. The maximum string length is 63 characters.

**Returns:**
java.lang.String - A text string that identifies topics or other important information about the file, such as project name, client name, or version number.
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Sets a text string that identifies topics or other important information about the file, such as project name, client name, or version number. The maximum string length is 63 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A text string that identifies topics or other important information about the file, such as project name, client name, or version number. |

### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Gets the language of the document. Can be updated in VSD and VSDX formats only.

**Returns:**
java.lang.String - The language of the document.
### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Sets the language of the document. Can be updated in VSD and VSDX formats only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The language of the document. |

### getManager() {#getManager--}
```
public final String getManager()
```


Gets a user-entered text string identifying the person in charge of the project or department. The maximum length is 63 characters.

**Returns:**
java.lang.String - A user-entered text string identifying the person in charge of the project or department.
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Sets a user-entered text string identifying the person in charge of the project or department. The maximum length is 63 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A user-entered text string identifying the person in charge of the project or department. |

### getPreviewPicture() {#getPreviewPicture--}
```
public final byte[] getPreviewPicture()
```


Gets the preview picture.

**Returns:**
byte[] - The preview picture.
### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public final void setPreviewPicture(byte[] value)
```


Sets the preview picture.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The preview picture. |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets a user-defined text string that describes the contents of the document. Maximum length is 63 characters.

**Returns:**
java.lang.String - A user-defined text string that describes the contents of the document.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets a user-defined text string that describes the contents of the document. Maximum length is 63 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A user-defined text string that describes the contents of the document. |

### getTemplate() {#getTemplate--}
```
public final String getTemplate()
```


Gets a string value specifying the file name of the template from which the document was created.

**Returns:**
java.lang.String - A string value specifying the file name of the template from which the document was created.
### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public final void setTemplate(String value)
```


Sets a string value specifying the file name of the template from which the document was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A string value specifying the file name of the template from which the document was created. |

### getTimeCreated() {#getTimeCreated--}
```
public final Date getTimeCreated()
```


Gets a date and time value indicating when the document was created.

**Returns:**
java.util.Date - A date and time value indicating when the document was created.
### setTimeCreated(Date value) {#setTimeCreated-java.util.Date-}
```
public final void setTimeCreated(Date value)
```


Sets a date and time value indicating when the document was created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | A date and time value indicating when the document was created. |

### getTimeEdited() {#getTimeEdited--}
```
public final Date getTimeEdited()
```


Gets a date and time value indicating when the document was last edited.

**Returns:**
java.util.Date - A date and time value indicating when the document was last edited.
### getTimePrinted() {#getTimePrinted--}
```
public final Date getTimePrinted()
```


Gets a date and time value indicating when the document was last printed.

**Returns:**
java.util.Date - A date and time value indicating when the document was last printed.
### getTimeSaved() {#getTimeSaved--}
```
public final Date getTimeSaved()
```


Gets a date and time value indicating when the document was last saved.

**Returns:**
java.util.Date - A date and time value indicating when the document was last saved.
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets a user-defined text string that serves as a descriptive title for the document. Maximum length is 63 characters.

**Returns:**
java.lang.String - A user-defined text string that serves as a descriptive title for the document.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sets a user-defined text string that serves as a descriptive title for the document. Maximum length is 63 characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A user-defined text string that serves as a descriptive title for the document. |

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

