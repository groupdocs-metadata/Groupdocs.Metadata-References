---
title: PresentationFormat
second_title: GroupDocs.Metadata for Java API Reference
description: Defines various presentation subformats.
type: docs
weight: 397
url: /java/com.groupdocs.metadata.core/presentationformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
[com.groupdocs.metadata.core.IEnumValue](../../com.groupdocs.metadata.core/ienumvalue)
```
public enum PresentationFormat extends Enum<PresentationFormat> implements IEnumValue
```

Defines various presentation subformats.
## Fields

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | The format is not recognized. |
| [Ppt](#Ppt) | Represents the .PPT PowerPoint format. |
| [Pptx](#Pptx) | Represents the .PPTX PowerPoint format. |
| [Potm](#Potm) | Represents the .POTM PowerPoint format. |
| [Potx](#Potx) | Represents the .POTX PowerPoint format. |
| [Pptm](#Pptm) | Represents the .PPTM PowerPoint format. |
| [Pps](#Pps) | Represents the .PPS PowerPoint format. |
| [Ppsx](#Ppsx) | Represents the .PPSX PowerPoint format. |
| [Ppsm](#Ppsm) | Represents the .PPSM PowerPoint format. |
| [Pot](#Pot) | Represents the .POT PowerPoint format. |
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
public static final PresentationFormat Unknown
```


The format is not recognized.

### Ppt {#Ppt}
```
public static final PresentationFormat Ppt
```


Represents the .PPT PowerPoint format. A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/ppt/

### Pptx {#Pptx}
```
public static final PresentationFormat Pptx
```


Represents the .PPTX PowerPoint format. Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pptx/

### Potm {#Potm}
```
public static final PresentationFormat Potm
```


Represents the .POTM PowerPoint format. Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/potm/

### Potx {#Potx}
```
public static final PresentationFormat Potx
```


Represents the .POTX PowerPoint format. Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. This format was created to replace the POT file format that is based on the binary file format and is supported with PowerPoint 97-2003. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/potx/

### Pptm {#Pptm}
```
public static final PresentationFormat Pptm
```


Represents the .PPTM PowerPoint format. Files with PPTM extension are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. They are similar to PPTX files with the difference that the lateral can't execute macros though they can contain macros. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pptm/

### Pps {#Pps}
```
public static final PresentationFormat Pps
```


Represents the .PPS PowerPoint format. PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pps/

### Ppsx {#Ppsx}
```
public static final PresentationFormat Ppsx
```


Represents the .PPSX PowerPoint format. PPSX, Power Point Slide Show, files are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/ppsx/

### Ppsm {#Ppsm}
```
public static final PresentationFormat Ppsm
```


Represents the .PPSM PowerPoint format. Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/ppsm/

### Pot {#Pot}
```
public static final PresentationFormat Pot
```


Represents the .POT PowerPoint format. Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Files created with these versions of Microsoft PowerPoint are in binary format as compared to those created in Office OpenXML file formats using the higher versions of PowerPoint. Learn more about this file format  [here][] .


[here]: https://wiki.fileformat.com/presentation/pot/

### values() {#values--}
```
public static PresentationFormat[] values()
```




**Returns:**
com.groupdocs.metadata.core.PresentationFormat[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PresentationFormat valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PresentationFormat](../../com.groupdocs.metadata.core/presentationformat)
### getByRawValue(int rawValue) {#getByRawValue-int-}
```
public static PresentationFormat getByRawValue(int rawValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawValue | int |  |

**Returns:**
[PresentationFormat](../../com.groupdocs.metadata.core/presentationformat)
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
