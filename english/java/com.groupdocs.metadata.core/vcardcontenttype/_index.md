---
title: VCardContentType
second_title: GroupDocs.Metadata for Java API Reference
description: Defines vCard record content types.
type: docs
weight: 403
url: /java/com.groupdocs.metadata.core/vcardcontenttype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum VCardContentType extends Enum<VCardContentType> implements IEnumValue
```

Defines vCard record content types.
## Fields

| Field | Description |
| --- | --- |
| [Custom](#Custom) | The custom content type. |
| [Text](#Text) | The text content type. |
| [Binary](#Binary) | The binary content type. |
| [DateTime](#DateTime) | The date time content type. |
| [Agent](#Agent) | The agent content type. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
### Custom {#Custom}
```
public static final VCardContentType Custom
```


The custom content type.

### Text {#Text}
```
public static final VCardContentType Text
```


The text content type.

### Binary {#Binary}
```
public static final VCardContentType Binary
```


The binary content type.

### DateTime {#DateTime}
```
public static final VCardContentType DateTime
```


The date time content type.

### Agent {#Agent}
```
public static final VCardContentType Agent
```


The agent content type.

### values() {#values--}
```
public static VCardContentType[] values()
```




**Returns:**
com.groupdocs.metadata.core.VCardContentType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static VCardContentType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[VCardContentType](../../com.groupdocs.metadata.core/vcardcontenttype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static VCardContentType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[VCardContentType](../../com.groupdocs.metadata.core/vcardcontenttype)
### getFirst() {#getFirst--}
```
public static IEnumValue getFirst()
```




**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getAllValues() {#getAllValues--}
```
public Object[] getAllValues()
```


Returns the array of all values defined in the class.

**Returns:**
java.lang.Object[]
### getEnumValueByRawValue(int rawValue) {#getEnumValueByRawValue-int-}
```
public IEnumValue getEnumValueByRawValue(int rawValue)
```


Returns the enumeration value by the raw value associated with it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getEnumValueByName(String name) {#getEnumValueByName-java.lang.String-}
```
public IEnumValue getEnumValueByName(String name)
```


Returns the enumeration value by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
### getRawValueType() {#getRawValueType--}
```
public RawIntegerType getRawValueType()
```


Returns the underlying type of the raw value of this enumeration value.

**Returns:**
[RawIntegerType](../../com.groupdocs.metadata.core/rawintegertype)
### getRawValue() {#getRawValue--}
```
public int getRawValue()
```


Returns the raw value of this enumeration value.

**Returns:**
int
