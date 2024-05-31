---
title: ExportFormat
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines file formats to which you can export metadata properties.
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.metadata.export/exportformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum ExportFormat extends Enum<ExportFormat> implements IEnumValue
```

Defines file formats to which you can export metadata properties.
## Fields

| Field | Description |
| --- | --- |
| [Xls](#Xls) | Represents the .XLS Excel format. |
| [Xlsx](#Xlsx) | Represents the .XLSX Excel format. |
| [Xml](#Xml) | Represents the .XML format. |
| [Csv](#Csv) | Represents the .CSV format. |
| [Json](#Json) | Represents the .JSON format. |
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
### Xls {#Xls}
```
public static final ExportFormat Xls
```


Represents the .XLS Excel format.

### Xlsx {#Xlsx}
```
public static final ExportFormat Xlsx
```


Represents the .XLSX Excel format.

### Xml {#Xml}
```
public static final ExportFormat Xml
```


Represents the .XML format.

### Csv {#Csv}
```
public static final ExportFormat Csv
```


Represents the .CSV format.

### Json {#Json}
```
public static final ExportFormat Json
```


Represents the .JSON format.

### values() {#values--}
```
public static ExportFormat[] values()
```




**Returns:**
com.groupdocs.metadata.export.ExportFormat[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ExportFormat valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ExportFormat](../../com.groupdocs.metadata.export/exportformat)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static ExportFormat getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[ExportFormat](../../com.groupdocs.metadata.export/exportformat)
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
