---
title: FallsIntoCategorySpecification
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a specification that verifies whether the passed property falls into a particular category i.e.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.metadata.search/fallsintocategoryspecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class FallsIntoCategorySpecification extends Specification
```

Represents a specification that verifies whether the passed property falls into a particular category (i.e. contains tags from the specified category).
## Constructors

| Constructor | Description |
| --- | --- |
| [FallsIntoCategorySpecification(TagCategory category)](#FallsIntoCategorySpecification-com.groupdocs.metadata.tagging.TagCategory-) | Initializes a new instance of the  FallsIntoCategorySpecification  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCategory()](#getCategory--) | Gets the category into which a property must fall to satisfy the specification. |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### FallsIntoCategorySpecification(TagCategory category) {#FallsIntoCategorySpecification-com.groupdocs.metadata.tagging.TagCategory-}
```
public FallsIntoCategorySpecification(TagCategory category)
```


Initializes a new instance of the  FallsIntoCategorySpecification  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| category | [TagCategory](../../com.groupdocs.metadata.tagging/tagcategory) | The category into which a property must fall to satisfy the specification. |

### getCategory() {#getCategory--}
```
public final TagCategory getCategory()
```


Gets the category into which a property must fall to satisfy the specification.

**Returns:**
[TagCategory](../../com.groupdocs.metadata.tagging/tagcategory) - The category into which a property must fall to satisfy the specification.
### isSatisfiedBy(MetadataProperty candidate) {#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-}
```
public boolean isSatisfiedBy(MetadataProperty candidate)
```


Verifies whether a  MetadataProperty  satisfies the specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [MetadataProperty](../../com.groupdocs.metadata.core/metadataproperty) | A metadata property to test. |

**Returns:**
boolean - True, if the passed property satisfies the specification; otherwise, false.
