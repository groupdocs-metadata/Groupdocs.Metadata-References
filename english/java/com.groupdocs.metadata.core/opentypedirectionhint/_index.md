---
title: OpenTypeDirectionHint
second_title: GroupDocs.Metadata for Java API Reference
description: Represents the OpenType font direction.
type: docs
weight: 377
url: /java/com.groupdocs.metadata.core/opentypedirectionhint/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum OpenTypeDirectionHint extends Enum<OpenTypeDirectionHint> implements IEnumValue
```

Represents the OpenType font direction.
## Fields

| Field | Description |
| --- | --- |
| [FullyMixed](#FullyMixed) | Fully mixed directional glyphs. |
| [OnlyLeftToRight](#OnlyLeftToRight) | Only strongly left to right. |
| [LeftToRightAndNeutrals](#LeftToRightAndNeutrals) | Like  OnlyLeftToRight  but also contains neutrals. |
| [OnlyRightToLeft](#OnlyRightToLeft) | Only strongly right to left. |
| [RightToLeftAndNeutrals](#RightToLeftAndNeutrals) | Like  OnlyRightToLeft  but also contains neutrals. |
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
### FullyMixed {#FullyMixed}
```
public static final OpenTypeDirectionHint FullyMixed
```


Fully mixed directional glyphs.

### OnlyLeftToRight {#OnlyLeftToRight}
```
public static final OpenTypeDirectionHint OnlyLeftToRight
```


Only strongly left to right.

### LeftToRightAndNeutrals {#LeftToRightAndNeutrals}
```
public static final OpenTypeDirectionHint LeftToRightAndNeutrals
```


Like  OnlyLeftToRight  but also contains neutrals.

### OnlyRightToLeft {#OnlyRightToLeft}
```
public static final OpenTypeDirectionHint OnlyRightToLeft
```


Only strongly right to left.

### RightToLeftAndNeutrals {#RightToLeftAndNeutrals}
```
public static final OpenTypeDirectionHint RightToLeftAndNeutrals
```


Like  OnlyRightToLeft  but also contains neutrals.

### values() {#values--}
```
public static OpenTypeDirectionHint[] values()
```




**Returns:**
com.groupdocs.metadata.core.OpenTypeDirectionHint[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static OpenTypeDirectionHint valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[OpenTypeDirectionHint](../../com.groupdocs.metadata.core/opentypedirectionhint)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static OpenTypeDirectionHint getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[OpenTypeDirectionHint](../../com.groupdocs.metadata.core/opentypedirectionhint)
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
