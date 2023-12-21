---
title: PropertyDescriptor
second_title: GroupDocs.Metadata for Java API Reference
description: Represents a descriptor of a property that can be accessed through the GroupDocs.Metadata search engine.
type: docs
weight: 206
url: /java/com.groupdocs.metadata.core/propertydescriptor/
---
**Inheritance:**
java.lang.Object
```
public class PropertyDescriptor
```

Represents a descriptor of a property that can be accessed through the GroupDocs.Metadata search engine.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the property name. |
| [getType()](#getType--) | Gets the property type. |
| [getAccessLevel()](#getAccessLevel--) | Gets the property access level. |
| [getTags()](#getTags--) | Gets a collection of tags associated with the property. |
| [getInterpreter()](#getInterpreter--) | Gets the property value interpreter. |
### getName() {#getName--}
```
public final String getName()
```


Gets the property name.

**Returns:**
java.lang.String - The property name.
### getType() {#getType--}
```
public final MetadataPropertyType getType()
```


Gets the property type.

**Returns:**
[MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype) - The property type.
### getAccessLevel() {#getAccessLevel--}
```
public PropertyAccessLevels getAccessLevel()
```


Gets the property access level.

**Returns:**
[PropertyAccessLevels](../../com.groupdocs.metadata.core/propertyaccesslevels) - The property access level.
### getTags() {#getTags--}
```
public final IReadOnlyList<PropertyTag> getTags()
```


Gets a collection of tags associated with the property.

**Returns:**
[IReadOnlyList](../../com.groupdocs.metadata.core/ireadonlylist) - A collection of tags associated with the property.
### getInterpreter() {#getInterpreter--}
```
public final ValueInterpreter getInterpreter()
```


Gets the property value interpreter.

**Returns:**
[ValueInterpreter](../../com.groupdocs.metadata.core/valueinterpreter) - The property value interpreter.
