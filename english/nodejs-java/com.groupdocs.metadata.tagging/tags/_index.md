---
title: Tags
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Contains various sets of tags with which most important metadata properties are marked.
type: docs
weight: 19
url: /nodejs-java/com.groupdocs.metadata.tagging/tags/
---
**Inheritance:**
java.lang.Object
```
public class Tags
```

Contains various sets of tags with which most important metadata properties are marked. The tags allow you to find and update metadata properties in different packages regardless of the metadata standard and file format.
## Constructors

| Constructor | Description |
| --- | --- |
| [Tags()](#Tags--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPerson()](#getPerson--) | Gets a set of tags that mark metadata properties holding information about the people contributed to file or intellectual content creation. |
| [getTool()](#getTool--) | Gets the tags intended to mark metadata properties related to the tools (software and hardware) that were used to create a file. |
| [getTime()](#getTime--) | Gets a set of tags that mark metadata properties used to describe the lifecycle of a file. |
| [getContent()](#getContent--) | Gets the tags that are attached to metadata properties describing the content of a file. |
| [getPropertyType()](#getPropertyType--) | Gets a set of tags that bear additional information about the type of a property rather than about its purpose. |
| [getDocument()](#getDocument--) | Gets a set of tags that are applied to document-specific properties only. |
| [getOrigin()](#getOrigin--) | Gets the tags that help a user to determine the origin of a file (e.g. |
| [getCorporate()](#getCorporate--) | Gets a set of tags intended to mark metadata properties related to a company that participated in file creation. |
| [getLegal()](#getLegal--) | Gets a set of tags that are attached to metadata properties holding information about the owners of the file content and the rules under which the content can be used. |
### Tags() {#Tags--}
```
public Tags()
```


### getPerson() {#getPerson--}
```
public static PersonTagCategory getPerson()
```


Gets a set of tags that mark metadata properties holding information about the people contributed to file or intellectual content creation. These tags can help you to find the document creator, editor or even the client for whom the work was performed. Despite the name of the category some metadata properties marked with the tags can contain a company name rather than a person's name.

**Returns:**
[PersonTagCategory](../../com.groupdocs.metadata.tagging/persontagcategory) - A set of tags that mark metadata properties holding information about the people contributed to file or intellectual content creation.
### getTool() {#getTool--}
```
public static ToolTagCategory getTool()
```


Gets the tags intended to mark metadata properties related to the tools (software and hardware) that were used to create a file.

**Returns:**
[ToolTagCategory](../../com.groupdocs.metadata.tagging/tooltagcategory) - The tags intended to mark metadata properties related to the tools (software and hardware) that were used to create a file.
### getTime() {#getTime--}
```
public static TimeTagCategory getTime()
```


Gets a set of tags that mark metadata properties used to describe the lifecycle of a file. The tags deal with time points when a file or intellectual content was created, edited, printed, etc.

**Returns:**
[TimeTagCategory](../../com.groupdocs.metadata.tagging/timetagcategory) - A set of tags that mark metadata properties used to describe the lifecycle of a file.
### getContent() {#getContent--}
```
public static ContentTagCategory getContent()
```


Gets the tags that are attached to metadata properties describing the content of a file. The tags are useful to find out the content language, type (genre), subject, rating, etc.

**Returns:**
[ContentTagCategory](../../com.groupdocs.metadata.tagging/contenttagcategory) - The tags that are attached to metadata properties describing the content of a file.
### getPropertyType() {#getPropertyType--}
```
public static PropertyTypeTagCategory getPropertyType()
```


Gets a set of tags that bear additional information about the type of a property rather than about its purpose. Using these tags you can detect metadata properties that contain URL links to external resources, properties describing fonts, colors, geolocation and so on.

**Returns:**
[PropertyTypeTagCategory](../../com.groupdocs.metadata.tagging/propertytypetagcategory)
### getDocument() {#getDocument--}
```
public static DocumentTagCategory getDocument()
```


Gets a set of tags that are applied to document-specific properties only. The tags can be useful to determine from which part of an office document a property was extracted.

**Returns:**
[DocumentTagCategory](../../com.groupdocs.metadata.tagging/documenttagcategory) - A set of tags that are applied to document-specific properties only.
### getOrigin() {#getOrigin--}
```
public static OriginTagCategory getOrigin()
```


Gets the tags that help a user to determine the origin of a file (e.g. template or another source).

**Returns:**
[OriginTagCategory](../../com.groupdocs.metadata.tagging/origintagcategory) - The tags that help a user to determine the origin of a file (e.g. template or another source).
### getCorporate() {#getCorporate--}
```
public static CorporateTagCategory getCorporate()
```


Gets a set of tags intended to mark metadata properties related to a company that participated in file creation.

**Returns:**
[CorporateTagCategory](../../com.groupdocs.metadata.tagging/corporatetagcategory) - A set of tags intended to mark metadata properties related to a company that participated in file creation.
### getLegal() {#getLegal--}
```
public static LegalTagCategory getLegal()
```


Gets a set of tags that are attached to metadata properties holding information about the owners of the file content and the rules under which the content can be used.

**Returns:**
[LegalTagCategory](../../com.groupdocs.metadata.tagging/legaltagcategory) - A set of tags that are attached to metadata properties holding information about the owners of the file content and the rules under which the content can be used.
