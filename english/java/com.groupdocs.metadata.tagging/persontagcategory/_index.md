---
title: PersonTagCategory
second_title: GroupDocs.Signature for Java API Reference
description: Provides tags that mark metadata properties holding information about the people contributed to file or intellectual content creation.
type: docs
weight: 15
url: /java/com.groupdocs.metadata.tagging/persontagcategory/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.tagging.TagCategory](../../com.groupdocs.metadata.tagging/tagcategory)
```
public class PersonTagCategory extends TagCategory
```

Provides tags that mark metadata properties holding information about the people contributed to file or intellectual content creation. These tags can help you to find the document creator, editor or even the client for whom the work was performed. Despite the name of the category some metadata properties marked with the tags can contain a company name rather than a person's name.
## Methods

| Method | Description |
| --- | --- |
| [getCreator()](#getCreator--) | Gets the tag that denotes the original author of a file/document. |
| [getContributor()](#getContributor--) | Gets the tag that labels a property containing the name of a person who somehow contributed to file creation. |
| [getEditor()](#getEditor--) | Gets the tag that labels a person who edited a file. |
| [getModel()](#getModel--) | Gets the tag that denotes information about a person the content of the file is about. |
| [getClient()](#getClient--) | Gets the tag that labels information about the client for whom the file/intellectual content was created. |
| [getManager()](#getManager--) | Gets the tag that labels information about a person who managed the making process of a file. |
| [getPublisher()](#getPublisher--) | Gets the tag marking a person responsible for making the file available. |
| [getArtist()](#getArtist--) | Gets the tag that denotes the original performer of a file. |
| [getRecipient()](#getRecipient--) | Gets the tag that denotes the original recipients of a mail. |
### getCreator() {#getCreator--}
```
public final PropertyTag getCreator()
```


Gets the tag that denotes the original author of a file/document.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes the original author of a file/document.
### getContributor() {#getContributor--}
```
public final PropertyTag getContributor()
```


Gets the tag that labels a property containing the name of a person who somehow contributed to file creation. Please note that the tag is not applied towards metadata properties marked with more specific tags from this category. E.g. if a property labeled with the Creator tag.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a property containing the name of a person who somehow contributed to file creation.
### getEditor() {#getEditor--}
```
public final PropertyTag getEditor()
```


Gets the tag that labels a person who edited a file. The tag is usually used to mark a property containing information about the last editor.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels a person who edited a file.
### getModel() {#getModel--}
```
public final PropertyTag getModel()
```


Gets the tag that denotes information about a person the content of the file is about. For photos that is a person shown in the image.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes information about a person the content of the file is about.
### getClient() {#getClient--}
```
public final PropertyTag getClient()
```


Gets the tag that labels information about the client for whom the file/intellectual content was created.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels information about the client for whom the file/intellectual content was created.
### getManager() {#getManager--}
```
public final PropertyTag getManager()
```


Gets the tag that labels information about a person who managed the making process of a file.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that labels information about a person who managed the making process of a file.
### getPublisher() {#getPublisher--}
```
public final PropertyTag getPublisher()
```


Gets the tag marking a person responsible for making the file available.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag marking a person responsible for making the file available.
### getArtist() {#getArtist--}
```
public final PropertyTag getArtist()
```


Gets the tag that denotes the original performer of a file.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes the original performer of a file.
### getRecipient() {#getRecipient--}
```
public final PropertyTag getRecipient()
```


Gets the tag that denotes the original recipients of a mail.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag that denotes the original recipients of a mail.
