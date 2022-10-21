---
title: WordProcessingRevisionType
second_title: GroupDocs.Metadata for Java API Reference
description: Specifies the type of the change being tracked by a revision.
type: docs
weight: 357
url: /java/com.groupdocs.metadata.core/wordprocessingrevisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum WordProcessingRevisionType extends Enum<WordProcessingRevisionType> implements IEnumValue
```

Specifies the type of the change being tracked by a revision.
## Fields

| Field | Description |
| --- | --- |
| [Insertion](#Insertion) | New content was inserted into the document. |
| [Deletion](#Deletion) | Content was removed from the document. |
| [FormatChange](#FormatChange) | Change of formatting was applied to the parent node. |
| [StyleDefinitionChange](#StyleDefinitionChange) | Change of formatting was applied to the parent style. |
| [Moving](#Moving) | Content was moved in the document. |
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
### Insertion {#Insertion}
```
public static final WordProcessingRevisionType Insertion
```


New content was inserted into the document.

### Deletion {#Deletion}
```
public static final WordProcessingRevisionType Deletion
```


Content was removed from the document.

### FormatChange {#FormatChange}
```
public static final WordProcessingRevisionType FormatChange
```


Change of formatting was applied to the parent node.

### StyleDefinitionChange {#StyleDefinitionChange}
```
public static final WordProcessingRevisionType StyleDefinitionChange
```


Change of formatting was applied to the parent style.

### Moving {#Moving}
```
public static final WordProcessingRevisionType Moving
```


Content was moved in the document.

### values() {#values--}
```
public static WordProcessingRevisionType[] values()
```




**Returns:**
com.groupdocs.metadata.core.WordProcessingRevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static WordProcessingRevisionType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[WordProcessingRevisionType](../../com.groupdocs.metadata.core/wordprocessingrevisiontype)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static WordProcessingRevisionType getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[WordProcessingRevisionType](../../com.groupdocs.metadata.core/wordprocessingrevisiontype)
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
