---
title: AnySpecification
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a specification that applies no filters to a property.
type: docs
weight: 11
url: /java/com.groupdocs.metadata.search/anyspecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class AnySpecification extends Specification
```

Represents a specification that applies no filters to a property.
## Constructors

| Constructor | Description |
| --- | --- |
| [AnySpecification()](#AnySpecification--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### AnySpecification() {#AnySpecification--}
```
public AnySpecification()
```


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
