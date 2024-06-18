---
title: ZipCompressionMethod
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines ZIP compression methods.
type: docs
weight: 411
url: /nodejs-java/com.groupdocs.metadata.core/zipcompressionmethod/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum ZipCompressionMethod extends Enum<ZipCompressionMethod> implements IEnumValue
```

Defines ZIP compression methods.
## Fields

| Field | Description |
| --- | --- |
| [NoCompression](#NoCompression) | The file is stored (no compression). |
| [Shrunk](#Shrunk) | The file is Shrunk. |
| [Imploded](#Imploded) | The file is Imploded. |
| [Reserved](#Reserved) | A reserved compression method. |
| [Deflated](#Deflated) | The file is Deflated. |
| [BZip2](#BZip2) | The file is compressed with the BZip2 algorithm. |
| [Lzma](#Lzma) | The Lempel-Ziv-Markov chain-Algorithm. |
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
### NoCompression {#NoCompression}
```
public static final ZipCompressionMethod NoCompression
```


The file is stored (no compression).

### Shrunk {#Shrunk}
```
public static final ZipCompressionMethod Shrunk
```


The file is Shrunk.

### Imploded {#Imploded}
```
public static final ZipCompressionMethod Imploded
```


The file is Imploded.

### Reserved {#Reserved}
```
public static final ZipCompressionMethod Reserved
```


A reserved compression method.

### Deflated {#Deflated}
```
public static final ZipCompressionMethod Deflated
```


The file is Deflated.

### BZip2 {#BZip2}
```
public static final ZipCompressionMethod BZip2
```


The file is compressed with the BZip2 algorithm.

### Lzma {#Lzma}
```
public static final ZipCompressionMethod Lzma
```


The Lempel-Ziv-Markov chain-Algorithm.

### values() {#values--}
```
public static ZipCompressionMethod[] values()
```




**Returns:**
com.groupdocs.metadata.core.ZipCompressionMethod[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ZipCompressionMethod valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ZipCompressionMethod](../../com.groupdocs.metadata.core/zipcompressionmethod)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static ZipCompressionMethod getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[ZipCompressionMethod](../../com.groupdocs.metadata.core/zipcompressionmethod)
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
