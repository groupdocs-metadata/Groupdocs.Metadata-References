---
title: DiagramFormat
second_title: GroupDocs.Metadata for Java API Reference
description: Defines various diagram subformats.
type: docs
weight: 357
url: /java/com.groupdocs.metadata.core/diagramformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum DiagramFormat extends Enum<DiagramFormat> implements IEnumValue
```

Defines various diagram subformats.
## Fields

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | The format is not recognized. |
| [Vdx](#Vdx) | Represents the .VDX Visio format. |
| [Vsd](#Vsd) | Represents the .VSD Visio format. |
| [Vsdx](#Vsdx) | Represents the .VSDX Visio format. |
| [Vss](#Vss) | Represents the .VSS Visio format. |
| [Vsx](#Vsx) | Represents the .VSX Visio format. |
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
### Unknown {#Unknown}
```
public static final DiagramFormat Unknown
```


The format is not recognized.

### Vdx {#Vdx}
```
public static final DiagramFormat Vdx
```


Represents the .VDX Visio format. Any drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. A Visio drawing XML file is created in Visio software, which is developed by Microsoft. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/vdx/

### Vsd {#Vsd}
```
public static final DiagramFormat Vsd
```


Represents the .VSD Visio format. VSD files are drawings created with Microsoft Visio application to represent variety of graphical objects and the interconnection between these. Such drawings can contain visual objects such as visual objects, flow charts, UML diagram, information flow, organizational charts, software diagrams, network layout, database models, objects mapping and other similar information. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/vsd/

### Vsdx {#Vsdx}
```
public static final DiagramFormat Vsdx
```


Represents the .VSDX Visio format. Files with .VSDX extension represent Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It was developed to replace the binary file format, .VSD, which is supported by earlier versions of Microsoft Visio. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/vsdx/

### Vss {#Vss}
```
public static final DiagramFormat Vss
```


Represents the .VSS Visio format. VSS are stencil files created with Microsoft Visio 2007 and earlier. A relatively new file format is .VSSX that was introduced with Microsoft Visio 2013. Stencil files provide drawing objects that can be included in a .VSD Visio drawing. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/vss/

### Vsx {#Vsx}
```
public static final DiagramFormat Vsx
```


Represents the .VSX Visio format. Files with .VSX extension refer to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/image/vsx/

### values() {#values--}
```
public static DiagramFormat[] values()
```




**Returns:**
com.groupdocs.metadata.core.DiagramFormat[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DiagramFormat valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DiagramFormat](../../com.groupdocs.metadata.core/diagramformat)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static DiagramFormat getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[DiagramFormat](../../com.groupdocs.metadata.core/diagramformat)
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
