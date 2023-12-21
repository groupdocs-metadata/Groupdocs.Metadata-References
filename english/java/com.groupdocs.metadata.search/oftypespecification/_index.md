---
title: OfTypeSpecification
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a specification that filters properties of a particular type.
type: docs
weight: 15
url: /java/com.groupdocs.metadata.search/oftypespecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class OfTypeSpecification extends Specification
```

Represents a specification that filters properties of a particular type.
## Constructors

| Constructor | Description |
| --- | --- |
| [OfTypeSpecification(MetadataPropertyType propertyType)](#OfTypeSpecification-com.groupdocs.metadata.core.MetadataPropertyType-) | Initializes a new instance of the  OfTypeSpecification  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPropertyType()](#getPropertyType--) | Gets the type of properties that satisfy the specification. |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### OfTypeSpecification(MetadataPropertyType propertyType) {#OfTypeSpecification-com.groupdocs.metadata.core.MetadataPropertyType-}
```
public OfTypeSpecification(MetadataPropertyType propertyType)
```


Initializes a new instance of the  OfTypeSpecification  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyType | [MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype) | The type of properties that satisfy the specification. |

### getPropertyType() {#getPropertyType--}
```
public final MetadataPropertyType getPropertyType()
```


Gets the type of properties that satisfy the specification.

**Returns:**
[MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype) - The type of properties that satisfy the specification.
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
