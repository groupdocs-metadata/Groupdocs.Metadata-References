---
title: PropertyValue
second_title: GroupDocs.Signature for Java API Reference
description: Represents a property value.
type: docs
weight: 207
url: /java/com.groupdocs.metadata.core/propertyvalue/
---
**Inheritance:**
java.lang.Object
```
public class PropertyValue
```

Represents a property value.
## Constructors

| Constructor | Description |
| --- | --- |
| [PropertyValue(int value)](#PropertyValue-int-) | Initializes a new instance of the  PropertyValue  class with an integer value. |
| [PropertyValue(long value)](#PropertyValue-long-) | Initializes a new instance of the  PropertyValue  class with a long value. |
| [PropertyValue(boolean value)](#PropertyValue-boolean-) | Initializes a new instance of the  PropertyValue  class with a boolean value. |
| [PropertyValue(double value)](#PropertyValue-double-) | Initializes a new instance of the  PropertyValue  class with a double value. |
| [PropertyValue(String value)](#PropertyValue-java.lang.String-) | Initializes a new instance of the  PropertyValue  class with a string value. |
| [PropertyValue(Date value)](#PropertyValue-java.util.Date-) | Initializes a new instance of the  PropertyValue  class with a  DateTime  value. |
| [PropertyValue(String[] values)](#PropertyValue-java.lang.String---) | Initializes a new instance of the  PropertyValue  class with a string array. |
| [PropertyValue(byte[] values)](#PropertyValue-byte---) | Initializes a new instance of the  PropertyValue  class with a byte array. |
| [PropertyValue(double[] values)](#PropertyValue-double---) | Initializes a new instance of the  PropertyValue  class with an array of double values. |
| [PropertyValue(int[] values)](#PropertyValue-int---) | Initializes a new instance of the  PropertyValue  class with an array of integer values. |
| [PropertyValue(long[] values)](#PropertyValue-long---) | Initializes a new instance of the  PropertyValue  class with an array of long values. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets the  MetadataPropertyType . |
| [getRawValue()](#getRawValue--) | Gets the raw value. |
| [<TElement>toArray(Class<TElement> elementType)](#-TElement-toArray-java.lang.Class-TElement--) | Converts the property value to an array of the specified type. |
| [<T>toClass(Class<T> type)](#-T-toClass-java.lang.Class-T--) | Converts the property value to a reference type. |
| [toString()](#toString--) | Returns a string that represents the property value. |
| [acceptValue(ValueAcceptor valueAcceptor)](#acceptValue-com.groupdocs.metadata.core.ValueAcceptor-) | Extracts the property value using a custom ValueAcceptor. |
### PropertyValue(int value) {#PropertyValue-int-}
```
public PropertyValue(int value)
```


Initializes a new instance of the  PropertyValue  class with an integer value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | An  int  value. |

### PropertyValue(long value) {#PropertyValue-long-}
```
public PropertyValue(long value)
```


Initializes a new instance of the  PropertyValue  class with a long value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | A  long  value. |

### PropertyValue(boolean value) {#PropertyValue-boolean-}
```
public PropertyValue(boolean value)
```


Initializes a new instance of the  PropertyValue  class with a boolean value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A  bool  value. |

### PropertyValue(double value) {#PropertyValue-double-}
```
public PropertyValue(double value)
```


Initializes a new instance of the  PropertyValue  class with a double value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | A  double  value. |

### PropertyValue(String value) {#PropertyValue-java.lang.String-}
```
public PropertyValue(String value)
```


Initializes a new instance of the  PropertyValue  class with a string value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | A  string  value. |

### PropertyValue(Date value) {#PropertyValue-java.util.Date-}
```
public PropertyValue(Date value)
```


Initializes a new instance of the  PropertyValue  class with a  DateTime  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | A  DateTime  value. |

### PropertyValue(String[] values) {#PropertyValue-java.lang.String---}
```
public PropertyValue(String[] values)
```


Initializes a new instance of the  PropertyValue  class with a string array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.String[] | A string array. |

### PropertyValue(byte[] values) {#PropertyValue-byte---}
```
public PropertyValue(byte[] values)
```


Initializes a new instance of the  PropertyValue  class with a byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | byte[] | A byte array. |

### PropertyValue(double[] values) {#PropertyValue-double---}
```
public PropertyValue(double[] values)
```


Initializes a new instance of the  PropertyValue  class with an array of double values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | double[] | An array of double values. |

### PropertyValue(int[] values) {#PropertyValue-int---}
```
public PropertyValue(int[] values)
```


Initializes a new instance of the  PropertyValue  class with an array of integer values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | int[] | An array of integer values. |

### PropertyValue(long[] values) {#PropertyValue-long---}
```
public PropertyValue(long[] values)
```


Initializes a new instance of the  PropertyValue  class with an array of long values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | long[] | An array of long values. |

### getType() {#getType--}
```
public final MetadataPropertyType getType()
```


Gets the  MetadataPropertyType .

**Returns:**
[MetadataPropertyType](../../com.groupdocs.metadata.core/metadatapropertytype) - The type of the property.
### getRawValue() {#getRawValue--}
```
public final Object getRawValue()
```


Gets the raw value.

**Returns:**
java.lang.Object - The raw value.
### <TElement>toArray(Class<TElement> elementType) {#-TElement-toArray-java.lang.Class-TElement--}
```
public final TElement[] <TElement>toArray(Class<TElement> elementType)
```


Converts the property value to an array of the specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elementType | java.lang.Class<TElement> |  |

**Returns:**
TElement[] - The value represented as an array of the specified type or null if there is no such conversion.

 TElement : The type of an element.
### <T>toClass(Class<T> type) {#-T-toClass-java.lang.Class-T--}
```
public final T <T>toClass(Class<T> type)
```


Converts the property value to a reference type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.Class<T> |  |

**Returns:**
T - The converted value or null if there is no such conversion.

 T : The exact type to convert to.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the property value.

**Returns:**
java.lang.String - A string that represents the property value.
### acceptValue(ValueAcceptor valueAcceptor) {#acceptValue-com.groupdocs.metadata.core.ValueAcceptor-}
```
public void acceptValue(ValueAcceptor valueAcceptor)
```


Extracts the property value using a custom ValueAcceptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| valueAcceptor | [ValueAcceptor](../../com.groupdocs.metadata.core/valueacceptor) | An acceptor that extracts the value. |

