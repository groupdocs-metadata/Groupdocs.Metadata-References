---
title: AndSpecification
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a composite specification that uses the logical AND operator to combine two given search specifications.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.metadata.search/andspecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class AndSpecification extends Specification
```

Represents a composite specification that uses the logical AND operator to combine two given search specifications.
## Methods

| Method | Description |
| --- | --- |
| [getLeft()](#getLeft--) | Gets the left specification. |
| [getRight()](#getRight--) | Gets the right specification. |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### getLeft() {#getLeft--}
```
public final Specification getLeft()
```


Gets the left specification.

**Returns:**
[Specification](../../com.groupdocs.metadata.search/specification) - The left specification.
### getRight() {#getRight--}
```
public final Specification getRight()
```


Gets the right specification.

**Returns:**
[Specification](../../com.groupdocs.metadata.search/specification) - The right specification.
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
