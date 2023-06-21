---
title: MetadataProperty
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a metadata property.
type: docs
weight: 160
url: /java/com.groupdocs.metadata.core/metadataproperty/
---
**Inheritance:**
java.lang.Object
```
public class MetadataProperty
```

Represents a metadata property.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the property name. |
| [getValue()](#getValue--) | Gets the property value. |
| [getInterpretedValue()](#getInterpretedValue--) | Gets the interpreted property value, if available. |
| [getDescriptor()](#getDescriptor--) | Gets the descriptor associated with the metadata property. |
| [getTags()](#getTags--) | Gets a collection of tags associated with the property. |
### getName() {#getName--}
```
public final String getName()
```


Gets the property name.

**Returns:**
java.lang.String - The property name.
### getValue() {#getValue--}
```
public final PropertyValue getValue()
```


Gets the property value.

**Returns:**
[PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) - The property value.
### getInterpretedValue() {#getInterpretedValue--}
```
public final PropertyValue getInterpretedValue()
```


Gets the interpreted property value, if available. The interpreted value is a user-friendly form of the original property value. For example, it returns a human-readable string instead of numeric flags and ids, if necessary, translates byte arrays to text, etc.

**Returns:**
[PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) - The interpreted property value, if available.
### getDescriptor() {#getDescriptor--}
```
public final PropertyDescriptor getDescriptor()
```


Gets the descriptor associated with the metadata property.

**Returns:**
[PropertyDescriptor](../../com.groupdocs.metadata.core/propertydescriptor) - The descriptor associated with the metadata property.
### getTags() {#getTags--}
```
public final IReadOnlyList<PropertyTag> getTags()
```


Gets a collection of tags associated with the property.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A collection of tags associated with the property.
