---
title: WithNameSpecification
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents a specification that filters properties with a particular name.
type: docs
weight: 18
url: /nodejs-java/com.groupdocs.metadata.search/withnamespecification/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.search.Specification](../../com.groupdocs.metadata.search/specification)
```
public class WithNameSpecification extends Specification
```

Represents a specification that filters properties with a particular name.
## Constructors

| Constructor | Description |
| --- | --- |
| [WithNameSpecification(String propertyName)](#WithNameSpecification-java.lang.String-) | Initializes a new instance of the  WithNameSpecification  class. |
| [WithNameSpecification(String propertyName, boolean ignoreCase)](#WithNameSpecification-java.lang.String-boolean-) | Initializes a new instance of the  WithNameSpecification  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPropertyName()](#getPropertyName--) | Gets the name of properties that satisfy the specification. |
| [getIgnoreCase()](#getIgnoreCase--) | Gets a value indicating whether the case of the strings being compared should be ignored. |
| [isSatisfiedBy(MetadataProperty candidate)](#isSatisfiedBy-com.groupdocs.metadata.core.MetadataProperty-) | Verifies whether a  MetadataProperty  satisfies the specification. |
### WithNameSpecification(String propertyName) {#WithNameSpecification-java.lang.String-}
```
public WithNameSpecification(String propertyName)
```


Initializes a new instance of the  WithNameSpecification  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The type of properties that satisfy the specification. |

### WithNameSpecification(String propertyName, boolean ignoreCase) {#WithNameSpecification-java.lang.String-boolean-}
```
public WithNameSpecification(String propertyName, boolean ignoreCase)
```


Initializes a new instance of the  WithNameSpecification  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | The type of properties that satisfy the specification. |
| ignoreCase | boolean | A value indicating whether the case of the strings being compared should be ignored. |

### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Gets the name of properties that satisfy the specification.

**Returns:**
java.lang.String - The name of properties that satisfy the specification.
### getIgnoreCase() {#getIgnoreCase--}
```
public final boolean getIgnoreCase()
```


Gets a value indicating whether the case of the strings being compared should be ignored.

**Returns:**
boolean - True if the case should be ignored; otherwise, false.
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
