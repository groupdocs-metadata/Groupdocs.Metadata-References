---
title: XmpArray
second_title: GroupDocs.Metadata for Java API Reference
description: Represents base abstraction for XMP array.
type: docs
weight: 248
url: /java/com.groupdocs.metadata.core/xmparray/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.PropertyValue](../../com.groupdocs.metadata.core/propertyvalue), [com.groupdocs.metadata.core.XmpValueBase](../../com.groupdocs.metadata.core/xmpvaluebase)
```
public class XmpArray extends XmpValueBase
```

Represents base abstraction for XMP array.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpArray(XmpArrayType arrayType, XmpValueBase[] items)](#XmpArray-com.groupdocs.metadata.core.XmpArrayType-com.groupdocs.metadata.core.XmpValueBase---) | Initializes a new instance of the  XmpArray  class. |
| [XmpArray(XmpArrayType arrayType, XmpComplexType[] items)](#XmpArray-com.groupdocs.metadata.core.XmpArrayType-com.groupdocs.metadata.core.XmpComplexType---) | Initializes a new instance of the  XmpArray  class. |
## Methods

| Method | Description |
| --- | --- |
| [getArrayType()](#getArrayType--) | Gets the type of the XMP array. |
| [<T>from(T[] array, XmpArrayType type)](#-T-from-T---com.groupdocs.metadata.core.XmpArrayType-) | Creates an  XmpArray  instance form an array of  XmpComplexType . |
| [from(String[] array, XmpArrayType type)](#from-java.lang.String---com.groupdocs.metadata.core.XmpArrayType-) | Creates an  XmpArray  instance form a string array. |
| [from(int[] array, XmpArrayType type)](#from-int---com.groupdocs.metadata.core.XmpArrayType-) | Creates an  XmpArray  instance form an integer array. |
| [from(Date[] array, XmpArrayType type)](#from-java.util.Date---com.groupdocs.metadata.core.XmpArrayType-) | Creates an  XmpArray  instance form a date array. |
| [from(double[] array, XmpArrayType type)](#from-double---com.groupdocs.metadata.core.XmpArrayType-) | Creates an  XmpArray  instance form a double array. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Converts XMP value to the xml representation. |
| [<T>toPlatformArray(Class<T> type)](#-T-toPlatformArray-java.lang.Class-T--) | Converts the  XmpArray  to a platform-specific array. |
### XmpArray(XmpArrayType arrayType, XmpValueBase[] items) {#XmpArray-com.groupdocs.metadata.core.XmpArrayType-com.groupdocs.metadata.core.XmpValueBase---}
```
public XmpArray(XmpArrayType arrayType, XmpValueBase[] items)
```


Initializes a new instance of the  XmpArray  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arrayType | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | Array type. |
| items | [XmpValueBase\[\]](../../com.groupdocs.metadata.core/xmpvaluebase) | Array items. |

### XmpArray(XmpArrayType arrayType, XmpComplexType[] items) {#XmpArray-com.groupdocs.metadata.core.XmpArrayType-com.groupdocs.metadata.core.XmpComplexType---}
```
public XmpArray(XmpArrayType arrayType, XmpComplexType[] items)
```


Initializes a new instance of the  XmpArray  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arrayType | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | Array type. |
| items | [XmpComplexType\[\]](../../com.groupdocs.metadata.core/xmpcomplextype) | Array items. |

### getArrayType() {#getArrayType--}
```
public final XmpArrayType getArrayType()
```


Gets the type of the XMP array.

**Returns:**
[XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) - The type of the XMP array.
### <T>from(T[] array, XmpArrayType type) {#-T-from-T---com.groupdocs.metadata.core.XmpArrayType-}
```
public static XmpArray <T>from(T[] array, XmpArrayType type)
```


Creates an  XmpArray  instance form an array of  XmpComplexType .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | T[] | The array to create an  XmpArray  from. |
| type | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | The type of the  XmpArray .

 T : The element type of the source array. |

**Returns:**
[XmpArray](../../com.groupdocs.metadata.core/xmparray) - An  XmpArray  containing all the elements from the original array.
### from(String[] array, XmpArrayType type) {#from-java.lang.String---com.groupdocs.metadata.core.XmpArrayType-}
```
public static XmpArray from(String[] array, XmpArrayType type)
```


Creates an  XmpArray  instance form a string array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | java.lang.String[] | The array to create an  XmpArray  from. |
| type | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | The type of the  XmpArray . |

**Returns:**
[XmpArray](../../com.groupdocs.metadata.core/xmparray) - An  XmpArray  containing all the elements from the original array.
### from(int[] array, XmpArrayType type) {#from-int---com.groupdocs.metadata.core.XmpArrayType-}
```
public static XmpArray from(int[] array, XmpArrayType type)
```


Creates an  XmpArray  instance form an integer array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | int[] | The array to create an  XmpArray  from. |
| type | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | The type of the  XmpArray . |

**Returns:**
[XmpArray](../../com.groupdocs.metadata.core/xmparray) - An  XmpArray  containing all the elements from the original array.
### from(Date[] array, XmpArrayType type) {#from-java.util.Date---com.groupdocs.metadata.core.XmpArrayType-}
```
public static XmpArray from(Date[] array, XmpArrayType type)
```


Creates an  XmpArray  instance form a date array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | java.util.Date[] | The array to create an  XmpArray  from. |
| type | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | The type of the  XmpArray . |

**Returns:**
[XmpArray](../../com.groupdocs.metadata.core/xmparray) - An  XmpArray  containing all the elements from the original array.
### from(double[] array, XmpArrayType type) {#from-double---com.groupdocs.metadata.core.XmpArrayType-}
```
public static XmpArray from(double[] array, XmpArrayType type)
```


Creates an  XmpArray  instance form a double array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | double[] | The array to create an  XmpArray  from. |
| type | [XmpArrayType](../../com.groupdocs.metadata.core/xmparraytype) | The type of the  XmpArray . |

**Returns:**
[XmpArray](../../com.groupdocs.metadata.core/xmparray) - An  XmpArray  containing all the elements from the original array.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Converts XMP value to the xml representation.

**Returns:**
java.lang.String - Returns  string  representation of XMP value.
### <T>toPlatformArray(Class<T> type) {#-T-toPlatformArray-java.lang.Class-T--}
```
public final T[] <T>toPlatformArray(Class<T> type)
```


Converts the  XmpArray  to a platform-specific array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | java.lang.Class<T> |  |

**Returns:**
T[] - A platform-specific array containing elements of the  XmpArray .

 T : The type of the array element.
