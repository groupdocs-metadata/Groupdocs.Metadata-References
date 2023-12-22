---
title: XmpTime
second_title: GroupDocs.Metadata for Java API Reference
description: Representation of a time value in seconds.
type: docs
weight: 334
url: /java/com.groupdocs.metadata.core/xmptime/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.metadata.core.MetadataPackage](../../com.groupdocs.metadata.core/metadatapackage), [com.groupdocs.metadata.core.CustomPackage](../../com.groupdocs.metadata.core/custompackage), [com.groupdocs.metadata.core.XmpMetadataContainer](../../com.groupdocs.metadata.core/xmpmetadatacontainer), [com.groupdocs.metadata.core.XmpComplexType](../../com.groupdocs.metadata.core/xmpcomplextype)
```
public final class XmpTime extends XmpComplexType
```

Representation of a time value in seconds.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpTime()](#XmpTime--) | Initializes a new instance of the  XmpTime  class. |
| [XmpTime(XmpRational scale, int value)](#XmpTime-com.groupdocs.metadata.core.XmpRational-int-) | Initializes a new instance of the  XmpTime  class. |
## Methods

| Method | Description |
| --- | --- |
| [getScale()](#getScale--) | Gets the scale for the time value. |
| [setScale(XmpRational value)](#setScale-com.groupdocs.metadata.core.XmpRational-) | Sets the scale for the time value. |
| [getValue()](#getValue--) | Gets the time value in the specified scale. |
| [setValue(Integer value)](#setValue-java.lang.Integer-) | Sets the time value in the specified scale. |
### XmpTime() {#XmpTime--}
```
public XmpTime()
```


Initializes a new instance of the  XmpTime  class.

### XmpTime(XmpRational scale, int value) {#XmpTime-com.groupdocs.metadata.core.XmpRational-int-}
```
public XmpTime(XmpRational scale, int value)
```


Initializes a new instance of the  XmpTime  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scale | [XmpRational](../../com.groupdocs.metadata.core/xmprational) | The scale. |
| value | int | The value. |

### getScale() {#getScale--}
```
public final XmpRational getScale()
```


Gets the scale for the time value.

**Returns:**
[XmpRational](../../com.groupdocs.metadata.core/xmprational) - The scale for the time value. For NTSC, use 1001/30000, or the less accurate 100/2997. 

 For PAL, use 1/25.
### setScale(XmpRational value) {#setScale-com.groupdocs.metadata.core.XmpRational-}
```
public final void setScale(XmpRational value)
```


Sets the scale for the time value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpRational](../../com.groupdocs.metadata.core/xmprational) | The scale for the time value. For NTSC, use 1001/30000, or the less accurate 100/2997. 

 For PAL, use 1/25. |

### getValue() {#getValue--}
```
public final Integer getValue()
```


Gets the time value in the specified scale.

**Returns:**
java.lang.Integer - The time value in the specified scale.
### setValue(Integer value) {#setValue-java.lang.Integer-}
```
public final void setValue(Integer value)
```


Sets the time value in the specified scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer | The time value in the specified scale. |

