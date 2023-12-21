---
title: PresentationInspectionPackage
second_title: GroupDocs.Signature for Java API Reference
description: Contains information about presentation parts that can be considered as metadata in some cases.
type: docs
weight: 198
url: /java/com.groupdocs.metadata.core/presentationinspectionpackage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage)
```
public final class PresentationInspectionPackage extends CustomPackage
```

Contains information about presentation parts that can be considered as metadata in some cases.

**Learn more**

 *  [Working with metadata in Presentations][]


[Working with metadata in Presentations]: https://docs.groupdocs.com/display/metadatajava/Working+with+metadata+in+Presentations
## Methods

| Method | Description |
| --- | --- |
| [getHiddenSlides()](#getHiddenSlides--) | Gets an array of the hidden slides. |
| [getComments()](#getComments--) | Gets an array of the comments. |
| [removeProperties(Specification specification)](#removeProperties-com.groupdocs.metadata.search.Specification-) | Removes metadata properties satisfying a specification. |
| [clearComments()](#clearComments--) | Removes all detected user comments from the presentation. |
| [clearHiddenSlides()](#clearHiddenSlides--) | Removes all detected hidden slides from the presentation. |
| [sanitize()](#sanitize--) | Removes writable metadata properties from the package. |
### getHiddenSlides() {#getHiddenSlides--}
```
public final PresentationSlide[] getHiddenSlides()
```


Gets an array of the hidden slides.

**Returns:**
com.groupdocs.metadata.core.PresentationSlide[] - The hidden slides.
### getComments() {#getComments--}
```
public final PresentationComment[] getComments()
```


Gets an array of the comments.

**Returns:**
com.groupdocs.metadata.core.PresentationComment[] - The comments.
### removeProperties(Specification specification) {#removeProperties-com.groupdocs.metadata.search.Specification-}
```
public int removeProperties(Specification specification)
```


Removes metadata properties satisfying a specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specification | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to test each metadata property for a condition. |

**Returns:**
int - The number of affected properties.
### clearComments() {#clearComments--}
```
public final void clearComments()
```


Removes all detected user comments from the presentation.

### clearHiddenSlides() {#clearHiddenSlides--}
```
public final void clearHiddenSlides()
```


Removes all detected hidden slides from the presentation.

### sanitize() {#sanitize--}
```
public int sanitize()
```


Removes writable metadata properties from the package. The operation is recursive so it affects all nested packages as well.

**Returns:**
int - The number of affected properties.
