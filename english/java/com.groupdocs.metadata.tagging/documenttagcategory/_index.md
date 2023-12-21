---
title: DocumentTagCategory
second_title: GroupDocs.Metadata for Java API Reference
description: Provides tags that are applied to document-specific properties only.
type: docs
weight: 12
url: /java/com.groupdocs.metadata.tagging/documenttagcategory/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.tagging.TagCategory](../../com.groupdocs.metadata.tagging/tagcategory)
```
public class DocumentTagCategory extends TagCategory
```

Provides tags that are applied to document-specific properties only. The tags can be useful to determine from which part of an office document a property was extracted.
## Methods

| Method | Description |
| --- | --- |
| [getBuiltIn()](#getBuiltIn--) | Gets the tag that indicates that the property it labels is built-in. |
| [getReadOnly()](#getReadOnly--) | Gets the tag that indicates that the property it labels is read-only and cannot be changed by GroupDocs.Metadata. |
| [getHiddenData()](#getHiddenData--) | Gets the tag indicating a document part that is not visible for regular users. |
| [getUserComment()](#getUserComment--) | Gets the tag that labels user comments shown in the document content. |
| [getPage()](#getPage--) | Gets the tag that denotes a property holding information about a document page. |
| [getStatistic()](#getStatistic--) | Gets the tag indicating a property containing document statistics (word count, character count, etc). |
| [getField()](#getField--) | Gets the tag that denotes a property holding information about a form field or calculated field extracted from a document. |
| [getRevision()](#getRevision--) | Get the tag labeling a property containing information about a document revision (tracked change). |
### getBuiltIn() {#getBuiltIn--}
```
public final PropertyTag getBuiltIn()
```


Gets the tag that indicates that the property it labels is built-in.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that indicates that the property it labels is built-in.
### getReadOnly() {#getReadOnly--}
```
public final PropertyTag getReadOnly()
```


Gets the tag that indicates that the property it labels is read-only and cannot be changed by GroupDocs.Metadata.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that indicates that the property it labels is read-only and cannot be changed by GroupDocs.Metadata.
### getHiddenData() {#getHiddenData--}
```
public final PropertyTag getHiddenData()
```


Gets the tag indicating a document part that is not visible for regular users.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag indicating a document part that is not visible for regular users.
### getUserComment() {#getUserComment--}
```
public final PropertyTag getUserComment()
```


Gets the tag that labels user comments shown in the document content.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels user comments shown in the document content.
### getPage() {#getPage--}
```
public final PropertyTag getPage()
```


Gets the tag that denotes a property holding information about a document page.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes a property holding information about a document page.
### getStatistic() {#getStatistic--}
```
public final PropertyTag getStatistic()
```


Gets the tag indicating a property containing document statistics (word count, character count, etc).

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag indicating a property containing document statistics (word count, character count, etc).
### getField() {#getField--}
```
public final PropertyTag getField()
```


Gets the tag that denotes a property holding information about a form field or calculated field extracted from a document.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes a property holding information about a form field or calculated field extracted from a document.
### getRevision() {#getRevision--}
```
public final PropertyTag getRevision()
```


Get the tag labeling a property containing information about a document revision (tracked change).

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag labeling a property containing information about a document revision (tracked change).
