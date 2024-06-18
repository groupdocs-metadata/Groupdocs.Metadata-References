---
title: CadPackage
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents CAD Computer-aided design metadata.
type: docs
weight: 30
url: /nodejs-java/com.groupdocs.metadata.core/cadpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class CadPackage extends CustomPackage
```

Represents CAD (Computer-aided design) metadata.

**Learn more**

 *  [Working with CAD metadata][]


[Working with CAD metadata]: https://docs.groupdocs.com/display/metadatajava/Working+with+CAD+metadata
## Methods

| Method | Description |
| --- | --- |
| [getAcadVersion()](#getAcadVersion--) | Gets the AutoCAD drawing database version number. |
| [getHeight()](#getHeight--) | Gets the drawing height. |
| [getWidth()](#getWidth--) | Gets the drawing width. |
| [getAuthor()](#getAuthor--) | Gets the drawing author. |
| [getComments()](#getComments--) | Gets the user comments. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Gets the hyperlink base. |
| [getKeywords()](#getKeywords--) | Gets the keywords. |
| [getLastSavedBy()](#getLastSavedBy--) | Gets the name of the last editor. |
| [getRevisionNumber()](#getRevisionNumber--) | Gets the revision number. |
| [getSubject()](#getSubject--) | Gets the subject. |
| [getTitle()](#getTitle--) | Gets the title. |
| [getCreatedDateTime()](#getCreatedDateTime--) | Gets the date and time when the drawing was created. |
| [getModifiedDateTime()](#getModifiedDateTime--) | Gets the date and time when the drawing was modified. |
| [getCustomProperties()](#getCustomProperties--) | Gets the package containing custom metadata properties. |
### getAcadVersion() {#getAcadVersion--}
```
public final CadAcadVersion getAcadVersion()
```


Gets the AutoCAD drawing database version number.

**Returns:**
[CadAcadVersion](../../com.groupdocs.metadata.core/cadacadversion) - The AutoCAD drawing database version number.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the drawing height.

**Returns:**
int - The drawing height.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the drawing width.

**Returns:**
int - The drawing width.
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the drawing author.

**Returns:**
java.lang.String - The drawing author.
### getComments() {#getComments--}
```
public final String getComments()
```


Gets the user comments.

**Returns:**
java.lang.String - The user comments.
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Gets the hyperlink base.

**Returns:**
java.lang.String - The hyperlink base.
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Gets the keywords.

**Returns:**
java.lang.String - The keywords.
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Gets the name of the last editor.

**Returns:**
java.lang.String - The name of the last editor.
### getRevisionNumber() {#getRevisionNumber--}
```
public final String getRevisionNumber()
```


Gets the revision number.

**Returns:**
java.lang.String - The revision number.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject.

**Returns:**
java.lang.String - The subject.
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets the title.

**Returns:**
java.lang.String - The title.
### getCreatedDateTime() {#getCreatedDateTime--}
```
public final Date getCreatedDateTime()
```


Gets the date and time when the drawing was created.

**Returns:**
java.util.Date - The date and time when the drawing was created.
### getModifiedDateTime() {#getModifiedDateTime--}
```
public final Date getModifiedDateTime()
```


Gets the date and time when the drawing was modified.

**Returns:**
java.util.Date - The date and time when the drawing was modified.
### getCustomProperties() {#getCustomProperties--}
```
public final CadCustomPropertyPackage getCustomProperties()
```


Gets the package containing custom metadata properties.

**Returns:**
[CadCustomPropertyPackage](../../com.groupdocs.metadata.core/cadcustompropertypackage) - The package containing custom metadata properties.
