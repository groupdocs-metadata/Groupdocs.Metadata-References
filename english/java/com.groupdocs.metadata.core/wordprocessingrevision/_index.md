---
title: WordProcessingRevision
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a revision tracked change in a document.
type: docs
weight: 245
url: /java/com.groupdocs.metadata.core/wordprocessingrevision/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class WordProcessingRevision extends CustomPackage
```

Represents a revision (tracked change) in a document.

**Learn more**

 *  [Working with metadata in WordProcessing documents][]


[Working with metadata in WordProcessing documents]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Word+Processing+documents
## Methods

| Method | Description |
| --- | --- |
| [getAuthor()](#getAuthor--) | Gets the author of the revision. |
| [getDateTime()](#getDateTime--) | Gets the date/time of the revision. |
| [getRevisionType()](#getRevisionType--) | Gets the type of the revision. |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Gets the author of the revision.

**Returns:**
java.lang.String - The author of the revision.
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


Gets the date/time of the revision.

**Returns:**
java.util.Date - The date/time of the revision.
### getRevisionType() {#getRevisionType--}
```
public final WordProcessingRevisionType getRevisionType()
```


Gets the type of the revision.

**Returns:**
[WordProcessingRevisionType](../../com.groupdocs.metadata.core/wordprocessingrevisiontype) - The type of the revision.
