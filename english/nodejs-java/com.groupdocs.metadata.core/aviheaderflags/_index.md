---
title: AviHeaderFlags
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Represents AVI Header flags.
type: docs
weight: 25
url: /nodejs-java/com.groupdocs.metadata.core/aviheaderflags/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public final class AviHeaderFlags implements IEnumValue
```

Represents AVI Header flags.
## Fields

| Field | Description |
| --- | --- |
| [HasIndex](#HasIndex) | Indicates the AVI file has an index. |
| [MustUseIndex](#MustUseIndex) | Indicates that application should use the index, rather than the physical ordering of the chunks in the file, to determine the order of presentation of the data. |
| [IsInterleaved](#IsInterleaved) | Indicates the AVI file is interleaved. |
| [TrustCkType](#TrustCkType) | Use CKType to find key frames. |
| [WasCaptureFile](#WasCaptureFile) | Indicates the AVI file is a specially allocated file used for capturing real-time video. |
| [Copyrighted](#Copyrighted) | Indicates the AVI file contains copyrighted data and software. |
## Methods

| Method | Description |
| --- | --- |
| [getByRawValue(int rawValue)](#getByRawValue-int-) |  |
| [getFirst()](#getFirst--) |  |
| [getAllValues()](#getAllValues--) |  |
| [getEnumValueByRawValue(int rawValue)](#getEnumValueByRawValue-int-) |  |
| [getEnumValueByName(String name)](#getEnumValueByName-java.lang.String-) |  |
| [getRawValueType()](#getRawValueType--) |  |
| [getRawValue()](#getRawValue--) |  |
| [name()](#name--) |  |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### HasIndex {#HasIndex}
```
public static final AviHeaderFlags HasIndex
```


Indicates the AVI file has an index.

### MustUseIndex {#MustUseIndex}
```
public static final AviHeaderFlags MustUseIndex
```


Indicates that application should use the index, rather than the physical ordering of the chunks in the file, to determine the order of presentation of the data. For example, this flag could be used to create a list of frames for editing.

### IsInterleaved {#IsInterleaved}
```
public static final AviHeaderFlags IsInterleaved
```


Indicates the AVI file is interleaved.

### TrustCkType {#TrustCkType}
```
public static final AviHeaderFlags TrustCkType
```


Use CKType to find key frames.

### WasCaptureFile {#WasCaptureFile}
```
public static final AviHeaderFlags WasCaptureFile
```


Indicates the AVI file is a specially allocated file used for capturing real-time video. Applications should warn the user before writing over a file with this flag set because the user probably defragmented this file.

### Copyrighted {#Copyrighted}
```
public static final AviHeaderFlags Copyrighted
```


Indicates the AVI file contains copyrighted data and software. When this flag is used, software should not permit the data to be duplicated.

### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static AviHeaderFlags getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[AviHeaderFlags](../../com.groupdocs.metadata.core/aviheaderflags)
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
### name() {#name--}
```
public String name()
```


Returns the name of this enumeration value.

**Returns:**
java.lang.String
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
