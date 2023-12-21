---
title: NotSpecification
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a composite specification that negates any other specification.
type: docs
weight: 14
url: /java/com.groupdocs.metadata.search/notspecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class NotSpecification extends Specification
```

Represents a composite specification that negates any other specification.
## Methods

| Method | Description |
| --- | --- |
| [getWrapped()](#getWrapped--) | Gets the base specification to be negated. |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### getWrapped() {#getWrapped--}
```
public final Specification getWrapped()
```


Gets the base specification to be negated.

**Returns:**
[Specification](../../com.groupdocs.metadata.search/specification) - The base specification to be negated.
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
