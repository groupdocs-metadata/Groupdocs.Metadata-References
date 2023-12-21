---
title: ValueInterpreter
second_title: GroupDocs.Signature for Java API Reference
description: Defines operations required to interpret metadata property values.
type: docs
weight: 275
url: /java/com.groupdocs.metadata.core/valueinterpreter/
---
**Inheritance:**
java.lang.Object
```
public abstract class ValueInterpreter
```

Defines operations required to interpret metadata property values.
## Constructors

| Constructor | Description |
| --- | --- |
| [ValueInterpreter()](#ValueInterpreter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInterpretedValueType()](#getInterpretedValueType--) | Gets the type of the interpreted value. |
| [toInterpretedValue(PropertyValue originalValue)](#toInterpretedValue-com.groupdocs.metadata.core.PropertyValue-) | Interprets the provided property value. |
| [toSourceValue(PropertyValue interpretedValue)](#toSourceValue-com.groupdocs.metadata.core.PropertyValue-) | Converts an interpreted value back to its original form. |
### ValueInterpreter() {#ValueInterpreter--}
```
public ValueInterpreter()
```


### getInterpretedValueType() {#getInterpretedValueType--}
```
public abstract MetadataPropertyType getInterpretedValueType()
```


Gets the type of the interpreted value.

**Returns:**
[MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype) - The type of the interpreted value.
### toInterpretedValue(PropertyValue originalValue) {#toInterpretedValue-com.groupdocs.metadata.core.PropertyValue-}
```
public final PropertyValue toInterpretedValue(PropertyValue originalValue)
```


Interprets the provided property value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalValue | [PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) | The value to interpret. |

**Returns:**
[PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) - The interpreted value.
### toSourceValue(PropertyValue interpretedValue) {#toSourceValue-com.groupdocs.metadata.core.PropertyValue-}
```
public final PropertyValue toSourceValue(PropertyValue interpretedValue)
```


Converts an interpreted value back to its original form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| interpretedValue | [PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) | The interpreted value to convert. |

**Returns:**
[PropertyValue](../../com.groupdocs.metadata.core/propertyvalue) - The original value.
