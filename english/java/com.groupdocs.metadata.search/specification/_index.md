---
title: Specification
second_title: GroupDocs.Signature for Java API Reference
description: Provides a base abstract class for search specifications that can be combined using logical operators.
type: docs
weight: 17
url: /java/com.groupdocs.metadata.search/specification/
---
**Inheritance:**
java.lang.Object
```
public abstract class Specification
```

Provides a base abstract class for search specifications that can be combined using logical operators.
## Constructors

| Constructor | Description |
| --- | --- |
| [Specification()](#Specification--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
| [and(Specification other)](#and-com.groupdocs.metadata.search.Specification-) | Combines two search specifications using the logical AND operator. |
| [or(Specification other)](#or-com.groupdocs.metadata.search.Specification-) | Combines two search specifications using the logical OR operator. |
| [not()](#not--) | Negates the specification. |
### Specification() {#Specification--}
```
public Specification()
```


### isSatisfiedBy(MetadataProperty candidate) {#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-}
```
public abstract boolean isSatisfiedBy(MetadataProperty candidate)
```


Verifies whether a  MetadataProperty  satisfies the specification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| candidate | [MetadataProperty](../../com.groupdocs.metadata.core/metadataproperty) | A metadata property to test. |

**Returns:**
boolean - True, if the passed property satisfies the specification; otherwise, false.
### and(Specification other) {#and-com.groupdocs.metadata.search.Specification-}
```
public final Specification and(Specification other)
```


Combines two search specifications using the logical AND operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to combine with. |

**Returns:**
[Specification](../../com.groupdocs.metadata.search/specification) - A composite specification.
### or(Specification other) {#or-com.groupdocs.metadata.search.Specification-}
```
public final Specification or(Specification other)
```


Combines two search specifications using the logical OR operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Specification](../../com.groupdocs.metadata.search/specification) | A specification to combine with. |

**Returns:**
[Specification](../../com.groupdocs.metadata.search/specification) - A composite specification.
### not() {#not--}
```
public final Specification not()
```


Negates the specification.

**Returns:**
[Specification](../../com.groupdocs.metadata.search/specification) - A composite specification.
