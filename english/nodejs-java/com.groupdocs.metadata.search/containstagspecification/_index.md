---
title: ContainsTagSpecification
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a specification that checks whether the passed property contains the specified tag.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.metadata.search/containstagspecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class ContainsTagSpecification extends Specification
```

Represents a specification that checks whether the passed property contains the specified tag.
## Constructors

| Constructor | Description |
| --- | --- |
| [ContainsTagSpecification(PropertyTag tag)](#ContainsTagSpecification-com.groupdocs.metadata.tagging.PropertyTag-) | Initializes a new instance of the  ContainsTagSpecification  class. |
## Methods

| Method | Description |
| --- | --- |
| [getTag()](#getTag--) | Gets the tag a property must contain to satisfy the specification. |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### ContainsTagSpecification(PropertyTag tag) {#ContainsTagSpecification-com.groupdocs.metadata.tagging.PropertyTag-}
```
public ContainsTagSpecification(PropertyTag tag)
```


Initializes a new instance of the  ContainsTagSpecification  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | [PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) | The tag a property must contain to satisfy the specification. |

### getTag() {#getTag--}
```
public final PropertyTag getTag()
```


Gets the tag a property must contain to satisfy the specification.

**Returns:**
[PropertyTag](../../com.groupdocs.metadata.tagging/propertytag) - The tag a property must contain to satisfy the specification.
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
